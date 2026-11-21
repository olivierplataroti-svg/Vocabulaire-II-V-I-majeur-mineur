# Vocabulaire II–V–I — Majeur et mineur

Deux parcours de treize modules et un espace personnel **Mes licks**. Interface violet et rose clair, suivi par tonalité et tempo, journal modifiable, séances libres, variations, bilans et sauvegardes JSON.

Les étapes reprennent les trois exercices des méthodes de Louis Alléaume (Jazzcomposer.fr), avec préparations facultatives, paliers de transposition et révisions différées. Aucun calendrier en semaines n’est imposé. Une étape peut accueillir autant de séances que nécessaire ; sa validation reste distincte.

## Mes licks

Une fiche regroupe un nom, des catégories et des liens Drive vers des PDF, images ou audios. Les notes et descriptions musicales sont facultatives. Chaque support peut préciser une tonalité, une page, des mesures ou un repère audio. Un même fichier peut servir plusieurs fiches ou passages.

Les tonalités et étapes sont choisies par l’utilisateur. Favoris, dates de reprise, états de travail et archives permettent de retrouver les fiches. Une séance peut associer plusieurs licks : elle conserve un seul identifiant et une seule durée dans les totaux et dans le journal. Les séances de méthode et de vocabulaire personnel se filtrent séparément. La progression des 26 modules reste indépendante.

Une variation de la méthode peut être conservée dans Mes licks. L’import des sauvegardes conserve les enregistrements les plus récents et ne double pas les séances. Les sauvegardes antérieures restent compatibles.

## Durées réelles des séances

La saisie est manuelle pour les séances de méthode et de licks : choisir **Au piano**, **Musical hors piano** ou **Mixte** avant d’enregistrer. Pour une séance mixte, saisir séparément les minutes au piano et hors piano ; le total se calcule automatiquement. Le compteur piano additionne uniquement les minutes au piano déclarées. Le total musical inclut les deux activités. Aucun chronomètre n’est utilisé.

Le journal, les filtres, les sauvegardes JSON et l’export CSV conservent cette répartition. Une séance partagée entre plusieurs licks compte une seule fois. Les séances sans répartition issues d’une ancienne sauvegarde conservent leur durée totale ; aucune durée au piano n’est inventée. Toute nouvelle saisie ou correction demande un choix explicite parmi les trois natures de travail.

## Ressources personnelles

Les méthodes, audios et références privées restent dans Drive et dans les données personnelles. Ils ne sont pas recopiés dans ce dépôt public. La version Sites privée charge le catalogue automatiquement. Sur GitHub Pages, importer le fichier personnel de ressources dans **Réglages > Importer mes ressources**. Il contient les références des deux méthodes et la collection initiale de 65 fiches / 77 supports. Une réimportation ne remplace pas les fiches déjà personnalisées et n’ajoute aucun historique de pratique.

Les documents s’ouvrent directement dans Drive avec le compte Google autorisé. Le suivi est enregistré dans ce navigateur ; Sites et GitHub ont des stockages distincts. Le raccordement à la synchronisation du tableau de bord constitue l’étape suivante.

## Publication et vérification

La version Sites sert `dist/`. Pour GitHub Pages, les fichiers publics sont à la racine : Settings > Pages > Deploy from a branch > `main` > `/ (root)`.

Aucun paquet ni compilation nécessaire. Vérifier avec `node --test tests/core.test.cjs tests/licks.test.cjs tests/practice-time.test.cjs` et `node --check app.js`. Les audits du catalogue privé sont ignorés lorsque ce fichier n’est pas présent dans le dépôt public.
