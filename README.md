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
1. CPU (Central Processing Unit)
Role: General‑purpose processor, executes instructions sequentially.
Good at: Control logic, branching, running operating systems, everyday apps.
Limitation: Not optimized for massive parallel math operations.

2. GPU (Graphics Processing Unit)
Role: Originally for graphics rendering, now widely used for AI.
Good at: Parallel matrix/vector computations.
Why useful for AI: Neural networks involve huge matrix multiplications; GPUs can process thousands of operations simultaneously.

3. NPU / AI Accelerator
Role: Specialized hardware designed only for AI workloads.
Good at: Running neural networks efficiently with low power.
Why modern systems use it: Faster inference, lower energy, optimized for tensor operations (e.g., Apple Neural Engine, Google TPU).

4. Parallel Computation
Definition: Breaking tasks into smaller pieces and running them simultaneously.
Importance: AI models have millions of parameters; parallelism makes training feasible.

5. Why AI Depends on Compute + Memory
Compute: Needed for billions of multiplications/additions in training.
Memory: Needed to store huge datasets, model parameters, and intermediate results.
Without both, training large models would be impossible.

6. Training vs Inference (Hardware View)
Training:
Heavy compute load (backpropagation, gradient updates).
Requires GPUs/TPUs with massive parallelism and large memory.
Inference:
Running the trained model to produce outputs.
Less compute‑intensive, often optimized on CPUs or NPUs for speed and efficiency.

7. AI Application → AI Model → Software/Framework (PyTorch, TensorFlow)
                 ↓
        CPU / GPU / Accelerator → Memory
8. Real AI Workload Example
Workload: Image recognition (e.g., classifying photos in Google Photos).
Best hardware: GPU or NPU.
Reason: Image recognition uses convolutional neural networks (CNNs) with heavy matrix operations. GPUs accelerate training, while NPUs make inference fast and power‑efficient on mobile devices.

Mission-8 Where could this help your VLSI track?
| VLSI Area | Task | How AI Might Help | Why Human Knowledge Still Matters |
--------------------------------------------------------------------------
**Design Verification (DV)** -> Debugging repetitive testbench failures -> AI can quickly analyze simulation logs, detect recurring error patterns, and even suggest likely bug sources. -> Human/domain expertise is needed to validate whether the AI’s suggestion makes sense in the design context and to apply correct fixes.
AI can accelerate repetitive debugging in DV by spotting log patterns and predicting root causes. But engineers must still apply their domain knowledge to ensure correctness, because hardware verification involves nuanced design intent that AI alone cannot fully understand.

Mission-9 Build your own AI-use rule
My 5 Rules for Using AI ->
Verification First:  
I will always cross‑check AI answers with at least two reliable sources before trusting them, especially for technical or factual content.
(Justified by Mission 5: AI can sound confident but still be wrong, so verification is essential.)
Protect Confidential Information:  
I will never input proprietary project details, exam papers, or sensitive company data into AI systems to avoid leaks or misuse.
Take Responsibility:  
I will treat AI outputs as drafts or suggestions, but the final work submitted will always be my responsibility, reviewed and corrected by me.
Use AI for Productivity, Not Dependence:  
I will use AI to speed up repetitive tasks (debugging logs, summarising notes, drafting letters) but not rely on it as a substitute for my own learning or problem‑solving.
Context Matters:  
I will always provide clear context (engineering domain, exam prep style, coding framework) when asking AI for help, so the output is relevant and accurate.

These five rules form my personal AI‑use agreement. They ensure I use AI safely, intelligently, and responsibly in my VLSI and exam preparation journey.
