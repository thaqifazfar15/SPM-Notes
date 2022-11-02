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
title: #### Find the Ratio in $\:m:n\:$ when given point P, A and B
collapse: open 
icon:calculator
color: 188, 32, 79

$$x=\frac{nx_1+mx_{2}}{{m+n}}$$

$$y = \frac{ny_{1}+my_{2}}{{m+n}}$$
Just need to use either one.
``` 


```ad-note
title: #### Info: 
collapse: open
icon:info-circle

$formula\:or\:definition$ 
```
---

## 2. Parallel Lines and Perpendicular Lines

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