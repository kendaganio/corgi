---
layout: default
title: Layout
---

# Layout Components
---

#### Containers

A container may be any element with a `.container` class. It adds padding to all sides.

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

You can create a `.columns` element and add as many `.column` children you want
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

The `columns` class comes with the `-unpadded` modifier to remove default padding.
<div class="example">
  <div class="preview">
    <div class="columns -unpadded">
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
<div class="columns -unpadded">
  <div class="column">
    <div class="box">.column</div>
  </div>
  <div class="column">
    <div class="box">.column</div>
  </div>
</div> 
{% endhighlight %}

You may nest a `columns` container inside a `column` and it will take the width of the parent column
and make equal width children. It's a good idea to add the `-unpadded` modifier to the nested `columns` 
element to lessen padception.

<div class="example">
  <div class="preview">
    <div class="columns">
      <div class="column text-center">
        <div class="box">.column</div>
        <div class="columns -unpadded">
          <div class="column text-center">
            <div class="box">I am</div>
          </div>
          <div class="column text-center">
            <div class="box">nested</div>
          </div>
        </div>
      </div>
      <div class="column text-center">
        <div class="box">Ignore me.</div>
      </div>
    </div> 
  </div>
</div>

{% highlight html %}
<div class="columns">
  <div class="column">
    <div class="box">.column</div>

    <!-- Nested .columns, because why not -->
    <div class="columns -unpadded">
      <div class="column">
        <div class="box">I am</div>
      </div>
      <div class="column">
        <div class="box">nested</div>
      </div>
    </div>
  </div>

  <div class="column">
    <div class="box">Ignore me.</div>
  </div>
</div> 
{% endhighlight %}


#### Grid

Please consider learning [CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/grid)
