---
layout: page
group: navigation
title: <span class="glyphicon glyphicon-exclamation-sign" />よくある質問
order: 5
---

{% for faq in site.data.faq %}
<div class="panel panel-default">
  <div class="panel-heading">
    <h3 class="panel-title">Q. {{ faq.q }}</h3>
  </div>
  <div class="panel-body">
    {{ faq.a | newline_to_br}}
  </div>
</div>
{% endfor %}
