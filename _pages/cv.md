---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 5
cv_pdf: /assets/pdf/jinnyeong_yang_CV.pdf # replace this file to update the CV
description:
# To go back to the HTML CV rendered from _data/cv.yml, set `layout: cv`, add
# `cv_format: rendercv` and `toc: {sidebar: left}`, and delete the body below.
---

<p>
  <a href="{{ page.cv_pdf | relative_url }}" target="_blank" rel="noopener"><i class="fa-solid fa-file-pdf"></i> Open / download PDF</a>
</p>

<object data="{{ page.cv_pdf | relative_url }}" type="application/pdf" style="width: 100%; height: 85vh; border: 1px solid var(--global-divider-color);">
  <p>
    Your browser can't display the PDF here —
    <a href="{{ page.cv_pdf | relative_url }}">open the CV PDF</a> instead.
  </p>
</object>
