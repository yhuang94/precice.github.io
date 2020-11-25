---
title: Community Projects
permalink: community-projects.html
keywords:
summary:
toc: true
---

{{site.data.alerts.note}}
Do you use preCICE? We are always happy to hear about interesting projects that use preCICE. <br>
<a class="button primary" href="../resources/#contact">Tell us your story!</a>
{{site.data.alerts.end}}

{% assign testimonials = site.testimonials | reverse %}
{% for testimonial in testimonials %}
## {{ testimonial.title }}
<div class="row" markdown="1">
<div class="col-md-6" markdown="1">
{{ testimonial.content }}

—**[{{ testimonial.author }}]({{ testimonial.author_link }})**

{{ testimonial.organisation }}
</div>
<div class="col-md-6" markdown="1">
![](images/testimonials/{{ testimonial.img }})
</div>
</div>
{% endfor %}

