---
layout: page
title: Japan.R
---
{% include JB/setup %}

<img src="./images/logo.jpg">

## Japan.R とは
日本各地で統計処理ソフトウェアである R に関する勉強会が行われています。

* [Tokyo.R](http://groups.google.co.jp/group/r-study-tokyo)
* [Tokyo.R 女子部](http://atnd.org/events/40519)
* [Tsukuba.R](http://wiki.livedoor.jp/syou6162/)
* [Wako.R](http://atnd.org/events/39314)
* [Nagoya.R](http://corpus-study.info/nagoyar/)
* [Osaka.R](https://sites.google.com/site/osakarwiki/)
* [Shiga.R](http://atnd.org/events/5939)
* [Hirosima.R](http://atnd.org/events/16115)
* [沖縄R同好会(Okinawa.R)](http://www.facebook.com/okinawa.r)

これらの勉強会の主催者や参加者が年に一度集まって開催されるイベントがJapan.Rです。

### 現在予定しているイベント

* Japan.R 2013　開催日未定

### 過去に開催したイベント

* [第3回Japan.R](./pages/2012)　2012年12月1日（土）開催
* 第2回Japan.R　2011年11月26日（土）開催
    * [午前の部: はじめての「R」](http://atnd.org/events/22043)
    * [午後の部: ブースセッション、LT大会](http://atnd.org/events/22044)
    * [懇親会](http://atnd.org/events/22046)
* 第1回Japan.R　2010年11月27日（土）開催
    * [午前の部: はじめての「R」](http://atnd.org/events/9223)
    * [午後の部](http://atnd.org/events/9806)
    * [懇親会](http://atnd.org/events/10042)

## 新着情報

<ul class="posts">
  {% for post in site.posts %}
  <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
