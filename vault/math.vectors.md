---
id: c22KmW1rhvQZkNtp1FCkr
title: Vectors
desc: ''
updated: 1642181700888
created: 1641833454971
---

## General Information
### Definition
Entities that possess both a direction and magnitude.

- Magnitude: strength of force
- Direction: direction of force


### Calc 3 Definition
A directed line segment

### Notation
-  $\vec{PQ}$
   - Extends from point P to point Q 
- $P = (1,5)$
  -  Position vector of $\langle 1,5 \rangle$
### Position Vectors
The position vector of point P in the coordinate plane is the vector of $\vec{OP}$ from the origin to the point $P$

## Algebraic Operations

### Addition

Tip to Tail method

$\vec{U}+\vec{V}=\langle U_1+V_1+U_2,V_2\rangle$

**Example**
![[math.vectors.problems#^Addition]]

### Scalar Multiplication
If $c \epsilon  {\rm I\!R}$, $c\vec{A}$ is defined to be the vector that is $|c|$ times as long as $\vec{A}$, in the same direction as $\vec{A}$ idf $c>0$ and in the opposite direction if $C<0$

### Subtraction

### Finding Magnitude
Pythagorean Theorem

**Example**

Find $|\vec{A}|$ when $\vec{A} = \langle 2,3 \rangle$

$|\vec{A}|= \sqrt{2^2+3^2} =\sqrt{13}$


### Unit Vector

#### Definition
A vector of length 1

**Example**

 Given a vector $\vec{A} = \langle 2,3 \rangle$, can you find a unit vector in the same direction.

**Steps To Find**
1. find $|\vec{A}|$
2. $\frac{\vec{A}}{|\vec{A}|}$

### Limit Vectors
- ** $i$ ➡️ $\langle 1,0 \rangle$**
- ** $j$ ➡️ $\langle 0,1 \rangle$**

**Example**

$u = \langle -5,6 \rangle$  ➡️  $u=-5i+6j$
$j = \langle 3,2 \rangle$  ➡️  $u=3i+2j$

### Vectors in 3D Space

#### Definition
A vector in space ${\rm I\!R}^3$

#### Notation
- $(x,y,z)$

#### Magnitude of 3D Vector

$|\vec{v}| = \sqrt{v_1^2+v_2^2+v_3^2}$
#### Limit Vectors in 3D space
- ** $i$ ➡️ $\langle 1,0,0 \rangle$**
- ** $j$ ➡️ $\langle 0,1,0 \rangle$**
- ** $k$ ➡️ $\langle 0,0,1 \rangle$**

#### Distance Between 3D Vectors
Represented as $\overrightarrow{P_1P_2}$ 

- $\overrightarrow{P_1P_2} = \langle (x_2-x_1), (y_2-y_1), (z_2-z_1) \rangle$
- $\overrightarrow{P_1P_2} = (x_2-x_1)i + (y_2-y_1)j + (z_2-z_1)k$

#### Finding Length
$|f\overrightarrow{P_1P_2}| = \sqrt{(x_2-x_1)^2 + (y_2-y_1)^2 + (z_2-z_1)^2}$

### Dot Product

#### Definition
Given 2 nonzero vectors $\vec{U}$ and $\vec{V}$ in 2D or 3D, their dot product is $\vec{U}\cdot\vec{V}= |\vec{U}||\vec{V}|\cos{\theta}$ where $\theta$ is the angle between $\vec{U}$ and $\vec{V}$ with $0\leq\theta\leq\pi$

**Equation**

$\vec{U}=\langle U_1,U_2,U_3\rangle$

$\vec{V}=\langle V_1,V_2,V_3\rangle$

$U \cdot V = U_1V_1+U_2V_2+U_3V_3=|\vec{U}||\vec{V}|\cos{\theta}$

#### Key Notes

- Dot product is commutative

### Orthogonal Vectors
Two vectors are orthogonal if $\vec{U}\cdot\vec{V}=0$. In 2D and 3D spaces, orthogonal means perpendicular ($\frac{\pi}{2}$ angle between them)
#### Key Notes
- There are an infinite number of orthogonal vectors to any one vector when length is not specified
- 
#### Projections
The orthogonal projectio is a vector that goes along $\vec{U}$ with length $|\vec{V}|\cos{\theta}$

**Equation**

$proj_{\vec{U}}\vec{V}= \frac{\vec{U}}{|\vec{U}|}|\vec{V}|\cos{\theta}$

### Cross Product

#### Definition

**Equation**