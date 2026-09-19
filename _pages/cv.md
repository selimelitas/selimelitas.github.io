---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Eğitim
======
* [Okul adı], [Bölüm], [Yıl]

İş Deneyimi
======
* Elektronik Teknisyeni (Emekli)
  * [Kurum adı] — [Başlangıç–Bitiş yılı]
  * Görevler: [Arıza tespiti, bakım-onarım, vb. — kısaca yaz]

Beceriler
======
* Elektronik devre analizi ve arıza tespiti (multimetre, osiloskop vb.)
* Linux (özellikle Pardus)
* Python
* GTK4 ile masaüstü uygulama geliştirme
* Sanallaştırma (VirtualBox — USB boot imajı araçları)

Yayınlar
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Eğitmenlik
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>