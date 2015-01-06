---
layout: post
title: jekyll-scholar 사용하기
comments: true
#redirect_from: "2014/07/31/how-to-use-jekyll-scholar/"
#permalink: how-to-use-jekyll-scholar
category: Writing
tags: [jekyll, plugins, jekyll-scholar, Markdown]
---

### 논문 인용하기

본문중에서 다음과 같이 하면 된다.

{% highlight ruby %}
{% raw %}{% cite oh2013fit -f my/oh2013fit %}{% endraw %}
{% endhighlight %}


### 참고문헌 넣기

{% highlight ruby %}
{% raw %}{% bibliography -f my/oh2013fit.bib %}{% endraw %}
{% endhighlight %}
