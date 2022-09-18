---
layout: default
section: Lablog
permalink: /circles/circle-theorems-cyclic-quadrilateral
maths: true
geogebra: true
geogebra-id: "dcjztd3y"
geogebra-height: 380
geogebra-width: 335
title: Circle theorems - cyclic quadrilateral
description: A cyclic quadrilateral has each of its four points on a circle. We discuss and prove that opposite angles of a cyclic quadrilateral sum to 180&deg;.
---

# Circle theorems: cyclic quadrilateral opposite angles

{% include nav_circles.html %}

## Cyclic quadrilateral definition

A cyclic quadrilateral is one whose four vertices can be placed on the circumference of a circle. Not all quadrilaterals are cyclic.

## Two results

1. Opposite angles of a cyclic quadrilateral sum to 180&deg;.
1. On the minor arc &ang;BQA is constant.

From the [inscribed angle theorem]({% post_url /lablog/circles/2021-03-03-circle-theorems-inscribed-angle %}) the angle a chord makes with a point on its major arc is constant. Putting this together with (1) leads immediately to (2).

## Try it yourself

We've seen this diagram before - for the inscribed angle theorem, where the point Q is not usually drawn. But here it allows us to draw a cyclic quadrilateral.

In the diagram below you can move around any point except O.

Before we do this, let's think about the set up, to ensure we don't fall into a diagram dependency trap.

Four points on a circle might appear to be awkwardly placed: perhaps all fall one side of a diameter. But in any situation we can draw a line between the first and third points, A and B, rotating the diagram so that the AB chord is horizontal.

We now have P on the major arc and Q on the minor arc. We do not know the length of AB, the exact positioning of P or Q or the angles &ang;APB or &ang;AQB.

<div id="geogebra" class="displayed"></div>

But just have a play. Move A and B around until you're happy. Then keep A and B fixed and move P and/or Q. Note that:

1. &ang;APB is constant, as expected from the [inscribed angle theorem]({% post_url /lablog/circles/2021-03-03-circle-theorems-inscribed-angle %}).
1. &ang;APB + &ang;AQB = 180&deg;.
1. &ang;AQB is constant.

## A misleading traditional proof?

<div class="clearfix">
<img style="float:left; padding-right:25px;" src="/assets/img/circles/cyclic-quadrilateral-proof-trad.png">

<p>The proof at <a href="https://www.bbc.co.uk/bitesize/guides/z3c7tv4/revision/4">BBC bitesize</a> - essentially summarized to the left - seems misleading. It <b>assumes</b> the constant angle on a minor arc result, but they have proved only the major arc result.</p>

<p>The problem is that the x and 2x parts have not been justified, nor is it obvious why we can assume that O is inside &Delta;CEF.</p>

<p>Our proof is quite different.</p>
</div>

## The quadrilateral proof

This is my own proof, though it would be a surprise if it existed nowhere else.

From the [inscribed angle theorem]({% post_url /lablog/circles/2021-03-03-circle-theorems-inscribed-angle %}) we know that &ang;APB is constant (= &alpha; say) as P varies over the major arc. For any given Q this means that &ang;APB + &ang;AQB is constant as P varies over the major arc.

**This means that we are allowed to choose P conveniently.** This is a rather neat reversal of my normal diagram dependency proof critique.

We choose P so that O lies within the &Delta;APB. We draw additional radii OP and OQ. We then have four isosceles triangles. We set their equal angles &alpha;, &beta;, &gamma;, and &delta; as shown.

![convenient cyclic quadrilateral](/assets/img/circles/cyclic-quadrilateral-proof.png "convenient cyclic quadrilateral")

<p>The sum of the angles in the four triangles is also the sum of the labelled angles plus those around the centre of the circle. So 4*180&deg; = 360&deg; + 2(&alpha; + &beta; + &gamma; + &delta;).</p>

Rearranging, we have 180&deg; = (&alpha; + &beta;) + (&gamma; + &delta;) = &ang;APB + &ang;AQB, as required. &#8718;

## The angle on minor arc proof

We knew that on the major arc &ang;APB is constant. We now know that &ang;APB + &ang;AQB is constant and equal to 180&deg;. We deduce that on the minor arc &ang;AQB is constant and is equal to 180&deg; - &ang;APB.

## Where next?

After all that excitement it's time for the technical [tangent radius]({% post_url /lablog/circles/2021-03-05-circle-theorems-tangent-radius %}) theorem.
