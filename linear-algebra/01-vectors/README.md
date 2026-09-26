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
25050 \\
1500000
\end{bmatrix}
$$

could represent:

``python
[Open, Close, Low, High, Volume]

``
So:

> Vector = ordered list of numbers
This is probably the most important representation for ML.