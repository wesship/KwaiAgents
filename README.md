> [!NOTE]
> This project is a fork of [KwaiKEG/KwaiAgents](https://github.com/KwaiKEG/KwaiAgents). The original project and its contributors can be found there.

# KwaiAgents

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![CI/CD Status](https://github.com/wesship/KwaiAgents/actions/workflows/ci.yml/badge.svg)](https://github.com/wesship/KwaiAgents/actions/workflows/ci.yml)

> A generalized information-seeking agent system with Large Language Models (LLMs). This repository includes the KAgentSys-Lite system, KAgentLMs (agent-tuned LLMs), KAgentInstruct (instruction-tuning data), and KAgentBench (agent evaluation benchmark).

---

## ✨ Features

- **KAgentSys-Lite**: A lightweight agent system for planning, reflection, and tool-use.
- **KAgentLMs**: A series of LLMs fine-tuned for agent tasks.
- **KAgentInstruct**: Over 200k instruction-tuning examples for agent training.
- **KAgentBench**: A benchmark with over 3,000 examples for evaluating agent capabilities.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.10
- Conda (Anaconda or Miniconda)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/wesship/KwaiAgents.git
   cd KwaiAgents
   ```
2. Create and activate a Conda environment:
   ```bash
   conda create -n kagent python=3.10
   conda activate kagent
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

To run the agent system with GPT-3.5:

```bash
export OPENAI_API_KEY=your-api-key
kagentsys --query="Who is Andy Lau's wife?" --llm_name="gpt-3.5-turbo" --lang="en"
```

---

## 🛠️ Built With

- [Python](https://www.python.org/)
- [PyTorch](https://pytorch.org/)

---

## 🤝 Contributing

Contributions are welcome! Please see the [contributing guidelines](CONTRIBUTING.md) for more information.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
