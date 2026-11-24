# Plan 2

1. Dans code/state_machine.py, remplacer le raise NotImplementedError de signer
   en suivant son docstring et son commentaire Indice (REP-103 : antihoraire
   positif, horaire négatif). Ne pas modifier test/.
   Tests à faire passer :
   test_signer_is_forward_vrai_rend_une_vitesse_lineaire_positive,
   test_signer_is_forward_faux_rend_une_vitesse_lineaire_negative,
   test_signer_is_clockwise_vrai_rend_une_vitesse_angulaire_negative,
   test_signer_is_clockwise_faux_rend_une_vitesse_angulaire_positive,
   test_action_depuis_config_lit_les_vitesses_de_la_configuration,
   test_action_depuis_config_distance_hors_borne_est_ramenee_au_maximum,
   test_action_depuis_config_reculer_sans_parametre_rend_une_vitesse_lineaire_negative,
   test_action_depuis_config_sans_parametre_applique_les_valeurs_par_defaut_de_la_config,
   test_executer_action_publie_plus_d_un_message_twist,
   test_executer_action_laisse_la_tortue_immobile_apres_coup,
   test_interpreter_action_valide_lit_les_vitesses_dans_la_config_pas_dans_la_reponse,
   test_interpreter_sequence_rend_un_plan_a_plusieurs_etapes.
2. Lancer : pytest test/test_state_machine.py test/test_boucle.py test/test_llm_interpreter.py
   Si ces tests passent, dans progress.md cocher « signer »
   ([ ] devient [x]) et noter le résultat réel de pytest. Sinon, ne rien
   cocher et corriger.