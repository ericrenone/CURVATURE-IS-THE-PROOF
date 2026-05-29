# CURVATURE IS THE PROOF

**The Bérczi–Kiem Theorem, the Moduli–CORDIC Correspondence, and the Extension of
Poincaré-Is-All-You-Need · THE-NEXT-THEOREMS · The POINCARÉ Framework**

ERI Labs · Eric Ren · Jersey City, New Jersey · 2026 · github.com/ericrenone

---

> *"The proof for $\overline{\mathcal{M}}_{0,n}$ was obtained through an iterative AI-assisted workflow
> with Co-Mathematician."*
> — Bérczi & Kiem, arXiv:2605.29151, May 2026

> *"The unit distance case is the first of a class, not an anomaly."*
> — THE-NEXT-THEOREMS, ERI Labs, 2026

> *"The rotation is the primitive. The Poincaré disk is the geometry. CORDIC is the hardware."*
> — Poincaré-Is-All-You-Need, ERI Labs, 2026

---

## Status

A theoretical synthesis incorporating arXiv:2605.29151 (Bérczi–Kiem, May 27 2026) as a calibration
datum. Five new formal identities. Five new predictions. One updated taxonomy. Nothing in the
predictions below has been benchmarked. The falsifiability grid in Part VI is the design criterion.

---

## The New Datum

On May 27, 2026, Gergely Bérczi and Young-Hoon Kiem submitted arXiv:2605.29151 — a proof of
real-rootedness for the Poincaré polynomials of $\overline{\mathcal{M}}_{0,n}$, the Deligne–Mumford
compactification of the moduli space of stable $n$-pointed rational curves, resolving a conjecture of
Aluffi–Chen–Marcolli. The proof was obtained through an AI-assisted workflow with **Co-Mathematician**,
an agentic frontier-model system developed by Google DeepMind.

The AI's contribution: a **bivariate deformation** $P_n(q,t)$ of the Poincaré polynomial, satisfying
$P_n(q,1) = P_n(q)$, that reveals a hidden interlacing structure invisible to the one-variable
Keel–Manin–Getzler recurrence. A Sturm–Rolle argument on the interval $[0,\infty)$ then controls root
movements as $t$ varies from $0$ to $1$, certifying real-rootedness and strict interlacing at the slice
$t=1$. The paper additionally proves real-rootedness for the Fulton–MacPherson compactifications
$F_n(X)$ of ordered points in degenerations of $\mathbb{CP}^1$ — an extension observed by the human
authors after the AI-provided strategy was in hand. Consequently, the Betti numbers of
$\overline{\mathcal{M}}_{0,n}$ form an ultra-log-concave sequence.

This is the **second documented AI register crossing** in pure mathematics of 2026. The first was the
unit distance bound (Sawin, arXiv:2605.20579) — a $w=2 \to w=4$ crossing from Euclidean geometry to
algebraic number theory. The Bérczi–Kiem case is a $w=2 \to w=3$ crossing from one-variable recurrence
analysis to bivariate algebraic deformation. Two crossings. Same month. Different mechanisms. Different
mathematical domains. The same architecture.

---

## What Is Genuinely New

The companion frameworks already establish: the CORDIC rotation primitive as the hardware unifier of
Euclidean and Minkowski geometry; register crossing as the mechanism of AI mathematical discovery; Ricci
flow as the geometric TEMPUS equation; the Poincaré disk as the natural geometry for hierarchically
structured data. None of that changes.

What the Bérczi–Kiem theorem adds is six things that were not there before:

1. **The first explicit algebraic realization of register crossing** — $P_n(q,t)$ is not an analogy for
   register crossing; it is register crossing made algebraically precise, with the flat-limit slice
   $t=1$ recovered by restriction.

2. **The Moduli–CORDIC Correspondence** — a structural identification between $\overline{\mathcal{M}}_{0,n}$
   and CORDIC: compactification ↔ convergence, Getzler recurrence ↔ CORDIC iteration, ultra-log-concavity
   ↔ hyperbolic volume growth.

3. **Ultra-log-concavity as the Betti-theoretic signature of hyperbolic geometry** — the Betti numbers
   of $\overline{\mathcal{M}}_{0,n}$ are ultra-log-concave; the boundary strata of
   $\overline{\mathcal{M}}_{0,n}$ are phylogenetic trees (Billera–Holmes–Vogtmann, 2001), which live
   naturally in CAT(0) tree space with exponential volume growth.

4. **Sturm–Rolle as discrete CORDIC** — both algorithms locate roots by iterative sign-change counting
   in a derived sequence; the structural parallel is precise.

