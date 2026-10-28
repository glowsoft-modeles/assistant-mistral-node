# Assistant conversationnel avec Mistral

Un point d'accès de conversation branché sur l'API de Mistral AI.

Modèle de départ Bastide (`assistant-mistral-node`), écrit par Glowsoft. Il se construit et se déploie sans modification ; la campagne hebdomadaire le construit avec des valeurs d'essai.

## Variables

Le déploiement en un clic les demande avant la construction ; copiez `.env.example` pour un essai local.

- `MISTRAL_API_KEY` (requise) : La clé d'API de votre compte Mistral AI. À obtenir ici : https://console.mistral.ai/api-keys
- `MISTRAL_MODELE` (facultative) : Le nom du modèle interrogé ; « mistral-small-latest » par défaut. À obtenir ici : https://docs.mistral.ai/getting-started/models/models_overview/
