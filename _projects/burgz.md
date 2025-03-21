---
layout: page
title: APOCALUNCH RUSH
description: is a unique first-person cooking and tower defense “griller-killer.”
img: assets/img/12.jpg
importance: 1
category: work
related_publications: false
---

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        This project was developed in 15 weeks as apart of the <a href="https://games.usc.edu/">USC Games</a> CTIN-489 Intermediate Games Project course in collaboration with <a href="https://www.berklee.edu/">Berklee College of Music</a>.

        As Co-Designer, I worked on a team with one other designer to 
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/lunchrush1.png" title="example image" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid path="assets/img/lunchrush2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <embed src="https://drive.google.com/viewerng/
viewer?embedded=true&url=https://hemohorse.github.io/assets/pdf/APOCALUNCH_RUSH.pdf" width="500" height="375">
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