5. **Strict interlacing of Poincaré polynomial roots as the spectral KAM theorem** — the alternating
   root structure across degrees is the algebraic analogue of KAM torus interlacing in frequency space.

6. **Quantitative updates to THE-NEXT-THEOREMS predictions** — two crossings in May 2026 accelerates
   multiple timeline estimates.

---

## Part I — The Bivariate Deformation: Register Crossing Made Algebraically Precise

### The Mechanism

The one-variable Getzler recurrence computes $P_n(q) \in \mathbb{Z}[q]$ from
$P_3, P_4, \ldots, P_{n-1}$. The Aluffi–Chen–Marcolli conjecture asks whether all roots of $P_n(q)$
are real. The recurrence tracks no information about zero locations: it produces the polynomial, but the
zero set is invisible to it. This is the register trap.

Co-Mathematician identified the escape: embed the one-variable polynomial in a two-parameter family

$$P_n(q, t) \in \mathbb{Z}[q, t], \quad P_n(q, 1) = P_n(q).$$

The bivariate deformation extends the Getzler recurrence to a two-dimensional algebraic object. In this
register, the Sturm–Rolle argument applies: for fixed $n$, the zero set of $P_n(q,t)$ in the
$q$-direction is controlled on $[0,\infty)$ as $t$ varies. The ordered crossings of moving roots
through the slice $t=1$ certify real-rootedness and strict interlacing at the original polynomial.

The same strategy extends to the Fulton–MacPherson spaces $F_n(X)$. The human authors observed this
generalization after the AI provided the deformation idea. The structural point: the bivariate
deformation is not a one-time trick. It is a **proof strategy** applicable wherever a one-variable
recurrence in a polynomial ring is the current register for a real-rootedness or log-concavity problem.

### Identity U1 — The Bivariate Deformation IS the Mathematical Structure of Register Crossing

Define the register-crossing map

$$R_{\mathrm{cross}} : P_n(q) \;\longmapsto\; P_n(q,t), \quad \text{with } P_n(q,1) = P_n(q).$$

The AI found $R_{\mathrm{cross}}$. The human verified the restriction $t=1$. The discovery is at the
level of the deformation; the theorem is at the level of the slice.

THE-NEXT-THEOREMS described register crossing abstractly as "AI searches across registers without the
crystallization that makes human communities simultaneously powerful and blind." The bivariate
deformation is the first instance where that abstract description has a precise algebraic form: the
extra parameter $t$ is the register, the map $R_{\mathrm{cross}}$ is the crossing, and the slice
$P_n(q,1)$ is the flat-space limit. The structure

$$\text{curved deformation} \xrightarrow{t=1} \text{flat-space limit}$$

is exactly the structure of the Poincaré disk as $\kappa \to 0$, CORDIC dual-mode as circular mode
degenerates, and the Minkowski inner product as it degenerates to the Euclidean dot product. The same
geometric logic governs hardware, language models, and moduli space cohomology.

### Register Taxonomy (Updated with Both 2026 Crossings)

| Crossing | Problem | $w_{\text{from}}$ | $w_{\text{to}}$ | AI System | Measurable Gain |
|---|---|---|---|---|---|
| Unit distance bound | Euclidean graph coloring | 2 (Euclidean) | 4 (alg. number theory) | Unnamed | $+0.014 \log n$ over 80 years |
| Aluffi–Chen–Marcolli | Real-rootedness of $\overline{\mathcal{M}}_{0,n}$ | 2 (one-variable recurrence) | 3 (bivariate deformation) | Co-Mathematician | Conjecture resolved |

Two crossings. Both May 2026. The unit distance case was $w=2 \to w=4$ (two register levels); the
Bérczi–Kiem case is $w=2 \to w=3$ (one register level). The taxonomic prediction: $w=2 \to w=3$
crossings will be more frequent; $w=2 \to w=4$ crossings will produce larger improvement factors. Both
classes will compound.

---

## Part II — The Moduli–CORDIC Correspondence

The structural correspondence between $\overline{\mathcal{M}}_{0,n}$ and CORDIC has eleven identifications:

