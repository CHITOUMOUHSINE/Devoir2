# Plan 4

1. Dans code/arcs.py, remplacer le raise NotImplementedError de
   echantillonner_arc en suivant son docstring et son commentaire Indice
   (Euler explicite, modèle unicycle, collision testée avant chaque pas).
   Ne pas modifier test/.
   Tests à faire passer :
   test_arc_en_ligne_droite_rotation_nulle_donne_un_segment,
   test_arc_frole_l_obstacle_sans_le_toucher,
   test_arc_entre_dans_l_obstacle_est_detecte,
   test_arc_dont_le_segment_etait_libre_est_refuse,
   test_arc_sens_lineaire_negatif_recule_et_detecte_l_obstacle_derriere,
   test_arc_sens_angulaire_negatif_tourne_a_l_oppose_du_sens_positif,
   test_aucun_obstacle_declare_aucune_collision_sans_lever,
   test_arc_a_portee_du_rayon_plus_tolerance_mais_hors_du_rayon_brut_est_detecte.
2. Lancer : pytest test/test_arcs.py
   Si ces tests passent, dans progress.md cocher « echantillonner_arc »
   ([ ] devient [x]) et noter le résultat réel de pytest. Sinon, ne rien
   cocher et corriger.
3. Lancer toute la suite : pytest
   Noter le résultat final réel dans progress.md.
