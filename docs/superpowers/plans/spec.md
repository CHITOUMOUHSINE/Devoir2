# Spec

Le programme doit permettre à un robot mobile commandé vocalement
de comprendre les instructions de l'utilisateur, gérer les confirmations
et les refus, planifier ses déplacements et éviter les obstacles.

Les fonctions à implémenter sont :

- `evaluer()` dans `trajectory.py` : calculer la position du robot
  selon son profil de vitesse.
- `echantillonner_arc()` dans `arcs.py` : échantillonner les trajectoires
  en arc et vérifier les collisions avec les obstacles.
- `signer()` : déterminer le signe des vitesses linéaire et angulaire
  selon le sens de déplacement et de rotation.
- `Transitions.repondu()` : gérer les réponses de l'utilisateur
  et les transitions entre les états du système.

La suite `test/` doit passer en entier.

Ne fais que ce que le plan en cours demande.

Interdit :

- Modifier les fichiers de `test/`.
- Changer la signature d'une fonction existante.
- Ajouter une dépendance.
- Modifier des fonctions sans rapport avec le plan en cours.
