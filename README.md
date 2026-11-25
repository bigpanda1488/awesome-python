Panda-AI-Framework/
├── README.md
├── pyproject.toml
├── .gitignore
├── .env.example
├── panda_ai/
│   ├── __init__.py
│   └── main.py
└── tests/
    └── test_api.py
python -m venv .venv
source .venv/bin/activate
pip install -e '.[dev]'
uvicorn panda_ai.main:app --port 8000
 