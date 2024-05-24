---
title: About
nav:
  order: 3
  tooltip: About me
---

# {% include icon.html icon="fa-solid fa-users" %}About me


Marine ecologist and microbiologist from the UK who is slightly obsessed with marine macrophytes. I have studied ecology in systems ranging from ticks to limpets and most recently habitat forming macroalgae. My work uses manipulative field and mesocosm experiments to explore the role of host-associated microbes in host function and fitness. Outside of the lab you can find me either in the pottery studio or with my head stuck in a rockpool looking for critters.



{% capture content %}

{%
  include figure.html
  image="images/.jpg"
  caption="The team at our annual Christmas party, 2025"
  link="team"
  width="400px"
%}

{% endcapture %}

{% include grid.html style="square" content=content %}
