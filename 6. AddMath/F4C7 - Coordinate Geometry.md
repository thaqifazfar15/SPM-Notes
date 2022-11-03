## 1. Divisor of a Line Segment

````ad-note (formula-notes?)
title: #### Find the Coordinates of point $P(x,y)$ between point $A(x_1,y_1)$ and $B(x_2,y_2)$ in the ratio $m:n$
collapse: open 
icon:calculator
color: 188, 32, 79

$$P(x,y) = (\frac{nx_1+mx_{2}}{{m+n}}, \frac{ny_{1}+my_{2}}{{m+n}})$$

```desmos-graph
left = -5
right = 8
bottom = -6
---
y = x - 1 | -3 < y < 4 | BLACK
y = -3 | dashed | -2 < x < 2 | BLUE
x = 2 | dashed | -3 < y < 1 | BLUE
y = 1 | dashed | 2 < x < 5 | BLUE
x = 5 | dashed | 1 < y < 4 | BLUE
(2,1) | label: P(x,y)
(-2,-3) | label: A(x1,y1)
(5,4) | label: B(x2,y2)
(0,-1) | label: m | cross
(3.5,2.5) | label: n | cross
```
````

```ad-note  
title: #### Find the Ratio, $\:m:n\:$ when given point P, A and B
collapse: open 
icon:calculator
color: 188, 32, 79

$$x=\frac{nx_1+mx_{2}}{{m+n}}$$

$$y = \frac{ny_{1}+my_{2}}{{m+n}}$$
Just need to use either one.
``` 


```ad-note
title: #### Info: Find the midpoint between 2 points
collapse: open
icon:info-circle

$$Coordinates\:of\: Midpoint= (\frac{x_1+x_2}{2},\frac{y_1+y_2}{2})$$
```
---

## 2. Parallel Lines and Perpendicular Lines
#### Equations of Straight Lines

```ad-note 
title: #### Find the Equation of Lines
collapse: open 
icon:calculator
color: 188, 32, 79

- When $m$ and coordinates of one point is given.
$$y-y_1=m(x-x_1)$$

- When $x$-intercept and $y$-intercept are given. Where **$a$ is $x$-intercept** and **$b$ is $y$-intercept.**
$${\frac{x}{a}}+{\frac{y}{b}}=1$$

``` 

```ad-note 
title: #### Find the Gradient, $m$
collapse: open 
icon:calculator
color: 188, 32, 79

$$Gradient, m = \frac{{y_2-y_1}}{{x_2-x_{1}}}$$
``` 

```ad-note 
title: #### Gradient of Perpendicular Lines
collapse: open 
icon:calculator
color: 188, 32, 79

$$m_{1}m_{2}= -1$$
```

```ad-note
title: #### Info: Perpendicular Bisector Meaning
collapse: open
icon:info-circle

Perpendicular bisector is ***a line that passes through the midpoint*** between two points. 
```
---

## 3. Areas of Polygons

````ad-note 
title: #### Find the Area of Triangles
collapse: open 
icon:calculator
color: 188, 32, 79

```desmos-graph
height = 400
top = 8
bottom = -4
left = -8
---
y = 2x + 2 | -2 < x < 2 | BLACK
y = 5/8x - 0.75 | -2 < x < 6 | BLACK
y = -3/4x + 7.5 | 2 < x < 6 | BLACK
(-2,-2) | label: A(x1,y1)
(6,3) | label: B(x2,y2)
(2,6) | label: C(x3,y3)
```
$$Area = \frac{1}{2}\:\begin{vmatrix}   x_{1} & x_{2} & x_{3} & x_{1}\\ y_{1} & y_{2} & y_{3} & y_{1}   \end{vmatrix}$$

$$Area = \frac{1}{2}\:\begin{vmatrix} \:(x_1y_2+x_2y_3+x_3y_1)\:-\:(x_2y_1+x_3y_2+x_1y_3)\:\end{vmatrix}$$

The coordinates of vertices are arranged **anticlockwise.**

This formula can also used to find the **area of polygon with n sides.**
```` 
---

## 4. Equations of Loci

Locus of a moving points is the path taken by the point subject to certain conditions.

#### i. Determining the Equations of Locus

````ad-note 
title: #### Locus of a Moving Point from a **Fixed  Point** is Constant
collapse: open 
icon:calculator
color: 188, 32, 79

```desmos-graph
left =  -9
---
x^2+y^2 = 4^2 | BLACK
(0,0) | label: A(x1,y1) | BLACK
y = x | BLACK | 0 < x < 2.8
(1.5,1.5) | BLACK | Cross | label: r
(2.8,2.8) | label: P(x,y) | BLACK
```
$$PA = r$$
$$\sqrt{(x-x_1)^{2}-(y-y_1)^{2}}=r$$
$${(x-x_1)^{2}-(y-y_1)^{2}}=r^{2}\:,where\:r>0$$
```` 

````ad-note 
title: #### Ratio of Distance of Moving Point from Two Fixed Point is Constant
collapse: open 
icon:calculator
color: 188, 32, 79

```desmos-graph
left =  -9
---
x^2+y^2 = 4^2 | BLACK
(-4,0) | label: P(x,y) | BLACK
y = 2.5x + 10 | BLACK | -6 < x < -4
(-6,-5) | BLACK | label: A(x1,y1)
y = 0.75x - 0.5 | BLACK | -6 < x < -2
(-2,-2) | label: B(x2,y2) | BLACK
y = -x - 4 | BLACK | -4 < x < -2
(-3,-1) | cross | label: n | BLACK
(-5,-2.5) | cross | label: m | BLACK
```
$$\frac{PA}{PB} = \frac{m}{n}$$
$$\frac{\sqrt{(x-x_1)^{2}-(y-y_1)^{2}}}{\sqrt{(x-x_2)^{2}-(y-y_{2)^{2}}}}=\frac{m}{n}$$
$$\frac{{(x-x_1)^{2}-(y-y_1)^{2}}}{{(x-x_2)^{2}-(y-y_{2)^{2}}}}=\frac{m^2}{n^2}$$

When distance between two points are the same, **$\:m=n.$**
```` 
