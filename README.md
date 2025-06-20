## Konwinski Prize - Automated Code Patch Generation
This repository contains my solution for the Konwinski Prize competition on Kaggle, which focuses on automated software engineering using large language models to generate code patches for bug fixes.

### Competition Overview

We have to develop AI systems that are capable of automatically generating code patches to fix bugs in real-world software repositories.

### Problem Description

- **Task**: Generate code patches to fix identified bugs in software repositories
- **Input**: Problem statement, repository archive, pip packages, environment setup commands
- **Output**: Code patch (diff format) that fixes the described issue
- **Evaluation**: Functional correctness and code quality of generated patches


### Model Selection
- **Primary Model**: StarCoder2-3B ( For Code generation)
- **Framework**: Hugging Face Transformers with CUDA acceleration
- **Optimization**: FP16 precision for faster inference

### Setup and Execution
#### Prerequisites
- Python 3.11+
- CUDA-compatible GPU (recommended)
- 8GB+ GPU memory
- Sufficient disk space for repository extraction
#### Installation
- git clone https://github.com/lakshmiprasanna07/Github-issue-resolver.git
- cd Github-issue-resolver
- pip install -r requirements.txt
#### Execution
jupyter notebook main.ipynb

### License
This project is licensed under the MIT License - see the LICENSE file for details.

### Contact
For questions about the implementation or collaboration opportunities, please open an issue or contact lakshmiprasanna.lp07@gmail.com
