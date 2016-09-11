---
layout: page
group: navigation
title: <span class="glyphicon glyphicon-tent" />本道場のご案内
order: 1
---

# 道場主（主催者）

<div class="row">
  {% for c in site.data.champions %}
  <div class="col-md-6">
    <div class="thumbnail">
      <img src="{{ c.photo }}" alt="{{ c.name }}">
      <div class="caption">
        <h2>{{ c.name }}（{{ c.kana }}）{{ c.id }}</h2>
        <p>{{ c.profile }}</p>
      </div>
    </div>
  </div>
  {% endfor %}
</div>

# 標準的な流れ

<div class="row">
<div class="col-md-3"><div class="panel panel-warning">
  <div class="panel-heading">1. はじめに（10分間）</div>
  <div class="panel-body">自己紹介とアイスブレイク<a href="http://kata.coderdojo.com/wiki/Warm_up_Games">Warm up Games</a></div>
</div></div>
<div class="col-md-3"><div class="panel panel-warning">
  <div class="panel-heading">2. 第一部（45分間）</div>
  <div class="panel-body">プログラミング<br />休憩（+10分間）</div>
</div></div>
<div class="col-md-3"><div class="panel panel-warning">
  <div class="panel-heading">3. 第二部（45分間）</div>
  <div class="panel-body">プログラミング<br />休憩（+10分間）</div>
</div></div>
<div class="col-md-3"><div class="panel panel-warning">
  <div class="panel-heading">4. 成果発表（30分間）</div>
  <div class="panel-body">
1. やったこと<br />
2. わかったこと<br />
3. 次にやりたいこと
  </div>
</div></div>
</div>


# 主に保護者の方へ

## <span class="glyphicon glyphicon-ok" />CoderDojoすぎなみは、子どもたちのためのプログラミングコミュニティです

* 子どもたちが、お互いに学び合い、教え合いながら、自分だけの制作活動を行う場です。
* こちらから教材を指定することはありません。子どもたちに自分でやりたいことを見つけてもらいます。

## <span class="glyphicon glyphicon-ok" />CoderDojoすぎなみは、プログラミング教室ではありません
* （大事なことなので2回言いますが）こちらから教材を指定することはありません。子どもたちに自分でやりたいことを見つけてもらいます。
* やりたいことが見つからない・解決策がわからない・とにかく困っている、といった子どもたちの悩みを支援するために、[メンター](/mentors/)を用意しています。生ではないので、何かを教えてくれるとは限りませんが、一緒になって悩みを考えてくれるでしょう。
* プログラミングを学ぶことも大切ですが、プログラミングやものづくりを通じて、創造性や人間性などのスキル（ソフトスキル）も身につけてもらうことを目指しています。

## <span class="glyphicon glyphicon-ok" />CoderDojoすぎなみは、ボランティアにより運営されています
* 参加する子どもたちや保護者からは、参加費を頂いておりません。
* ご支援については、[ありがたく受け付けております](/sponsorship/)。

## <span class="glyphicon glyphicon-ok" />CoderDojoすぎなみは、地域の開かれた場所であることを目指します
* 子どもたちにとって、地域（杉並区）における居場所のひとつになることを願っています。
* さまざな背景をもった人たちとの交流を通して、社会とのつながりを感じてほしいと思っています。

## <span class="glyphicon glyphicon-ok" />CoderDojoすぎなみは、CoderDojoの活動に賛同しています

* CoderDojoについて知りたい方は、[CoderDojoのサイト](https://coderdojo.com/)をご覧ください。

# 参考資料

* [CoderDojoガイダンス（最新版）](http://www.slideshare.net/togazo/coderdojo-introduction-jp)
* [Dojo運営・企画資料](http://www.slideshare.net/togazo/coder-dojo-201501)
* [コーダー道場こだいら](http://coderdojo-kodaira.github.io/)
