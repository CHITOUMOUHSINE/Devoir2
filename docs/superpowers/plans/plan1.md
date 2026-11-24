# Plan 1

1. Dans code/state_machine.py, remplacer le raise NotImplementedError de
   Transitions.repondu en suivant son docstring et son commentaire Indice
   (l'état courant décide où mène un refus ; SORTIE et INDECIS d'abord).
   Ne pas modifier test/.
   Tests à faire passer :
   test_refus_en_confirmation_commande_renvoie_a_ecoute_jamais_a_interpretation,
   test_refus_en_confirmation_action_renvoie_a_interpretation_jamais_a_ecoute,
   test_scenario_nominal_avance_oui_oui_quitter_finit_en_arret_avec_une_action,
   test_max_tours_borne_une_boucle_qui_ne_convergerait_jamais,
   test_la_commande_dictee_traverse_la_machine_jusqu_a_l_execution,
   test_apres_trois_essais_rates_la_machine_revient_ecouter_et_n_execute_rien.
2. Lancer : pytest test/test_state_machine.py test/test_boucle.py
   Si ces tests passent, dans progress.md cocher « Transitions.repondu »
   ([ ] devient [x]) et noter le résultat réel de pytest. Sinon, ne rien
   cocher et corriger.