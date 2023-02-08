---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

* **Orrison, R.**, M. Vuille, J.E. Smerdon, J. Apaéstegui, V. Azevedo, J.L.P.S. Campos, F.W. Cruz, M.E. Della Libera, and N.M. Stríkis, 2022: South American Monsoon variability over the last millennium in paleoclimate records and isotope-enabled climate models. Clim. Past, 18, 2045-2062, <u><a href="{{https://cp.copernicus.org/articles/18/2045/2022/}}">doi:10.5194/cp-18-2045-2022</a></u>. [PDF](https://rgorrison.github.io/files/Orrison_2022_SASM_LMvariability.pdf)
* **Orrison, R.**, Vuille, M., Smerdon, J. E., Apaéstegui, J., Azevedo, V., Campos, J. L. P. S., Cruz, F., W., Della
Libera, M. E. and Stríkis, N. M., (2022), Last Millennium δ<sup>18</sup>O, δ<sup>13</sup>C and U/Th ages of MV1 and MV30 stalagmite records from Mata Virgem cave (central Brazil). PANGAEA, <u><a href="{{https://doi.pangaea.de/10.1594/PANGAEA.948181}}">doi: 10.1594/PANGAEA.948183</a></u>.
* **Orrison, R.**, (2022), SASM-MCEOF-v1.1.0, Zenodo [code, data set], <u><a href="{{https://doi.org/10.5281/zenodo.6949234}}">doi: 10.1594/PANGAEA.948183</a></u>.
* Della Libera, M.E., V.F. Novello, F.W. Cruz, **R. Orrison**, M. Vuille, S.Y. Maezumi, J. de Souza, J.C. Rodriguez, J.L.P.S. Campos, A. Ampuero, G. Utida, N.M. Stríkis, C. Fernandes Stumpf, V. Azevedo, H. Zhang, R.L. Edwards and H. Cheng, 2022: Paleoclimatic and paleoenvironmental changes in Amazonian lowlands over the last three millennia and their implications for pre-Columbian populations. Quaternary Sci. Rev., 279, 107383, <u><a href=" {{https://www.sciencedirect.com/science/article/abs/pii/S0277379122000142}}">doi:10.1016/quascirev.2022.107383</a></u>. [PDF](https://rgorrison.github.io/files/DellaLibera_2022_Rondonia.pdf) 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=Iy7JmM8AAAAJ&hl=en&oi=ao}}">my Google Scholar profile</a>.</u>
{% endif %}


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
