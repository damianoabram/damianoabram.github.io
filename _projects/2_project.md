---
layout: page
title: via della soddisfazione - cima d'ambiez - dolomiti di brenta
description:
img: assets/img/3.jpg
importance: 1
category: climbs
---

On the 24th June 2018 with my friend Francesco. One of the craziest experiences in my life, but also a very fun one.

There is a fundamental rule in the mountains: wake up early. The weather is more stable in the morning. The longer we remain on the wall in the afternoon, the higher are the chances of being caught in a storm, surrounded by lightnings that are more than happy to hit us, if we make their way to the ground easier. Being high up on a mountain with a lot of metallic equipement, this is not so unlikely. So, around 6 a.m., we were in San Lorenzo Dorsino, ready to take the old Land Rover Defender taxi, full with other sleepy alpinists, that would have taken us up the wavy dirt road of Val d'Ambiez. The driver left us at Rifugio Cacciatore with the promise of meeting again at 4 p.m. for the ride home. From Rifugio Cacciatore, we hiked up other 800m with our ropes on the shoulders, until we reached the base of the beautiful 400m wall of Cima d'Ambiez, made of one of the best and most compact rock in the dolomites. We would have climbed a route called [Via della Soddisfazione](https://www.sassbaloss.com/pagine/uscite/cimaambiez2/cimaambiez2.htm), UIAA VI, no bolts, a few pegs here and there, for the rest we would have had to rely on nuts and cams. Since I don't know how to use this gear, Francesco would have climbed first, placing all the protections. I would have followed soon after retrieving all the gear he had jammed in the cracks and the other features of the wall.

The beginning was quite promising, no clouds in the sky, a gentle sun warming up our skin, beautiful cliffs and amazing climb. Around 10 a.m., the renowned white mists of Val d'Ambiez slowly made their appearance. Although we had to give up on the nice sun, we were still excited: when the fog rises, mountains become even more beautiful and mysterious. Their shape keeps mutating, providing glimpses of a reality inaccessible on clear, sunny days. With our minds captured by those views, we continued our climb.  The rock slowly acquired a reddish shade and even the shape of the holds changed: in thousands of years, the water dripping from the wall has dug many tiny vertical holes the size of a finger tip. Climbing on such features is always a joy!

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/cimadambiez.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The wall of Cima d'Ambiez. Via della Soddisfazione is marked in pink.
</div>




To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal it's glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
