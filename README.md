# matsurigoto

Standalone Etzhayyim public-service actor. Canonical implementation and data are
Clojure/CLJC and EDN. External lexicons and WASM component metadata are isolated
under `wire/`; canonical lexicon projections and the execution ontology live in
`contracts/`.

Run the complete offline suite with `kbb -M:test`.
