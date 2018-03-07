---
layout: default
title: Navigation
---

# Navigation
---

#### Navbar

A navbar is a `nav` element with the `.navbar` class. Inside the `nav` you can nest `ul` elements with
the classes `.navbar-left` and `.navbar-right`. By default the `ul` element will flow from the left.

<div class="example">
  <div class="container preview">
    <nav class="navbar">
      <ul class="navbar-left">
        <li>
          <a href="" target="_blank">Home</a>
        </li>
        <li>
          <a href="" target="_blank">About</a>
        </li>
        <li>
          <a href="" target="_blank">Contact</a>
        </li>
      </ul>

      <ul class="navbar-right">
        <li>
          <a href="" target="_blank">Login</a>
        </li>
        <li>
          <a href="" target="_blank">Sign up</a>
        </li>
      </ul>
    </nav>
  </div>
</div>
{% highlight html %}
<nav class="navbar">
  <ul class="navbar-left">
    <li>
      <a href="" target="_blank">Home</a>
    </li>
    <li>
      <a href="" target="_blank">About</a>
    </li>
    <li>
      <a href="" target="_blank">Contact</a>
    </li>
  </ul>

  <ul class="navbar-right">
    <li>
      <a href="" target="_blank">Login</a>
    </li>
    <li>
      <a href="" target="_blank">Sign up</a>
    </li>
  </ul>
</nav>
{% endhighlight %}