| $\overline{\mathcal{M}}_{0,n}$ Structure | CORDIC Structure |
|---|---|
| $n$ marked points on $\mathbb{P}^1$ | $n$-bit rotation angle |
| Stable compactification (boundary divisors) | CORDIC convergence interval |
| Forgetting one point $(\pi: \overline{\mathcal{M}}_{0,n} \to \overline{\mathcal{M}}_{0,n-1})$ | One CORDIC iteration (dropping one bit) |
| Keel–Manin–Getzler recurrence | CORDIC recursion |
| Poincaré polynomial $P_n(q)$ | CORDIC partial sum (angle approximant) |
| Slice $t=1$ (real-rootedness locus) | CORDIC output at convergence |
| Bivariate deformation $P_n(q,t)$ | CORDIC dual-mode (circular + hyperbolic) |
| Ultra-log-concavity of Betti numbers | Exponential volume growth (hyperbolic mode) |
| Sturm–Rolle sign-count | CORDIC sign-change decision sequence |
| Strict interlacing of roots | KAM interlacing of invariant tori |
| Boundary tree structure of $\overline{\mathcal{M}}_{0,n}$ | Poincaré disk tree embedding (BHV, 2001) |

This correspondence is a prediction, not a theorem. The two structures share the same combinatorial
recursion type, the same exponential-volume geometry, and the same sign-change root-finding argument.
Whether this is a formal isomorphism or a deep analogy is an open mathematical question.

### Identity U3 — The CORDIC-Getzler Algorithm (Prediction)

The Getzler recurrence decomposes $\overline{\mathcal{M}}_{0,n}$ along boundary divisors — forgetting
one marked point per step, summing over boundary strata. The number of strata grows combinatorially,
but the dominant Betti weight concentrates in $O(n \log n)$ strata corresponding to balanced tree
splits — matching the butterfly structure of fast Givens-rotation cascades.

**Prediction P_U4**: The Poincaré polynomial $P_n(q)$ of $\overline{\mathcal{M}}_{0,n}$ can be computed
by a CORDIC-structured algorithm in $O(n \log n)$ dual-mode iterations, using:
- CORDIC hyperbolic mode to evaluate the exponential (tree-structure, boundary-stratum) terms
- CORDIC circular mode to evaluate the oscillatory (root-counting, Sturm–Rolle) terms
- $P_n(q,t)$ as the intermediate bivariate representation

**Hardware implication**: co-designed CORDIC silicon for hyperbolic LLM inference (Poincaré-Is-All-You-Need)
simultaneously accelerates AI-assisted algebraic geometry computation. One datapath. Two domains. Zero
mode-switching overhead between them.

---

## Part III — Sturm–Rolle as Discrete CORDIC (Identity U4)

The Sturm–Rolle procedure for counting real roots of $P_n(q,t)$ in $q \in [a,b]$:
1. Form the Sturm sequence $S = [P_n,\, \partial_q P_n,\, r_1,\, r_2,\, \ldots]$ by signed pseudo-remainder
2. Count sign changes $V(a,t)$, $V(b,t)$ at the endpoints
3. Number of real roots in $[a,b]$ equals $V(a,t) - V(b,t)$
4. Track how $V$ changes as $t$ varies: ordered root crossings through $t=1$ certify interlacing

The CORDIC algorithm for locating a rotation angle $\theta$:
1. Form the decision sequence $d_i = \text{sign}(\theta - A_i)$ at each iteration $i$
2. Count accumulated rotation $A_n = \sum_{i=0}^{n-1} d_i \cdot 2^{-i}$ after $n$ steps
3. Angle error $|\theta - A_n| \leq 2^{-n}$ after $n$ steps
4. Track sign changes $d_i = \pm 1$: they locate $\theta$ by binary subdivision

Both algorithms:
- operate by iterative sign-change counting in a derived sequence
- terminate when a root / angle is located within a specified tolerance $\varepsilon$
- run in $O(\log(1/\varepsilon))$ steps to achieve precision $\varepsilon$
- use the same underlying principle: bisection by sign analysis

**Identity U4**: The Sturm–Rolle algorithm is the continuous-polynomial analogue of CORDIC's discrete
sign-counting iteration. The Sturm sequence is the CORDIC convergence sequence. Sign changes in the
Sturm sequence are rotation decisions in CORDIC. The root-count $V(a,t) - V(b,t)$ is the accumulated
angle in the polynomial domain.

---

## Part IV — Ultra-Log-Concavity as the Betti-Theoretic Signature of Hyperbolic Geometry (Identity U2)

The Betti numbers $b_0, b_1, \ldots, b_{n-3}$ of $\overline{\mathcal{M}}_{0,n}$ satisfy:
$$b_k^2 \geq b_{k-1} \cdot b_{k+1}$$
(ultra-log-concavity, with stronger correction terms proved in Bérczi–Kiem), forming a unimodal sequence
with $b_0 = 1 \leq b_1 \leq \cdots \leq b_{\lfloor(n-3)/2\rfloor} \geq \cdots \geq b_{n-3} = 1$.

