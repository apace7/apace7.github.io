---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Refereed Journal Publications
------

1. **Pace, Andrew B.**, Martinez, G. D., Kaplinghat, M., Muñoz, R. R., 2014, MNRAS, 442, 1718; *Evidence for substructure in Ursa Minor dwarf spheroidal galaxy using a Bayesian object detection method* <span style="color:blue"> [ADS](http://adsabs.harvard.edu/abs/2014MNRAS.442.1718P) </span>

1. Fillingham, Sean P., Cooper, Michael C., **Pace, Andrew B.**, Boylan-Kolchin, Michael, Bullock, James S., Garrison-Kimmel, Shea, Wheeler, Coral, 2016, MNRAS, 463, 1916; *Under pressure: quenching star formation in low-mass satellite galaxies via stripping* <span style="color:blue"> [ADS](http://adsabs.harvard.edu/abs/2016MNRAS.463.1916F) </span>

1. A. Kamada, M. Kaplinghat, **A.B. Pace**, H. Yu, 2017, PRL, 119, 111102; *Self-Interacting Dark Matter Can Explain Diverse Galactic Rotation Curves* <span style="color:blue"> [ADS](http://adsabs.harvard.edu/abs/2017PhRvL.119k1102K) </span>

1. T.S. Li et al. including **ABP** 2017, APJ, 838, 8; *Farthest Neighbor: The Distant Milky Way Satellite Eridanus II* <span style="color:blue"> [ADS](http://adsabs.harvard.edu/abs/2017ApJ...838....8L) </span>

1. T.S. Li, J.D. Simon, **A.B. Pace**, et al. 2018, APJ, 857, 145;
*Ships Passing in the Night: Spectroscopic Analysis of Two Ultra-Faint Satellites in the Constellation Carina* <span style="color:blue"> [ADS](http://adsabs.harvard.edu/abs/2018ApJ...857..145L) </span>



[]( <span style="color:blue"> [ADS]() </span> )

For the full list of academic publications, see my [CV](link) and [publication](link) list or check out my [ADS](link), [Spires](link), [Google Scholar](link) profile.



Submitted
------

1. **A.B. Pace**, L.E. Strigari, 2018;
*Scaling Relations for Dark Matter Annihilation and Decay Profiles in Dwarf Spheroidal Galaxies* <span style="color:blue"> [ADS](http://adsabs.harvard.edu/abs/2018arXiv180206811P) </span> 



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
