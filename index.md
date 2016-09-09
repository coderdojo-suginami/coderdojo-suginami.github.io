---
layout: default
---

<div class="jumbotron text-center">
  <h1>コーダー道場すぎなみ<br />へようこそ！</h1>
  <p>
  杉並区にある子どもたちのためのプログラミングクラブです。<br />
  ボランティアにより、非営利に運営されています。</p>
  <p><a class="btn btn-primary btn-lg" href="/about/" role="button">もっとくわしく知りたい &raquo;</a></p>
</div>


<div class="row">
<div class="col-md-12">
    <h1>次回開催</h1>
	{% include event_list.html %}
  </div>

  <div class="col-md-4">
    <h2><span class="glyphicon glyphicon-user" />ニンジャ</h2>
	<p>...</p>
  </div>
  <div class="col-md-4">
    <h2><span class="glyphicon glyphicon-eye-open" />メンター</h2>
	<p>...</p>
  </div>
  <div class="col-md-4">
    <h2><span class="glyphicon glyphicon-heart-empty" />支援のお願い</h2>
	<p>...</p>
  </div>
</div>

{% include sponsors.md %}
