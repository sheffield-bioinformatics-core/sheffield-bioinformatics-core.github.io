---
title: Team
permalink: /team/
slug: team
type: text
---

Current members of the Sheffield Bioinformatics Core team, and associated staff and students are listed below. Click on a team member's name to get a full biography.

Previous members of the team can be found on our [Alumni](/team/alumni) page.

{% assign people = site.people | sort: 'othernames' | sort: 'surname' | sort: 'level'  %}
<div class="people-list">
{% for person in people %}
    {% if person.alumnum == false %}
      {% if person.othernames and person.surname %}
        <h2><a href="{{person.url}}">{{person.othernames}} {{person.surname}} - {{person.role}}</a></h2>
      {% endif %}
      <div class="mycontainer">
  <div><p>{{ person.summary }}</p></div>
  <div><p><img src="/assets/images/people/{{person.othernames}}.jpg" width="250"></p></div>
</div>
    {% endif %}
{% endfor %}
</div>
