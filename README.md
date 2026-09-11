# frontier-math-target-data

Target registries, problem shapes, and a normalized technique catalog for attacking open
mathematics, plus the Erdos problems database in one YAML file.

Author: Jared Wilder. First public timestamp: 2026-09-10. Data dated 2026-07-18.

## What is here

| file | what it is |
|---|---|
| `targets/erdos_problems.yaml` | 13,452 lines, one record per Erdos problem: number, prize, open/closed state with a last-update date, OEIS cross-references, Lean formalization state, and tags |
| `targets/ORACLE-KBK-UNIFIED-TARGET-REGISTRY-ROUND2` | the unified registry of attackable targets |
| `targets/ORACLE-KBK-PROBLEM-SHAPES-ROUND2` | a classification of open problems by structural shape |
| `targets/ORACLE-KBK-TECHNIQUE-REGISTRY-NORMALIZED` | a normalized catalog of published mathematical techniques with stable identifiers |
| `targets/ORACLE-KBK-TECHNIQUE-PROBLEM-SHAPE-EDGES-ROUND2` | which technique classes apply to which problem shapes |
| `targets/ORACLE-KBK-EXPANDED-CANDIDATE-FAMILIES-ROUND2` | candidate problem families |
| `targets/ORACLE-KBK-TARGET-SCORING-SCHEMA` | how a target's payoff was scored, with the schema exposed |
| `ammo/` | the attack ammunition documents: summaries of published techniques and where they bite |

## What is deliberately NOT here

Three files from the same directory are **withheld**: the composite battle plans, the composite
superblades, and 8.7 MB of derived launch objects.

Those encode how the machine chooses which technique to fire at which target and in what
composition. That is method, not mathematics, and it is the author's to keep. Everything above is
data about open problems and published techniques, which is useful to anyone and secret to nobody.

Saying which files were held back, and why, seemed better than quietly shipping a subset.

## Provenance

`erdos_problems.yaml` is derived from the Erdos problems community database maintained by Thomas
Bloom at erdosproblems.com, with the teorth/erdosproblems data as its source. **Openness is that
database's marking, not the author's.** The same rule governs the companion frontier at
github.com/jaredwilder/open-math-frontier, which holds 9,926 targets from seven sources with 8,501
carrying a callable mechanical verifier.

## License

Apache-2.0 for the material authored here. The Erdos problem database retains its upstream terms.
