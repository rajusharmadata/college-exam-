# Mathematical Topics and Proofs

This repository contains solutions and explanations to a variety of mathematical topics, including group theory, Boolean algebra, set theory, functions, and more. Below is a detailed list of the topics covered.

## Topics Covered

### 1. **Complete and Regular Graphs**
   - **Complete Graph**: A graph where every pair of distinct vertices is connected by a unique edge.
   - **Regular Graph**: A graph where every vertex has the same degree (i.e., the same number of edges incident to it).

### 2. **Pigeonhole Principle**
   - **Statement**: If more than \( n \) objects are placed into \( n \) boxes, then at least one box must contain more than one object.
   - **Example**: If 11 people are assigned to 10 rooms, at least one room must have more than one person.

### 3. **Partial Order Relation**
   - Let \( S \) be the set of all numbers and \( R \) be the relation in \( S \) defined by \( a \leq b \).
   - **Partial Order**: The relation is reflexive, antisymmetric, and transitive.
   - **Proof**:
     - Reflexive: \( a \leq a \).
     - Antisymmetric: If \( a \leq b \) and \( b \leq a \), then \( a = b \).
     - Transitive: If \( a \leq b \) and \( b \leq c \), then \( a \leq c \).

### 4. **Hasse Diagram for Divisibility Relation**
   - **Set**: \( A = \{1, 2, 3, 4, 6, 8, 9, 12, 18, 24\} \)
   - **Relation**: \( a \) divides \( b \).
   - **Hasse Diagram**: Construct the diagram representing the divisibility relation by plotting elements of \( A \) and connecting them based on divisibility.

### 5. **Composition of Functions**
   - Given functions:
     - \( f(x) = 3x^2 + 2 \)
     - \( g(x) = 7x - 5 \)
     - \( h(x) = \frac{1}{x} \)
   - **Composition**:
     - \( (f \circ g \circ h)(x) \)
     - \( (g \circ g)(x) \)
     - \( (g \circ h)(x) \)

### 6. **Cyclic Groups and Abelian Groups**
   - **Cyclic Group**: A group generated by a single element.
   - **Abelian Group**: A group where the operation is commutative, i.e., \( ab = ba \) for all \( a, b \in G \).
   - **Proof**: Every cyclic group is abelian because it is generated by a single element, so the group operation is trivially commutative.

### 7. **Converting to Conjunctive Normal Form (CNF)**
   - Convert the given Boolean expression \( xy' + x'y' + x'y \) into CNF form.

### 8. **Injectivity of Functions**
   - **Function**: \( f(x) = x^2 - 1 \)
   - **Proof**: Check if the function is injective, i.e., if \( f(x_1) = f(x_2) \) implies \( x_1 = x_2 \).

### 9. **Boolean Algebra Proofs**
   - **Expression 1**: Prove the Boolean identity:
     \[
     [x' (x + y)]' + [y (y + x')]' + [y (y' + x)] [y (y' + x)]' = 1
     \]
   - **Expression 2**: Prove:
     \[
     (x + yz) (y' + x) (y' + z') = x (y' + z')
     \]

### 10. **Binomial Theorem (Pascal's Identity)**
   - **Theorem**: Prove that:
     \[
     \binom{n+1}{r} = \binom{n}{r-1} + \binom{n}{r}
     \]

### 11. **Truth Table and Tautology**
   - Construct a truth table for the expression \( (p \Rightarrow q) \Rightarrow (p \land q) \equiv (\neg p \Rightarrow q) \land (q \Rightarrow p) \) and check if it's a tautology.

### 12. **Binary Operation on Integers**
   - **Operation**: Define a binary operation \( * \) on \( \mathbb{Z} \) by \( x * y = x + y + 1 \).
   - **Check**: Verify if \( (\mathbb{Z}, *) \) is an abelian group. Discuss the properties of an abelian group.

### 13. **Equivalence Relation**
   - **Theorem**: If \( R \) is an equivalence relation on a set \( A \), then \( R^{-1} \) is also an equivalence relation on \( A \).

### 14. **Partial Order on Divisibility**
   - **Set**: \( N \) is the set of natural numbers.
   - **Relation**: Define \( aRb \) if \( a \) divides \( b \).
   - **Proof**: Show that this defines a partial order relation.

### 15. **Algebraic Structure (Group Theory)**
   - **Set**: \( G = \{ 1, -1, i, -i \} \) with ordinary multiplication.
   - **Questions**:
     - (i) Is \( G \) abelian?
     - (ii) Determine the order of each element in \( G \).
     - (iii) Is \( G \) a cyclic group? If so, determine its generator.

### 16. **Adjacency Matrix**
   - **Definition**: The adjacency matrix represents the edges of a graph.
   - **Example**: Construct the adjacency matrix for a given graph.

### 17. **Subgroup Test**
   - **Theorem**: A necessary and sufficient condition for a non-empty subset \( H \) of \( G \) to be a subgroup is that for all \( a, b \in H \), \( ab^{-1} \in H \).

### 18. **Lagrange’s Theorem**
   - **Statement**: Prove that in a finite group, the order of a subgroup divides the order of the group.

### 19. **Distributive Inequalities in Lattices**
   - Prove the following inequalities in any lattice:
     - \( a \land (b \lor c) \geq (a \land b) \lor (a \land c) \)
     - \( a \lor (b \land c) \leq (a \lor b) \land (a \lor c) \)

### 20. **Bijective Function and Inverse**
   - **Function**: \( f(x) = \frac{x-1}{x-3} \), where \( f: \mathbb{R} - \{ 3 \} \to \mathbb{R} - \{ 1 \} \).
   - **Proof**: Show that \( f \) is bijective and compute its inverse.

---

## Conclusion

This README serves as an overview of various mathematical topics with proofs, examples, and important concepts. Each topic is explained and mathematically proven to provide a thorough understanding of the subject matter.

---

### Contributions

Feel free to contribute or suggest modifications to improve the content. This is an open-source project for anyone learning or interested in mathematical group theory, Boolean algebra, and related topics.

---

### License

This repository is licensed under the MIT License. See LICENSE for more information.
