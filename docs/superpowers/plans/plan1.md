# Plan 1 — Fonction evaluer()

1. Dans code/trajectory.py, implémenter uniquement la fonction evaluer()
   en respectant son docstring et les commentaires Indice.
2. Gérer :

   - L'accélération.
   - La vitesse constante.
   - La décélération.
   - Les instants avant le départ et après la fin.
   - Le cas d'une distance nulle.
3. Ne modifier aucun autre fichier de code.
   Ne modifier aucun fichier dans test/.
4. Exécuter les tests ciblés :

   - test_position_finale_egale_la_distance_demandee
   - test_vitesse_nulle_aux_deux_bouts
   - test_vitesse_maximale_respectee
   - test_evaluer_a_l_interieur_de_la_descente_egale_la_formule_cinematique
   - test_distance_nulle_rend_un_profil_de_duree_nulle_sans_division
   - test_evaluer_ecrete_avant_le_depart_et_apres_la_fin
5. Mettre à jour obligatoirement :

   - progress.md : cocher le plan uniquement si les 6 tests passent.
   - audit.md : enregistrer les fichiers modifiés, les tests exécutés,
     leurs résultats et les éventuelles erreurs.

Règle : ne jamais passer au plan suivant tant que les 6 tests
ne sont pas validés.
