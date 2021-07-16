---
title: "Git Branch"
date: 2021-07-12 15:17:20 +0900
categories: TIL
---

<h2>Git Branch</h2>
원본 버전은 유지한 상태에서 다른 기능을 추가하고 싶을 때 branch를 사용한다.
branch는 뜻 그대로 가지를 생각하면 이해하기가 싶다. 동료와 협업이나 다른 기능을 넣을 때 branch를 이용해 분기한다.

<h3>사용법</h3>

{% highlight ruby %}
git branch # 뒤에 원하는 branch이름을 작성하면 branch가 현재 HEAD에 생성됨
git checkout # 원하는 branch로 이동
{% endhighlight %}

<h3>merge</h3>

{% highlight ruby %}
git merge # 합칠 branch(ex.master)에서 합쳐질 branch를 입력함
{% endhighlight %}

--3way branch