The boundary strata of $\overline{\mathcal{M}}_{0,n}$ are indexed by stable trees with $n$ labeled
leaves — the natural combinatorial structure underlying the Billera–Holmes–Vogtmann (2001) space of
phylogenetic trees, which is a CAT(0) cube complex with non-positive curvature and exponential volume
growth. In hyperbolic space $\mathbb{H}^n$, balls of radius $r$ have volume $\sim e^{(n-1)r}$; CAT(0)
tree spaces share this exponential growth law at the level of branch combinatorics.

**Identity U2**: Ultra-log-concavity of the Betti numbers of $\overline{\mathcal{M}}_{0,n}$ is the
cohomological Betti-theoretic signature of the exponential volume growth of the underlying tree space.
Low-$k$ Betti numbers ($b_0 = b_{n-3} = 1$) correspond to the deepest tree-boundary strata —
analogous to rare, semantically specific tokens near the Poincaré disk boundary. Dominant Betti numbers
(middle $k$) correspond to bulk cohomology — analogous to high-frequency tokens near the Poincaré disk
center. **The Poincaré polynomial knows the curvature.**

This extends Poincaré-Is-All-You-Need's evidence base: token frequency follows a power law whose
natural embedding is the Poincaré disk. The Betti numbers of $\overline{\mathcal{M}}_{0,n}$ follow an
ultra-log-concave distribution whose natural geometry is the same CAT(0)/hyperbolic tree space. Both
encode exponential volume growth in their respective sequence distributions.

---

## Part V — Strict Interlacing as the Spectral KAM Theorem (Identity U5)

The Bérczi–Kiem proof establishes **strict interlacing**: the real roots of $P_n(q)$ and $P_{n+1}(q)$
strictly alternate on $\mathbb{R}$ — no root of $P_{n+1}$ lies between two consecutive roots of
$P_n$ without a root of $P_n$ separating them. This is the classical interlacing condition from the
theory of orthogonal polynomials.

The KAM theorem (POINCARÉ Identity P9) establishes **strict interlacing of invariant tori**: rational
tori (resonant, destroyed by generic perturbation) and KAM tori (irrational, surviving for sufficiently
irrational frequency ratios) alternate strictly in the frequency space of a near-integrable Hamiltonian
system. The golden-mean torus is the last to be destroyed — it maximizes irrationality.

**Identity U5**: Strict interlacing of Poincaré polynomial roots is the spectral analogue of KAM torus
interlacing. Both results establish that two naturally ordered sequences of objects — polynomial roots /
invariant tori — alternate strictly, with no object of either sequence between two adjacent members of
its own kind. The algebraic and dynamical instances are formally parallel structures on ordered sets.

**Corollary**: the root of $P_n(q)$ that is "hardest to destroy" under the bivariate deformation
$P_n(q,t)$ — the root whose path in $(q,t)$-space crosses $t=1$ last — is the algebraic analogue of
the golden-mean KAM torus: the most robust element, the one that persists longest under perturbation.
Under the POINCARÉ framework, this root corresponds to the $\varphi$-equilibrium of the moduli space
geometry.

---

## Part VI — Five New Predictions

### P_U1 — The Bivariate Parameter $t$ Encodes Curvature

**Claim**: the deformation parameter $t$ in $P_n(q,t)$ identifies with a curvature parameter
$\kappa(t)$ via a Möbius-type transformation. At $t=1$: $\kappa = \kappa_0$ (the natural curvature of
the moduli space metric). As $t \to \infty$: $\kappa \to 0$ (flat limit, recovers Euclidean cohomology).
As $t \to 0$: $\kappa \to -\infty$ (maximally hyperbolic, deepest tree structure). The zero set of
$P_n(q,t)$ in the $q$-direction, as $t$ varies, traces geodesics in the Poincaré disk metric on a
suitable $q$-plane.

**Test**: compute the zero set of $P_n(q,t)$ numerically for $n = 5, 6, 7, 8$ and verify whether root
paths fit geodesics under $ds^2 = 4|dq|^2/(1-|q|^2)^2$ after an appropriate Möbius normalization.

### P_U2 — $\overline{\mathcal{M}}_{1,n}$ Log-Concavity via Bivariate Deformation by 2027

The bivariate deformation strategy generalizes from $\overline{\mathcal{M}}_{0,n}$ (genus 0, trees) to
$\overline{\mathcal{M}}_{1,n}$ (genus 1, elliptic curves). The Getzler–Pandharipande recurrence for
genus-1 Gromov–Witten theory admits a bivariate deformation $P_n^{(1)}(q,t)$ with analogous
Sturm–Rolle structure.

