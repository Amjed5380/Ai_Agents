# AI Customer Support Agent

## Project Overview

This project implements a **Customer Support AI Agent** using Python. It can understand customer queries, select appropriate tools, and generate responses based on the user's requirements.

Unlike a basic chatbot, this agent follows a tool-based approach to make decisions and perform specific tasks.

## Objectives

- Build a tool-based AI agent.
- Implement intelligent query routing.
- Retrieve relevant answers using TF-IDF and Cosine Similarity.
- Perform mathematical calculations.
- Provide human-support escalation.
- Maintain conversation history.
- Create an interactive chatbot interface using Gradio.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TF-IDF Vectorization
- Cosine Similarity
- Gradio
- Regular Expressions (RE)
- Abstract Syntax Trees (AST)

## Dataset

**Bitext Customer Support Dataset**

The project uses the Bitext Customer Support Training Dataset containing customer instructions, responses, categories, and intents.

Dataset source: [Hugging Face – Bitext Customer Support Dataset](https://huggingface.co/datasets/bitext/Bitext-customer-support-llm-chatbot-training-dataset)

## Key Features

### 1. FAQ Search Tool

- Uses TF-IDF vectorization.
- Finds relevant questions using Cosine Similarity.
- Retrieves matching customer support responses.

### 2. Calculator Tool

- Performs basic mathematical operations.
- Supports addition, subtraction, multiplication, and division.
- Uses Python AST for expression evaluation.

### 3. Human Support Escalation

- Identifies requests for human assistance.
- Provides a customer support escalation message.

### 4. Agent Decision Making

- Analyzes user queries.
- Selects the appropriate tool based on query patterns.
- Routes requests to the corresponding function.

### 5. Conversation Memory

- Stores user queries.
- Records selected tools.
- Maintains agent responses in conversation history.

### 6. Interactive Chat Interface

- Built using Gradio.
- Allows users to interact with the AI agent.
- Provides a conversational interface.

## Agent Workflow

1. Receive user query.
2. Analyze the query.
3. Select the appropriate tool.
4. Execute the selected tool.
5. Generate the response.
6. Store conversation history.
7. Return the response to the user.

## Project Structure

```text
AI-Customer-Support-Agent/
│
├── AI_Agent.ipynb
├── README.md
└── requirements.txt
```

## Installation

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
```

Navigate to the project directory:

```bash
cd AI-Customer-Support-Agent
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

## How to Run

1. Open `AI_Agent.ipynb` using Jupyter Notebook or Google Colab.
2. Run the notebook cells sequentially.
3. Load the dataset and initialize the tools.
4. Execute the AI agent.
5. Launch the Gradio interface to interact with the chatbot.

## Example Queries

| User Query | Agent Action |
|---|---|
| How can I get my money back? | FAQ Search |
| I want to cancel my order | FAQ Search |
| What is 250 + 240? | Calculator |
| What is 20 / 5? | Calculator |
| I want to speak to a human agent | Support Escalation |

## Future Enhancements

- Integrate Large Language Models (LLMs).
- Implement semantic search using embeddings.
- Add more customer support tools.
- Improve decision-making capabilities.
- Integrate a real-time customer support system.
- Maintain persistent conversation memory.

## Author

**Amjed**

AI & ML Learner | Python | Machine Learning | Deep Learning

---

If you find this project useful, consider giving the repository a star!
