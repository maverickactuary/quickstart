---
layout: default
section: Lablog
permalink: /circles/circle-theorems-chord-bisection
maths: true
geogebra: false
title: Circle theorems - chord bisection
description: The angle made between a chord and a radius which bisects the chord is 90 degrees. We discuss and prove this simple result.
---

# Circle theorems: chord bisection

{% include nav_circles.html %}

## Chord bisection by radius theorem

If a chord AB is bisected at C **by a radius OD** then &ang;OCQ = 90&deg;. This is a simple and intuitively obvious. The set up is:

![chord bisection](/assets/img/circles/chord-bisection-proof.png "chord bisection")

## The proof

In the diagram we aim to show that &Delta;OAC and &Delta;OBC are congruent, so have the same angles.

In &Delta;AOC and &Delta;:

1. Since both are radii, \|OA\| =\|OB\|.
1. OC is a common side.
1. \|AC\| = \|BC\| as OQ bisects AB.

By the [SSS theorem](https://en.wikipedia.org/wiki/Congruence_(geometry)) - which most allow you to take as axiomatic - we conclude that that the two triangles are congruent. In particular &ang;ACO = &ang;BCO. But it is also clear that &ang;ACO + &ang;BCO = 180&deg; so we conclude that &ang;BCO = 90&deg;, as required.

## Where next?

Finally we have a theorem about [equal length tangents]({% post_url /lablog/circles/2021-03-08-circle-theorems-equal-length-tangents %}).
