---
layout: default
---

# $ cat about.txt
{:id="about"}

DC207 is a DEF CON group focused on community, education, mentoring and bringing the hacker and InfoSec community in Maine together. We meet the second Thursday of every month in the Old Port at 6 PM. For event information please visit events.dc207.org. Our gatherings feature presentations, workshops, CTFs, and anything else in which the community is interested. The group is community-driven, and allows its members to be active so they can learn or teach about a subject they are passionate about. DC207 also supports the already-existing security-related and technology-focused groups, and we encourage members of all groups to collaborate and share knowledge. We are strong together!
<br><br>
The mission of the DC207 group is to advance knowledge and educate anyone interested in science, technology, and other areas of information security through project collaborations, group gatherings, and group activities that will best serve our community and the world.

# $ cat contact.txt
{:id="contact"}

E-mail us at root@dc207.org

# $ cat meetings.txt
{:id="posts"}

### title: #tryharder, my OSCP experience and tips<br>
### date of meeting: September 12 2019<br>
### description: All things OSCP <br><br>
Looking to try harder and earn your OSCP? Why not come join us then! We'll be talking all things OSCP, and Ben Mason will be walking us through how the OSCP test works and how you ought to study to earn the cert! 

### title: DEFCON Rollup<br>
### date of meeting: August 15th<br>
### description: DC207 members swap stories about their DEFCON highlights<br><br>
Since DEFCON was being held at our typical meeting time, we're meeting a week later to discuss all things DEFCON. We'll chat about highlights, talks, and experinces. Join us for a recap!

### title: IT'S A TRAP!<br>
### date of meeting: June 13th 2019<br>
### description: A practical session covering pentesting basics in the cloud. <br><br>
Last time, we had some fun with a CTF game, but we identified some areas to cover. Ryan Botot will present "IT'S A TRAP!", a practical hands-on excercise on pentesting cloud servers. So come prepared with your computer and the willingness to learn about some new concepts. 

### title: DC207 CTF<br>
### date of meeting: May 9th 2019<br>
### description: Shall we play another game? <br><br>
After the fun of our first CTF, it's back again! We'll break up into teams and challenge you and your team mates to break the security of servers and applications. We'll be screening the 1995 classic "The Net" - you won't want to miss it!

### title: War Games - Teaching threat modeling <br>
### date of meeting: April 11th 2019<br>
### description: Want to learn a card trick? <br><br>
Ready to have some fun and learn about threat modeling in the process? We'll be breaking into groups and playing elevation of privilege. It's a super fun way to learn how to make the dull threat modeling a little more fun and lively. Come join us for drinks, cards, and pizza, it'll be a blast.

### title: Remote persistant access<br>
### date of meeting: March 14th 2019<br>
### description: Pentesting tools in action<br><br>
Join us back at out home in Covetrus for a talk about pentesting and remote access. Agenda items will also include planning for the May CTF game. 

### title: DC207 Lockpick Workshop<br>
### date of meeting: Febuary 21st 2019<br>
### description: Lockpicking workshop.<br><br>
Join us for a fun workshop teaching the subject of lockpicking. This fun will really open some doors (get it?) for people. RSVP for a free lockpick kit and deadbolt to learn with. Will be hosted at Locally Sauced on Thompson's Point. 

### title: DC207 CTF<br>
### date of meeting: January 10th 2019<br>
### description: Shall we play a game?.<br><br>
Please join us for an evening of hacking, snacking, drinking, and watching the movie "Hackers". Meeting

### title: Let’s not wait for the heat death of the universe before we secure our APIs<br>
### date of meeting: December 13th 2018<br>
### description: Horrors of API security revealed! Talk by Ben Hamilton.<br><br>
Meeting two! DC207 is back in action with a hot security topic, pizza, and prizes on December 13th. Ben Hamilton will be presenting a talk focused on vulnrabilities in APIs. He'll explore how APIs are an often overlooked by development teams.<br><br>

Pizza from OTTO, softdrinks on site. The CTF event requires a write-up, submit yours @ root@dc207.org for a chance for to win a Pen-testing Raspberry Pi. See you there!

### title: DC207 Resurrected: OSINT - What we already know <br>
### date of meeting: November 08 2018<br>
### description: DC207 Resurrected. Talk by Benjamin Allen, OSINT - What we already know.<br><br>
Our first meeting will take place on November 8th, 2018. We'll have a 20 minute talk about open source intellegence titled: "OSINT - What we already know". We'll explore open source intellegence and how effective it can be in gain access to resources. You'll learn what you need to do to profile yourself, and your own company.<br><br>

We'll also take a little time to talk though the solution of the CTF challenge posted below. We'll talk about how we want to run our meetings, CTF challenges, and have a drink or two afterwards.
# $ cat CTF.txt
{:id="projects"}

<ul>
{% for project in site.categories.projects %}
<li><a href="{{ project.link }}">{{ project.title }}</a> - {{ project.description }}</li>
{% endfor %}
</ul>

