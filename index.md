---
layout: default
---

# $ cat about.txt
{:id="about"}

DC207 is a DEF CON group focused on community, education, mentoring and bringing the hacker and InfoSec community in Maine together. We meet the fourth Friday of every month in the Old Port. It is a gathering that will feature presentations, workshops, CTFs, and anything else in which the community is interested. The group is community-driven, and allows its members to be active so they can learn or teach about a subject they are passionate about. DC207 also supports the already-existing security-related and technology-focused groups, and we encourage members of all groups to collaborate and share knowledge. We are strong together!
<br><br>
The mission of the DC207 group is to advance knowledge and educate anyone interested in science, technology, and other areas of information security through project collaborations, group gatherings, and group activities that will best serve our community and the world.

# $ cat contact.txt
{:id="contact"}

E-mail us at root@dc207.org

# $ cat team.txt
{:id="team"}

<ul>
{% for member in site.categories.team reversed %}
<li id="{{ member.title }}">{{ member.title }}
<ul>
<li>{{ member.mail }}</li>
<li><a href="https://github.com/{{ member.github }}">https://github.com/{{ member.github }}</a></li>
<li><a href="{{ member.site }}">{{ member.site }}</a></li>
</ul>
</li>
{% endfor %}
</ul>

# $ cat projects.txt
{:id="projects"}

<ul>
{% for project in site.categories.projects %}
<li><a href="{{ project.link }}">{{ project.title }}</a> - {{ project.description }}</li>
{% endfor %}
</ul>

# $ cat tools.txt
{:id="tools"}

<ul>
{% for tool in site.categories.tools %}
<li><a href="{{ tool.link }}">{{ tool.title }}</a> - {{ tool.description }}</li>
{% endfor %}
</ul>

# $ cat talks.txt
{:id="talks"}

<ul>
{% for talk in site.categories.talks %}
<li><a href="{{ talk.link }}" title="{{ talk.description }}">{{ talk.title }}</a> at {{ talk.where }}</li>
{% endfor %}
</ul>

# $ cat posts.txt
{:id="posts"}

<ul>
{% for post in site.categories.posts %}

{% if post.en %}
<li>{{ post.title }} :: <a href="{{ post.url }}" title="{{ post.description }}">en</a> :: <a href="{{ post.pt }}" title="{{ post.description_pt }}">pt_br</a></li>
{% endif %}

{% endfor %}
</ul>

# $ cat articles.txt
{:id="articles"}

<ul>
{% for post in site.categories.articles %}

{% if post.en %}
<li>{{ post.title }} :: <a href="{{ post.url }}" title="{{ post.description }}">en</a> :: <a href="{{ post.pt }}" title="{{ post.description_pt }}">pt_br</a></li>
{% endif %}

{% endfor %}
</ul>
