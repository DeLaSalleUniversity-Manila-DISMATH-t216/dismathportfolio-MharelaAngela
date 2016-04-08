# dismathportfolio-MharelaAngela
dismathportfolio-MharelaAngela created by Classroom for GitHub

### Mharela Angela A. Tan DISMATH EL

## WEEK 1:
###### Orientation
* I was introduced to **Discrete Mathematics**, a challenging yet interesting subject.
* I have understood the difference of DISMATH from other branches of Mathematics.
* Because of the logic problems about knights and knaves, I was able to have a sort of "preview" of what I will learn from this course.

###### Basic terms in DISMATH
* Proposition
* Logical deduction
* Axiom
* Mathematical proof

The examples given in class helped me to distinguish which statements are propositions and which are not.
The kinds of TRUTH depending on its beholder were also enumerated.
* Legal truth
* Authoritative truth
* Scientific truth
* Probable truth 
* Philosophical truth

###### Logical Connectives
I was introduced to the concept of logical connectives, their symbols and their usage. The truth table for each logical connective were also shown and explained well. Again, the example propostions presented made it easier for me to understand the relationship of the input and output for each operator.
* Negation (¬) used as *NOT*
* Conjunction (˄) used as *AND*
* Disjunction (˅) used as *OR*
* Exclusive or (⊕) used as *XOR*
* Conditional (→) used as *IF, THEN*
* Biconditional (↔) used as *IF AND ONLY IF*

I also learned that when p → q:
* its converse q → p, and
* its inverse ¬p → ¬q are not equal to p → q
* its contrapositive ¬q → ¬p is equal to p → q

###### Logical Equivalences
* Identity laws
* Domination laws
* Idempotent laws
* Double negation law
* Commutative laws
* Associative laws
* Distributive laws
* De Morgan's laws
* Absorption laws
* Negation laws

At first, I had a hard time applying these laws in showing that two expressions are logically equivalent. Eventually, I understood it better by studying the proof of the laws.

## WEEK 2:
###### Predicate Logic
* I learned that not only sentences, but also propositions have a subject and a predicate.
* I understood the proper usage of quantifiers which are:
  * Existential quantifier (∃x) which means "there exists"
  * Universal quantifier (∀x) which means "for all"
* A *counterexample* is a disqualification from a universal claim.
* Real-life examples of existential and universal claims helped me to appreciate and understand the concept more.

###### Rules of Inference
This lesson was introduced to me by the defining some important terminologies.
* argument
* valid
* fallacy
* tautology

I realized that it is important to understand the concept and patterns of a valid argument in order apply the rules of inference correctly.
* Modus ponens
* Modus tollens
* Hypothetical syllogism
* Disjunctive syllogism
* Addition
* Simplification
* Conjunction
* Resolution

Both the Superman and the sunset problem helped me to understand logical equivalences and rules of inference. During class, I also realized that for some cases, it is better and easier to use truth tables for some problems.

## WEEK 3:
###### Methods of Proof
* Direct proof
 * Assume that p is true.
 * Show that q is also true.
* Proof by contraposition (indirect)
 * Assume that ¬q is true.
 * Show that ¬p is also true.
* Vacuous and Trivial proof
 * Vacuous proof: Show that p is false so p → q must be true.
 * Trivial proof: Show that q is true so p → q must be true.
* Proof by Contradiction
 * Assume that ¬p is true. (p refers to the whole statement)
 * Show that Step 1 ends up in a contradiction.

So far, I find the vacuous and trivial proof easiest to understand. I still get slightly confused with some problems involving the other kinds of proofs.

## WEEK 4:
###### Methods of Proof
* Proof of Equivalence
 * Show that p → q and q → p are both true to prove a biconditional statement.
* Counterexamples
 * We must find a counterexample x in which P(x) will be false to prove that an existential claim is false.
* Mathematical Induction
 * Basis Step: Verify P(1) is true.
 * Inductive Step: Show that P(x) → P(x+1) is true for all values of x.

