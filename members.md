---
title: Members
feature_text: |
  ## Current and Past Research Group Members
feature_image: "/assets/nobbys_beach.png"
excerpt: "A demo of Markdown and HTML includes"
aside: true
---
### Principal Investigator

{% include figure.html image="/assets/current/20140826JR023.png" position="left" caption="Peter T. Cummings" width="200" %}
<small>Peter Cummings is the John R. Hall Professor of Chemical Engineering at Vanderbilt University.</small>

<small>Education: B. Math (Hons I), University of Newcastle, Australia (1976); Ph.D., University of Melbourne, Australia (1980)</small>

<small>Peter Cummings' web page at Vanderbilt University is available [here.](https://engineering.vanderbilt.edu/bio/peter-cummings "here.")</small>

<small> </small>

### Research Faculty 

{% include figure.html image="/assets/current/chris_iacovella.jpg" position="left" caption="Christopher R. Iacovella" width="200" %}
<small>Chris is Research Assistant Professor of Chemical and Biomolecular Engineering at Vanderbilt University, working with Peter Cummings and [Clare McCabe.](https://engineering.vanderbilt.edu/bio/clare-mccabe "Clare McCabe.")</small>

<small>Education: B.S., Chemical Engineering, University of Buffalo, (XXXX); Ph.D., University of Michigan (XXXX)</small>

<small>Chris Iacovella's web page at Vanderbilt University is available [here.](https://engineering.vanderbilt.edu/bio/christopher-iacovella "here.") Chris works with graduate students and postdoctoral fellows on multiple projects.</small>

<small> </small>

### Postdoctoral Researchers

{% include figure.html image="/assets/current/wei_zhao.jpg" position="left" caption="Wei Zhao" width="200" %}
<small>Wei is performing research on systems relevant to capacitive energy storage devices.</small>

<small>Education: B.S., (XXXX); Ph.D., , (XXXX) </small>


### Graduate Students

{% include figure.html image="/assets/current/justin_gilmer.jpg" position="left" caption="Justin B. Gilmer" width="200" %}
<small>Justin is performing research on nanotribological systems and is a lead developer of [MoSDeF.](https://mosdef.org "MoSDeF.")</small>

<small>Education: B.S., Materials Science, Clemson University, (2016) </small>

<small> </small>

<small> </small>

<small> </small>

<small> </small>

<small> </small>

{% include figure.html image="/assets/current/ray_matsumoto.jpg" position="left" caption="Ray Matsumoto" width="200" %}
<small>Ray is performing simulation of systems relevant to capacitive energy storage devices. He also contributes to the development of [MoSDeF.](https://mosdef.org "MoSDeF.")</small>

<small>Education: B.S., Materials Science, Clemson University, (2015) </small>

<small> </small>

<small> </small>

<small> </small>

<small> </small>

<small> </small>

{% include figure.html image="/assets/current/co_quach.jpg" position="left" caption="Co D. Quach" width="200" %}
<small>Co perform research on nanotribological systems and is a contributor and maintainer of [MoSDeF.](https://mosdef.org "MoSDeF.")</small>

<small>Education: B.S., Chemistry and Applied Mathematics, Millsaps College, (2018) </small>

<small> </small>

<small> </small>

<small> </small>

<small> </small>

<small> </small>

{% include figure.html image="/assets/current/xiaobo_lin.jpg" position="left" caption="Xiaobo Lin" width="200" %}
<small>Xiaobo is performing simulation of systems relevant to capacitive energy storage devices.</small>

<small>Education: B.S., Chemical Engineering, Qingdao University of Science of Technology, (2017); Masters, Chemical Engineering, Northwestern University (2019) </small>


##### Heading 5

###### Heading 6

<small>A small element</small>

[A link](https://david.darn.es "A link")

Lorem ipsum dolor sit amet, consectetur adip* isicing elit, sed do eiusmod *tempor incididunt ut labore et dolore magna aliqua.

Duis aute irure dolor in [A link](https://david.darn.es "A link") reprehenderit in voluptate velit esse cillum **bold text** dolore eu fugiat nulla pariatur. Excepteur span element sint occaecat cupidatat non proident, sunt _italicised text_ in culpa qui officia deserunt mollit anim id `some code` est laborum.

* An item
* An item
* An item
* An item
* An item

1. Item one
2. Item two
3. Item three
4. Item four
5. Item five

> A simple blockquote

Some HTML...

``` html
<blockquote cite="http://www.imdb.com/title/tt0284978/quotes/qt1375101">
  <p>You planning a vacation, Mr. Sullivan?</p>
  <footer>
    <a href="http://www.imdb.com/title/tt0284978/quotes/qt1375101">Sunways Security Guard</a>
  </footer>
</blockquote>
```

...CSS...

``` css
blockquote {
  text-align: center;
  font-weight: bold;
}
blockquote footer {
  font-size: .8rem;
}
```

...and JavaScript

``` js
const blockquote = document.querySelector("blockquote")
const bolden = (keyString, string) =>
  string.replace(new RegExp(keyString, 'g'), '<strong>'+keyString+'</strong>')

blockquote.innerHTML = bolden("Mr. Sullivan", blockquote.innerHTML)
```

`Single line of code`

## HTML Includes

### Contact form

{% include site-form.html %}

``` html
{% raw %}{% include site-form.html %}{% endraw %}
```

### Demo map embed

{% include map.html id="1UT-2Z-Vg_MG_TrS5X2p8SthsJhc" title="Coffee shop map" %}

``` html
{% raw %}{% include map.html id="XXXXXX" title="Coffee shop map" %}{% endraw %}
```

### Button include

{% include button.html text="A button" link="https://david.darn.es" %}

{% include button.html text="A button with icon" link="https://twitter.com/daviddarnes" icon="twitter" %}

``` html
{% raw %}{% include button.html text="A button" link="https://david.darn.es" %}
{% include button.html text="A button with icon" link="https://twitter.com/daviddarnes" icon="twitter" %}{% endraw %}
```

### Icon include

{% include icon.html id="twitter" title="twitter" %} [{% include icon.html id="linkedin" title="twitter" %}](https://www.linkedin.com/in/daviddarnes)

``` html
{% raw %}{% include icon.html id="twitter" title="twitter" %}
[{% include icon.html id="linkedin" title="twitter" %}](https://www.linkedin.com/in/daviddarnes){% endraw %}
```

### Video include

{% include video.html id="zrkcGL5H3MU" title="Siteleaf tutorial video" %}

``` html
{% raw %}{% include video.html id="zrkcGL5H3MU" title="Siteleaf tutorial video" %}{% endraw %}
```


### Image includes

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Image with caption" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Right aligned image" position="right" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Left aligned image" position="left" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/1600/800?image=894" alt="Image with just alt text" %}

``` html
{% raw %}{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Image with caption" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Right aligned image" position="right" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/600/800?image=894" caption="Left aligned image" position="left" width="300" height="800" %}

{% include figure.html image="https://picsum.photos/1600/800?image=894" alt="Image with just alt text" %}{% endraw %}
```
