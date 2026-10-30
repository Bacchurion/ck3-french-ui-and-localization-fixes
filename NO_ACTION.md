# Liste des no-action

Ces problèmes ont bien été constatés, mais sortent du scope du mod pour être corrigés : soit niveau moteur, soit nécessite de toucher les évents ou autre. Ils possiblement aussi été constatés côté anglais

* Conseils oecuméniques : Dans le tooltip, la position pour les principes/doctrines tentent d'être affichés avant que l'on ai sélectionné notre position => mot manquant

* Complot d'amitié pour le fantoche : dans befriend_scheme_outcome_events.txt, befriend_outcome.0001, les 2 appels à  notify_puppeteer_of_scheme_outcome_effect doivent utiliser ` OWNER = scope:owner` et non pas `OWNER = scope:scheme.scheme_owner`