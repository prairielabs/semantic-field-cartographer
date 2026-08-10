# Theoretical basis

Background for the system. Not required for operation.

## Semantic Field Theory

Semantic fields overlay latent space and govern how symbols associate.
Symbols are the atomic unit. Symbols cluster into words — discrete units of
meaning. Words form constructs: any defined collection of symbols, from a
single word to a library.

Constructs may be assigned numbers. The numbers are unitless and relative,
expressed on [0,1], nondiscrete. For each scalar, 0 and 1 must be defined;
0.5 may serve as a neutral point where appropriate. These continuous
binaries are **scalars**, with constructs attributed to them.

## Scalar types

- **Tendency** — C₁ 0—0.5—1 C₂. Preference between two constructs.
- **Affinity** — C₁ + C₂ 0——1 C₁₊₂. Degree to which two constructs merge.
- **Absence** — C₁ 0——1 C₁. Presence of a construct versus its absence.
- **Degree** — C₁(0—1). Magnitude of a quality.

This system implements **degree only**. Tendency and affinity are
pair-indexed — relations between two constructs rather than values of one —
so a rectangular table cannot hold them. They are reserved deliberately.
Extensions that add them require a relational data model.

## Nesting and composites

Constructs nest. A civilization — a collection of organized symbols — has
qualities to degrees (e.g. Rome, 12 AD: greed 0.8, corruption 0.6,
wealth 0.5, stability 0.6). Subjects defined on axes C₁…C₆ are folded into
exactly three composites for display (e.g. C₁/C₃ → x, C₄ → y,
C₂/C₅/C₆ → z), because human spatial perception is three-dimensional. A
single scalar mapped directly to an axis is the one-component case. The
fold is declared by the person and its recipe is inspectable; dimensionality
reduction is never delegated to an algorithm.

## Shannon–Weaver background

Shannon and Weaver (*The Mathematical Theory of Communication*, 1949)
divide communication into three levels, posed serially: **A** — technical
(how accurately symbols are transmitted), **B** — semantic (how precisely
transmitted symbols convey meaning), **C** — effectiveness (how received
meaning affects conduct). Level A is addressed by information theory and
computing. Level C corresponds to applied inference. This system operates
at level B.

Weaver proposed adding a *semantic receiver* to the model: a second decoder
that matches the statistical semantic characteristics of a message to the
semantic capacities of the totality of receivers. A large language model
fits this specification; it is the component performing semantic judgment
in this system.

In this lineage (Boltzmann → Shannon), entropy measures remaining
alternatives, and constraint is anything that reduces it. The S column is a
computed mean over a construct's profile; the underlying concept is
field-level uncertainty. The system introduces no new mathematics — it
applies existing concepts at the semantic level.

## Measurement properties

Degrees are produced by the hosting model as semantic judgments. The
instrument therefore characterizes the model as well as the subject:
different models produce different maps from the same prompt, and the
differences are attributable to differences in their semantic
representations. Maps should record which model produced them and when.
Sparse or hedged regions of a map reflect sparse knowledge in the model and
should be disclosed. Unoccupied regions of the space are observations about
the matter and merit reporting.
