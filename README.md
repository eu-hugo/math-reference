(Personal notebook. Under construction...)

<!-- a place that holds everything in a form that actually makes sense to me, not scattered across textbooks with different notations and different levels of rigor. -->

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

<!-- Use semantic LaTeX commands (e.g. \lt) instead of literal or Unicode symbols -->

<!-- Use spaces around `:`, `\to`, `\mapsto`, `\iff`, `=`, `+`, `-`, etc; Space after commas; `\quad` for spacing -->

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

**Theorem** (Heron).

$$
\text{area} =\sqrt{s(s-a)(s-b)(s-c)}, \quad s = \frac{a + b + c}{2}
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

## Logarithm

**Definition.**

$$
\log_b x = y \iff b^y = x, \quad b \in \mathbb{R}^+, \quad b \neq 1, \quad x \in \mathbb{R}^+
$$

**Notation.**

$$
\ln x = \log_e x
$$

$$
\log x = \log_{10} x
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
\log_b b = 1
$$

$$
\log_b 1 = 0
$$

$$
\log_b b^x = x
$$

$$
b^{\log_b x} = x
$$

**Theorem** (change of base).

$$
\log_b x = \frac{\log_k x}{\log_k b}, \quad k \in \mathbb{R}^+, \quad k \neq 1
$$

**Proposition** (inequalities).

$$
\log_b x < \log_b y \iff x < y, \quad b > 1
$$

$$
\log_b x < \log_b y \iff x > y, \quad 0 < b < 1
$$

## Limit

**Definition** ($\epsilon - \delta$ definition).

$$
\lim_{x \to a} f(x) = L \iff \forall \epsilon > 0 \exists \delta > 0 \forall x \in \mathbb{R}, \big(a-\delta < x < a + \delta, x \neq a \implies L-\epsilon < f(x) < L+\epsilon\big)
$$

**Propoistion** (limits).

$$
\lim_{x\to 0}\frac{\sin x}{x}=1
$$

$$
\lim_{x\to 0}\frac{1-\cos x}{x}=0
$$

$$
\lim_{x\to 0}\frac{1-\cos x}{x^2}=\frac12
$$

$$
\lim_{x\to 0}\frac{\tan x}{x}=1
$$

$$
\lim_{x\to 0}\frac{e^x-1}{x}=1
$$

$$
\lim_{x\to 0}\frac{\ln(1+x)}{x}=1
$$

$$
\lim_{x\to 0}(1+x)^{1/x}=e
$$

$$
\lim_{n\to\infty}\left(1+\frac1n\right)^n=e
$$

$$
\lim_{x\to\infty}\left(1+\frac{a}{x}\right)^x=e^{a}
\quad (a\in\mathbb{R})
$$

$$
\lim_{x\to 0}\frac{a^x-1}{x}=\ln a
\quad (a>0)
$$

## Derivatives

**Definition** (differentiability at a point).

$$
f'(a) \coloneqq \lim_{h \to 0} \frac{f(a + h) - f(a)}{h}
$$

**Proposition** (derivatives).

$$
(x^n)' = n x^{n-1}
$$

$$
(\sin x)' = \cos x
$$

$$
(\cos x)' = -\sin x
$$

$$
(\tan x)' = \sec^2 x
$$

$$
(e^x)' = e^x
$$

$$
(\ln x)' = \frac{1}{x}
$$

$$
(a^x)' = a^x \ln a
$$

$$
(\sqrt{x})' = \frac{1}{2\sqrt{x}}
$$

$$
(uv)' = u'v + uv'
$$

$$
\left(\frac{u}{v}\right)' = \frac{u'v - uv'}{v^2}
$$

---

# Appendix

