# Plan 3

1. Dans code/trajectory.py, remplacer le raise NotImplementedError de evaluer
   en suivant son docstring et son commentaire Indice (trois phases : montée,
   plateau, descente). Ne pas modifier test/.
   Tests à faire passer :
   test_evaluer_ecrete_avant_le_depart_et_apres_la_fin,
   test_vitesse_nulle_aux_deux_bouts,
   test_vitesse_maximale_respectee,
   test_evaluer_a_l_interieur_de_la_descente_egale_la_formule_cinematique,
   test_distance_nulle_rend_un_profil_de_duree_nulle_sans_division,
   test_position_finale_egale_la_distance_demandee.
2. Lancer : pytest test/test_trajectory.py
   Si ces tests passent, dans progress.md cocher « evaluer »
   ([ ] devient [x]) et noter le résultat réel de pytest. Sinon, ne rien
   cocher et corriger.
