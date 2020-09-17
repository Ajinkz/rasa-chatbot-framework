### Minimal checklist of files we modified to build a basic FAQ assistant:

- `data/nlu.md`: Add NLU training data for faq/ intents
- `data/responses.md`: Add responses associated with faq/ intents
- `config.yml`: Add ReponseSelector in your NLU pipeline
- `domain.yml`: Add a retrieval action respond_faq and intent faq
- `data/stories.md`: Add a simple story for FAQs
- `test_stories.md`: Add E2E test stories for your FAQs