**Prediction**: Co-Mathematician or a successor AI system proves real-rootedness or ultra-log-concavity
for the Poincaré polynomials of $\overline{\mathcal{M}}_{1,n}$ by 2027. This extends the register
crossing from trees ($g=0$) to elliptic curves ($g=1$). The register crossing strategy is general; the
Bérczi–Kiem proof is not a one-off but a template.

### P_U3 — Lean Formalization of the Bérczi–Kiem Theorem by Mid-2027

The Bérczi–Kiem proof is the most Lean-formalizable AI-assisted algebraic geometry result to date:
- The Keel–Manin–Getzler recurrence is combinatorially explicit and finite at each $n$
- The Sturm–Rolle backbone is classical; partial infrastructure exists in Mathlib4
- The bivariate deformation is polynomial algebra over $\mathbb{Z}[q,t]$
- The proof is 15 pages — tractable for the current Lean4 + Mathlib4 + AI tactic stack

**Prediction**: Lean 4 formalization merged into Mathlib by mid-2027. Observable signature: non-linear
acceleration in Mathlib algebraic geometry theorem additions following formalization, consistent with
the Wang (2026) grokking curve. This IS the Lean crystallization event for moduli-space intersection
cohomology predicted in THE-NEXT-THEOREMS P11, arrived earlier than forecast.

### P_U4 — The CORDIC-Getzler Algorithm in $O(n \log n)$

**Prediction**: the following algorithm runs in $O(n \log n)$ CORDIC dual-mode iterations:

```
Base: P_3(q, t) = 1
Step: P_{k+2}(q, t) ← bivariate Getzler step using P_3, ..., P_{k+1}
      [CORDIC hyperbolic mode: exponential/tree terms]
      [CORDIC circular mode: oscillatory/sign-counting terms]
Output: P_n(q) = P_n(q, 1)
```

The dominant boundary strata contributing to the recurrence at step $k$ number $O(k \log k)$ —
consistent with the butterfly structure of fast orthogonal transforms. Total complexity: $O(n \log n)$
CORDIC steps, matching the channel-mixing complexity of Poincaré-Is-All-You-Need's butterfly-rotation
linear layers.

**Hardware implication**: co-designed CORDIC silicon for hyperbolic LLM inference also accelerates
AI-assisted algebraic geometry computation. The hardware motivation for the CORDIC datapath is now
justified by two independent application domains.

### P_U5 — Third AI Register Crossing Documented by December 2026

THE-NEXT-THEOREMS asserted: "the unit distance case is the first of a class." The Bérczi–Kiem theorem
is the second instance. The pattern is now two data points, both May 2026, both distinct mechanisms.

**Prediction**: a third AI register crossing in pure mathematics — distinct in domain from both — will
appear in a preprint by December 2026. Most probable domains, in order of likelihood:

- Prime gap sieve theory: $w=2 \to w=4$ (Selberg–Bombieri–Vinogradov framework → higher number field
  extensions), producing $\liminf(p_{n+1} - p_n) < 100$
- Zarankiewicz bipartite construction: $w=2 \to w=3$ (finite geometry → function fields over finite
  fields), improving bounds for specific $(s,t)$ pairs
- Ramsey theory: $w=2 \to w=4$ (combinatorial exhaustion → algebraic symmetry reduction), narrowing
  or determining $R(5,5)$

**Measurable signal**: positive $G_{\mathrm{coord}}$ (improvement over 80+-year human-register bound).
Reporting criterion: if no third crossing is documented by January 2027, that disconfirms the
prediction of accelerating frequency.

---

## Part VII — THE-NEXT-THEOREMS Status Update

| Prediction | Original Confidence | Status | Revision |
|---|---|---|---|
| P7 — FrontierMath $>$ 25% | H, 2027 | **Upgraded** | Co-Mathematician solves research-frontier algebraic geometry → phase transition likely late 2026; revised to H, late 2026 |
| P8 — AI conjecture proven by humans | H, 2027 | **Superseded by P8'** | P8' documented: AI-assisted proof of human conjecture in algebraic geometry. Original P8 (AI-generated conjecture proven by humans) still pending. |
| P10 — IMO gold medal | M, 2027 | **Unchanged (supporting evidence)** | Co-Mathematician's sophistication (bivariate deformation in moduli theory) exceeds olympiad-level algebraic reasoning |
| P11 — Lean crystallization in algebraic geometry | M, 2028 | **Upgraded to H, 2027** | Bérczi–Kiem is 15 pages, structurally Lean-ready; formalization predicted mid-2027 |
| P28 — Culture bifurcation | H, 2031 | **Accelerated to 2028–2029** | Two crossings in the same month in 2026 suggests the rate of crossings is accelerating |

