---
layout: page
permalink: /cv/
title: cv
nav: true
nav_order: 4
cv_pdf: CV.pdf
description: 
---
{% assign cv_url = page.cv_pdf | prepend: '/assets/pdf/' | relative_url %}
<div class="row">
    <div class="col-sm-12">
        <object data="{{ cv_url }}" width="100%" height="1200" type="application/pdf" aria-label="Jiangyifei Zhu's CV">
            <p>It appears your browser doesn't support embedded PDFs. 
            You can <a href="{{ cv_url }}">download the PDF here</a>.</p>
        </object>
    </div>
</div>

<div class="row mt-3">
    <div class="col-sm-12 text-center">
        <a href="{{ cv_url }}" class="btn btn-primary">Download CV</a>
    </div>
</div>
