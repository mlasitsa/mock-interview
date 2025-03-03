# mock-interview

# Tech Stack for AI-Powered Coding Recruiter

## 1️⃣ Frontend (User Interface)
**Next.js** → Interactive web app.
TypeScript → Ensures type safety.
Tailwind CSS → For responsive UI.
Framer Motion → Smooth animations.
Monaco Editor (VS Code’s editor API) → Adds a powerful, real-time code editor.
WebSockets (Socket.io) → Real-time updates on user progress.
WebRTC (Optional) → If adding real-time voice/video chat.

## 2️⃣ AI-Powered Question & Feedback System
OpenAI GPT-4o / Claude → Generates coding prompts & explains problems.
LangChain.js → Manages structured AI workflow for hints & memory.
LangGraph → Helps with multi-turn interactions (e.g., debugging).
Groq API (Function Calling) → Calls AI functions to analyze code structure.
## 3️⃣ Code Execution & Evaluation
Playground API / Judge0 / Piston API → Sandboxed execution of user code.
Docker (Optional) → Run user code securely inside isolated containers.
AI Feedback Engine (RAG - Retrieval Augmented Generation) → AI analyzes:
Syntax correctness.
Edge case handling.
Time complexity.
Code readability.
## 4️⃣ Backend & Database
Node.js (Express.js / Fastify) → Manages API requests.
MongoDB / PostgreSQL → Stores user solutions & feedback.
Redis (Optional) → Caches AI responses to reduce token usage.

## 5️⃣ Voice & Real-Time Assistance
Whisper API / Deepgram → Converts user speech to text.
ElevenLabs API → Reads AI hints back in natural voice.
WebRTC or Twilio (Optional) → Enables real-time recruiter conversations.


# 🚀 MVP Breakdown (Minimum Viable Product)

## Phase 1: Build a Basic Coding Interview Bot
✅ Show AI-generated questions
✅ Embed a Monaco code editor
✅ Save user responses to a database
✅ Allow AI to analyze and give text-based feedback

## Phase 2: Add Execution & Live AI Feedback
✅ Integrate Judge0 API for real-time code execution
✅ AI provides syntax and logic corrections
✅ Implement time complexity analysis

## Phase 3: Add Voice & Recruiter Simulation
✅ Convert AI hints to voice using ElevenLabs
✅ Support live coding interviews
✅ AI simulates a recruiter, asking behavioral questions in between coding
