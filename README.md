A personal notebook. 

(under construction...)

---

**Convention.** Each formula is a canonical representative of its equivalence class.

**Notation.** Formula parameters are written as named quantities (e.g. $\text{radius}$, $\text{height}$); elsewhere standard variables apply.

<!-- Editorial labels

Axiom / Postulate: Fundamental assumed truth; the unproven foundation of a system.

Definition: Precise statement establishing the exact meaning of a concept.

Theorem: Major, highly significant mathematical statement that has been proven.

Proposition: Important, useful, standalone proven fact, lesser in scope than a theorem.

Lemma: Helper result proven primarily to step toward a larger theorem.

Corollary: Direct, immediate consequence of a preceding theorem or proposition.

Property: Inherent, easily derived characteristic of a formally defined mathematical object.

Claim: Localized, minor assertion often used internally within a larger proof.

Proof: Rigorous logical deduction establishing the truth of a Theorem, Proposition, Lemma, or Claim.

Conjecture: Educated guess believed true but currently lacking rigorous proof.

Convention: Agreed-upon rule chosen to resolve ambiguity among valid options.

Notation: Explicit assignment of symbols or shorthand to represent mathematical concepts.

Remark: Extra context, historical note, useful perspective or subtle observation for the reader.

Example: Concrete, specific instance illustrating a definition, theorem, or concept.

-->

<!-- Use semantic LaTeX commandsinstead of literal or Unicode symbols 
\lt
\ast
\coloneqq
etc
-->

