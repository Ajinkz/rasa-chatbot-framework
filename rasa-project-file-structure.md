### Files from rasa project

| Filename                  | Uses                                                 |
|---------------------------|------------------------------------------------------|
| `__init__.py`              | an empty file that helps python find your actions    |
| `actions.py`                | code for your custom actions                         |
| `config.yml` ‘*’            | configuration of your NLU and Core models            |
| `credentials.yml`           | details for connecting to other services             |
| `data/nlu.md` ‘*’           | your NLU training data                               |
| `data/stories.md` ‘*’       | your stories                                         |
| `domain.yml` ‘*’            | your assistant’s domain                              |
| `endpoints.yml`             | details for connecting to channels like fb messenger |
| `models/<timestamp>.tar.gz` | your initial model                                   |


```
.
├── __init__.py
├── actions.py
├── config.yml
├── credentials.yml
├── data
│   ├── nlu.md
│   └── stories.md
├── domain.yml
├── endpoints.yml
└── models
    └── <timestamp>.tar.gz
```
