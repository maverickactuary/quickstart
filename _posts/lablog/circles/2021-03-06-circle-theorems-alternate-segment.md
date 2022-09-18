---
layout: default
section: Lablog
permalink: /circles/circle-theorems-alternate-segment
maths: true
geogebra: true
geogebra-id: "ysvwkgse"
geogebra-height: 275
geogebra-width: 275
title: Circle theorems - alternate segment
description: We explain and prove the alternate segment theorem, that the angle between the tangent and chord equals the angle in the alternate segment.
---

# Circle theorems: alternate segment

{% include nav_circles.html %}

## Statement and diagram

The alternate segment theorem states that **the angle between the tangent and chord equals the angle in the alternate segment.** The alternate segment? A diagram can help unpack that.

Let's draw:

- a circle, centre O
- a point P on its circumference
- a tangent to the circle at P

Now connect:

- O and P to form a radius
- P, A and B to form a triangle

![alternate segment](/assets/img/circles/alternate-segment-statement-1.png "alternate segment")

The chord PA divides the circle into a major segment and a minor segment. There is an angle in each and the alternate segment theorem says these are equal - in our diagram to &beta;.

Similarly, the chord PB divides the circle into major minor segments and the highlighted angles are equal - to &alpha;, say.

The "most opposite" angles are equal.

## Important notes to the diagram

The diagram is usually drawn as above but in general:

- the circle centre O does not have to be inside &Delta;PAB
- the point P does not have to be on the major segment

We can therefore pull A and B down, so that neither of the above hold and the angle equivalence will remain, although the values of &alpha; and &beta; will of course change.

![alternate segment](/assets/img/circles/alternate-segment-statement-2.png "alternate segment")

## Try it yourself

This is perhaps the least intuitive of the circle theorems. Have a play!

<div id="geogebra" class="displayed"></div>

## Proof

We join the points O and B with a line.

![alternate segment proof](/assets/img/circles/alternate-segment-proof.png "alternate segment proof")

From the [inscribed angle theorem]({% post_url /lablog/circles/2021-03-03-circle-theorems-inscribed-angle %}) we know that as we move A the &ang;PAB remains constant and in fact equals &ang;POB / 2. **This holds even where A moves so that O is no longer inside &Delta;PAB.**

As &ang;POB = 2&alpha;, &ang;OPB + &ang;OBP = 180&deg; - 2&alpha;. Since &Delta;POB is isosceles &ang;OBP = &ang;OPB. So &ang;OPB = 90&deg; - &alpha;.

We also know that &ang;B'PO = 90&deg;. So &ang;B'PB = &ang;B'PO - &ang;POB = 90&deg; - (90&deg; - &alpha;) = &alpha; = &ang;PAB. &#8718;

The result for &beta; is obtained in exactly the same way, joining O and A.

## Where next?

We wrap up with two technical results. First up is the [chord bisection theorem]({% post_url /lablog/circles/2021-03-07-circle-theorems-chord-bisection %}).
