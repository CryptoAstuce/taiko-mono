# 2. Origine L1 et blocs L2

Chaque bloc L2 conserve une relation avec une origine L1. Le client utilise cette origine pour déterminer le contexte historique, les frontières de confirmation et la continuité de la chaîne.

Les contrats et le client transportent des métadonnées comme le numéro de lot, l’origine L1 et les références de bloc. Ces liens permettent de vérifier qu’un bloc L2 appartient au parcours attendu.

Une réorganisation L1 peut imposer de revenir sur des propositions ou des curseurs de synchronisation. Le client doit traiter cette possibilité explicitement.

Les tables auxiliaires ne sont utiles que si elles restent cohérentes avec les blocs et événements réellement observés.

Suite : [Propositions et vérification](03-propositions-verification.md).
