---
layout: default
title: Buttons
---

# Buttons
---

You may attach the `.button` to class to an input, button, or anchor element.

<div class="example">
  <div class="container preview">
    <button class="button">Button</button>
    <input class="button" type="submit" value="Submit"/>
    <a class="button" href="#">Anchor</a>
  </div>
</div>

{% highlight html %}
<button class="button">Button</button>
<input class="button" type="submit" value="Submit"/>
<a class="button" href="#">Anchor</a>
{% endhighlight %}

By default you have four color modifiers for buttons namely: `-default`, `-primary`, `-danger`, and `-success`

<div class="example">
  <div class="container preview">
    <button class="button -default">Button</button>
    <button class="button -primary">Primary</button>
    <input class="button -success" type="submit" value="Submit"/>
    <a class="button -danger" href="#">Anchor</a>
  </div>
</div>

{% highlight html %}
<button class="button -default">Button</button>
<button class="button -primary">Button</button>
<input class="button -success" type="submit" value="Submit"/>
<a class="button -danger" href="#">Anchor</a>
{% endhighlight %}

If you don't care for the default button styles you have `-outline` styled buttons as well.

<div class="example">
  <div class="container preview">
    <button class="button -outline">Default</button>
    <button class="button -primary-outline">Primary</button>
    <button class="button -danger-outline">Danger</button>
    <button class="button -success-outline">Success</button>
  </div>
</div>

{% highlight html %}
<button class="button -outline">Default</button>
<button class="button -primary-outline">Primary</button>
<button class="button -danger-outline">Danger</button>
<button class="button -success-outline">Success</button>
{% endhighlight %}

