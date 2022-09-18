---
layout: default
section: Lablog
permalink: /circles/circle-theorems-inscribed-angle
maths: true
geogebra: true
geogebra-id: "bttt7qpz"
geogebra-height: 380
geogebra-width: 325
title: Circle theorems - inscribed angle
description: The inscribed angle theorem - the angle made by a chord and a point on the chord's major arc is half the angle at the centre. Discussion and rigorous proof.
---

# Circle theorems: inscribed angle

{% include nav_circles.html %}

[Thales's theorem]({% post_url /lablog/circles/2021-03-02-circle-theorems-thales %}) is that the angle made between points A and B on the ends of a circle **diameter** and a third point P on the circle circumference is 90&deg;.

If we move beyond Thales, so that the points A and B are on the circumference but do not form a diameter, the corresponding theorems become more interesting - and more challenging to prove.

The [inscribed angle theorem](https://en.wikipedia.org/wiki/Inscribed_angle) can be stated in several ways. My preference is that "the angle on the circumference of the major arc is half that at the centre".

## Try it yourself

In the diagram below you can move all the points except O, the centre of the circle. This helps us makes sense of what the theorem is saying and also points to two other related results.

**First try moving around the point P.** Without moving A, O or B, move P between A and B: &ang;APB stays at 45&deg;.

As an aside, &ang;AQB is 135&deg; i.e. 180&deg; minus &ang;APB. We'll see more of this later.

<div id="geogebra" class="displayed"></div>

**Now move around the point A between P and Q.** The angles change, but we still have:

- **Major arc:** &ang;APB = &ang;AOB / 2
- **Opposite angles:** &ang;AQB = 180&deg; - &ang;APB i.e. &ang;AQB + &ang;APB = 180&deg;

**Finally move around the point Q between A and B.** We have:

- **Minor arc:** &ang;AQB is constant = 180&deg; minus &ang;AOB / 2
- **Opposite angles:** &ang;AQB+&ang;APB = 180&deg;

## Three closely related results

If P lies between A and B on the major arc and similarly for Q in the minor arc, we have three results:

1. **Major arc:** &ang;APB is constant and is equal to half of &ang;AOB.
1. **Cyclic quadrilateral:** &ang;APB+&ang;AQB=180&deg;.
1. **Minor arc:** &ang;AQB is constant and is equal to 180&deg; minus half of &ang;AOB.

We will now prove 1, while leaving 2 and 3 until our [cyclic quadrilaterals]({% post_url /lablog/circles/2021-03-04-circle-theorems-cyclic-quadrilateral %}) article.

## Proof: angle on major arc

We break the result into three parts.

**In the first part** we have a diagram where the centre of the circle, O, lies within &Delta;APB. In this case we draw the (red) line OP. AO and OP are radii, so are the same length. 

This means &Delta;AOP is isosceles, so we can call the two equal angles &alpha;, as shown. Similarly in &Delta;BOP we have equal angles &beta;.

![inscribed angle proof part 1](/assets/img/circles/inscribed-angle-proof-1.png "inscribed angle proof part 1")

Since the angles in a triangle sum to 180&deg; we must have &ang;AOP = 180&deg;-2&alpha;. Similarly &ang;BOP = 180&deg;-2&beta;.

It is also clear that the three angles surrounding O total 360&deg; so that 360&deg; = &ang;AOP + &ang;BOP + &ang;AOB.

Substituting what we know, we have 360&deg; = 180&deg;-2&alpha; + 180&deg;-2&beta; + &ang;AOB.

This simplifies to &ang;AOB = 2(&alpha; + &beta;).

From this follows two things:

1. **The angle at the centre is twice the angle at the circumference.**
1. **&ang;APB is constant.** &ang;AOB = 2(&alpha; + &beta;) is independent of P. So &alpha; + &beta; is constant.

The proof often stops there - for example see [this flawed proof](https://www.bbc.co.uk/bitesize/guides/zcsgdxs/revision/2) from BBC bitesize.

<blockquote>Great. Job done, right? Not quite. One important point with geometry problems like this ... is that we have to make sure that our arguments work whatever the diagram.</blockquote>
*Source: [mathematician Vicky Neale](https://theoremoftheweek.wordpress.com/2010/07/17/theorem-32-the-angle-at-the-centre-is-twice-the-angle-at-the-circumference/)*

The proof is incomplete, falling victim to diagram dependency - in this case choosing a "convenient" diagram in the set up. As soon as we move P far enough left (or right) the partial pretty proof falls apart. This is also confirmed by [this wikipedia article](https://en.wikipedia.org/wiki/Inscribed_angle).

**In the second part** we move P further to the left, so that BOP is a straight line. The previous argument will not work.

![inscribed angle proof part 2](/assets/img/circles/inscribed-angle-proof-2.png "inscribed angle proof part 2")

We use Thales's theorem: &ang;BAP = 90&deg;, so that &alpha; = 45&deg;. As it is also clear that &ang;AOB = 90&deg; we have &ang;APB = &ang;AOB /2.

Alternatively we note that the total angles in &Delta;BAP is 4&alpha; = 180&deg; so, again, &alpha; = 45&deg;.

**In the third part** we move P further still to the left (or to the right) so that the centre O lies outside of &Delta;APB.

![Inscribed angle proof part 3](/assets/img/circles/inscribed-angle-proof-3.png "Inscribed angle proof part 2")

**Again we want to show that &ang;APB = &ang;AOB / 2 = &alpha;, say.** We again draw the red radius. As OP and OB are both radii, &Delta;BOP is isosceles, so we can fill in the angles &beta;.

As OP and OA are both radii, &Delta;AOP is isosceles, so we can fill in the &ang;OAP = &alpha; + &beta;. We've got to here:

![inscribed angle proof part 3](/assets/img/circles/inscribed-angle-proof-3a.png "inscribed angle proof part 3")

We now have a so-called "angle chase":

- Total angles in &Delta;AOP: &ang;AOP = 180&deg; - 2(&alpha; + &beta;)
- &ang;AOB = &ang;COB = &ang;BOP - &ang;COP = (180&deg; - 2&beta;) - [180&deg; - 2(&alpha; + &beta;)] = 2&alpha;

So &ang;APB = &ang;AOB / 2 = &alpha; in this third case.

That's all three cases proved. &#8718;

## Where next?

For the minor arc and opposite angles results see [cyclic quadrilaterals]({% post_url /lablog/circles/2021-03-04-circle-theorems-cyclic-quadrilateral %}).