<!-- Use spaces in code for `:`, `\to`, `\mapsto`, `\iff`, `=`, `+`, `-`, ","; 
use `\quad` and `\` for rendering spaces -->

---

[I Foundations](#part-i-foundations)

[II Algebra](#part-ii-algebra)

[III Analysis](#part-iii-analysis)

[IV Geometry](#part-iv-geometry)

[V Discrete Mathematics](#part-v-discrete-mathematics)

[VI Applied Mathematics](#part-vi-applied-mathematics)

---

# Part I Foundations

## Set Theory
### Basic Concepts
#### Operations (Unions, Intersections)
### Relations and Functions
### Cardinality
#### Countable and Uncountable Sets
#### Cantor's Diagonal Argument
### Axiomatic Set Theory
#### ZFC Axioms

## Logic
### Propositional Logic
### Predicate Logic
### Proof Systems
#### Induction
#### Contradiction
### Model Theory
### Computability Theory
#### Turing Machines
#### The Halting Problem
### Gödel's Incompleteness Theorems

# Part II Algebra

## Elementary Algebra
### Numbers and Operations
#### Complex Numbers
##### Euler's Identity
### Polynomials
#### Fundamental Theorem of Algebra

## Linear Algebra
### Vector Spaces
### Matrices and Determinants
#### Rank, Nullity, and Trace
### Linear Transformations
### Eigenvalues and Eigenvectors
#### Spectral Theorem
### Matrix Factorizations
#### Singular Value Decomposition (SVD)

## Abstract Algebra
### Groups
#### Symmetry and Permutation Groups
#### Group Homomorphisms
### Rings and Ideals
### Fields
### Galois Theory
### Representation Theory
### Homological Algebra

## Category Theory
### Categories, Functors, and Natural Transformations
### Limits and Colimits
### Adjunctions
### Yoneda Lemma

## Number Theory
### Divisibility
#### Euclidean Algorithm
### Primes
#### Prime Number Theorem
#### Riemann Hypothesis
### Modular Arithmetic
#### Chinese Remainder Theorem
#### Fermat's Little Theorem
### Algebraic Number Theory
### Analytic Number Theory
### Cryptography
#### RSA
#### Elliptic Curves

# Part III Analysis

## Calculus
### Limits and Continuity
#### Epsilon-Delta Definition
### Differential Calculus
#### Mean Value Theorem
### Integral Calculus
#### Fundamental Theorem of Calculus
### Sequences and Series
#### Convergence Tests
#### Taylor and Fourier Series

## Multivariable and Vector Calculus
### Partial Derivatives
### Gradients and Directional Derivatives
### Multiple Integrals
### Vector Calculus
#### Divergence, Gradient, and Curl
#### Stokes', Green's, and Divergence Theorems

## Real Analysis
### Metric Spaces
### Topology of R^n
### Measure Theory
#### Lebesgue Integration
#### Lp Spaces
### Convergence Types (Pointwise vs Uniform)

## Complex Analysis
### Analyticity
#### Cauchy-Riemann Equations
### Cauchy's Integral Formula
### Residues and Poles
### Conformal Mapping

## Functional Analysis
### Hilbert and Banach Spaces
### Operator Theory
### Distributions (Generalized Functions)

## Differential Equations
### Ordinary Differential Equations (ODEs)
### Partial Differential Equations (PDEs)
#### Heat, Wave, and Laplace Equations
### Dynamical Systems
#### Chaos Theory

# Part IV Geometry

## Classical Geometry
### Euclidean Geometry
### Non-Euclidean Geometry
#### Hyperbolic Geometry
#### Elliptic Geometry

## Analytic Geometry
### Coordinate Systems
### Conic Sections

## Differential Geometry
### Manifolds
### Tensors
### Riemannian Geometry
#### Curvature (Ricci, Riemann)
#### Geodesics
### Symplectic Geometry

## Algebraic Geometry
### Varieties and Schemes
### Sheaves and Cohomology

## Topology
### Point-Set Topology
#### Compactness and Connectedness
#### Hausdorff Spaces
### Algebraic Topology
#### Fundamental Groups (Homotopy)
#### Homology and Cohomology
### Knot Theory
### Differential Topology

# Part V Discrete Mathematics

## Combinatorics
### Counting Principles
### Generating Functions
### Graph Theory
#### Paths, Cycles, and Connectivity
#### Planarity and Coloring
#### Trees
### Ramsey Theory

## Discrete Structures
### Posets and Lattices
### Complexity Theory
#### P vs NP

# Part VI Applied Mathematics

## Probability and Statistics
### Probability Theory
#### Law of Large Numbers
#### Central Limit Theorem
### Statistics
#### Hypothesis Testing
#### Regression Analysis
### Stochastic Processes
#### Markov Chains
#### Brownian Motion

## Information Theory
### Shannon Entropy
### Coding Theory

## Numerical Analysis
### Root Finding
### Numerical Integration/Differentiation
### Monte Carlo Methods

## Optimization
### Linear Programming
### Convex Optimization
### Game Theory
#### Nash Equilibrium

---

## Function

**Definition** (function).

$$
f : A \to B, \quad x \mapsto f(x)
$$

**Definition** (domain, codomain, image).

$$
\text{domain}(f) = A, \quad \text{codomain}(f) = B, \quad \text{image}(f) = \{f(x) \mid x \in A\} \subseteq B
$$

**Definition** (injectivity).

$$
f(x_1) = f(x_2) \implies x_1 = x_2
$$

**Definition** (surjectivity).

$$
\forall y \in B\ \exists x \in A : f(x) = y
$$

**Definition** (bijectivity).

$$
f \text{ bijective} \iff f \text{ injective} \land f \text{ surjective}
$$

**Definition** (inverse function).

$$
f \text{ bijective} \implies \exists f^{-1} : B \to A,\ f^{-1}(f(x)) = x \land f(f^{-1}(y)) = y
$$

**Definition** (composition).

$$
(g \circ f)(x) \coloneqq g(f(x)), \quad f : A \to B,\ g : B \to C
$$

**Definition** (even function).

$$
f(-x) = f(x) \quad \forall x \in A
$$

**Definition** (odd function).

$$
f(-x) = -f(x) \quad \forall x \in A
$$

## Elementary Functions

**Definition** (power function).

$$
f(x) = x^n, \quad n \in \mathbb{Z}
$$

**Proposition.**

$$
\text{domain} = \mathbb{R}, \quad \text{range} = \mathbb{R}^+ \cup \{0\}\ \text{if } n \text{ even},\quad \text{range} = \mathbb{R}\ \text{if } n \text{ odd}
$$

$$
f(-x) = f(x) \iff n \text{ even}
$$

$$
f(-x) = -f(x) \iff n \text{ odd}
$$

**Definition** (absolute value function).

$$
f(x) = |x|
$$

**Proposition.**

$$
\text{domain} = \mathbb{R}, \quad \text{range} = \mathbb{R}^+ \cup \{0\}
$$

$$
f(-x) = f(x) \quad \text{(even)}
$$

**Definition** (square root function).

$$
f(x) = \sqrt{x}
$$

**Proposition.**

$$
\text{domain} = \mathbb{R}^+ \cup \{0\}, \quad \text{range} = \mathbb{R}^+ \cup \{0\}
$$

**Definition** (exponential function).

$$
f(x) = b^x, \quad b \in \mathbb{R}^+, \quad b \neq 1
$$

**Proposition.**

$$
\text{domain} = \mathbb{R}, \quad \text{range} = \mathbb{R}^+
$$

$$
b \gt 1 \implies f \text{ strictly increasing}
$$

$$
0 \lt b \lt 1 \implies f \text{ strictly decreasing}
$$

**Definition** (natural exponential function).

$$
f(x) = e^x
$$

**Proposition** (derivative).

$$
\text{domain} = \mathbb{R}, \quad \text{range} = \mathbb{R}^+
$$

$$
\frac{d}{dx} e^x = e^x
$$

**Definition** (logarithmic function).

$$
f(x) = \log_b x, \quad b \in \mathbb{R}^+, \quad b \neq 1
$$

**Proposition**.

$$
\text{domain} = \mathbb{R}^+, \quad \text{range} = \mathbb{R}
$$

$$
b \gt 1 \implies f \text{ strictly increasing}
$$

$$
0 \lt b \lt 1 \implies f \text{ strictly decreasing}
$$

**Definition** (natural logarithm function).

$$
f(x) = \ln x
$$

**Proposition** (derivative).

$$
\text{domain} = \mathbb{R}^+, \quad \text{range} = \mathbb{R}
$$

$$
\frac{d}{dx} \ln x = \frac{1}{x}
$$

## Triangle

**Definition** (geometric).

$$
(A, B, C \in \mathbb{R}^2) \land (A, B, C \text{ non-collinear}) \implies \triangle ABC := \overline{AB} \cup \overline{BC} \cup \overline{CA}
$$

**Notation** (standard elements).

$$
a = \|\overline{BC}\|, \quad b = \|\overline{CA}\|, \quad c = \|\overline{AB}\|
$$

$$
A = \angle BAC, \quad B = \angle ABC, \quad C = \angle BCA
$$

**Definition** (parameter space).

$$
\mathcal{T} = \{(a, b, c) \in (\mathbb{R}^+)^3 \mid a + b > c \land b + c > a \land a + c > b\}
$$

**Theorem** (angle sum).

$$
A + B + C = \pi
$$

**Definition** (scalene).

$$
a \neq b \neq c \neq a
$$

**Definition** (isosceles).

$$
a = b \neq c
$$

**Definition** (equilateral).

$$
a = b = c \quad
$$

**Definition** (acute).

$$
A < \frac{\pi}{2},\ B < \frac{\pi}{2},\ C < \frac{\pi}{2}
$$

**Definition** (right).

$$
A = \frac{\pi}{2} \lor B = \frac{\pi}{2} \lor C = \frac{\pi}{2}
$$

**Definition** (obtuse).

$$
A > \frac{\pi}{2} \lor B > \frac{\pi}{2} \lor C > \frac{\pi}{2}
$$

**Proposition** (side ratios, special right triangles).

$$
1 : 1 : \sqrt{2} \quad \text{(}45^\circ\text{-}45^\circ\text{-}90^\circ\text{)}
$$

$$
1 : \sqrt{3} : 2 \quad \text{(}30^\circ\text{-}60^\circ\text{-}90^\circ\text{)}
$$

**Theorem** (pythagorean).

$$
a^2 + b^2 = c^2 \iff \angle C = \frac{\pi}{2}
$$

**Corollary.**

$$
\sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2} \quad \text{(distance between two points)}
$$

$$
\sqrt{a^2 + b^2} \quad \text{(hypotenuse)}
$$

$$
\sqrt{c^2 - a^2} \quad \text{(leg)}
$$

**Proposition** (area).

$$
\frac{1}{2} \cdot \text{base} \cdot \text{height}
$$

**Corollary.**

$$
\frac{\text{base}}{4} \cdot \sqrt{4 \cdot \text{leg}^2 - \text{base}^2} \quad \text{(isosceles)}
$$

$$
\frac{\sqrt{3}}{4} \cdot \text{side}^2 \quad \text{(equilateral)}
$$

**Proposition** (area).

$$
\frac{1}{2} \cdot a \cdot b \cdot \sin C
$$

**Corollary.**

$$
\frac{a^2 \cdot \sin B \cdot \sin C}{2 \cdot \sin A}
$$

**Theorem** (Heron's formula).

$$
\sqrt{s(s-a)(s-b)(s-c)}, \quad s = \frac{a + b + c}{2}
$$

**Proposition** (perimeter).

$$
a + b + c
$$

**Definition** (congruence).

$$
\triangle ABC \cong \triangle DEF \iff (\overline{AB} = \overline{DE} \land \overline{BC} = \overline{EF} \land \overline{CA} = \overline{FD} \land \angle A = \angle D \land \angle B = \angle E \land \angle C = \angle F)
$$

**Definition** (similarity).

$$
\triangle ABC \sim \triangle DEF \iff (\angle A = \angle D \land \angle B = \angle E \land \angle C = \angle F)
$$

**Corollary.**

$$
\triangle ABC \sim \triangle DEF \implies \frac{AB}{DE} = \frac{BC}{EF} = \frac{AC}{DF} = \text{scale factor}, \quad \text{scale factor} \in \mathbb{R}^+
$$

**Proposition** (similarity criteria).

$$
\angle A = \angle D,\ \angle B = \angle E \quad \text{(AA)}
$$

$$
\frac{AB}{DE} = \frac{AC}{DF},\ \angle A = \angle D \quad \text{(SAS)}
$$

$$
\frac{AB}{DE} = \frac{BC}{EF} = \frac{AC}{DF} \quad \text{(SSS)}
$$

**Corollary** (scale factor).

$$
\text{perimeter}(\triangle ABC) = \text{scale factor} \cdot \text{perimeter}(\triangle DEF)
$$

$$
\text{area}(\triangle ABC) = \text{(scale factor)}^2 \cdot \text{area}(\triangle DEF)
$$

## Cube

**Definition** (cube).

$$
\{\text{side} \in \mathbb{R}^+ \mid \text{all edges} = \text{side}\}
$$

**Proposition.**

$$
\text{side}^3 \quad \text{(volume)}
$$

$$
6 \cdot \text{side}^2 \quad \text{(surface area)}
$$

$$
\text{side} \cdot \sqrt{2} \quad \text{(face diagonal)}
$$

$$
\text{side} \cdot \sqrt{3} \quad \text{(space diagonal)}
$$

## Transformations

**Definition.**

$$
T : \mathbb{R}^2 \to \mathbb{R}^2, \quad (x, y) \mapsto (x', y')
$$

**Definition** (rigid transformation).

$$
T \text{ is rigid} \iff \| T(x_1, y_1) - T(x_2, y_2) \| = \| (x_1, y_1) - (x_2, y_2) \|
$$

**Theorem.**

$$
T \text{ is rigid} \iff T \in \{T_{a,b},\ R_\theta,\ S\}
$$

**Definition** (translation).

$$
T_{a,b} : \mathbb{R}^2 \to \mathbb{R}^2, \quad (x, y) \mapsto (x + a, y + b), \quad a, b \in \mathbb{R}
$$

**Definition** (rotation).

$$
R_\theta : \mathbb{R}^2 \to \mathbb{R}^2, \quad (x, y) \mapsto (x \cos\theta - y \sin\theta, x \sin\theta + y \cos\theta), \quad \theta \in \mathbb{R}
$$

**Corollary.**

$$
R_{\frac{\pi}{2}}(x, y) = (-y, x)
$$

$$
R_{\pi}(x, y) = (-x, -y)
$$

$$
R_{\frac{3\pi}{2}}(x, y) = (y, -x)
$$

**Definition** (reflection).

$$
S_x : \mathbb{R}^2 \to \mathbb{R}^2, \quad (x, y) \mapsto (x, -y)
$$

$$
S_y : \mathbb{R}^2 \to \mathbb{R}^2, \quad (x, y) \mapsto (-x, y)
$$

$$
S_{y=x} : \mathbb{R}^2 \to \mathbb{R}^2, \quad (x, y) \mapsto (y, x)
$$

$$
S_{y=-x} : \mathbb{R}^2 \to \mathbb{R}^2, \quad (x, y) \mapsto (-y, -x)
$$

## Modulus

**Definition.**

$$
|x| = \sqrt{x^2}
$$

**Proposition.**

$$
|x| \geq 0
$$

$$
|x| = 0 \iff x = 0
$$

$$
|xy| = |x||y|
$$

$$
\left|\frac{x}{y}\right| = \frac{|x|}{|y|}, \quad y \neq 0
$$

$$
|x|^2 = x^2
$$

**Theorem** (triangle inequality).

$$
|x + y| \leq |x| + |y|
$$

**Corollary.**

$$
|x - y| \geq \big||x| - |y|\big|
$$

**Proposition** (inequalities).

$$
|x| < a \iff -a < x < a
$$

$$
|x| > a \iff x > a \lor x < -a
$$

## Addition

**Notation.**

$$
\text{addend} + \text{addend} = \text{sum}
$$

**Remark** (synonyms).

$$
\text{addend} = \text{summand} = \text{augend}
$$

**Proposition.**

$$
a + b = b + a \quad \text{(commutativity)}
$$

$$
(a + b) + c = a + (b + c) \quad \text{(associativity)}
$$

$$
a + 0 = a \quad \text{(identity)}
$$

$$
a + (-a) = 0 \quad \text{(inverse)}
$$

## Subtraction

**Notation.**

$$
\text{minuend} - \text{subtrahend} = \text{difference}
$$

**Definition.**

$$
a - b = a + (-b)
$$

**Proposition.**

$$
a - b \neq b - a \quad \text{(non-commutativity)}
$$

$$
(a - b) - c \neq a - (b - c) \quad \text{(non-associativity)}
$$

$$
a - 0 = a
$$

$$
a - a = 0
$$

## Multiplication

**Notation.**

$$
\text{multiplicand} \times \text{multiplier} = \text{product}
$$

**Remark** (synonyms).

$$
\text{multiplicand} \times \text{multiplier} = \text{factor} \times \text{factor}
$$

**Proposition.**

$$
a \cdot b = b \cdot a \quad \text{(commutativity)}
$$

$$
(a \cdot b) \cdot c = a \cdot (b \cdot c) \quad \text{(associativity)}
$$

$$
a \cdot 1 = a \quad \text{(identity)}
$$

$$
a \cdot 0 = 0 \quad \text{(absorption)}
$$

$$
a \cdot (b + c) = a \cdot b + a \cdot c \quad \text{(distributivity)}
$$

$$
a \cdot \frac{1}{a} = 1, \quad a \neq 0 \quad \text{(inverse)}
$$

## Division

**Notation.**

$$
\text{dividend} \div \text{divisor} = \text{quotient, fraction, ratio}
$$

**Definition.**

$$
a \div b = a \cdot \frac{1}{b}, \quad b \neq 0
$$

**Proposition.**

$$
a \div b \neq b \div a \quad \text{(non-commutativity)}
$$

$$
(a \div b) \div c \neq a \div (b \div c) \quad \text{(non-associativity)}
$$

$$
a \div 1 = a
$$

$$
a \div a = 1, \quad a \neq 0
$$

$$
a \div 0 = \text{undefined}
$$

$$
0 \div a = 0, \quad a \neq 0
$$

$$
\frac{a \div b}{c \div d} = \frac{a \cdot d}{b \cdot c}, \quad b, c, d \neq 0
$$

## Exponentiation

**Notation.**

$$
\text{base}^{\text{exponent}} = \text{power}
$$

**Definition.**

$$
b^n = \underbrace{b \cdot b \cdots b}_{n}, \quad b \in \mathbb{R}, \quad n \in \mathbb{N}
$$

**Proposition.**

$$
b^m \cdot b^n = b^{m+n}
$$

$$
\frac{b^m}{b^n} = b^{m-n}, \quad b \neq 0
$$

$$
(b^m)^n = b^{mn}
$$

$$
(ab)^n = a^n b^n
$$

$$
\left(\frac{a}{b}\right)^n = \frac{a^n}{b^n}, \quad b \neq 0
$$

$$
b^0 = 1, \quad b \neq 0
$$

$$
b^{-n} = \frac{1}{b^n}, \quad b \neq 0
$$

$$
b^{\frac{1}{n}} = \sqrt[n]{b}
$$

$$
b^{\frac{m}{n}} = \sqrt[n]{b^m}
$$

**Definition** (natural exponential).

$$
e = \lim_{n \to \infty} \left(1 + \frac{1}{n}\right)^n = \sum_{n=0}^{\infty} \frac{1}{n!}
$$

**Proposition** (inequalities).

$$
b^x < b^y \iff x < y, \quad b > 1
$$

$$
b^x < b^y \iff x > y, \quad 0 < b < 1
$$

## Root

**Notation.**

$$
\sqrt[\text{degree}]{\text{radicand}} = \text{radical, root}
$$

**Definition.**

$$
\sqrt[n]{x} = y \iff y^n = x, \quad n \in \mathbb{N}, \quad x \in \mathbb{R}^+
$$

**Notation.**

$$
\sqrt[2]{x} = \sqrt{x}
$$

**Proposition.**

$$
\sqrt[n]{xy} = \sqrt[n]{x} \cdot \sqrt[n]{y}
$$

$$
\sqrt[n]{\frac{x}{y}} = \frac{\sqrt[n]{x}}{\sqrt[n]{y}}, \quad y \neq 0
$$

$$
\sqrt[n]{x^m} = x^{\frac{m}{n}}
$$

$$
\sqrt[m]{\sqrt[n]{x}} = \sqrt[mn]{x}
$$

$$
\sqrt[n]{x^n} = |x|
$$

**Proposition** (inequalities).

$$
\sqrt[n]{x} < \sqrt[n]{y} \iff x < y, \quad n \in \mathbb{N}^+
$$

## Logarithm

**Notation.**

$$
\log_\text{base}(\text{anti-logarithm}) = \text{logarithm}
$$

**Definition.**

$$
\log_b x = y \iff b^y = x, \quad b \in \mathbb{R}^+, \quad b \neq 1, \quad x \in \mathbb{R}^+
$$

**Definition** (natural logarithm).

$$
\ln x = \int_{1}^{x} \frac{1}{t} \, dt, \quad x > 0
$$

**Notation.**

$$
\ln x = \log_e x
$$

$$
\log x = \log_{10} x
$$

**Proposition** (exponential–logarithm inverses).

$$
b^{\log_b x} = x
$$

$$
\log_b b^x = x
$$

$$
e^{\ln x} = x, \quad x > 0
$$

$$
\ln(e^x) = x
$$

**Proposition.**

$$
\log_b(xy) = \log_b x + \log_b y
$$

$$
\log_b\left(\frac{x}{y}\right) = \log_b x - \log_b y
$$

$$
\log_b(x^n) = n \log_b x
$$

$$
c \log_b x + d \log_b y = \log_b(x^c y^d)
$$

**Corollary.**

$$
\log_b b = 1
$$

$$
\log_b 1 = 0
$$

$$
\log_b\left(\sqrt[y]{x}\right) = \frac{\log_b x}{y}
$$

$$
\ln(a \times 10^n) = \ln a + n \ln 10
$$

**Theorem** (change of base).

$$
\log_b x = \frac{\log_k x}{\log_k b}, \quad k \in \mathbb{R}^+, \quad k \neq 1
$$

**Proposition** (symmetry).

$$
x^{\log_x y} = y^{\log_y x}
$$

**Proposition** (iterated logarithm).

$$
\log \left(\log(c^d)\right) = \log(\log c) + \log d
$$

$$
\log \left(\log \left(\sqrt[d]{c}\right)\right) = \log(\log c) - \log d
$$

**Proposition** (sum and difference expansion).

$$
\log_b(a + c) = \log_b a + \log_b \left(1 + \frac{c}{a}\right)
$$

$$
\log_b(a - c) = \log_b a + \log_b \left(1 - \frac{c}{a}\right)
$$

**Proposition** (inequalities).

$$
\log_b x \lt \log_b y \iff x \lt y, \quad b \gt 1
$$

$$
\log_b x \lt \log_b y \iff x \gt y, \quad 0 \lt b \lt 1
$$

**Proposition** (exotic identity).

$$
x^{\frac{\log(\log x)}{\log x}} = \log x
$$

**Proposition** (integral).

$$
\int \log_a x \, dx = x(\log_a x - \log_a e) + C
$$

## Polynomial Equations

### Linear Equation

**Notation.**

$$
\text{coefficient} \cdot x + \text{constant} = 0
$$

**Definition** (linear equation).

$$
ax + b = 0, \quad a, b \in \mathbb{R}, \quad a \neq 0
$$

**Definition** (linear function).

$$
f(x) = ax + b
$$

**Proposition** (root).

$$
x = -\frac{b}{a}
$$

**Proposition** (monotonicity).

$$
f \text{ strictly increasing} \iff a \gt 0
$$

$$
f \text{ strictly decreasing} \iff a \lt 0
$$

**Definition** (slope).

$$
m = \frac{y_2 - y_1}{x_2 - x_1}, \quad x_1 \neq x_2
$$

**Definition** (forms).

$$
ax + b = 0 \quad \text{(standard)}
$$

$$
y = mx + c, \quad m, c \in \mathbb{R} \quad \text{(slope-intercept)}
$$

$$
y - y_1 = m(x - x_1) \quad \text{(point-slope)}
$$

$$
\frac{x}{a} + \frac{y}{b} = 1, \quad a, b \neq 0 \quad \text{(intercept)}
$$

$$
ax + by + c = 0, \quad a, b \in \mathbb{R},\ (a, b) \neq (0, 0) \quad \text{(general)}
$$

**Proposition** (parallel and perpendicular lines).

$$
m_1 = m_2 \iff \text{lines are parallel}
$$

$$
m_1 \cdot m_2 = -1 \iff \text{lines are perpendicular}
$$

### Quadratic Equation

**Notation.**

$$
\text{coefficient} \cdot x^2 + \text{coefficient} \cdot x + \text{constant} = 0
$$

**Definition** (quadratic equation).

$$
ax^2 + bx + c = 0, \quad a, b, c \in \mathbb{R}, \quad a \neq 0
$$

**Definition** (quadratic function).

$$
f(x) = ax^2 + bx + c
$$

**Definition** (discriminant).

$$
\Delta \coloneqq b^2 - 4ac
$$

**Theorem** (nature of roots).

$$
\Delta > 0 \iff \text{two distinct real roots}
$$

$$
\Delta = 0 \iff \text{one repeated real root}
$$

$$
\Delta < 0 \iff \text{two complex conjugate roots}
$$

**Proposition** (domain and range).

$$
\text{domain} = \mathbb{R}, \quad \text{range} = \left[-\frac{\Delta}{4a}, +\infty\right) \text{ if } a \gt 0, \quad \text{range} = \left(-\infty, -\frac{\Delta}{4a}\right] \text{ if } a \lt 0
$$

**Proposition** (symmetry).

$$
f(-x) = f(x) \iff b = 0 \quad \text{(even, symmetric about } x = 0\text{)}
$$

**Definition** (vertex).

$$
(h, k) \coloneqq \left(-\frac{b}{2a}, -\frac{\Delta}{4a}\right)
$$

**Corollary.**

$$
x = h \quad \text{(axis of symmetry)}
$$

$$
(h, k) \text{ is a minimum if } a \gt 0, \text{ a maximum if } a \lt 0
$$

**Definition** (forms).

$$
ax^2 + bx + c = 0 \quad \text{(standard)}
$$

$$
a(x - h)^2 + k = 0 \quad \text{(vertex)}
$$

$$
a(x - x_1)(x - x_2) = 0 \quad \text{(factored)}
$$

**Theorem** (quadratic formula).

$$
x = \frac{-b \pm \sqrt{\Delta}}{2a}
$$

###### Remark. Also known as Bhaskara's formula.

**Corollary** (rationalized form).

$$
x = \frac{2c}{-b \mp \sqrt{\Delta}}
$$

**Corollary** (repeated root).

$$
\Delta = 0 \implies x = -\frac{b}{2a}
$$

**Proposition** (Vieta's formulas).

$$
x_1, x_2 \text{ roots of } ax^2 + bx + c = 0 \implies x_1 + x_2 = -\frac{b}{a}, \quad x_1 \cdot x_2 = \frac{c}{a}
$$

**Corollary** (factored form).

$$
ax^2 + bx + c = a(x - x_1)(x - x_2)
$$

**Proposition** (completing the square).

$$
ax^2 + bx + c = a\left(x + \frac{b}{2a}\right)^2 - \frac{\Delta}{4a}
$$

**Proposition** (root identities).

$$
(x_1 - x_2)^2 = \frac{\Delta}{a^2}
$$

$$
x_1^2 + x_2^2 = \frac{b^2 - 2ac}{a^2}
$$

### Cubic Equation

**Definition** (cubic equation).

$$
ax^3 + bx^2 + cx + d = 0, \quad a, b, c, d \in \mathbb{R}, \quad a \neq 0
$$

**Definition** (cubic function).

$$
f(x) = ax^3 + bx^2 + cx + d
$$

**Proposition** (domain and range).

$$
\text{domain} = \mathbb{R}, \quad \text{range} = \mathbb{R}
$$

**Proposition** (symmetry).

$$
f(-x) = -f(x) \iff b = d = 0 \quad \text{(odd, symmetric about origin)}
$$

**Definition** (depressed cubic).

$$
x = t - \frac{b}{3a} \implies t^3 + pt + q = 0, \quad p = \frac{3ac - b^2}{3a^2}, \quad q = \frac{2b^3 - 9abc + 27a^2 d}{27a^3}
$$

**Definition** (discriminant).

$$
\Delta \coloneqq 18abcd - 4b^3 d + b^2 c^2 - 4ac^3 - 27a^2 d^2
$$

**Theorem** (nature of roots).

$$
\Delta > 0 \iff \text{three distinct real roots}
$$

$$
\Delta = 0 \iff \text{repeated root}
$$

$$
\Delta < 0 \iff \text{one real root and two complex conjugate roots}
$$

**Definition** (Cardano auxiliary).

$$
D \coloneqq \left(\frac{q}{2}\right)^2 + \left(\frac{p}{3}\right)^3
$$

**Theorem** (Cardano's formula).

$$
t = \sqrt[3]{-\frac{q}{2} + \sqrt{D}} + \sqrt[3]{-\frac{q}{2} - \sqrt{D}}, \quad x = t - \frac{b}{3a}
$$

**Proposition** (Vieta's formulas).

$$
x_1, x_2, x_3 \text{ roots} \implies x_1 + x_2 + x_3 = -\frac{b}{a}, \quad x_1 x_2 + x_1 x_3 + x_2 x_3 = \frac{c}{a}, \quad x_1 x_2 x_3 = -\frac{d}{a}
$$

###### Remark. Cardano's formula appeared in <em>Ars Magna</em> (1545), though the method originated with del Ferro and Tartaglia. The quartic was solved by Ferrari; Abel and Ruffini proved no general algebraic solution exists for degree $\geq 5$.

# Differential Calculus 

## Limit

**Definition** ($\epsilon - \delta$ definition).

$$
\lim_{x \to a} f(x) = L \iff \forall \epsilon > 0 \exists \delta > 0 \forall x \in \mathbb{R}, \big(a-\delta < x < a + \delta, x \neq a \implies L-\epsilon < f(x) < L+\epsilon\big)
$$

## Derivative

**Definition** (derivative at a point).

$$
f'(a) \coloneqq \lim_{h \to 0} \frac{f(a + h) - f(a)}{h}, \quad f : \mathbb{R} \to \mathbb{R}, \quad a \in \mathbb{R}
$$

**Definition** (derivative as a function).

$$
f'(x) \coloneqq \lim_{h \to 0} \frac{f(x + h) - f(x)}{h}
$$

**Notation** (Leibniz).

$$
\frac{dy}{dx} \coloneqq \lim_{\Delta x \to 0} \frac{f(x + \Delta x) - f(x)}{\Delta x}, \quad y = f(x)
$$

# Integral Calculus

## Integration

**Definition** (Riemann sum).

$$
S_n \coloneqq; \sum_{i=1}^{n} f(x_i^{\ast}) \Delta x_i, \quad x_i^{\ast} \in [x_{i-1}, x_i], \quad a = x_0 \lt \cdots \lt x_n = b
$$

**Definition** (Riemann integral).

$$
\int_{a}^{b} f(x) \ dx \coloneqq \lim_{\max \Delta x_i \to 0} \sum_{i=1}^{n} f(x_i^\ast) \Delta x_i
$$

**Notation** (uniform partition).

$$
\int_{a}^{b} f(x) \ dx = \lim_{n \to \infty} \sum_{i=1}^{n} f\left(a + i \cdot \frac{b-a}{n}\right) \frac{b-a}{n}
$$

**Definition** (antiderivative).

$$
F'(x) = f(x) \quad \forall x \in I
$$

**Definition** (indefinite integral).

$$
\int f(x) \ dx \coloneqq F(x) + C, \quad C \in \mathbb{R}
$$

**Proposition** (properties).

$$
\int k f(x) \, dx = k \int f(x) \, dx, \quad k \in \mathbb{R}
$$

$$
\int [f(x) \pm g(x)] \, dx = \int f(x) \, dx \pm \int g(x) \, dx
$$

$$
\int [af(x) + bg(x)] \, dx = a \int f(x) \, dx + b \int g(x) \, dx \quad \text{(linearity)}
$$

$$
\int f(x) g'(x) \, dx = f(x)g(x) - \int f'(x) g(x) \, dx \quad \text{(integration by parts)}
$$

$$
\int f(g(x)) g'(x) \, dx = F(g(x)) + C \quad \text{(substitution)}
$$

$$
\int f(ax + b) \, dx = \frac{1}{a} F(ax + b) + C, \quad a \neq 0
$$

**Theorem** (Fundamental Theorem of Calculus, Part I).

$$
F(x) \coloneqq \int_{a}^{x} f(t) \ dt \implies F'(x) = f(x)
$$

**Theorem** (Fundamental Theorem of Calculus, Part II).

$$
\int_{a}^{b} f(x) \ dx = F(b) - F(a)
$$

**Proposition** (properties).

$$
\int_{a}^{a} f(x) \, dx = 0
$$

$$
\int_{a}^{b} f(x) \, dx = -\int_{b}^{a} f(x) \, dx
$$

$$
\int_{a}^{b} f(x) \, dx + \int_{b}^{c} f(x) \, dx = \int_{a}^{c} f(x) \, dx \quad \text{(additivity)}
$$

$$
\int_{a}^{b} [cf(x) + dg(x)] \, dx = c\int_{a}^{b} f(x) \, dx + d\int_{a}^{b} g(x) \, dx \quad \text{(linearity)}
$$

$$
\int_{a}^{b} f(x) \, dx \leq \int_{a}^{b} g(x) \, dx \quad \text{if } f(x) \leq g(x) \text{ on } [a, b] \quad \text{(monotonicity)}
$$

$$
\left|\int_{a}^{b} f(x) \, dx\right| \leq \int_{a}^{b} |f(x)| \, dx \quad \text{(triangle inequality)}
$$

## Matrice

## Vector Field Theory

# Appendix

# References

- Gradshteyn, I. S., & Ryzhik, I. M. (2014). *Table of Integrals, Series, and Products* (8th ed.). Academic Press.
- Zwillinger, D. (Ed.). (2018). *CRC Standard Mathematical Tables and Formulas* (33rd ed.). CRC Press.
- Gowers, T. (Ed.). (2008). The Princeton Companion to Mathematics. Princeton University Press.
