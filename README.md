# Vocabulaire II–V–I — Majeur et mineur

Application personnelle au piano. Deux parcours de treize modules, suivi par tonalité et tempo, journal modifiable, séances libres, variations, bilans et sauvegardes JSON.

Les étapes reprennent les trois exercices des méthodes de Louis Alléaume (Jazzcomposer.fr), avec préparations facultatives, paliers de transposition et révisions différées. Aucun calendrier en semaines n’est imposé. Les niveaux sont déclarés par l’utilisateur.

Les deux PDF et les 294 audios restent accessibles avec le compte Google autorisé : lecteur intégré et bouton d’ouverture dans Drive. Les méthodes et leurs références privées ne sont pas recopiées dans le dépôt public. Sur GitHub Pages, importer son catalogue personnel dans Réglages > Importer une sauvegarde ou mes ressources. Le catalogue reste dans le navigateur et peut aussi être inclus dans une sauvegarde JSON. La version Sites privée le charge automatiquement.

Le suivi est enregistré dans ce navigateur. L’import JSON fusionne les identifiants et conserve les modifications les plus récentes. Le raccordement à la synchronisation du tableau de bord constitue l’étape suivante.

## Publication

Sites sert `dist/`. La racine contient les mêmes fichiers pour GitHub Pages. Settings > Pages > Deploy from a branch > `main` > `/ (root)`.

## Vérification

`node tests/core.test.cjs` et `node --check app.js`. Aucun paquet ni compilation nécessaire.
