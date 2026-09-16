# 4. Client Taiko et synchronisation

Le taiko-client suit les événements L1, construit ou récupère les données nécessaires et transmet les informations au moteur L2. Le client Rust propose une implémentation alternative du même rôle général.

La synchronisation doit conserver des curseurs cohérents pour les blocs, les origines L1 et les propositions. Un redémarrage ou une réorganisation peut exiger une réconciliation.

Les bindings de contrats rendent les appels typés, tandis que le moteur d’exécution applique les règles de la chaîne. Le client coordonne ces composants sans remplacer les garanties des contrats.

Les paramètres RPC L1/L2, les identifiants de chaîne et les adresses de services font partie du contexte de sécurité.

Suite : [Pont, signaux et messages](05-pont-signaux-messages.md).
