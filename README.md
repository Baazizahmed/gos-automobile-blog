# gos-automobile-blog
Plan de Développement Final et README.md (Version Définitive)
On repart sur des bases propres avec ce plan d'action. C'est la feuille de route définitive pour votre projet.
Étape 0 : Création du Projet (si ce n'est pas déjà fait)
Generated bash
# Dans un dossier parent, en dehors de l'ancien projet
symfony new gos-automobile-blog --webapp
cd gos-automobile-blog
git init
git add .
git commit -m "Initial project structure for GOS Automobile Blog"
Use code with caution.
Bash
Liste des Commandes de Branche du Projet (README.md)
Copiez-collez la commande git branch ... correspondant au ticket que vous souhaitez commencer.
Sprint 1 : Fondations et Structure de Données
Description : Installer les outils d'analyse statique du code.
git branch sprint1-ticket1-setup/static-code-analyzers
Description : Créer toutes les entités de la base de données (User, Post (Prestation), Category, Setting, ResetPasswordRequest) et leurs relations.
git branch sprint1-ticket2-build/database-entities
Description : Mettre en place Webpack Encore, Sass et Bootstrap.
git branch sprint1-ticket3-setup/frontend-assets
Sprint 2 : Gestion des Employés et Sécurité
Description : Créer une fixture pour l'utilisateur SUPER_ADMIN.
git branch sprint2-ticket1-build/admin-user-fixtures
Description : Mettre en place le système de connexion/déconnexion avec make:auth.
git branch sprint2-ticket2-build/employee-auth-system
Description : Construire la fonctionnalité de "réinitialisation de mot de passe" pour les employés. (Ce ticket est ambitieux, il peut devenir optionnel si le temps manque).
git branch sprint2-ticket3-build/password-reset-feature
Sprint 3 : Construction du Panneau d'Administration
Description : Créer la maquette de base du back-office et le tableau de bord.
git branch sprint3-ticket1-build/admin-dashboard-layout
Description : Créer le CRUD pour gérer les Catégories de Service.
git branch sprint3-ticket2-add/admin-crud-for-categories
Description : Créer le CRUD pour gérer les Prestations (la table post), avec l'upload d'image, le choix de la catégorie, etc.
git branch sprint3-ticket3-add/admin-crud-for-services
Sprint 4 : Construction du Site Vitrine Public
Description : Créer la page d'accueil qui affiche une sélection des prestations ou des catégories.
git branch sprint4-ticket1-build/public-homepage
Description : Créer la page "Nos Prestations" qui liste toutes les prestations publiées.
git branch sprint4-ticket2-build/public-service-listing
Description : Créer la page de détail d'une prestation, accessible via son slug.
git branch sprint4-ticket3-build/public-single-service-page
Description : Appliquer le style CSS/Sass final sur tout le site public.
git branch sprint4-ticket4-style/public-site-design
Sprint 5 : Finalisation
Description : Créer le CRUD pour gérer les Informations du Garage (table Setting).
git branch sprint5-ticket1-add/admin-crud-for-settings
Description : Mettre en place la gestion des rôles (SUPER_ADMIN vs ADMIN).
git branch sprint5-ticket2-secure/role-management
Description : Tests finaux et rédaction de la documentation.
git branch sprint5-ticket3-docs/final-testing-and-documentation