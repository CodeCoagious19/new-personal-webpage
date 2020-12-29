---
title: "Lezione 01"
layout: corso
---

## Aggiungere collezioni tramite jekyll e liquid

- Stabilire il nome della collezione di file `.md` all'interno di `_config.yml` ad esempio:

```yml
collections:
  corso_python:
    output: true
```

Crea una cartella con il nome `_corso_python` e inserisci tutti i file `.md` della collezione.

Per creare un loop automatico che legga questi file, utilizza nel tuo layout ad esempio potesti crarne uno nuovo, `corso.html` la seguente sintassi:

```html
<div class="side-bar">
    {% for lesson in site.corso_python %}
    {% if page.url == lesson.url %}
        <a class="active side-bar-element" href="{{ lesson.url }}">{{ lesson.title }}</a>
    {% else %}
        <a class="side-bar-element" href="{{ lesson.url }}">{{ lesson.title }}</a>
    {% endif %}
    {% endfor %}
</div>
```

Eos eu docendi tractatos sapientem, brute option menandri in vix, quando vivendo accommodare te ius. Nec melius fastidii constituam id, viderer theophrastus ad sit, hinc semper periculis cum id. Noluisse postulant assentior est in, no choro sadipscing repudiandae vix. Vis in euismod delenit dignissim. Ex quod nostrum sit, suas decore animal id ius, nobis solet detracto quo te.

{% comment %}
Might you have an include in your theme? Why not try it here!
{% include my-themes-great-include.html %}
{% endcomment %}

No laudem altera adolescens has, volumus lucilius eum no. Eam ei nulla audiam efficiantur. Suas affert per no, ei tale nibh sea. Sea ne magna harum, in denique scriptorem sea, cetero alienum tibique ei eos. Labores persequeris referrentur eos ei.


Eos eu docendi tractatos sapientem, brute option menandri in vix, quando vivendo accommodare te ius. Nec melius fastidii constituam id, viderer theophrastus ad sit, hinc semper periculis cum id. Noluisse postulant assentior est in, no choro sadipscing repudiandae vix. Vis in euismod delenit dignissim. Ex quod nostrum sit, suas decore animal id ius, nobis solet detracto quo te.

{% comment %}
Might you have an include in your theme? Why not try it here!
{% include my-themes-great-include.html %}
{% endcomment %}

No laudem altera adolescens has, volumus lucilius eum no. Eam ei nulla audiam efficiantur. Suas affert per no, ei tale nibh sea. Sea ne magna harum, in denique scriptorem sea, cetero alienum tibique ei eos. Labores persequeris referrentur eos ei.
Eos eu docendi tractatos sapientem, brute option menandri in vix, quando vivendo accommodare te ius. Nec melius fastidii constituam id, viderer theophrastus ad sit, hinc semper periculis cum id. Noluisse postulant assentior est in, no choro sadipscing repudiandae vix. Vis in euismod delenit dignissim. Ex quod nostrum sit, suas decore animal id ius, nobis solet detracto quo te.

{% comment %}
Might you have an include in your theme? Why not try it here!
{% include my-themes-great-include.html %}
{% endcomment %}

No laudem altera adolescens has, volumus lucilius eum no. Eam ei nulla audiam efficiantur. Suas affert per no, ei tale nibh sea. Sea ne magna harum, in denique scriptorem sea, cetero alienum tibique ei eos. Labores persequeris referrentur eos ei.
Eos eu docendi tractatos sapientem, brute option menandri in vix, quando vivendo accommodare te ius. Nec melius fastidii constituam id, viderer theophrastus ad sit, hinc semper periculis cum id. Noluisse postulant assentior est in, no choro sadipscing repudiandae vix. Vis in euismod delenit dignissim. Ex quod nostrum sit, suas decore animal id ius, nobis solet detracto quo te.

{% comment %}
Might you have an include in your theme? Why not try it here!
{% include my-themes-great-include.html %}
{% endcomment %}

No laudem altera adolescens has, volumus lucilius eum no. Eam ei nulla audiam efficiantur. Suas affert per no, ei tale nibh sea. Sea ne magna harum, in denique scriptorem sea, cetero alienum tibique ei eos. Labores persequeris referrentur eos ei.