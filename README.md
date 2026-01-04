# LLM-Document-Translator
le but  est : 
Créer une application web de traduction automatique de documents (PDF / Word) à l’aide d’un modèle LLM pré-entraîné, permettant à l’utilisateur d’uploader un fichier, choisir la langue source et cible, puis télécharger le document traduit.

1- Bibliothèques utilisées

Streamlit : interface web simple et interactive

Transformers (Hugging Face) : chargement du modèle de traduction pré-entraîné

MarianMTModel / MarianTokenizer : traduction automatique

python-docx : lecture et génération de fichiers Word

pdfplumber : extraction du texte des fichiers PDF

reportlab (2ᵉ code) : génération de fichiers PDF

tempfile / os : gestion des fichiers temporaires et optimisation

2- Différence entre les deux codes
Premier code (translate)

Traduit paragraphe par paragraphe → lent pour les gros fichiers

Sauvegarde uniquement en Word

Interface simple

Pas de barre de progression

 Deuxième code(translate_pro)

Traduit par batch → plus rapide

Affiche une barre de progression

Sauvegarde Word + PDF

Interface améliorée

Gère mieux les PDF vides

Optimisé avec cache et paramètres Streamlit
