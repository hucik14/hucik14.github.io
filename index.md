---
---
Welcome to a small animated collection of various mechanism I’ve made. If you want to reach out, use the [contact form](https://docs.google.com/forms/d/e/1FAIpQLSfuRs3_uNcINh2yRX_F4iCAaxD1PlyUjmmNVjVHe6W_Tt3u5w/viewform?usp=dialog).

You can also visit my [GitHub](https://github.com/hucik14) · [Google Scholar](https://scholar.google.com/citations?user=5sNQdNMAAAAJ) · [Printables](https://www.printables.com/@hucik14_497869) profiles.

---

Jump to a project:
<p class="toc">
{% for p in site.data.projects %}
  {% assign pid = p.id | default: p.title | slugify %}
  <a href="#{{ pid }}">{{ p.title }}</a>{% unless forloop.last %} | {% endunless %}
{% endfor %}
</p>

---

{% for p in site.data.projects %}
  {% include project.html p=p %}
  {% unless forloop.last %}<hr>{% endunless %}
{% endfor %}

---

## License

Site code: Apache 2.0 (see [LICENCE](https://github.com/hucik14/hucik14.github.io/blob/main/LICENSE))  
Content (text/images/gifs): CC BY-NC 4.0 (see [LICENCE-CONTENT](https://github.com/hucik14/hucik14.github.io/blob/main/LICENSE-CONTENT))
