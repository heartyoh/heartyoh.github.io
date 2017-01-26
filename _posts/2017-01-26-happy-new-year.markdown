---
layout: post
title:  "새해 복 많이 받으세요!"
date:   2017-01-26 17:31:27 +0900
categories: happy new year
---
{% highlight javascript %}
var 연휴 = ['설전날', '설날', '설다음날'];
연휴.push('대체휴일');
연휴.forEach((공휴일) => {
  console.warn(`☕ 일해야지. ${공휴일}`);
})
// ☕ 일해야지. 설전날
// ☕ 일해야지. 설날
// ☕ 일해야지. 설다음날
// ☕ 일해야지. 대체휴일
{% endhighlight %}
