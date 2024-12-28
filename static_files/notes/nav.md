---
layout: page
title: Navigation
---

## Navigation

### 1:60 Rule

The purpose of this rule is to calculate a new heading when we are
found to be off track.

For practice see [here](https://github.com/jurienbay/q1in60).

#### Definition

The definition is that, $$1nm$$ subtends an angle of $$1^{\circ}$$ at a distance of $$60nm$$.

Mathematically speaking, this is a statement of *arc-distance* as follows;

   The distance traveled along an arc is equal to the arc radius times the arc angle
   divided by 60.

#### Proof

By definition, circumference equals $$2 \pi r$$ and that a circles angular circumference
is $$360^{\circ}$$.

A proportion of a circle is therefore $$\frac{\theta}{360}$$ and therefore;

\\[
\begin{align}
d & = \left\( 2 \pi r \right\) \left\( \frac{\theta}{360} \right\) \\
  & = \frac{\pi r \theta}{180} \text{ and } \frac{180}{\pi} \approx 57.296. \\
  & \implies d \approx \frac{r \theta}{60} \text{ where } \theta \text{ is in degrees}.
\end{align}
\\]
