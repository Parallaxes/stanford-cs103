# Lecture 0: Introduction, Set Theory



### Key Questions in CS103

**Computability Theory** - What probles can you solve with a computer?

**Complexity Theory** - Why are some problems harder to solve than others?

**Discrete Mathematics** - How can we be certain in our answers to these questions?



## Introduction to Set Theory

A **set** is an unordered collection of distinct objects, which may be anything, including other sets.


### Set Notation

Curly braces seperate elements:

$$ \{a, b, c, d\} $$


### Semantics of Sets

Two sets are equal when they have the same contents, ignoring the order.

$$ \{a, b, c\} = \{c, b, a\} $$

<br>
Sets cannot contain duplicate elements. Any repeated elments are ignored.

$$ \{a, b, c\} = \{a, a, a, b, b, c\} $$

<br>
The objects that make up a set are called the elements of that set.

$$ 
a \in \{a, b, c, d\} \\
e \notin \{a, b, c, d\}
$$

The symbol $\in$ means "is an element of" and the $\notin$ means "is not an element of."

<br>
Sets can contain any number of elements.

$$ \{\} = \emptyset $$

The *empty set* is the set with no elements. We denote this empty set using the $\emptyset$ symbol.