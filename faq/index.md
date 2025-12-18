---
layout: page
group: navigation
title: ❓よくある質問
order: 5
---

{% for faq in site.data.faq %}
<div class="card mb-3">
  <div class="card-header">
    <h5 class="card-title">Q. {{ faq.q }}</h5>
  </div>
  <div class="card-body">
    {{ faq.a | newline_to_br}}
  </div>
</div>
{% endfor %}
