---
layout: archive
title: ""
permalink: /talks/
author_profile: true
---
Invited Talks
======
* 2020. Decoding sensorimotor decisions from eye movements. Hosted by Martin Rolfs, Humboldt University of Berlin, Germany, September 18.
* 2020. Eye movement signatures during sensorimotor decisions. Hosted by Tobias Donner, University Medical Center Hamburg-Eppendorf, Germany, June 3.
* 2019. Eye movements as indicators of visual and sensorimotor processing. Hosted by Philippe Lefèvre, School of Engineering. Université Catholique de Louvain, Brussels, Belgium, July 23.
* 2019. Linking eye movements to visual predictions. Centre for Neuroscience. Hosted by Randy Flanagan, Queen’s University, Kingston, Ontario, Canada, February 20.
* 2018. Linking eye movements to visual predictions. Hosted by Stefanie Becker, School of Psychology. University of Queensland, Brisbane, Queensland, Australia, August 20.


Conference Talks
======


Conference Posters
======



{% if author.googlescholar %}
  You can also find published conference proceedings on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.talks reversed %}
  {% include archive-single.html %}
{% endfor %}
