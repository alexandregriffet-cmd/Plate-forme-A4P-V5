# A4P Platform V5

Version métier statique premium pour GitHub Pages.

## Ce que fait cette V5
- création de club et d'équipe
- génération d'un lien unique de passation CMP
- formulaire joueur avant questionnaire
- collecte structurée des réponses dans `localStorage`
- dashboard staff club
- fiche équipe détaillée
- résultat individuel de passation
- export du dernier CMP vers `localStorage["a4p_hub_results"]`

## Déploiement GitHub
1. Créer un nouveau dépôt GitHub
2. Déposer tous les fichiers du pack à la racine
3. Activer GitHub Pages sur la branche `main`
4. Ouvrir `index.html`

## Limites actuelles
- stockage local navigateur
- pas encore de base distante ni d'authentification multi-utilisateur

## Parcours conseillé
1. Ouvrir `create-team.html`
2. Créer une équipe
3. Copier le lien de passation
4. Ouvrir ce lien dans un autre appareil ou navigateur
5. Remplir plusieurs passations
6. Ouvrir `dashboard.html`
7. Ouvrir `equipe.html`
