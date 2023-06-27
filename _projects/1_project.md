---
layout: page
title: [NSF RETTL]
description: [Using Artificial Intelligence to Transform Online Video Lectures into Effective and Inclusive Agent-Based Presentations]
img: assets/img/pro_1_a.png
importance: 1
category: work
---

Students in introductory STEM courses frequently encounter video lectures that include an instructor standing next to a progression of slides. A challenge with these video lectures is that students may lose interest in science when they see the instructors as unhelpful (e.g., when they portray negative emotions while teaching) or unwelcoming (e.g., when they do not reflect the gender, ethnic, and racial diversity of the audience). This project aims to develop, validate, study, and make publicly available an artificial-intelligence (AI)-based framework that takes existing online instructional video lectures on introductory STEM topics created by human instructors and transforms them into instructionally effective and inclusive agent-based presentations. This work is intended to help improve science instruction and attract students from under-represented groups.

The research team will apply artificial intelligence methods to extract gesture and voice from instructional videos with human instructors and transform them into instruction delivered by a diverse set of emotionally and socially sensitive onscreen animated embodied agents. Experimental research studies will investigate: 1) whether students learn better from an AI-transformed version of a video lecture than the original instructor-made video lecture; and 2) which features of onscreen agents in AI-transformed video lectures produce improved learning outcomes and processes, comparing delivery from an onscreen agent who does or does not match the student's gender, ethnicity, or race. Overall, results from the project will impact access to high-quality inclusive STEM learning experiences.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/pro_1_b.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/pro_1_c.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/pro_1_d.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, Comparison Between Instructor and Virtual Agent. Middle, Database of Virtual Agent. Right, AI-Transformed Lecture.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
	<iframe class="responsive-iframe" frameborder="" src="https://itch.io/embed-upload/7654651?color=333333" allowfullscreen=""></iframe>
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


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
