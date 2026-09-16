# 1. Un based rollup Ethereum-native

Taiko Alethia se présente comme un based rollup : la construction et l’ordonnancement des blocs s’appuient sur Ethereum plutôt que sur un séquenceur central permanent.

Le dépôt regroupe les contrats du protocole, un client en Go, un client Rust et des outils d’écosystème. Cette organisation relie la preuve, le consensus L1 et l’exécution L2.

Le rollup conserve une séparation entre les données publiées sur L1 et l’état exécuté sur L2. Les contrats L1 arbitrent les transitions acceptées.

La propriété based réduit certaines hypothèses de séquenceur, mais n’élimine pas les risques de disponibilité, de preuve et de configuration réseau.

Suite : [Origine L1 et blocs L2](02-origine-l1-blocs-l2.md).
