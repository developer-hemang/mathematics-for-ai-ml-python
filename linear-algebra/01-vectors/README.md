# Vectors

# What is a Vector?
A vector is a mathematical object that represents a quantity with both a value and a direction.

In simple terms:

> A vector tells us “how much” and “in which direction.”

For AI/ML, however, there is an important extension:

> A vector is also commonly used to represent multiple related numerical values as one mathematical object.

For example:

$$
A =
\begin{bmatrix}
1  \\
3 
\end{bmatrix}
$$

This is a 2-dimensional vector.

It contains two numbers:

- 3 → component along the first dimension
- \(4\) → component along the second dimension

## Vector in the simplest possible way

Imagine you are standing at a point.

If I say:

> Move 5 meters

you don't know exactly where to go.

But if I say:

> Move 5 meters east

now you know both:
- Magnitude: 5 meters
- Direction: East

That's a vector.

 ### Example

$$
\LARGE  v = 5 \text{ meters east}
$$

So:

**Vector = magnitude + direction**

A vector can be expressed or represented in several different ways, and understanding these representations is useful because AI/ML uses some of them heavily.

1. A list of numbers
2. A point in space
3. An arrow

## 1. Vector as a list of numbers

#### Example: 

$$
v =
\begin{bmatrix}
1  \\
3 
\end{bmatrix}
$$

This is simply a list of components: [3,4]

You can interpret it as:
- 3 in the X dimension
- 4 in the Y dimension

In AI/ML, this is especially important.

### For Example

$$
\begin{bmatrix}
25000 \\
25100 \\
24900 \\
25050 \\
1500000
\end{bmatrix}
$$

could represent:

```python
[Open, Close, Low, High, Volume]

```
So:

> Vector = ordered list of numbers
This is probably the most important representation for ML.

## 2. Vector as a point in space

Take: 

$$
\begin{bmatrix}
3 \\
4 \\
\end{bmatrix}
$$

we can plot the coordinates : 

$$
\LARGE   \text{ (3,4) }
$$

on a coordinate system:

```python
Y
↑
|
|             ● (3,4)
|
|
|
|
+----------------------→ X
0

```

Here, (3,4) is a point.

but we can interpret that point as the vector:

$$
\begin{bmatrix}
3 \\
4 \\
\end{bmatrix}
$$

starting from the origin:

$$
\LARGE \text{(0,0)}
$$

so:

$$ \LARGE (0,0) \to (3,4) $$

represents the vector.


### important distinction 

Strictly speaking:

$$
\LARGE \text{(3,4)}
$$

as a point means "the location at x=3 , y=4"

While:

$$
\LARGE v = \text{(3,4)}
$$

as a vector means "move 3 units in X and 4 units in Y."
They have the same coordinates but different interpretations.


## 3. Vector as an arrow

The same vector:

$$
\LARGE v = 
\begin{bmatrix}
3 \\
4 \\
\end{bmatrix}
$$

can be represented as an arrow:

```python

Y
↑
|
|             ●
|           ↗
|         ↗
|       ↗
|     ↗
|   ↗
| ↗
●------------------------→ X
(0,0)

```

The arrow communicates two things:

### Length

The length represents the magnitude.

# Vector Magnitude

$$ \LARGE (0,0) \to (3,4) $$

$$ \LARGE |v| = \sqrt{3^2 + 4^2} $$

$$ \LARGE |v| = 5 $$

### Direction

The direction is approximately:

$$ \LARGE \theta \approx 53.13^\circ $$

So the arrow tells us:

> Move 5 units in a direction of approximately 53.13°.


# Row and column vectors




$$ \LARGE   \vec{a} = (3,4) $$

$$ \LARGE \text(and) $$

$$ \LARGE  \vec{a} = (3,4,5) $$

$$ \LARGE \text{can also be expressed as column matrices (also called column vectors)} $$

 

 
$$ \LARGE \vec{a} = \begin{bmatrix} 3 \\ 4 \end{bmatrix} \quad \text{and} \quad \vec{b} = \begin{bmatrix} 3 \\ 4 \\ 5 \end{bmatrix} $$

