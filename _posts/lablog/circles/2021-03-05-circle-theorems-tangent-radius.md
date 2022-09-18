---
layout: default
section: Lablog
permalink: /circles/circle-theorems-tangent-radius
maths: true
geogebra: false
title: Circle theorems - tangent radius
description: The angle between a circle's radius and the tangent at its end is 90&deg;. Proofs of this obvious result can be complex. We offer a straightforward proof.
---

# Circle theorems: tangent radius

{% include nav_circles.html %}

## Statement

The angle between a circle's radius and the tangent at its end is 90&deg;.

This is my least favourite circle theorem. While the result seems clear [discussions](https://math.stackexchange.com/questions/158955/how-to-prove-that-the-tangent-to-a-circle-is-perpendicular-to-the-radius-drawn-t) suggest people find it hard to prove or disagree over what is an acceptable proof. 

This and the risk of diagram dependency this is largely what put me off geometry years ago. Let's take a careful look.

## A simple fully constructive proof

Draw a diameter AB and construct a perpendicular diameter PQ, using the standard  [perpendicular bisector construction](https://www.mathopenref.com/constbisectline.html). Construct a line A'B' parallel to AB through Q using [this neat method](https://www.mathopenref.com/constparalleltt.html).

![tangent radius](/assets/img/circles/tangent-radius-constructive-proof.png "tangent radius")

AB and A'B' are parallel, so \|AA\| = \|B'B'\| = \|OQ\|. All points on BQA, other than Q, have distance to AB of less than \|OQ\|.

Therefore A'B' intersects the circle at precisely one point, Q, and so is (by definition) a tangent at Q. As AB and A'B' are parallel, &ang;B'QO' = &ang;BOP = 90&deg;. &#8718;

Does the proof need to be constructive? I think not: for me the line A'B' with the required characteristics clearly exists. But an awkward person might want more!

I like the minimalist reflection proof mentioned later even more.

## An alternative proof

In the diagram below the [chord bisection theorem]({% post_url /lablog/circles/2021-03-07-circle-theorems-chord-bisection %}) says that if the radius OQ bisects the chord AB then &ang;OCA = &ang;OCB = 90&deg;.

![chord bisection](/assets/img/circles/chord-bisection-proof.png "chord bisection")

Draw a line parallel to AB through Q. We can do this in several ways, just using ruler and straight edge. [A neat way](https://www.mathopenref.com/constparalleltt.html) uses similar triangles. Extend OA to A' and OB to B' to meet this parallel line:

![tangent radius](/assets/img/circles/tangent-radius-proof.png "tangent radius")

Since A'B' is parallel to AB the common distance between the two lines is \|CQ\|.  All the points on the arc AQB, other than the point Q, are closer to AB than \|CQ\|. So A'B' intersects the circle at precisely one point, Q, and so is (by definition) a tangent at Q.

Finally since we already know that &ang;OCB = 90&deg; and A'B' is parallel to AB, &ang;OQB' = 90&deg;. &#8718;

This proof aims to rigorously extend the [chord bisection theorem]({% post_url /lablog/circles/2021-03-07-circle-theorems-chord-bisection %}) but my approach above uses the same idea, but more simply. It also removes the dependency on the chord bisection theorem.

## Is the result obvious?

Are there other reasons we might think the result obvious? Look again at the diagram:

![tangent radius](/assets/img/circles/tangent-radius-proof.png "tangent radius")

**A direct extension of the chord bisection theorem** suggests &ang;OQB' is clearly 90&deg; though a picky person might say the chord has disappeared at that point.

**Minimalist reflection.** Suppose &ang;OQA' = &alpha; and &ang;OQB' = &beta;. Reflect the diagram in OQ. Everything is the same, as AB was horizontal and A'B' was parallel to AB. &alpha; and &beta; swap, so that &alpha; = &beta;. Clearly &alpha; + &beta; = 180&deg;, so we have &alpha; = &beta; = 90&deg;.

<p class="highlight">The last one is my personal favourite: it uses the circle, radius and tangent symmetry and captures the "obvious" nature of the result. Is it sufficiently rigorous?</p>

## Where next?

Next is the [alternate segment theorem]({% post_url /lablog/circles/2021-03-06-circle-theorems-alternate-segment %}).

Also check out these [outstanding construction worksheets](https://www.mathopenref.com/worksheetlist.html). These construction techniques seem to have faded from maths education.
