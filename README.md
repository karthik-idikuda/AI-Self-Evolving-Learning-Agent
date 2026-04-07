# AI Self-Evolving Learning Agent

Autonomous AI agent that evaluates its own performance and modifies its source code to improve, running inside a sandboxed environment with rollback safety.

## Features

- Self-evaluation loop with performance benchmarks
- Automated code modification via LLM-driven rewrites
- Sandboxed Docker execution environment
- Version control and automatic rollback on regression
- Performance metrics tracking across iterations

## Tech Stack

Python, GPT-4, Docker, Git, Subprocess

## Getting Started

### Prerequisites

- Python 3.8+
- pip

### Installation

```bash
git clone https://github.com/karthik-idikuda/AI-Self-Evolving-Learning-Agent.git
cd AI-Self-Evolving-Learning-Agent
pip install -r requirements.txt
```

### Usage

```bash
python evolve.py
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