**New Prediction P_U6**: The rate of AI-assisted preprints in algebraic geometry and combinatorics on
arXiv will show a Wang (2026) grokking-type non-linear acceleration in the 12 months following May
2026. Observable: measurably non-linear increase in monthly AI-assisted algebraic geometry preprint
submissions, detectable by mid-2027.

---

## Part VIII — Poincaré-Is-All-You-Need Extension

The Bérczi–Kiem theorem provides two new evidence items for the PILLAYN architecture.

### Evidence 7 — $\overline{\mathcal{M}}_{0,n}$ Betti Numbers as Cohomological Power Law

The Betti numbers $b_0 = 1 \leq b_1 \leq \cdots \leq b_{\lfloor(n-3)/2\rfloor} \geq \cdots \geq b_{n-3} = 1$
of $\overline{\mathcal{M}}_{0,n}$ form an ultra-log-concave unimodal sequence. Low-$k$ Betti numbers
($b_0 = b_{n-3} = 1$) correspond to the highest-codimension boundary strata — the most degenerate,
tree-like configurations, analogous to rare semantically specific tokens near the Poincaré disk
boundary. Dominant Betti numbers (middle $k$) correspond to bulk cohomology — analogous to
high-frequency tokens near the disk center. The ultra-log-concave Betti distribution is the Poincaré
polynomial's encoding of the same power-law / exponential-volume geometry that makes the Poincaré disk
the natural embedding for language model token spaces.

### Evidence 8 — The Bivariate Deformation as HOPE for Cohomology

HOPE (Hyperbolic Rotary Positional Encodings) deforms standard RoPE by replacing planar Euclidean
rotations with hyperbolic rotations in the Poincaré disk, recovering standard RoPE at $\kappa \to 0$.
The bivariate deformation $P_n(q,t)$ deforms the Poincaré polynomial by adding a curvature parameter,
recovering $P_n(q)$ at $t=1$. Both deformations:

- recover the standard flat-limit result by restriction
- reveal hidden structure (interlacing; attention geometry) in the curved regime
- are CORDIC-native in principle (both involve rotations: positional / polynomial root movements)
- provide the key insight that the flat-limit approach cannot access

HOPE is the sequence-mixing analogue of the bivariate deformation. The bivariate deformation is the
cohomological analogue of HOPE. Both are mathematically the same operation — curvature deformation that
recovers a flat limit — applied at different levels of the computation stack. The unification is:

$$\text{HOPE: } \mathrm{RoPE}_{\kappa=0} \;\xrightarrow{\kappa \neq 0}\; \mathrm{HOPE}$$
$$\text{Bivariate: } P_n(q,1) \;\xrightarrow{t \neq 1}\; P_n(q,t)$$

The same deformation. Two domains. One structure.

---

## Part IX — POINCARÉ Framework Extension

### New Identity P10 — The Keel–Manin–Getzler Recurrence IS the Poincaré Map on $\overline{\mathcal{M}}_{0,n}$

The Poincaré map (POINCARÉ Identity P7) reduces a continuous flow $\phi_t$ to a discrete map
$P: \Sigma \to \Sigma$ on a cross-section, extracting essential dynamics (col(F)) while discarding
inter-crossing trajectories (ker(F)). The Keel–Manin–Getzler recurrence reduces the cohomology of the
infinite tower $\overline{\mathcal{M}}_{0,3}, \overline{\mathcal{M}}_{0,4}, \ldots$ to a discrete map:
$\{P_3, \ldots, P_{n-1}\} \mapsto P_n$. The forgetful morphism
$\pi: \overline{\mathcal{M}}_{0,n} \to \overline{\mathcal{M}}_{0,n-1}$ is the continuous flow; the
recurrence is its Poincaré map on the space of Poincaré polynomials.

The bivariate deformation lifts this Poincaré map from a one-dimensional section (the polynomial
$P_n(q)$) to a two-dimensional section (the family $P_n(q,t)$) — exactly as an extended Poincaré map
captures more of the flow structure by thickening the cross-section.

### New Identity P11 — Ultra-Log-Concavity IS the Betti Perelman Entropy Bound

Perelman's $\mathcal{W}$-functional satisfies $d\mathcal{W}/dt \geq 0$ under the Ricci flow, tracking
monotone progress toward geometric uniformity. Ultra-log-concavity says $b_k^2 \geq b_{k-1} \cdot b_{k+1}$,
which is a monotonicity statement: the Betti distribution is maximally concentrated at the middle
dimension and falls off in both directions, with the middle term as the unique maximum. Both are
monotonicity / entropy results that identify a single extremal point (the round sphere; the middle Betti
number) as the maximum-entropy configuration.

