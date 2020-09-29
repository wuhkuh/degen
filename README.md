# Derivation generator for C&H's sentential logic

Generates derivations for sequents in C&H's sentential
logic;\
Prints Gentzen-style diagrams for the LaTeX `bussproofs`
package.

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

- AND-Introduction, AND-Elimination
- AXIOM
- IF-Introduction, IF-Elimination
- IFF-Introduction, IFF-Elimination
- NOT-Introduction NOT-Elimination
- OR-Introduction OR-Elimination
- RAA

Discharging of statements is (naturally) supported.\
For now, a sequent may only have a single consequent.
