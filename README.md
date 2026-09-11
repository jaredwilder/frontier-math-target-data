# Open-problem and technique data

A public data collection for open mathematics: problem registries, structural classifications, a normalized catalog of published techniques, and an Erdős-problems database in one YAML file.

Author: Jared Wilder. First public timestamp: 2026-09-10. Data dated 2026-07-18.

## Contents

| file | contents |
|---|---|
| `targets/erdos_problems.yaml` | 13,452 lines, one record per Erdős problem: number, prize, open/closed state with update date, OEIS cross-references, Lean formalization state, and tags |
| `targets/ORACLE-KBK-UNIFIED-TARGET-REGISTRY-ROUND2` | unified registry of mathematical targets |
| `targets/ORACLE-KBK-PROBLEM-SHAPES-ROUND2` | classification of open problems by structural shape |
| `targets/ORACLE-KBK-TECHNIQUE-REGISTRY-NORMALIZED` | normalized catalog of published mathematical techniques with stable identifiers |
| `targets/ORACLE-KBK-TECHNIQUE-PROBLEM-SHAPE-EDGES-ROUND2` | links between technique classes and problem shapes |
| `targets/ORACLE-KBK-EXPANDED-CANDIDATE-FAMILIES-ROUND2` | candidate problem families |
| `targets/ORACLE-KBK-TARGET-SCORING-SCHEMA` | historical scoring schema used to prioritize targets |
| `ammo/` | summaries of published techniques and the kinds of problems to which they apply |

The filenames retain the terminology of the original research system; the mathematical content is ordinary problem metadata and technique indexing.

## Publication boundary

Three source files from the same historical workspace are not public: composite strategy plans, composite technique-selection files, and about 8.7 MB of derived launch data.

Those files encode a private research workflow for selecting and composing techniques. They are not needed to use the public problem and literature data above. The separation is recorded explicitly so the public dataset has a clear boundary.

## Provenance

`erdos_problems.yaml` is derived from the Erdős Problems community database maintained by Thomas Bloom at erdosproblems.com, using the `teorth/erdosproblems` data as its source. Open/closed status is inherited from that database rather than assigned by this repository.

The companion `jaredwilder/open-math-frontier` combines multiple public sources into a larger index of 9,926 targets, 8,501 of which carry a callable finite/mechanical checker.

## License

Apache-2.0 for material authored here. The Erdős problem database retains its upstream terms.