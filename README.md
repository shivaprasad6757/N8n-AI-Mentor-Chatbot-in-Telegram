# 🤖 AI Mentor Chatbot
### Telegram • n8n • Gemini/OpenAI LLM
A 24/7 Automated Learning Assistant for Innomatics Research Labs
This repository contains the workflow and logic behind an AI Mentor Chatbot built to support students anytime, anywhere. Designed using n8n and LLM-based intelligence, the chatbot helps learners resolve technical doubts instantly through Telegram.

**🚀 Project Overview**
Students at Innomatics often encounter technical doubts late at night or outside regular mentoring hours. This AI Mentor Chatbot ensures round-the-clock assistance, providing instant, clear explanations using LLM-powered responses.

**The chatbot guides the student step-by-step:**
- Greets the user
- Asks them to choose a topic
- Stores the selected subject
- Collects the student’s technical doubt
- Sends it to an LLM for real-time analysis
- Responds with an easy-to-understand explanation

**🎯 Objective**
**Build an AI-driven Telegram chatbot that can:**
- 👋 Greet students when they say “hi”, “hello”, etc.
- 📚 Collect topic selection (Python, EDA, ML, DL)
- 📝 Store chosen topic for ongoing conversation
- ❓ Capture technical doubts
- 🤖 Generate explanations using LLM models (Gemini / OpenAI)
- 📩 Deliver clear, step-by-step answers instantly
- 🕒 Provide 24/7 support without mentor intervention

**🧩 Why This Chatbot Matters**
- Mentors aren't always available after class hours
- Students frequently get doubts while practicing
- Faster responses = better learning outcomes
- Manual doubt-solving is slow & not scalable
- Telegram makes the system highly accessible
- Automation ensures consistent and accurate answers

##### **⚙️ Tech Stack & Architecture**
**🔧 Technologies Used**
- n8n Workflow Automation
- Telegram Bot API
- Google Gemini LLM / OpenAI GPT
- Memory Nodes for storing topic selections
- Switch / IF Logic for conversation flow

**🧠 Workflow Steps**
**1)Telegram Trigger Node**
- Captures incoming messages.

**2)Greeting Detection**
- Responds with onboarding message.

**3)Topic Selector**
- Asks user to choose from Python, EDA, ML, or DL.

**4)Memory Storage Node**
- Saves the student’s selected topic.

**5)Doubt Collection**
- Waits for the user to input a question.

**6)LLM Processing Node**
- Sends the query + topic to LLM for contextual explanation.

**7)Structured Response Delivery**
- Telegram Send node replies instantly.

**🧠 Key Features**
- ✔️ Greeting and onboarding logic
- ✔️ Topic-based conversation flow
- ✔️ Context-aware LLM responses
- ✔️ Simple Memory for storing topic selections
- ✔️ Multistep conversation management
- ✔️ Fully automated and scalable
- ✔️ Works 24/7

**🚀 How to Deploy**
- Clone the repository
- Import the workflow JSON file into n8n
- Set up your Telegram Bot Token
- Add your Gemini/OpenAI API key
- Enable memory nodes
- Activate the workflow
- Start chatting with your AI mentor!

**🧠 Skills Strengthened**
- Automation workflow design
- Prompt engineering
- Building Telegram-based conversational systems
- LLM integration
- Context management and state handling
- Real-world chatbot architecture
- n8n workflow debugging and optimization

**📸 Screenshot**
<img width="1426" height="728" alt="Screenshot 2025-11-14 202309" src="https://github.com/user-attachments/assets/8ef4f50c-26d4-4592-8625-fc11dbd25093" />
