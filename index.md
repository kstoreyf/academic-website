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
  - title: "News"
    url: "#news"
---

{% comment %}
<h2 id="research">Research</h2>
{% endcomment %}

{% include about.md %}
{% include_relative _layouts/cards.html content=site.research title="Research" label="research" %}
{% include_relative _layouts/simple.md src="teaching.md" %}
{% include_relative _layouts/simple.md src="writing.md" %}
{% include_relative _layouts/simple.md src="news.md" %}