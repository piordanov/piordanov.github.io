---
layout: default
title: Home
---
{: .f2 .tc .sans-serif .fw7}
# Peter Iordanov

### Computer Science, UIUC 2017

I am a software engineer and VR hobbyist. Currently I am a solutions engineer at [Fulcrum Global Technologies](https://fulcrumgt.com) in Chicago, Illinois, where we develop multiple software applications to automate and simplify the business operations of legal firms.

{: .f35 .tc .spartan}
# Projects

<div class="flex flex-wrap justify-center">
  {% for project in site.projects %}
    <div class="outline pa3 mr2 project-block">
      <h2><a href="{{ project.url }}">{{ project.title }}</a></h2>
    </div>
  {% endfor %}
</div>