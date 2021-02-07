---
title: Research
feature_text: |
  ## Research
feature_image: "/assets/nobbys_beach.png"
excerpt: "Description of research in Cummings group"
aside: true
---

The research in our group, which is computational in nature, falls into three main categories.

A significant focus of our scientific/engineering research is focused on capacitive energy storage systems - specifically [supercapacitors.](https://en.wikipedia.org/wiki/Supercapacitor "supercapacitors."), described in section 1 below. This research consists of both purely computational studies as well as research that is highly intergrated with experiment and synthesis. 

Another major science focus is on transport phenomena at the nanoscale - specifically [friction](https://en.wikipedia.org/wiki/Friction "friction") and [tribology.](https://en.wikipedia.org/wiki/Tribology "tribology.") When two surfaces, separated by distances of the order of nanometers, move with respect to each other, friction must be reduced via a lubricant. The typical lubricants used at the macroscale (e.g., the oil use to lubricates an automobile engine) do not function as lubricants when confined to distances of the order of nanometers. Hence, new lubricants must be discovered, and we aim to do this via molecular simulation. Pleas see section 2 below. 

All of our research is conducted using molecular simulation methods. Molecular simulation is a methodology for predicting the collective (in particular, thermodynamic and transport) properties of systems from information about how the molecules in the system interact with each other; this information is encapsulated in so-called [force fields](https://en.wikipedia.org/wiki/Force_field_(chemistry) "force fields"). Two major types of molecular simulations are routinely performed: molecular dynamics, in which Newton’s equations, or a convenient variation thereof, are solved for the dynamics of each atom in the system, and Monte Carlo simulation, in which configurations of the system are generated via a Markov chain process that asymptotically are distributed according to the appropriate equilibrium probability. Properties of interest are then computed as averages over the confugurations generated. Molecular simulation is a complex computational method with many intricacies involved in obtaining useful, reproducible results. Over the last decade, we have been developing the open-source Molecular Simulation Design Framework [(MoSDeF)](https://mosdef.orf "(MoSDeF)") that facilitates the development and execution of complex molecular simulations while making the simulations fully reproducible. Our efforts to develop MoSDeF are described in Section 3 below.

#### 1. Molecular Modeling of Systems Relevant to Capacitive Energy Storage Devices
Our research usinbg molecular modeling to understand, and ultimately predict, the physical properties of systems relevant to capacitive energy storage devices is funded by the Department of Energy Office of Science through an [Engineering Frontier Research Center](https://www.energyfrontier.us "Energy Frontier Research Center") called the Fluid Interface Reactions Structures and Trasnport (or [FIRST](https://web.ornl.gov/sci/first/ "FIRST") Center.

#### 2. Nanoscale Friction and Tribology

#### 3. Open-Source Software Development - The Molecular Simulation Design Framework (MoSDeF)


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
