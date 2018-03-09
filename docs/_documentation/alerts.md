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
<div class="alert -danger">It's dangerous out there!</div>
<div class="alert -primary">Welcome, old friend.</div>
<div class="alert -success">Good job!</div>
{% endhighlight %}

The alert component comes with a built-in close button to dismiss the alert. You
need to add your own custom Javascript to make this work for your needs.

<div class="example">
  <div class="container preview">
    <div class="alert -success">
      Congratulations! Your order has been completed.
      <button class="close">&#x2715;</button>
    </div>
  </div>
</div>

{% highlight html %}
<div class="alert -success">
  Congratulations! Your order has been completed.
  <button class="close">&#x2715;</button>
</div>
{% endhighlight %}
