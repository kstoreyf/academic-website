---
layout: home
title: Home
banner_image: "/images/banner.jpg"
buttons:
  - title: "Research"
    url: "#research"
  - title: "Teaching"
    url: "#teaching"
  - title: "Writing"
    url: "#writing"
  - title: "Updates"
    url: "#updates"
  - title: "Service"
    url: "#service"
---

{% comment %}
<h2 id="research">Research</h2>
{% endcomment %}

{% include about.md %}
{% include_relative _layouts/cards.html content=site.research title="Research" label="research" %}
{% include_relative _layouts/picture.md src="teaching.md" %}
{% comment %}
{% include_relative _layouts/cards.html content=site.writing title="Writing" label="writing" %}
{% include_relative _layouts/simple.md src="writing.md" %}
{% endcomment %}
{% include_relative _layouts/thumbnails.html content=site.writing title="Writing" label="writing" src="writing.md" %}
{% include_relative _layouts/picture.md src="updates.md" %}
{% include_relative _layouts/simple.md src="service.md" %}
