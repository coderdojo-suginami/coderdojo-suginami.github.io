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

# 道場の場所

## メイン道場

東京都杉並区高円寺北2-3-17 高円寺NKビル <br />
株式会社ヴァル研究所 <br />
JR高円寺駅（北口下車 徒歩3分）

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3239.8207470244547!2d139.64931011525948!3d35.70602848018848!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6018f287985dcff9%3A0x47f513f12c5d370e!2z44CSMTY2LTAwMDIg5p2x5Lqs6YO95p2J5Lim5Yy66auY5YaG5a-65YyX77yS5LiB55uu77yT4oiS77yR77yXIO-8iOagqu-8ieODtOOCoeODq-eglOeptuaJgA!5e0!3m2!1sja!2sjp!4v1473602343638" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

## サブ会場

TBD（杉並区の地域区民センターを使う予定です）

### 参考

* [公衆無線LANサービスを利用できる区の施設を教えてください。](http://www.city.suginami.tokyo.jp/faq/etc/etc/1004194.html)

> 本庁舎1階、各図書館、各地域区民センター、四宮区民集会所、久我山会館、杉並公会堂、座・高円寺（杉並芸術会館）です。

* [公衆無線LANサービスの事業者を教えてください。](http://www.city.suginami.tokyo.jp/faq/etc/etc/1004195.html)

> KDDI：本庁舎1階、各図書館、各地域区民センター、杉並公会堂、座・高円寺（芸術会館）、区立小中学校等（震災救援所） <br />
> ソフトバンク：高円寺地域区民センター、四宮区民集会所、久我山会館 <br />
> フリースポット：本庁舎1階、中央図書館2階

# 道場の指針

## <span class="glyphicon glyphicon-heart" />価値

* 交流：みんなと一緒に作業します。
* 奉仕：自発的に他人のために尽くします。
* 勇気：失敗することを恐れません。
* 尊敬：他人に対して敬意を払います。
* 興奮：自ら楽しむことを忘れません。

## <span class="glyphicon glyphicon-hand-right" />原則

価値にもとづき、実践を通じて、以下の変数を高めることを目指します。

* 安全性、人間性、理解度、注目度、満足度、多様性、相互利益性、責任感、達成感、自己肯定感

{% comment %}〜性、〜感、〜度などがよい{% endcomment %}

## <span class="glyphicon glyphicon-fire" />実践

* 手を動かしながら考える
* 3回調べてから質問する
* Show & Tell（a.k.a. 成果発表会）
* ベイビーステップで進む
* やりたいことリストを作る（プロダクトバックログ）
* 他の人のマネをする
* 他の人にマネしてもらう
* （随時追加予定）

<span class="glyphicon glyphicon-chevron-right" />参考：[CoderDojo ECHO (English)](http://kata.coderdojo.com/wiki/ECHO)


# 標準的な流れ

<div class="row">
<div class="col-md-4"><div class="panel panel-success">
  <div class="panel-heading">1. はじめに（10分間）</div>
  <div class="panel-body">自己紹介<br />アイスブレイク（<a href="http://kata.coderdojo.com/wiki/Warm_up_Games">Warm up Games</a>）</div>
</div></div>
<div class="col-md-4"><div class="panel panel-success">
  <div class="panel-heading">2. 稽古（50分間）✕ 2〜3回</div>
  <div class="panel-body">プログラミング<br />休憩（+10分間）</div>
</div></div>
<div class="col-md-4"><div class="panel panel-success">
  <div class="panel-heading">3. 成果発表（20分間）</div>
  <div class="panel-body">
1. やったこと<br />
2. わかったこと<br />
3. 次にやりたいこと
  </div>
</div></div>
</div>


# 主に保護者の方へ

## <span class="label label-primary"><span class="glyphicon glyphicon-ok" />CoderDojoすぎなみは、子どもたちのためのプログラミングコミュニティです</span>

* 子どもたちが、お互いに学び合い、教え合いながら、自分だけの制作活動を行う場です。
* こちらから教材を指定することはありません。子どもたちに自分でやりたいことを見つけてもらいます。

## <span class="label label-primary"><span class="glyphicon glyphicon-ok" />CoderDojoすぎなみは、プログラミング教室ではありません</span>
* （大事なことなので2回言いますが）こちらから教材を指定することはありません。子どもたちに自分でやりたいことを見つけてもらいます。
* やりたいことが見つからない・解決策がわからない・とにかく困っている、といった子どもたちの悩みを支援するために、[メンター](/mentors/)を用意しています。生ではないので、何かを教えてくれるとは限りませんが、一緒になって悩みを考えてくれるでしょう。
* プログラミングを学ぶことも大切ですが、プログラミングやものづくりを通じて、創造性や人間性などのスキル（ソフトスキル）も身につけてもらうことを目指しています。

## <span class="label label-primary"><span class="glyphicon glyphicon-ok" />CoderDojoすぎなみは、ボランティアにより運営されています</span>
* 参加する子どもたちや保護者からは、参加費を頂いておりません。
* ご支援については、[ありがたく受け付けております](/sponsorship/)。

## <span class="label label-primary"><span class="glyphicon glyphicon-ok" />CoderDojoすぎなみは、地域の開かれた場所であることを目指します</span>
* 子どもたちにとって、地域（杉並区）における居場所のひとつになることを願っています。
* さまざな背景をもった人たちとの交流を通して、社会とのつながりを感じてほしいと思っています。

## <span class="label label-primary"><span class="glyphicon glyphicon-ok" />CoderDojoすぎなみは、CoderDojoの活動に賛同しています</span>

* CoderDojoについて知りたい方は、[CoderDojoのサイト](https://coderdojo.com/)をご覧ください。

# 参考資料

* [CoderDojoガイダンス（最新版）](http://www.slideshare.net/togazo/coderdojo-introduction-jp)
* [Dojo運営・企画資料](http://www.slideshare.net/togazo/coder-dojo-201501)
* [コーダー道場こだいら](http://coderdojo-kodaira.github.io/)
