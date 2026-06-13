Application web full-stack qui transforme n'importe quel document académique en expérience d'apprentissage interactive. Déposez un PDF, Word ou PowerPoint et l'application génère automatiquement des résumés adaptatifs, des QCM, un feedback pédagogique personnalisé et une narration audio — le tout adapté au domaine et au niveau de l'étudiant.

Développé avec Python Flask et l'API OpenAI dans le cadre d'un projet universitaire axé IA à l'UQAC.

Fonctionnalités


Upload multi-format : PDF, DOCX, PPTX (jusqu'à 20 Mo)
Résumé adaptatif : points clés + résumé de synthèse, adapté au domaine et au niveau (débutant / intermédiaire / avancé)
Générateur de QCM : 10 questions à choix multiples extraites du document via GPT
Correction & feedback IA : réponses notées + retour personnalisé du tuteur IA (forces et points à retravailler)
Synthèse vocale : résumé lu à voix haute via OpenAI TTS
Sessions sécurisées : sessions Flask côté serveur, aucune donnée sensible dans les cookies.

Lancement
git clone https://github.com/mano4k/Assistant_P-dagogique_IA.git
cd ai-pedagogical-assistant
pip install -r requirements.txt
python app.py


Réalisé par : ILBOUDO Soutongnoma Hermann Rodrigue — UQAC, 2025
