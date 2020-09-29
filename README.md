# Derivation generator for C&H's sentential logic

Generates derivations for sequents in C&H's sentential
logic;\
Prints Gentzen-style diagrams for the
[bussproofs](https://ctan.org/pkg/bussproofs) TeX package.

## Language summary

### Symbols

- ABSURDUM
- AND
- IF
- IFF
- NOT
- OR

### Signature

- Any variable ranging over logical statements.

## Deduction rules

- AND-introduction, AND-elimination
- AXIOM
- IF-introduction, IF-elimination
- IFF-introduction, IFF-elimination
- NOT-introduction NOT-elimination
- OR-introduction OR-elimination
- RAA

Discharging of statements is (naturally) supported.\
For now, a sequent may only have a single consequent.
