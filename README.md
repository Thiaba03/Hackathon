# Hackathon
🚀 ATS AgroConnect - Système de Gestion de Recrutement Intelligent
ATS AgroConnect est une plateforme web fullstack conçue pour automatiser et optimiser le processus de recrutement. Grâce à l'analyse de documents (NLP) et un algorithme de scoring dynamique, elle permet aux recruteurs de filtrer les meilleurs talents en un clin d'œil.

🌟 Points Forts
Parsing Automatisé : Extraction intelligente des données de CV (PDF/DOCX) via spaCy.

Scoring Personnalisé : Algorithme de notation pondéré selon la typologie du poste.

Expérience Candidat Fluide : Formulaire multi-étapes sans rechargement (AJAX).

Dashboard Recruteur : Interface de pilotage complète avec filtres dynamiques.

🛠️ Stack Technique
Frontend
Framework : Bootstrap 5, Jinja2 (Templates)

Interactivité : JavaScript (Vanilla & AJAX / Fetch API)

Backend
Langage : Python 3.x

Framework : Flask

NLP / Traitement : spaCy (extraction d'entités), PyMuPDF, Textract

Sécurité : Flask-Session, Hashing (Werkzeug)

Base de Données
Système : MySQL

Modélisation : Schéma relationnel complexe (10 tables) avec gestion de fichiers binaires (LONGBLOB).

📋 Architecture de la Base de Données
Le système repose sur une base de données structurée pour garantir la traçabilité complète d'une candidature :

Gestion Recruteurs & Entreprises

Offres d'Emploi & Questions de présélection

Candidats & Documents (CV, Lettres de motivation)

Scoring & Feedback des utilisateurs

⚙️ Algorithme de Scoring
L'IA calcule un score de pertinence basé sur plusieurs critères modulables par le recruteur :

Compétences (40%) : Matching sémantique entre le CV et l'offre.

Expérience (30%) : Analyse des années et types de postes.

Questions (20%) : Évaluation des réponses aux questions de présélection.

Formation (10%) : Vérification des diplômes requis.
