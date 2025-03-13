---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<script>
  function resizeIframe(obj) {
    obj.style.height = obj.contentWindow.document.documentElement.scrollHeight + 'px';
  }
</script>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

<!-- {% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %} -->

<div class="row">
<iframe width="100%" frameBorder="0" onload="resizeIframe(this)" src='https://haltools.archives-ouvertes.fr/Public/afficheRequetePubli.php?idHal=thibault-prouteau&CB_ref_biblio=oui&CB_Resume_court=oui&CB_typdoc=oui&CB_audience=oui&CB_vignette=oui&langue=Anglais&tri_exp=typdoc&tri_exp2=date_publi&tri_exp3=date_publi&tri_exp4=audience&ordre_aff=AT&Fen=Aff&css=../css/VisuCondenseSsCadre.css'></iframe></div>