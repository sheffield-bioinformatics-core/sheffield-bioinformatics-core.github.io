---
title: Alumni
permalink: /team/alumni/
slug: alumni
type: text
---

Previous members of the Sheffield Bioinformatics Core team:

{% assign people = site.people | sort: 'othernames' | sort: 'surname' | sort: 'level'  %}
<div class="people-list">
{% for person in people %}
    {% if person.alumnum == true %}
      {% if person.othernames and person.surname %}
        <h2><a href="{{person.url}}">{{person.othernames}} {{person.surname}}</a></h2>
      {% endif %}
      <div class="mycontainer">
  <div><p>{{ person.summary }}</p></div>
  <div><p><img src="/assets/images/people/{{person.othernames}}.jpg" width="250"></p></div>
  </div>
    {% endif %}
{% endfor %}
</div>
