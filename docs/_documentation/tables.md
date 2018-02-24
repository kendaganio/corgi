---
layout: default
title: Tables
---

### Tables
---

Tables can be styled by using the `table` class.
<div class="example">
  <div class="container preview">
    <table class="table">
      <thead>
        <th>Name</th>
        <th>Handle</th>
        <th>Github</th>
      </thead>
      <tbody>
        <tr>
          <td>Ken</td>
          <td>sw1tchblade</td>
          <td>@kendaganio</td>
        </tr>
        <tr>
          <td>Marlon</td>
          <td>mrloan</td>
          <td>@marlonperillo</td>
        </tr>
        <tr>
          <td>Jhed</td>
          <td>h0neystar</td>
          <td>@johncrisostomo</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>
{% highlight html %}
<table class="table">
  <thead>
    <th>Name</th>
    <th>Handle</th>
    <th>Github</th>
  </thead>
  <tbody>
    <tr>
      <td>Ken</td>
      <td>sw1tchblade</td>
      <td>@kendaganio</td>
    </tr>
    <tr>
      <td>Marlon</td>
      <td>mrloan</td>
      <td>@marlonperillo</td>
    </tr>
    <tr>
      <td>Jhed</td>
      <td>h0neystar</td>
      <td>@johncrisostomo</td>
    </tr>
  </tbody>
</table>
{% endhighlight %}

You can add borders to all cells by adding a `-bordered` modifier. Also adding a `-full-width` modifier will make it expand to fit it's container's width.
<div class="example">
  <div class="container preview">
    <table class="table -bordered -full-width">
      <thead>
        <th>Name</th>
        <th>Creature Type</th>
      </thead>
      <tbody>
        <tr>
          <td>Ely</td>
          <td>Pupper</td>
        </tr>
        <tr>
          <td>Minguk</td>
          <td>Smol Tiger</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>
{% highlight html %}
<table class="table -bordered -full-width">
  <thead>
    <th>Name</th>
    <th>Creature Type</th>
  </thead>
  <tbody>
    <tr>
      <td>Ely</td>
      <td>Pupper</td>
    </tr>
    <tr>
      <td>Minguk</td>
      <td>Smol Tiger</td>
    </tr>
  </tbody>
</table>
{% endhighlight %}

The `-narrow` modifier will reduce the padding within the cells for thinner tables.
<div class="example">
  <div class="container preview">
    <table class="table -narrow">
      <thead>
        <th>Name</th>
        <th>Creature Type</th>
      </thead>
      <tbody>
        <tr>
          <td>Manse</td>
          <td>Crocodile</td>
        </tr>
        <tr>
          <td>Oreo</td>
          <td>Skunk</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>
{% highlight html %}
<table class="table -narrow">
  <thead>
    <th>Name</th>
    <th>Creature Type</th>
  </thead>
  <tbody>
    <tr>
      <td>Manse</td>
      <td>Crocodile</td>
    </tr>
    <tr>
      <td>Oreo</td>
      <td>Skunk</td>
    </tr>
  </tbody>
</table>
{% endhighlight %}
