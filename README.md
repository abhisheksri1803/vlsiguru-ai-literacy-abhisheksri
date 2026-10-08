# vlsiguru-ai-literacy-abhisheksri
My 16-week AI Literacy Layer portfolio and engineering journal.

Mission-1 Find AI around you
System/Feature ->	What it Does (Predicts/Classifies/etc.) ->	Evidence of AI/ML Involvement
Google Maps (Navigation) ->	Predicts traffic, recommends fastest route -> Verified: Google Maps uses ML to analyze real-time traffic data and predict congestion.
YouTube Recommendations ->	Recommends videos based on watch history	-> Verified: YouTube’s recommendation engine is powered by deep learning models.
Smartphone Face Unlock ->	Recognizes faces to unlock device	-> Verified: Face unlock uses deep learning-based facial recognition algorithms.

Mission-2 AI, ML, GenAI: put the pieces together
Artificial Intelligence (AI)
│
├── Machine Learning (ML)
│   │
│   └── Deep Learning (DL)
│
└── Generative AI (GenAI)
Explanation:
AI is the umbrella term.
ML is a subset of AI focused on learning from data.
DL is a deeper subset of ML using neural networks.
GenAI is not strictly a subset of DL but often uses DL to generate new content.

Mission-3 Is it really AI?

| System/Feature           | Classification 
---------------------------------------------------------------
| Calculator               | Rule-based / Traditional software 
| Temperature warning rule | Rule-based / Traditional software
| Spam filter              | ML-based AI
| Document summariser      | Generative AI
| Traffic ETA prediction   | ML-based AI

Mission-4 Make AI explain itself, then test it
An LLM is trained to predict the next word. Doing this billions of times on massive text data makes it capable of writing essays, answering questions, or generating code.
Evidence from Reliable Sources ->
Transformers and self‑attention are the backbone of modern LLMs, allowing parallel processing and long‑range context modeling .

Beginner explanation: LLMs are essentially trained to predict the next word, and from this simple objective, complex abilities like summarization and conversation emerge .
One Correction/Clarification ->
The assistant initially implied that Generative AI is separate from Deep Learning, but in reality, most GenAI systems (like ChatGPT) are built on deep learning transformers. I had to clarify that GenAI is not a parallel branch but an application of DL.

Mission-5 Can AI be confidently wrong?
Prompt (to AI assistant):  
“Who invented the World Wide Web?”
AI Answer (example):  
“The World Wide Web was invented by Tim Berners‑Lee in 1989 while working at CERN.”
Verification Source:
CERN official page: https://home.cern/science/computing/birth-web (home.cern in Bing)
World Wide Web Foundation: https://webfoundation.org/about/vision/history-of-the-web/ (webfoundation.org in Bing)
Result:
Correct. Both sources confirm Tim Berners‑Lee invented the World Wide Web in 1989 at CERN.
Lesson:
The test proved the AI answer was factually correct for this specific question.
However, it did not prove that the AI is always reliable. It only showed correctness in one case. AI can still be confidently wrong in other contexts, so independent verification is always necessary.

Mission-6 Chatbot or agent?
| Concept                  | What it Does                            | Example |
  ------------------------------------------------------------------------------------------------
| **LLM**                  | Generates text by predicting next words | ChatGPT writing an essay |
| **AI Application**       | Uses AI for a specific task             | Google Translate |
| **RAG**                  | Retrieves info + generates              | Bing Copilot with web grounding |
| **Tool‑Using Assistant** | Calls tools to extend abilities         | AI assistant creating a calendar event |
| **Agent**                | Plans + acts autonomously               | Self‑driving car |
Simple Flow Design
User → Model (LLM) → Tool/Retrieval (e.g., search, calculator) → Result → Response/Action

Everyday Agentic Workflow Example
Smart Home Assistant (like Alexa + smart devices):  
You say “Alexa, I’m leaving.”
→ The agent decides actions: turn off lights, lock doors, adjust thermostat.
→ It uses multiple tools (IoT devices) and executes them autonomously.

Mission-7  What actually runs AI?