## WEEK 5:
This week, we learned about the following:
* Recursive and Inductive definition
* Recursive algorithm
* Power series
* Program Correctness
* Hoare Triple

## WEEK 6:
* We were introduced to the lesson about sets and cardinality.
* We reviewed the lesson about quantifiers and nested quantifiers in preparation for our first quiz.

###### Functions
* A *function* f from A to B is an assignment of exactly one element of B to each element of A.
* Functions are also called *mappings/transformations*.
* Domain - set of real numbers
* Codomain - set of integers
* Range - actually occurring values
* Types of functions
 * One-to-one function (injective)
 * Onto function (subjective)
 * One-to-one and onto (bijective)
* A one-to-many relation is *not a function*.

## WEEK 7:
No classes for this week.

## WEEK 8:

###### Algorithms

* An algorithm is a finite set of precise instructions for performing a computation or for solving a problem.
* Different types of algorithms were discussed in class. These are: finding the maximum element, linear search and binary search.
* Algorithms have a *precondition* and a *postcondition*. The precondition is the condition of the input while the postcondition is the final assertion and/or condition of the output.
* A *pseudocode* is a high-level description of an algorithmic that uses structural conventions of programming language.
* We learned about the properties of algorithm which are: input, output, definiteness, correctness, finiteness, effectiveness and generality.

## WEEK 9:

* We implemented an algorithm using the MIT app inventor for better understanding of the linear and binary search.

###### Sorting

* We learned about the 2 kinds of sorting.
* Bubble sort - the largest element "bubbles up".
* Insertion sort - first element is already sorted.

We also learned about *Greedy Algorithm*, which, is an algorithm that selects the best choice at each step.

## WEEK 10:
###### Growth of Functions
* It is often described using Big-O Notation
* Complexity - the number of operations.
* Big-O - used for upper bound
* Big-Omega - used for lower bound
* Big-Theta - used for both upper and lower bound
* We also discussed about Algorithm Time Complexity.

## WEEK 11:
* No classes for this week.

## WEEK 12:
###### Graph Theory
* A graph is a discrete structure consisting of vertices and edges that connect these vertices.
* Degree - the number of edges incident with a node; a loop at a vertex contributes twice to the degree of that vertex
* Path - is a sequence of edges that begins at a vertex of a graph and travels from vertex to vertex along edges of the graph.
* The Handshaking Theorem states that the number of edges in a certain graph is equal to the product of the number of its vertices multiplied to the degrees, divided by 2.
* An Euler circuit is a circuit containing every edge of a graph; all nodes have even degrees; returns to initial vertex
* An Euler path is a path that passes through every edge not more than once; there are 2 nodes who have odd degrees
* A Hamilton circuit passes to through every vertex exactly once and returns to the vertex where it started.
* A Hamilton path is a simple path which passes through every vertex exactly once.
* A pendant is a node with one degree; no longer have a circuit.
* Two graphs are said to be isomorphic when their vertices have one-to-one correspondences without destroying or having to invent edges.
* Planar graphs are graphs that can be drawn in the plane without edges having to cross.
* To determine the number of regions in a certain graph, we may use the Euler's formula: r = e - v + 2
* According to Kuratowski's Theorem, a graph is nonplanar if and only if it contains a subgraph homeomorphic to K3,3 or K5.

## WEEK 13:
* We have discussed that a tree is an undirected graph without simple circuits.
* Graphs which have no simple circuits and are not necessarily connected are called forests.
* A rooted tree is a tree in which one vertex has been designated as the root and every edge is directed away from the root.
* Examples of an m-ary tree were shown and explained in class.
* Graph coloring is assigning a color to every vertex of the graph. No two adjacent vertices have the same color.
* Recycling of color is allowed and important in graph coloring. Chromatic number is the minimum number of colors that can be used to color a certain graph.
* Modeling Computation and Finite-state machines were also discussed in class.
* With these lessons and the stories that our professor have shared to the class, I have learned and understood how machines are slowly taking over human activities nowadays. 



