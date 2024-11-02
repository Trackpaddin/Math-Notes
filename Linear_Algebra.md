> What is a statement?

In logic, a statement is a sentence that is either true or false, but not both. If it is neither true nor false, it is not a statement. 
For example, any equation cannot be a statement if not all variables have been assigned values.

### Connectives

Compound sentences can be represented by **logical connectives** that are as follows: $\sim$ (not), $\land$ (and), $\lor$ (or), $\rightarrow$ (if…then), $\leftarrow$$\rightarrow$  (if and only if)

### Negation $\sim$

$\sim x$ is the **negation** of $x$ . Its Boolean value is the opposite of $x$ .

### Conjunction/Disjunction $\land$ / $\lor$

$x \land y$ is the **conjunction** of $x$ and $y$ . The conjunction is only true if both statements are true.
$x \lor y$ is the **disjunction** of $x$ and $y$ . If one or both statements are true, the disjunction is true.

### Implication (conditional or biconditional) $\rightarrow, \leftarrow \rightarrow$

Conditional sentences are where an **antecedent** implies a **consequent**, vice versa, or each implies the other.

**Conditionals** are false only when $x$ is true and $y$ is false
**Biconditionals** are true only if $x$ and $y$ are both true or both false

[More information and examples](https://math.libretexts.org/Courses/Prince_Georges_Community_College/MAT_1130_Mathematical_Ideas_Mirtova_Jones_(PGCC%3A_Fall_2022)/02%3A_Logic/2.02%3A_Introduction_to_Truth_Tables)

> To find the truth tables and solutions for compound statements with parentheses, etc. use order of operations rules and evaluate the variables' truth values first. By finding the truth values of each piece of the statement, you can then evaluate the given compound statement easily.

### Logical Equivalence

Written as: $x \equiv y$, meaning that two statements always have the same truth values. For example: $$x \leftarrow \rightarrow y \equiv (x \rightarrow y) \land (y \rightarrow x)$$(A biconditional statement is logically equivalent to two implications)

[Video on Conditional Statements and Logical Equivalence](https://youtu.be/F3544ZyO-eU)

The **converse** of $x \rightarrow y$ is $y \rightarrow x$.
The **contrapositive** of $x \rightarrow y$ is $\sim y \rightarrow \sim x$.

>While an implication and its converse are not logically equivalent, an implication and its contrapositive are.