$$
\begin{aligned}
\in &: \text{element of} \\
\notin &: \text{not element of} \\
\subset &: \text{subset} \\
\cup &: \text{union} \\
\cap &: \text{intersection} \\
\setminus &: \text{set difference} \\
\emptyset &: \text{empty set} \\
\forall &: \text{for all} \\
\exists &: \text{there exists} \\
\neg &: \text{negation} \\
\land &: \text{conjunction} \\
\lor &: \text{disjunction} \\
\to &: \text{implication} \\
\iff &: \text{biconditional} \\
\mapsto &: \text{maps to} \\
\coloneqq &: \text{defined as} \\
\triangle ABC &: \text{triangle with vertices } A, B, C \\
\overline{AB} &: \text{line segment from } A \text{ to } B \\
\|\cdot\| &: \text{norm} \\
\mathbb{R} &: \text{real numbers} \\
\mathbb{R}^+ &: \text{positive reals}
\end{aligned}
$$

## Area

$$
\begin{aligned}
\text{trapezoid} &: \frac{1}{2} \cdot (\text{base}_1 + \text{base}_2) \cdot \text{height} \\
\text{parallelogram} &: \text{base} \cdot \text{height} \\
\text{rectangle} &: \text{length} \cdot \text{width} \\
\text{square} &: \text{side}^2 \\
\text{triangle} &: \frac{1}{2} \cdot \text{base} \cdot \text{height} \\
\text{circle} &: \pi \cdot \text{radius}^2
\end{aligned}
$$

## Perimeter

$$
\begin{aligned}
\text{rectangle} &: 2 \cdot (\text{length} + \text{width}) \\
\text{square} &: 4 \cdot \text{side} \\
\text{triangle} &: \text{side}_1 + \text{side}_2 + \text{side}_3 \\
\text{circle} &: 2\pi \cdot \text{radius}
\end{aligned}
$$

## Volume

$$
\begin{aligned}
\text{rectangular prism} &: \text{length} \cdot \text{width} \cdot \text{height} \\
\text{cube} &: \text{side}^3 \\
\text{cylinder} &: \pi \cdot \text{radius}^2 \cdot \text{height} \\
\text{cone} &: \frac{1}{3} \cdot \pi \cdot \text{radius}^2 \cdot \text{height} \\
\text{pyramid} &: \frac{1}{3} \cdot \text{base area} \cdot \text{height} \\
\text{sphere} &: \frac{4}{3} \cdot \pi \cdot \text{radius}^3
\end{aligned}
$$

## Surface Area

$$
\begin{aligned}
\text{rectangular prism} &: 2 \cdot (\text{length} \cdot \text{width} + \text{length} \cdot \text{height} + \text{width} \cdot \text{height}) \\
\text{cube} &: 6 \cdot \text{side}^2 \\
\text{cylinder} &: 2\pi \cdot \text{radius}^2 + 2\pi \cdot \text{radius} \cdot \text{height} \\
\text{sphere} &: 4\pi \cdot \text{radius}^2 \\
\text{cone} &: \pi \cdot \text{radius}^2 + \pi \cdot \text{radius} \cdot \text{slant height}
\end{aligned}
$$

## Times Table

