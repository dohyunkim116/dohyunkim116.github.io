---
permalink: /
title: "Do Hyun Kim"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. candidate in the Department of Biostatistics at UCLA. My research interests include statistical genetics and computational statistics. I am currently working on developing statistical methods for conducting genetic studies of survival traits, including survival trait heritability quantification and GWAS, for large-scale biobank data.

Education
======
* Ph.D in Biostatistics, UCLA, 2026 (expected)
* B.S. in Molecular & Cellular Biology and Neuroscience, Johns Hopkins University, 2013

Publications
======
<ul class="minimal-publications">
  {% for post in site.publications reversed %}
    {% include minimal-publication.html %}
  {% endfor %}
</ul>
  
Talks
======
<ul class="minimal-talks">
  {% for post in site.talks reversed %}
    {% include minimal-talk.html %}
  {% endfor %}
</ul>