---
layout: default
title: Alerts
---

# Alerts
---

To create an alert you just add a `.alert` class to a `div`. You may also add
modifiers to change it's context.

<div class="example">
  <div class="container preview">
    <div class="alert">I'm boring.</div>
    <div class="alert -danger">It's dangerous out there!</div>
    <div class="alert -primary">Welcome, old friend.</div>
    <div class="alert -success">Good job!</div>
  </div>
</div>

{% highlight html %}
<div class="alert">I'm boring.</div>
<div class="alert -danger">
  It's dangerous out there!
  <span class="close">x</span>
</div>
<div class="alert -primary">Welcome, old friend.</div>
<div class="alert -success">Good job!</div>
{% endhighlight %}
