# LearnMate-AI
IBM Internship Project – AI + Cloud | Agentic AI with IBM Watsonx & Granite

LearnMate is an intelligent, agentic AI coach built using IBM Watsonx.ai that helps students and professionals create personalized, goal-driven learning roadmaps. It understands user interests, evaluates current skill levels, and dynamically recommends a tailored course pathway using agentic reasoning powered by IBM Granite foundation models and LangGraph.

🚀 Demo Preview

🎯 Example Query:
“How do I start a career in frontend development?”
<img width="674" height="437" alt="image" src="https://github.com/user-attachments/assets/0e732ff1-9555-44a2-90f2-4ed41b4c0e09" />

🧠 Key Features
✅ Personalised course roadmap generation
✅ Real-time skill assessment & adaptation
✅ Dynamic plan updates based on user progress
✅ AI-powered reasoning using ReAct + LangGraph
✅ Built on IBM Watsonx.ai with IBM Granite LLM
✅ Modular agent with external tool and vector store support

🛠️ Technology Stack
| Component             | Technology Used                |
| --------------------- | ------------------------------ |
| LLM                   | IBM Granite (watsonx.ai)       |
| Agent Framework       | LangGraph (ReAct Architecture) |
| Cloud Platform        | IBM Cloud Lite                 |
| Logic & Orchestration | IBM Cloud Functions            |
| Database              | IBM Cloudant (NoSQL)           |
| Vector Store          | Watsonx Vector Store           |
| Interface (Optional)  | HTML/CSS/JS or Streamlit       |

📌 How It Works
User Interaction: The agent gathers interests and current skill levels through conversation.
Skill Assessment: It performs logic checks or short Q&A to gauge the user's knowledge.
Course Pathway Generation: Uses reasoning via Granite LLM to generate a step-by-step roadmap.
Course Fetching: Integrates with external tools (APIs or vector store) to recommend real courses.
Adaptability: Learner progress updates the roadmap in real time.

📊 Results
Successfully deployed LearnMate agent using IBM Granite model
Generates intelligent, user-specific learning plans for multiple domains
Includes dynamic updates and personalization
Supports multiple use cases like Frontend Dev, Cybersecurity, UI/UX

📈 Future Scope
Voice-based interaction
API integration with platforms like Coursera or edX
Progress dashboard and email reminders
Support for regional languages and non-tech learners
