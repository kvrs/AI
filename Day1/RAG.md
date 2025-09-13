## Retrival Augmented Generation

RAG = Retrieval + Augmented + Generation

R → Retrieval

When a user asks a question, RAG first retrieves the most relevant information from a database or knowledge source.

G → Generation

Next, the LLM (Large Language Model) uses the retrieved info + the query to generate a clear, fact-based answer.

A → Augmented

The retrieved information is added (augmented) into the LLM’s prompt so it can respond using fresh, external knowledge, not just what’s in its memory.

## Closed-book vs Open-book Analogy

Pure LLM (Closed-book test) → Relies only on what it memorized during training (parametric knowledge).

RAG (Open-book test) → Can “look up” extra info in real time, like a student using notes or textbooks during an exam.
