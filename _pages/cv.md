---
layout: archive
title: "Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

<p style="margin-left: 40px"><b>M.S., Biomedical Engineering</b>
<br>New Jersey Institute of Technology, Newark
<br><i>September 2011 - January 2014</i></p>

<p style="margin-left: 40px"><b>B.S., Electronics Engineering</b>
<br>Ankara University, Ankara
<br><i>September 2007 - June 2011</i></p>

## Employment

<p style="margin-left: 40px"><b>Research Associate</b>
<br>Center for Injury Biomechanics, Materials, and Medicine
<br>New Jersey Institute of Technology, Newark, NJ
<br><i>December 2014 — July 2019</i></p>

<p style="margin-left: 40px"><b>Research Assistant</b>
<br>NYU Langone Health, Bellevue Hospital Center, New York, NY
<br><i>August 2016 — July 2018</i></p>

<p style="margin-left: 40px"><b>Research Assistant</b>
<br>Neural Prosthetics Laboratory
<br>New Jersey Institute of Technology, Newark, NJ
<br><i>January 2012 — January 2014</i></p>

## Peer-Reviewed Journal Publications

Mentees’ names underlined. Asterisk indicates dual first-author position.
Open access articles or preprints (<i class="ai ai-fw ai-open-access-square"></i>)
are linked below; all other PDFs (<i class="fa fa-file-pdf-o" aria-hidden="true">
</i>) are provided for **personal use only.** Supplementary materials on GitHub
(<i class="fa fa-github" aria-hidden="true"></i>) and OSF
(<i class="ai ai-fw ai-osf"></i>) for each publication are linked below the
citation.

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

## Refereed Conference Proceedings

Mentees’ names underlined. Asterisk indicates dual first-author position.
Open access articles or preprints (<i class="ai ai-fw ai-open-access-square"></i>)
are linked below; all other PDFs (<i class="fa fa-file-pdf-o" aria-hidden="true">
</i>) are provided for **personal use only.** Supplementary materials on GitHub
(<i class="fa fa-github" aria-hidden="true"></i>) and OSF
(<i class="ai ai-fw ai-osf"></i>) for each publication are linked below the
citation.

{% for post in site.proceedings reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
