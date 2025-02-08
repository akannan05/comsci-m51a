# Lecture 4: Gate Designs, Minterms

## Example 1:

Show the truth table and symbol gate design for the following:

$$
F = x' + xy + xyz
$$

**Solution**:

## Exercise:

Which of the following logic statements matches the gate design below?

a. $F = ABC + \overline{A}\overline{B}\overline{C}$
b. $F = A\overline{B}\overline{C} + AB\overline{C} + A\overline{B}C$
c. $F = A\overline{B}C + BAC + \overline{A}\overline{B}C$
d. $F = \overline{A}\overline{B}C + AB\overline{C} + A\overline{B}\overline{C}$
e. None of the above 

**Solution**: The answer is (e)

## Example 2:

Show the symbol gate design for $F$

$$
F = (x'+y+xz)'
$$

**Solution**: 

## Exercise:

Which truth table is correct for the following system:

**Solution**: The answer is 

## Exercise:

Which one is equal to $ABC + A'B + A' + B' + C'$

a. $A'$
b. $B'$
c. 1
d. 0
e. none

**Solution**: The answer is (c)

## Sum of Products

Any sequence of OR terms (products) can be summed up using the OR operator. 

For example $x_2'$, $x_3x_1'$, and $x_3'x_1'x_0$ can be described with the following gate
design

## Product of Sums

Any sequence of AND terms (sums) can be taken as a series of products using the AND
operator.

For example, $x_0$, $x_1' + x_3 + x_1'$, and $x_3' + x_1$ can be described with the
following gate design

## Minterms

A minterm $m_j$ represents the $j$th binary digit, where we have:
$$
x_i \to 1, \quad x_i' \to 0
$$ 

i.e, $m_9$ is denoted as $x_3x_2'x_1'x_0$, since this translates to $1001$, which is 9 in
decimal.

We interpret this as $m_9$ being a value of 1 if we have $x_3x_2'x_1'x_0$, and 0
otherwise.

Below is a helpful table to elucidate this concept

## Exercise:

Consider a system with four inputs. Which minterm is 'one' by the following input: 0011

a. $m_1$
b. $m_3$
c. $m_5$
d. $m_8$
e. $m_{12}$

**Solution**: The answer is (b)

## Exercise:

Which one is correct for $Z = m_1 + m_2 + m_6$

a. 
b.
c.
d.
e.

**Solution**: The answer is (d)

## Sum of Minterms

Minterms are essentially products of binary digits, so we can also represent them as a
sum of products. 

Below is an example for $z = \displaystyle \sum m(1,2,6)$

## Example 3

Given the following table, present $F$ and $G$ in the sum of minterms format, and draw a
gate level design

We can define the following:

$$
F = (X_2'X_1'X_0) + (X_2X_1'X_0) + (X_2X_1X_0') + (X_2X_1X_0)
$$ 
$$
G = (X_2X_1X_0)'
$$

Then the gate design is as follows:

## Exercise:

Given the following truth table, which is the correct sum of product form for $F$?

a. 
b.
c.
d.
e.

**Solution**: The answer is (c)
