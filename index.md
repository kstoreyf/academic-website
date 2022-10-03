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
  - title: "Outreach"
    url: "#outreach"
  - title: "Contact"
    url: "#contact"
---

{% include about.md %}
{% include_relative _layouts/thumbnails.html content=site.research title="Research" label="research" src="research.md"%}
{% include_relative _layouts/picture.md src="teaching.md" %}
{% include_relative _layouts/thumbnails.html content=site.writing title="Writing" label="writing" src="writing.md" %}
{% include_relative _layouts/picture.md src="updates.md" %}
{% include_relative _layouts/thumbnails.html content=site.outreach title="Outreach" label="outreach" src="outreach.md" %}
{% include_relative _layouts/picture.md src="service.md" %}
{% include_relative _layouts/simple.md src="contact.md" %}