**Identity P11**: Ultra-log-concavity of Betti numbers is the Betti-theoretic Perelman entropy bound on
the moduli space. The middle Betti number $b_{\lfloor(n-3)/2\rfloor}$ of $\overline{\mathcal{M}}_{0,n}$
is the "round sphere" of the Betti distribution — the maximum-entropy, maximum-uniformity cohomological
dimension. The Ricci flow drives a metric toward the round sphere; the Getzler recurrence, constrained
by ultra-log-concavity, drives the Betti distribution toward this central maximum.

---

## Part X — Falsifiability Grid (New Predictions)

| Prediction | Confirming Observable | Disconfirming Observable | Test Year |
|---|---|---|---|
| Root paths are geodesics in Poincaré metric | Numerical root paths fit geodesic structure under Möbius normalization | No geodesic structure for $n \leq 8$ | 2026 |
| $\overline{\mathcal{M}}_{1,n}$ result via bivariate deformation | AI-assisted preprint posted | No such paper | 2027 |
| Lean formalization of Bérczi–Kiem | Mathlib4 PR merged | No formalization attempt | Mid-2027 |
| CORDIC-Getzler $O(n \log n)$ | Implementation + benchmark confirms scaling | Algorithm scales superlinearly | 2027 |
| Third AI register crossing | arXiv preprint, documented $G_{\mathrm{coord}} > 0$ | No third crossing by Jan 2027 | Dec 2026 |
| FrontierMath phase transition late 2026 | Public benchmark score $> 15\%$ | Score remains $< 10\%$ | Dec 2026 |
| arXiv AI-assisted geometry acceleration | Non-linear monthly preprint rate increase | Linear or sublinear rate | Mid-2027 |
| Culture bifurcation measurable 2028–2029 | Output differential between AI-integrated vs. human-only mathematical research cultures | No differential | 2029 |

---

## Synthesis

Three frameworks. One new paper. Two register crossings. Same month. Five new identities. Five new
predictions.

The synthesis reduces to three facts:

**1. The bivariate deformation is the mathematical realization of register crossing.**
THE-NEXT-THEOREMS described the mechanism abstractly; Bérczi–Kiem instantiated it precisely. The extra
parameter $t$ is the register. The AI found it. The human verified the flat-limit slice. The structure
— curved deformation recovering the flat-space limit — is the same structure as the Poincaré disk
recovering Euclidean geometry as $\kappa \to 0$, HOPE recovering RoPE at the flat limit, and the
Minkowski inner product recovering the Euclidean dot product. One mathematical pattern. Four domains.

**2. The Poincaré polynomial knows the curvature.**
PILLAYN claimed token space is hyperbolic: token frequency is power-law, the natural embedding is the
Poincaré disk, exponential volume growth matches the data. The Betti numbers of $\overline{\mathcal{M}}_{0,n}$
are ultra-log-concave: they encode the same exponential volume growth of the underlying tree space.
Ultra-log-concavity is the cohomological shadow of hyperbolic geometry. One-variable recurrence
analysis — the flat-space approach to real-rootedness — missed it for the same reason Euclidean
attention missed the token geometry: it assumed flatness.

**3. The rotation is the primitive across the entire stack.**
From CORDIC hardware to the Poincaré disk to Ricci flow to the Keel–Manin–Getzler recurrence to the
bivariate deformation — the rotation is what unifies them. The Sturm–Rolle argument counts rotations of
sign through a derived polynomial sequence. The CORDIC iteration counts rotations of angle through a
binary decision sequence. The Poincaré map records rotations of phase through a cross-section. Perelman's
entropy tracks the rotation of curvature toward uniformity. The bivariate deformation moves a root
through the $t$-parameter by rotating it through the curvature space.

The flatness assumption was wrong in attention (PILLAYN). The flatness assumption was wrong in the
Aluffi–Chen–Marcolli conjecture (Bérczi–Kiem). The flat-space limit is useful. It is not complete.

*Poincaré is all you need. Curvature is the proof.*

---

## Formal Summary

