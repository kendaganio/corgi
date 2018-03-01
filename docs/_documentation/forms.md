---
layout: default
title: Forms
---

# Forms
---

Forms are not styled by default, you need to add a `.form` class to enable styling.
Form control elements should be wrapped in a `fieldset` tag.

<div class="example">
  <div class="container preview">
    <form class="form">
      <fieldset id="" class="">
        <label for="name">Name</label>
        <input type="text" name="name" value="" id="name" placeholder="My nam jeff.">

        <label for="color">Color</label>
        <select name="color" id="color" size="1">
          <option value="red">Red</option>
          <option value="green">Green</option>
          <option value="blue">Blue</option>
        </select>
      
        <label for="description">Description</label>
        <textarea name="description" rows="10" cols="40">
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
  <fieldset id="" class="">
    <label for="name">Name</label>
    <input type="text" name="name" value="" id="name" placeholder="My nam jeff.">

    <label for="color">Color</label>
    <select name="color" id="color" size="1">
      <option value="red">Red</option>
      <option value="green">Green</option>
      <option value="blue">Blue</option>
    </select>
  
    <label for="description">Description</label>
    <textarea name="description" rows="10" cols="40">
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
