---
title: About
nav:
  order: 3
  tooltip: About me
---

# {% include icon.html icon="fa-solid fa-users" %}About me


Marine ecologist and microbiologist from the UK who is slightly obsessed with marine macrophytes. I have studied ecology in systems ranging from ticks to limpets and most recently habitat forming macroalgae. My work uses manipulative field and mesocosm experiments to explore the role of host-associated microbes in host function and fitness. Outside of the lab you can find me either in the pottery studio or with my head stuck in a rockpool looking for critters.



{% capture content %}

Previous section of content

{%
  include section.html
  background="images/HB.jpg"
  dark=true
  size=full
%}

Next section of content

{%
  include figure.html
  image="images/AHM CV 2023-images-0.jpg"
  caption="The team at our annual Christmas party, 2025"
  link="team"
  width="2000px"
%}

{% include section.html size="20" %}

{% include figure.html image="images/AHM CV 2023-images-0.jpg" %}

{% include section.html %}

{% endcapture %}

{% include grid.html style="square" content=content %}