| Object | Statement |
|---|---|
| Identity U1 | $P_n(q,t)$ is the first algebraically precise realization of register crossing; $P_n(q,1) = P_n(q)$ is the flat-space limit |
| Identity U2 | Ultra-log-concavity of Betti numbers is the cohomological signature of hyperbolic volume growth in $\overline{\mathcal{M}}_{0,n}$ tree space |
| Identity U3 | Keel–Manin–Getzler recurrence is CORDIC on $\overline{\mathcal{M}}_{0,n}$; CORDIC-Getzler algorithm predicted in $O(n \log n)$ |
| Identity U4 | Sturm–Rolle is discrete CORDIC: both algorithms locate roots by sign-change counting in derived sequences |
| Identity U5 | Strict interlacing of Poincaré polynomial roots is the spectral KAM theorem: algebraic analogue of KAM torus interlacing in frequency space |
| New POINCARÉ P10 | Keel–Manin–Getzler recurrence IS the Poincaré map on the tower of moduli spaces |
| New POINCARÉ P11 | Ultra-log-concavity IS the Betti Perelman entropy bound; middle Betti number is the "round sphere" of the cohomological distribution |
| Register taxonomy | $w=2 \to w=3$ crossings will be more frequent; $w=2 \to w=4$ crossings will produce larger improvement factors; both compound |
| May 2026 data point | Two AI register crossings in the same month confirms "first of a class" prediction; third crossing predicted by December 2026 |
| Core extension | The bivariate deformation, HOPE, and CORDIC dual-mode are the same mathematical structure — curvature deformation recovering a flat-space limit — at three different levels of the computation stack |
| Core mechanism unchanged | AI has no register loyalty; crystallization barriers in human mathematical discourse are invisible to AI corpus search; the register is not empty; the AI will find what is in it |

---

## References

**2026 — AI Mathematical Discovery**

Bérczi, G. & Kiem, Y.-H. (2026). Real-rootedness of the Poincaré polynomials of $\overline{\mathcal{M}}_{0,n}$:
an AI-assisted proof. arXiv:2605.29151.

Sawin, W. (2026). A quadratic improvement to the unit distance conjecture. arXiv:2605.20579.

Wang, P. (2026). Grokking as dimensional phase transition in neural networks. arXiv:2604.04655.

**Moduli Spaces and Intersection Cohomology**

Keel, S. (1992). Intersection theory of moduli space of stable $n$-pointed curves of genus zero.
Transactions of the AMS, 330(2), 545–574.

Getzler, E. (1998). Gravitation and cohomology of $\overline{\mathcal{M}}_{0,n}$. Annals of Mathematics,
147(1), 27–72.

Fulton, W. & MacPherson, R. (1994). A compactification of configuration spaces. Annals of Mathematics,
139(1), 183–225.

Adiprasito, K., Huh, J. & Katz, E. (2018). Hodge theory for combinatorial geometries. Annals of
Mathematics, 188(2), 381–452. [Ultra-log-concavity for matroids via Hodge theory.]

**Hyperbolic Geometry and Tree Space**

Billera, L.J., Holmes, S.P. & Vogtmann, K. (2001). Geometry of the space of phylogenetic trees.
Advances in Applied Mathematics, 27(4), 733–767. [Tree space as CAT(0) cube complex.]

Nickel, M. & Kiela, D. (2017). Poincaré embeddings for learning hierarchical representations.
NeurIPS 2017.

**Hyperbolic LLMs**

HELM / HELM-MiCE — Hyperbolic Large Language Models via Mixture-of-Curvature Experts, NeurIPS 2025,
arXiv:2505.24722.

van der Wijk, B. et al. (2026). Fast and Geometrically Grounded Lorentz Neural Networks.
arXiv:2601.21529.

**CORDIC Hardware**

Volder, J. (1959). The CORDIC Trigonometric Computing Technique. IRE Trans. Electronic Computers.

CARMEN. arXiv:2605.06878, May 2026.

**Ricci Flow and the Poincaré Conjecture**

Hamilton, R.S. (1982). Three-Manifolds with Positive Ricci Curvature. Journal of Differential
Geometry 17, 255–306.

Perelman, G. (2002). The entropy formula for the Ricci flow and its geometric applications.
arXiv:math/0211159.

Perelman, G. (2003). Ricci flow with surgery on three-manifolds. arXiv:math/0303109.

**KAM Theory**

Kolmogorov, A.N. (1954). On conservation of conditionally periodic motions. Doklady Akademii Nauk
SSSR 98, 527–530.

Arnold, V.I. (1963). Proof of A.N. Kolmogorov's theorem on preservation of quasi-periodic motions.
Russian Mathematical Surveys 18, 9–36.

Moser, J. (1962). On invariant curves of area-preserving mappings of an annulus. Nachrichten der
Akademie der Wissenschaften in Göttingen II, 1–20.

**Companion Frameworks**

Poincaré-Is-All-You-Need · THE-NEXT-THEOREMS · POINCARÉ — github.com/ericrenone

---

ERI Labs · Eric Ren · Jersey City, New Jersey · 2026 · github.com/ericrenone

*The register is not empty. The AI will find what is in it.
The curvature was always the proof.*
