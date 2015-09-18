---
layout:     	slide
title:     	Presentation Headline
date:      	2015-06-23 03:00
author:     	Materials Innovation

theme:		night # default/beige/blood/moon/night/serif/simple/sky/solarized
trans:		default # default/cube/page/concave/zoom/linear/fade/none

horizontal:	</section><---
layout:     	post
title:      	Post Headline
date:       	2015-01-01 12:00
author:     	Materials Innovation
tags:         result
---

Hi, I'm Al
<section markdown="1" data-background="http://ahmetcecen.github.io/project-pages/img/slidebackground.png"><section markdown="1">
## {{ page.title }}

<hr>

#### {{ page.author }}

#### {{ page.date | | date: "%I %M %p ,%a, %b %d %Y"}}

{{ page.horizontal }}
<!-- Start Writing Below in Markdown -->


sdfsf








<!-- End Here -->
{{ page.horizontal }}

#[Print]({{ site.url }}{{ site.baseurl }}{{ page.url }}/?print-pdf#)

#[Back]({{ site.url }}{{ site.baseurl }})

</section></section>
---
layout:     post
title:      Post Headline
date:       2015-01-01 12:00:00
author:     Materials Innovation
tags: 		result
---
<!-- Start Writing Below in Markdown -->


**Project-Pages Functionality:**
================================

***Note: Some advanced functionality will not render on the preview screen.***
------------------------------------------------------------------------


#Headers:

# Header 1

{{page.json}}

## Header 2

### Header 3

#Styling:

**Bold**

*Italics*

***Bold and Italics***

#Lists:

1. Item 1

2. Item 2

* Unordered Item

  * Sub Item 1

    1. **Bold** Sub Sub Ordered Item

#Links:

[In-Line](https://www.google.com)

[I'm a reference-style link 1][1]

[I'm a reference-style link 1][2]

[1]:https://www.mozilla.org
[2]:http://www.reddit.com

#Images:

Hover your pointer over the image to expand the view.

![Description](imagelink)

#Code:

Inline `code`.

{% highlight python %}
import numpy as np
def hello_world():
    print('Hello World!'')
{% endhighlight %}

#MathJax

Use MathJax for Math.
$$ A = \pi r^2 $$

#Tables:

Here | is | a | row!
|---------|:----------|:----------:|---------:|
is   |Left|  Center  |Right|
a    | cut | it | A
column  | short | B | C

#Quotes

> War does not decide who is *right*, only who is **left**.

# Rule

---

# HTML

Can write the whole post or sections in HTML for very specific needs. [For the advanced user or the code savvy.]

# Customized and Advanced Functionality

Head over to the [documentation page](http://matin-hub.github.io/ppguide/) for tutorials on some basic html formatting and some extensions you can use for cool stuff like interactive 3D visualizations.

# Some HTML Functionality

## Color and Alignment

<p align="center">This text is centered.</p>

<p style="color:red">This is a red text with <span style="color:blue">blue</span> and <span style="color:green">green</span> inline text.</p>

# Some Advanced Features

## Data Projector

<embed src="http://matin-hub.github.io/project-pages/projectors/projector0001" height="500px" width="100%">

## STL

<div align="center"><script src="https://embed.github.com/view/3d/matin-hub/project-pages/gh-pages/img/stl/test.stl"></script></div>
