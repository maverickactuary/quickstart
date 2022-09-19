---
layout: default
section: Lablog
permalink: /circles/circle-theorems-equal-length-tangents
maths: true
geogebra: false
title: Circle theorems - equal length tangents
description: If lines extended from a point P meet a circle tangentially at points A and B then the lengths of PA and PB are equal. We discuss and prove this result.
---

# Circle theorems: equal length tangents

{% include nav_circles.html %}

## Statement

If lines extended from a point P meet a circle tangentially at points A and B then \|PA\| = \|PB\|.

![tangents equal length](/assets/img/circles/tangents-equal-length-proof.png "tangents equal length")

<p class="highlight">As is often the case in stating theorems, brevity and precision conflict; a statement such as "tangents which meet at the same point are equal in length" is brief but somewhat misleading: tangents can extend beyond A and B, meet at the same point (P), but still differ in length.</p>

## Proof

The [tangent radius theorem]({% post_url /lablog/circles/2021-03-05-circle-theorems-tangent-radius %}) implies that the radii OA and OB make an angle of 90&deg; with the tangents. 

&Delta;PAO is right angled so, by Pythagoras, \|PA\|<sup>2</sup> = \|PO\|<sup>2</sup> - \|OA\|<sup>2</sup>. Similarly, \|PB\|<sup>2</sup> = \|PO\|<sup>2</sup> - \|OB\|<sup>2</sup>.

Subtracting, \|PA\|<sup>2</sup> - \|PB\|<sup>2</sup> = \|OB\|<sup>2</sup> - \|OA\|<sup>2</sup> = 0, as OA and OB are both radii. So \|PA\|<sup>2</sup> = \|PB\|<sup>2</sup> and \|PA\| = \|PB\|. &#8718;

The Math open reference site has a [rather nice tangent construction](https://www.mathopenref.com/consttangents.html) with proof that they are indeed tangents.

## Where next?

Oxford's latest maths annual newsletter has just dropped into my inbox. Its postscript observes that:

1. The year 20-21 concatenates two consecutive integers, as does 21-22, 22-23 .... 100-101 etc.
1. 2021 is the product of two primes, 43 and 47. The last such year was 1763. The next will be 2491.

So far, so easy. The next time (1) *and* (2) will occur in a year will apparently be 794018604377235322848433897872605582794018604377235322848433897872605583.

According to [numbersaplenty.com](https://www.numbersaplenty.com/2021) Oxford's "next occurrence" claim is wrong, as 2307340946901148-2307340946901147 is the product of the primes 4803478892324963 and 4803478892324969.

<p>I have yet to check these! We need restricted solutions of \( p_1p_2 =  (10^{dig(n)}+1)n + 1 \) where \( n \) has \( dig(n) \) digits.</p>

(Having used [Geogebra](https://www.geogebra.org/) for these [circle theorems]({% post_url /lablog/circles/2021-03-01-circle-theorems-intro %}), I just squeezed in [Katex](https://katex.org/)).

As Ramanujan might have said, 2021 seems interesting year.
