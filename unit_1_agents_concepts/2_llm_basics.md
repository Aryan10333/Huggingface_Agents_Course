## 📚 **Study Notes – What Are LLMs? (Hugging Face Agents Course Unit 1)**

### 🧠 **1. What Is an LLM (Large Language Model)?**

* **LLM (Large Language Model)** is a type of **AI model** that *understands and generates human language*. ([Hugging Face][1])
* LLMs are trained on **massive text datasets** so they can learn *patterns, structure, context, and nuance* in natural language. ([Hugging Face][1])
* They typically contain **millions to billions of parameters** — numerical values the model uses to make predictions. ([Hugging Face][1])

---

### 🧩 **2. Core Architecture – Transformers**

* Most modern LLMs are built using the **Transformer architecture**, which relies on the **Attention mechanism** to capture relationships across long text sequences. ([Hugging Face][1])

#### 🔹 **Three Transformer Variants**

1. **Encoder-only**

   * Produces dense representations (embeddings).
   * Used for tasks like text classification or semantic search.
   * Example: **BERT**. ([Hugging Face][1])

2. **Decoder-only**

   * Focused on *generating text* one token at a time.
   * Common for LLMs used in chat and generative tasks.
   * Example: **Llama**. ([Hugging Face][1])

3. **Seq2Seq (Encoder–Decoder)**

   * Combines both: encoder processes input, decoder generates output.
   * Good for translation, summarization.
   * Example: **T5, BART**. ([Hugging Face][1])

👉 Most **LLMs** you’ll use for agents are **decoder-based** and very large. ([Hugging Face][1])

---

### 🔎 **3. Tokens and Next-Token Prediction**

* LLMs work with **tokens**, which are pieces of text — sometimes words, often sub-word units — optimized for efficiency. ([Hugging Face][1])
* The core objective during training is **next-token prediction**: given previous tokens, predict what comes next. ([Hugging Face][1])

  * This autoregressive approach enables the model to generate coherent text, complete prompts, and respond to questions. ([Hugging Face][1])

---

### 🔤 **4. Tokenization**

* **Tokenization** breaks raw text into tokens the model can process. ([Hugging Face][1])
* A vocabulary of tokens (e.g., ~32,000) covers common text patterns. ([Hugging Face][1])
* Special tokens help indicate structure in prompts — for start/end of messages or sequences. ([Hugging Face][1])

---

### 🧠 **5. How LLMs Power AI Agents**

* LLMs act as the **“brain”** of an AI agent:

  * They interpret **user instructions**.
  * Plan next steps or actions.
  * Maintain **context** in ongoing conversations.
* In agent systems, the LLM receives text inputs and outputs text that can include *reasoning, instructions, or tool invocations*. ([Hugging Face][2])

---

### 🧱 **6. Key Takeaways**

* Large Language Models are **general-purpose language predictors** trained on huge text corpora. ([Hugging Face][1])
* They are built with the **Transformer architecture**. ([Hugging Face][1])
* They use **tokenization** and **next-token prediction** to generate fluid text. ([Hugging Face][1])
* Modern AI agents depend heavily on LLMs to *understand input, generate responses or plans, and decide what actions/tools to use*. ([Hugging Face][2])


[1]: https://huggingface.co/learn/agents-course/unit1/what-are-llms "What are LLMs? - Hugging Face Agents Course"
[2]: https://huggingface.co/learn/agents-course/unit1/introduction "Introduction to Agents - Hugging Face Agents Course"
