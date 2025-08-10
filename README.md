AI Agentic Design Patterns with AutoGen – Code Examples

This repository contains Python code from the AI Agentic Design Patterns with AutoGen course by DeepLearning.AI.
Each lesson demonstrates a different multi-agent orchestration pattern using the AutoGen framework.


---

📂 Lessons Included

1. Lesson 1 – Multi-Agent Conversation and Stand-up Comedy

Create two conversational agents that exchange jokes.

Explore message history, termination conditions, and conversation summaries.



2. Lesson 2 – Sequential Chats and Customer Onboarding

Run multiple agents in sequence to onboard a customer.

Gather information, collect preferences, and engage users.



3. Lesson 3 – Reflection and Blogpost Writing

Writer and Critic agents collaborate to produce better content.

Add nested reviewers (SEO, Legal, Ethics, Meta) for improved results.



4. Lesson 4 – Tool Use and Conversational Chess

Agents play chess by calling registered tools (get_legal_moves, make_move).

Uses a board proxy agent and optional fun chitchat.

📦 Requirements

Install dependencies:

pip install autogen python-chess typing-extensions

You also need an OpenAI API key:

export OPENAI_API_KEY="your_api_key_here"


---

▶️ How to Run

1. Clone this repo:



git clone https://github.com/yourusername/ai-agentic-autogen-examples.git
cd ai-agentic-autogen-examples

2. Install dependencies.


3. Run each lesson either as a Jupyter Notebook or Python script.



Example:

jupyter notebook L4_Tool_Use_and_Conversational_Chess.ipynb

or

python L4_Tool_Use_and_Conversational_Chess.py


---

💡 Notes

Lesson outputs may vary due to LLM randomness.

Some lessons use gpt-4-turbo for better quality.

The chess examples require a Jupyter environment for SVG board rendering.
