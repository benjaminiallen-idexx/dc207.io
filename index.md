---
layout: default
---

# $ cat about.txt
{:id="about"}

DC207 is a DEF CON group focused on community, education, mentoring and bringing the hacker and InfoSec community in Maine together. We meet the second Thursday of every month in the Old Port at 7 Custom House St, 3rd floor. It is a gathering that will feature presentations, workshops, CTFs, and anything else in which the community is interested. The group is community-driven, and allows its members to be active so they can learn or teach about a subject they are passionate about. DC207 also supports the already-existing security-related and technology-focused groups, and we encourage members of all groups to collaborate and share knowledge. We are strong together!
<br><br>
The mission of the DC207 group is to advance knowledge and educate anyone interested in science, technology, and other areas of information security through project collaborations, group gatherings, and group activities that will best serve our community and the world.

# $ cat contact.txt
{:id="contact"}

E-mail us at root@dc207.org

# $ cat meetings.txt
{:id="posts"}

### title: DC207 Resurrected: OSINT - What we already know <br>
### date of meeting: 2018-11-09<br>
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

