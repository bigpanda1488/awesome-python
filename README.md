# Awesome Python

A curated collection of powerful Python frameworks, libraries, AI agents, security tools, Web3 technologies, and developer resources.

## Categories

- [Artificial Intelligence](#artificial-intelligence)
- [AI Agents](#ai-agents)
- [Machine Learning](#machine-learning)
- [Web Development](#web-development)
- [Cybersecurity](#cybersecurity)
- [Blockchain and Web3](#blockchain-and-web3)
- [Automation](#automation)
- [Developer Tools](#developer-tools)
- [Model Context Protocol](#model-context-protocol)

## Artificial Intelligence

- [PyTorch](https://github.com/pytorch/pytorch)
- [Transformers](https://github.com/huggingface/transformers)
- [Ollama](https://github.com/ollama/ollama-python)

## AI Agents

- [OpenAI Agents](https://github.com/openai/openai-agents-python)
- [LangChain](https://github.com/langchain-ai/langchain)
- [LangGraph](https://github.com/langchain-ai/langgraph)

## Cybersecurity

- [Cryptography](https://github.com/pyca/cryptography)
- [Bandit](https://github.com/PyCQA/bandit)

## Blockchain and Web3

- [Web3.py](https://github.com/ethereum/web3.py)
- [Ethereum](https://ethereum.org/)
- [Ronin](https://roninchain.com/)

## Model Context Protocol

- [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk)
- [FastMCP](https://github.com/PrefectHQ/fastmcp)

## Contributing

Contributions, suggestions, and pull requests are welcome.

## Acknowledgments

Inspired by [Awesome Python](https://awesome-python.com/).
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
 