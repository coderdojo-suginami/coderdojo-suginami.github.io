---
layout: page
group: navigation
title: <span class="glyphicon glyphicon-eye-open" />メンター
order: 3
---

{% comment %}
* 事前講習が必要みたい
http://www.slideshare.net/togazo/dojo1150528/12
{% endcomment %}

<img src="/images/teacher_woman.png" alt="teacher_woman" />

<!-- http://kata.coderdojo.com/wiki/Mentors_and_Volunteers_Information -->

## メンターとは？

**メンター**とは、得意な技術分野と経験を持った個人のことです。CoderDojoにおいては、参加者のガイド役となり、プロジェクト作業を支援します。ただし、こちらから何かを教えるのではなく、質問されたことに答えたり、つまづいているところを少しだけ助けてあげたりするだけです。子どもたちが自分で学ぶ姿勢を大切にしたいと思っています！

{% comment %}
道場は1回数時間程度を予定しています。地域の子どもたちのために、みなさまの知識と経験をお貸しください。道場でのメンターの経験は、きっと大きな価値になるでしょう。逆に子どもたちから、いろいろと教えられることがあるくらいです！
{% endcomment %}

## メンターの紹介

<style>
.row-height {
    display: flex;
    flex-wrap: wrap;
}
</style>

<div class="row row-height">
  {% for c in site.data.mentors %}
  <div class="col-md-4">
    <div class="thumbnail">
      <img src="{{ c.photo }}" alt="{{ c.name }}" class="img-circle">
      <div class="caption">
        <h2>{{ c.name }}（{{ c.kana }}）{{ c.id }}</h2>
        <p>{{ c.profile }}</p>
      </div>
    </div>
  </div>
  {% endfor %}
</div>

<div class="alert alert-danger" role="alert">
※メンターになるには、既存のメンターからの推薦が必要です。
</div>


## メンタリングの指針

* ニンジャが中心であり、ニンジャが楽しめるように工夫します。
* ニンジャが自分のプロジェクトを完成できるように支援します。
* 「3回調べてわからなかったら質問して！」の態度でニンジャを見守ります。
* ニンジャには、技術そのものよりも、技術を通じて何かを学んでもらえるようにします。
* あとで役に立つように、うまくいったパターンをまとめて、メンター同士で共有します。

## メンター同士の連絡方法

* [Facebookグループ](https://www.facebook.com/groups/coderdojosuginamimentors/)とGitHubの[issues](https://github.com/coderdojo-suginami/coderdojo-suginami.github.io/issues/)でやりとりします。

## 教材の選定 and/or 制作
* 何かいい教材があれば、情報共有しましょう。
  * [バッジ](https://zen.coderdojo.com/badges)をあげられる教材カードを先に翻訳するといいかも？

## メンターの行動規範

「CoderDojoすぎなみ」のメンターとして活動に参加するにあたり、以下の点に同意するものとします。

> 1. CoderDojoとは、子どもたちに「プログラミングを学ぶ場を提供するボランティア活動」であり、活動の中心は子どもたちであることを理解します。
> 2. すべての参加者（子ども、メンター、保護者、その他関係者）に対して礼儀正しく振舞い、決して尊大な態度をとりません。
> 3. すべての参加者と仲良く活動し、差別的・否定的な言動を行いません。
> 4. 会場内での安全に配慮し、CoderDojoが安全かつ円滑に開催できるように行動します。
> 5. CoderDojoの趣旨に賛同するスポンサーが会場を提供していることを理解し、会場の設備・備品等の扱いに注意するとともに場内を清潔に保つように努めます。
> 6. CoderDojoの活動において知り得た、参加者の個人情報を、本人の同意なしに他人に提供したり、公開したりしません。
> 7. CoderDojoにおいて、商業的・政治的・宗教的な宣伝および勧誘を一切行いません。ただし、商業的なものであって、CoderDojoの活動に即したものであると考える場合は、事前に主宰者の承諾を得ることを条件に、告知できるものとします。
> 8. メンターとしての活動は、ボランティア活動（無報酬で行う自発的活動）であることを理解します。報酬はもちろんのこと、活動にかかる交通費などの費用についても自己負担で参加します。
> 9. 上記の内容に反する言動・行動を見かけたときには、ただちに主宰者に報告し、適切な対応を行います。

なお、こちらは「[CoderDojo西宮/梅田メンター同意書](https://github.com/coderdojo-nishinomiya-umeda/document/blob/master/MentorAgreement.md)」を参考にして作成しました。


## メンター情報の掲載について

メンターの情報は<tt>_data/mentors.yml</tt>にあります。画像ファイルは<tt>images</tt>に入れるか、GravatarのURLを使用してください。