| ×  | 2  | 3  | 4  | 5  | 6  | 7  | 8  | 9  | 10 | 11 | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 |
|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|
| 2  | 4  |    |    |    |    |    |    |    |    |    | 24 | 26 | 28 | 30 | 32 | 34 | 36 | 38 |    |
| 3  | 6  |    |    |    |    |    |    |    |    |    | 36 | 39 | 42 | 45 | 48 | 51 | 54 | 57 |    |
| 4  | 8  |    |    |    |    |    |    |    |    |    | 48 | 52 | 56 | 60 | 64 | 68 | 72 | 76 |    |
| 5  | 10 |    |    |    |    |    |    |    |    |    | 60 | 65 | 70 | 75 | 80 | 85 | 90 | 95 |    |
| 6  | 12 |    |    |    |    |    |    |    |    |    | 72 | 78 | 84 | 90 | 96 | 102 | 108 | 114 |     |
| 7  | 14 |    |    |    |    |    |    |    |    |    | 84 | 91 | 98 | 105 | 112 | 119 | 126 | 133 |     |
| 8  | 16 |    |    |    |    |    |    |    |    |    | 96 | 104 | 112 | 120 | 128 | 136 | 144 | 152 |     |
| 9  | 18 |    |    |    |    |    |    |    |    |    | 108 | 117 | 126 | 135 | 144 | 153 | 162 | 171 |     |
| 10 | 20 |    |    |    |    |    |    |    |    |    | 120 | 130 | 140 | 150 | 160 | 170 | 180 | 190 |     |
| 11 | 22 |    |    |    |    |    |    |    |    |    | 132 | 143 | 154 | 165 | 176 | 187 | 198 | 209 |     |
| 12 | 24 | 36 | 48 | 60 | 72 | 84 | 96 | 108 |    | 132 | 144 |    |    |    |    |    |    |    |    |
| 13 | 26 | 39 | 52 | 65 | 78 | 91 | 104 | 117 |    | 143 |    | 169 |    |    |    |    |    |    |    |
| 14 | 28 | 42 | 56 | 70 | 84 | 98 | 112 | 126 |    | 154 |    |    | 196 |    |    |    |    |    |    |
| 15 | 30 | 45 | 60 | 75 | 90 | 105 | 120 | 135 |    | 165 |    |    |    | 225 |    |    |    |    |    |
| 16 | 32 | 48 | 64 | 80 | 96 | 112 | 128 | 144 |    | 176 |    |    |    |    | 256 |    |    |    |    |
| 17 | 34 | 51 | 68 | 85 | 102 | 119 | 136 | 153 |    | 187 |    |    |    |    |    | 289 |    |    |    |
| 18 | 36 | 54 | 72 | 90 | 108 | 126 | 144 | 162 |    | 198 |    |    |    |    |    |    | 324 |    |    |
| 19 | 38 | 57 | 76 | 95 | 114 | 133 | 152 | 171 |    | 209 |    |    |    |    |    |    |    | 361 |    |
| 20 | 40 | 60 | 80 | 100 | 120 | 140 | 160 | 180 |    | 220 |    |    |    |    |    |    |    |    | 400 |

## Prime numbers

First under fifth: 2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47

## Line Equations

Slope–Intercept Form
  
$$
y = \text{(slope)}x + \text{(y-intercept)}
$$

Point–Slope Form

$$
y - y_1 = \text{(slope)}(x - x_1), \quad P = (x_1,y_1)
$$

Two–Point Form

$$
y - y_1 = \frac{y_2 - y_1}{x_2 - x_1}(x - x_1), \quad P_1 = (x_1,y_1) \text{ and } P_2 = (x_2,y_2)
$$

Standard (General) Form

$$
Ax + By + C = 0
$$

Intercept Form

$$
\frac{x}{a} + \frac{y}{b} = 1
$$

Symmetric Form (2D)

$$
\frac{x - x_1}{a} = \frac{y - y_1}{b}
$$

Parametric Form

$$
\begin{cases}
x = x_0 + at \\
y = y_0 + bt
\end{cases}
$$

Vector Form

$$
\mathbf{r}(t) = \mathbf{r}_0 + t\mathbf{v}
$$

$$
\begin{pmatrix}
x \\
y
\end{pmatrix}
= \begin{pmatrix}
x_0 \\
y_0
\end{pmatrix} + t \begin{pmatrix}
a \\
b
\end{pmatrix}
$$

Normal (Hesse) Form

$$
x \cos \theta + y \sin \theta = p
$$

## Exponent Laws

$$
\begin{aligned}
a^m  a^n &= a^{m+n} \\
\frac{a^m}{a^n} &= a^{m-n} \\
(a^m)^n &= a^{mn} \\
(ab)^n &= a^n b^n \\
\left(\frac{a}{b}\right)^n &= \frac{a^n}{b^n}
\end{aligned}
$$

## Vector Space Axioms

1. $$u + v = v + u$$
2. $$(u + v) + w = u + (v + w)$$
3. $$\exists 0: v + 0 = v$$

$$
(A, B, C) \in (0, \pi)^3 \iff A \in (0, \pi),\ B \in (0, \pi),\ C \in (0, \pi)
$$

$$
(a, b, c) \in (\mathbb{R}^+)^3 \iff a \in \mathbb{R}^+,\ b \in \mathbb{R}^+,\ c \in \mathbb{R}^+
$$
