---
title: Annotations and Drawing the Eye
layout: lecture
---

## Visual Techniques

In a data visualization, *what* we want to highlight or identify changes how we provide that highlight.

How do we highlight something, using exclusively visual representations?  For instance, we could:

 * Change a characteristic: make it different
 * Add an "external" overlay to indicate
 * Provide textual information

---

<iframe width="560" height="315" src="https://www.youtube.com/embed/FuzdCXzSwc0?start=64" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

## Types of Annotations

We'll talk about a few specific papers today:

 * ["ChartAccent: Annotation for Data-Driven Storytelling"](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8031599) by Ren et al
 * ["Designing a Classification for User-authored Annotations in Data Visualization"](https://www.scitepress.org/Papers/2018/66137/66137.pdf) by Vanhulst et al
 * ["Canis: A High-Level Language for Data-Driven Chart Animations"](https://donghaoren.org/publications/eurovis20-canis.pdf) by Ge et al

The first two papers are complementary, and approach annotations from different perspectives.  The final one develops a specification for animations and transitions.

---

## Dimensions of Annotation Types

Ren et al identify two primary dimensions for annotation types:

<div class="multiCol">
    <div class="col fragment">
    <h3>Annotation Form</h3>
    <ul>
        <li>Text</li>
        <li>Shapes</li>
        <li>Highlights</li>
        <li>Images</li>
        <li>Combinations</li>
    </ul>
    </div>
    <div class="col fragment">
    <h3>Annotation Target</h3>
    <ul>
        <li>Data components</li>
        <li>Coordinate space</li>
        <li>Chart element</li>
        <li>Prior annotations</li>
    </ul>
    </div>
</div>

---

## Transitions

A common method for implementing annotations as part of a narrative is through
transitions or animations.  The Canis framework, which you can experiment with
at [canisjs.github.io](https://canisjs.github.io/) provides a means of
describing how to animate between charts and animations.

Because Canis uses a particular dialect of SVGs that we haven't yet developed,
we're going to explore it, but will not be "teaching" it per se.

---

## Work Together

Today we're going to work on building a data story in these stages:


1. Identify and collect our data.
2. Explore the data.  (Do we need to do this?  Let's discuss...)
3. Determine our strategy.
   * What stories does the data tell us?
   * What is the story we will tell?
   * What dimension will we use?
4. Storyboard how we will tell it
   * Clearly delineate progression
   * Demonstrate annotations

---

## What Story?

We'll do a hybrid of working together and working in groups, and I'll ask you to take different approaches in different times.

 > What can we tell about libraries from the circulation at different branches in Chicago?

---

## Dimensions of Storytelling

For this story, I want each group to identify one of these three items as their "dimension."

1. Detail
2. Spatial
3. Temporal

What changes about your tactics based on these?

---

## Storyboard

Choose one method of telling the story:

1. Single infographic
2. Slides
3. Animation

What UI and other methods will you use to tell this?  What annotations?  How
will you describe the points to annotate, and what will you use to do so?

---

## Report back
