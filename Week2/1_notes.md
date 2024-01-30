# Week 2

## Lecture 1: Fuzzy Propositions

| Symbol     | Connective  | Usage                                                 | Definition              |
| ---------- | ----------- | ----------------------------------------------------- | ----------------------- |
| $\neg$     | NOT         | $\neg P$                                              | $1 - T(P)$              |
| $\vee$     | OR          | $P \vee Q$                                            | $max\{T(P), T(Q)\}$     |
| $\wedge$   | AND         | $P \wedge Q$                                          | $min\{T(P), T(Q)\}$     |
| $\implies$ | IMPLICATION | $(P \implies Q)$ or $(\neg P \vee Q)$                 | $min\{(1-T(P)), T(Q)\}$ |
| $=$        | EQUALITY    | $(P = Q)$ or $[(P \implies Q) \wedge (Q \implies P)]$ | $1 - \|T(P) - T(Q)\|$   |
