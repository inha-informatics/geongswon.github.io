---
layout: page
title: Style Guide
image: '/images/pages/styleguide.jpg'
---
*기울기*라 적으면 기울기처럼 글자를 기울일 수 있습니다.

**굵게**라 적으면 굵게처럼 글자를 굵게 표시할 수 있습니다.

***굵게***라 적으면 굵으며 기운처럼 글자를 굵으면서도 기울게 표시할 수 있습니다.

<U>밑줄</U>라 적으면 밑줄처럼 밑줄을 그을 수 있습니다.

{% highlight js %}
'use strict';
var markdown = require('markdown').markdown;
function Editor(input, preview) {
  this.update = function() {
    preview.innerHTML = markdown.toHTML(input.value);
  };
  input.editor = this;
  this.update();
}
{% endhighlight %}

You can add inline code just like this, E.g. `.code { color: #fff; }`

{% highlight css %}
pre {
  background-color: #f4f4f4;
  max-width: 100%;
  overflow: auto;
}
{% endhighlight %}

---

Cras sed sodales enim. Duis nec erat magna. Sed scelerisque pretium mi et [unsplash](https://unsplash.com/) ullamcorper mauris aliquam ornare fringilla. In luctus commodo quam eget posuere.

---

<iframe src="https://player.vimeo.com/video/97202679" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

---

<iframe src="https://embed.ted.com/talks/ted_halstead_a_climate_solution_where_all_sides_can_win" width="640" height="360" frameborder="0" scrolling="no" allowfullscreen></iframe>

---

<iframe width="100%" height="166" scrolling="no" frameborder="no" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/29738591&amp;color=ff5500&amp;auto_play=false&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false"></iframe>

---

<p data-height="265" data-theme-id="light" data-slug-hash="YWvpRo" data-default-tab="css,result" data-user="kharrop" data-embed-version="2" data-pen-title="Referral Form" class="codepen">See the Pen <a href="http://codepen.io/kharrop/pen/YWvpRo/">Referral Form</a> by Kelly Harrop (<a href="http://codepen.io/kharrop">@kharrop</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="https://production-assets.codepen.io/assets/embed/ei.js"></script>

---

![about](/images/pages/about.jpeg)

---

<input type="text" placeholder="I'm an input field!">

---

<button class='c-btn c-btn--small'>Button</button>

<button class='c-btn'>Button</button>

<button class='c-btn c-btn--full'>Button</button>

{% highlight html %}
<button class='c-btn c-btn--small'>Button</button>
<button class='c-btn'>Button</button>
<button class='c-btn c-btn--full'>Button</button>
{% endhighlight %}
