# GitHub PR Review Agent

This project implements an AI-powered GitHub Pull Request (PR) review agent using the Perplexity API and GitHub API. The agent analyzes code changes in PRs and generates comprehensive review reports.

This project is an Agentic Workflow that combines the power of AI with GitHub's PR system to provide detailed code reviews automatically.

---

## Setup Instructions

### Step 1: Set up your virtual environment

Create and activate a virtual environment:

```bash
python3 -m venv ~/.venvs/prreview
source ~/.venvs/prreview/bin/activate
```

### Step 2: Set up environment variables

Create a `.env` file in the project root and add the following:

```bash
GITHUB_TOKEN=your_github_token
PERPLEXITY_API_KEY=your_perplexity_api_key
```

> **Note**: Replace `your_github_token` and `your_perplexity_api_key` with your actual GitHub and Perplexity API keys. Keep your API keys confidential and do not share them publicly.

### Step 3: Install required modules

Install all necessary modules in your virtual environment:

```bash
pip install -r requirements.txt
```

Ensure you have a `requirements.txt` file in your project directory with all the required dependencies listed.

### Step 4: Run the code

Execute the main Python script:

```bash
python GithubPRReviewWorkflow.py
```

---

## Additional Information

- Ensure you have Python 3.x installed on your system.
- The script currently supports analysis of `.py`, `.js`, `.java`, and `.cpp` files. You can extend this list in the `generate_report` function.
- For any issues or questions, please open an issue in this repository.

---

Happy reviewing!
