---
---
Welcome to a small animated collection of various mechanism I’ve made. I hope you will share the passion for kinematics with me and appreciate the beautiful goemetry behind the presented mechanisms. My name is Daniel, curently a postdoc at Robotics Laboratory, Seoul National University, Korea. If you want to reach out, find my emial on our [lab's website](https://sites.google.com/robotics.snu.ac.kr/fcp/people/researchers).

You can also visit my [GitHub](https://github.com/hucik14) · [Google Scholar](https://scholar.google.com/citations?user=5sNQdNMAAAAJ) · [Printables](https://www.printables.com/@hucik14_497869) profiles.

---
 
<p class="toc">
Jump to a project: 
{% for p in site.data.projects %}
  {% assign pid = p.id | default: p.title | slugify %}
  <a href="#{{ pid }}">{{ p.title }}</a>{% unless forloop.last %}  |  {% endunless %}
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
