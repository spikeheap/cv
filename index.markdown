---
layout: home
---
<div class="container">
  <div class="row mt-5">
    <div class="col-sm-8">
      <h1>
        {{ site.data.cv.profile.name }}
      </h1>
      <span class="h3 text-muted">{{ site.data.cv.profile.location }}</span>
      <div class="mt-2">
        {% include profile.md %}
      </div>

      {% include experience.html %}


    </div>
    <div class="col-sm">
      {% include contact-details.html %}
      {% include skills.html %}
    </div>
  </div>
</div>





