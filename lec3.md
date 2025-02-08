# Lecture 3: Identities of Boolean Algebra, Introduction to Gates

## Identities of Boolean Algebra

## Example 1:

Show that $E_1$ and $E_2$ are equivalent, given:

$$ 
E_1(x_2, x_1, x_0) = x_2 x_1 + x_2 x_1' + x_2 x_0 
$$

$$
E_2(x_2, x_1, x_0) = x_2
$$

**Solution**: 

We can convert the first two terms, $x_2 x_1 + x_2 x_1'$, by using the distributivity
property. Then we have:

$$
x_2 x_1 + x_2 x_1^' = x_2(x_1 + x_1')
$$ We can further simplify $x_1 + x_1'$ using the complement property. We have:

$$
x_2(x_1 + x_1') = x_2
$$ Finally, $x_2 + x_2 x_0$ can be simplified using the absorption property. We have:
$$
x_2 + x_2 x_0 = x_2
$$ as we wanted to show.

**Remark**: This can also be solved using a truth table (see below):

## Exercise:

Which one is equal to $x + y$?
a. $x' + y'$
b. $(x.y)'$
c. $(x'.y')'
d. $(xx'+x+y)
e. c and d

**Solution**: The answer is (e). 

## Exercise:

Which one is equal to $ABC + A' + AB'C$?
a. $A$
b. $A + C$
c. $A' + C$
d. $ABC + A$
e. c and d

**Solution**: The answer is (c).

## Example 2: 

Simplify the expression with Boolean Algebra, and use a truth table to show the output
for all input combinations.

$$
F = x+y+xyz+xz+x'yz'
$$

## Example 3:

Simplify the expression with Boolean Algebra, and use a truth table to show the output
for all input combinations.

$$
F = x+y+z+x'z'
$$

## Introduction to Gates

Below are all the gate diagrams that are relevant for this course:

Additionally, we can also use the following gate diagrams to represent a series of AND or
OR statements.

## Exercise:

Which of the following is/are a NOR gate?

**Solution**: The answer is (e).
