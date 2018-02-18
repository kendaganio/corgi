---
layout: default
title: Layout
---

# Layout Components
---

#### Containers

A container may be any element with a <code>.container</code> class. It adds padding to all sides.

<div id="container-demo" class="example">
  <div class="preview">
    <div class="container">
      I am a container 
    </div> 
  </div>
</div>

{% highlight html %}
<div class="container">
  I am a container
</div>
{% endhighlight %}


#### Columns

You can create a <code>.columns</code> element and add as many <code>.column</code> children you want
inside, and they will alway span equal width. This is all possible thanks to [flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox).

<div id="columns-demo" class="example">
  <div class="preview">
    <div class="columns">
      <div class="column text-center">
        <div class="box">.column</div>
      </div>
      <div class="column text-center">
        <div class="box">.column</div>
      </div>
      <div class="column text-center">
        <div class="box">.column</div>
      </div>
    </div> 
  </div>
</div>

{% highlight html %}
<div class="columns">
  <div class="column">
    <div class="box">.column</div>
  </div>
  <div class="column">
    <div class="box">.column</div>
  </div>
  <div class="column">
    <div class="box">.column</div>
  </div>
</div> 
{% endhighlight %}


#### Grid

Please consider learning [CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/grid)
