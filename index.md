---
layout: default
---
<style><!--
.jumbotron{
    background: url("/images/bg_natural_sougen.jpg");
    background-position: center center;
    background-size: cover;
}
//-->
</style>

<div class="jumbotron text-center">
  <img src="/images/logo_namisuke.png" alt="CoderDojo Suginami logo" />
  <p>
  杉並区にある子どもたちのための <br />
  プログラミング倶楽部です。<br />
  参加費は無料。<br />
  プログラミング教室ではなく「自主学習」を支援します。
  </p>
</div>

<div class="row">
  <div class="col-md-8">
    <h2>次回開催</h2>
	{% include event_list.html %}

	<h2>会場の募集</h2>
<p>杉並区内で開催できる会場（飲食自由な場所）を探しています。無償でお貸しいただける場合は、<a href="https://coderdojo-suginami.doorkeeper.jp/contact/new">こちらよりご連絡</a>ください。</p>
<p>▼会場にあると嬉しいもの（すべて揃っている必要はありません）：WiFi、電源、電源タップ、机・椅子、プロジェクタ</p>

    <h2>関連リンク</h2>
	<ul>
	<li><a href="https://coderdojo-suginami.doorkeeper.jp">Doorkeeper</a>（メンバー登録すると開催通知が届きます）</li>
	<li><a href="https://zen.coderdojo.com/dojo/jp/suginami-tokyo/suginami">CoderDojo suginami</a>（「CoderDojoすぎなみ」の紹介ページ）</li>
	</ul>
  </div>

<div class="col-md-4">
{% include facebook_page.html %}
</div>

  <div class="col-md-4">
    <h2><span class="glyphicon glyphicon-user" />ニンジャ</h2>
	<p>コーダー道場では、参加者のことを「ニンジャ」と呼ぶのじゃ。<a href="/ninjas/"><span class="glyphicon glyphicon-share-alt" /></a></p>
  </div>
  <div class="col-md-4">
    <h2><span class="glyphicon glyphicon-eye-open" />メンター</h2>
	<p>ニンジャのガイド役となり、やりたいことや困っていることを支援します。<a href="/mentors/"><span class="glyphicon glyphicon-share-alt" /></a></p>
  </div>
  <div class="col-md-4">
    <h2><span class="glyphicon glyphicon-heart-empty" />支援のお願い</h2>
	<p>活動に賛同いただける個人や法人のみなさまには、ご支援をお願いしています。<a href="/sponsorship/"><span class="glyphicon glyphicon-share-alt" /></a></p>
  </div>

</div> <!-- /div.row -->
