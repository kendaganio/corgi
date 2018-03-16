---
layout: default
title: Forms
---

# Forms
---

To style a form add a `.form` class to the form element. Input elements should be 
inside a `fieldset` element, and with a `.control` class.

<div class="example">
  <div class="container preview">
    <form class="form">
      <fieldset>
        <label for="name">Name</label>
        <input type="text" class="control" name="name" value="" id="name" placeholder="My nam jeff.">

        <label for="color">Color</label>
        <select class="control" name="color" id="color" size="1">
          <option value="red">Red</option>
          <option value="green">Green</option>
          <option value="blue">Blue</option>
        </select>
      
        <label for="description">Description</label>
        <textarea name="description" class="control" rows="10" cols="40">
This is some really long text
        </textarea>
        
        <label class="checkbox" for="check">
          <input type="checkbox" name="check" id="check">
          I'm a checkbox!
        </label>
        <label class="checkbox" for="check2">
          <input type="checkbox" name="check2" id="check2k">
          I'm another checkbox!
        </label>
        <br/>

        <input class="button -primary" type="submit" value="Let's go!">
      </fieldset>
    </form>
  </div>
</div>

{% highlight html %}
<form class="form">
  <fieldset>
    <label for="name">Name</label>
    <input type="text" class="control" name="name">

    <label for="color">Color</label>
    <select class="control" name="color" id="color" size="1">
      <option value="red">Red</option>
      <option value="green">Green</option>
      <option value="blue">Blue</option>
    </select>
  
    <label for="description">Description</label>
    <textarea name="description" class="control" rows="10" cols="40">
      This is some really long text
    </textarea>
    
    <label class="checkbox" for="check">
      <input type="checkbox" name="check" id="check">
      I'm a checkbox!
    </label>
    <label class="checkbox" for="check2">
      <input type="checkbox" name="check2" id="check2k">
      I'm another checkbox!
    </label>
    <br/>

    <input class="button -primary" type="submit" value="Let's go!">
  </fieldset>
</form>
{% endhighlight %}
