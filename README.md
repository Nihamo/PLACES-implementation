## PLACES: Prompting Language Models for Conversation Synthesis

This project implements the **PLACES framework** (Prompting Language Models for Conversation Synthesis) using the **Mistral-7B Instruct model**.
It demonstrates how **synthetic conversations** can be generated using carefully designed prompts — covering both **dyadic (2-person)** and **multi-party (3-person)** dialogues.

The goal is to create **high-quality, natural, and diverse dialogue datasets** without relying on costly or privacy-sensitive human data collection.

---

## Features

* **Dyadic Conversation Generation** (2 speakers)
* **Triadic Conversation Generation** (3 speakers, first-of-its-kind)
* **Role & Emotion-Conditioned Conversations** *(Future enhancement)*
* Prompts designed for **casual, natural-sounding** dialogue
* Built with **Hugging Face Transformers** + **Mistral-7B**

---

## How It Works

1. **Prompt Engineering**

   * Few-shot prompts define conversation style, roles, and background.
   * Ensures generated dialogues sound realistic, not robotic.

2. **Model Inference**

   * Conversations are generated using **Mistral-7B Instruct**, a powerful LLM optimized for instruction-following.
   * Sampling strategies ensure variety and coherence.

3. **Conversation Extraction**

   * Model outputs are cleaned to extract only the dialogue portion for dataset usage.

---

## Example

**Topic:** Climate Change
**Mode:** Dyadic
**Background:** Alice is an environmentalist, Bob is a student

**Generated Conversation:**

```
Alice: Hey Bob, did you see the news about rising sea levels?  
Bob: Yeah, it’s kinda scary. Makes me wonder what we can actually do.  
Alice: Small changes add up, like using less plastic or biking to school.  
Bob: True! I’ve been trying to carpool more with friends.  
Alice: That’s awesome, Bob!  
```

---

## Future Enhancements

* Persona & Emotion conditioning (e.g., *optimistic teacher*, *stressed student*)
* Task-oriented dialogue generation
* Grounded conversations with external knowledge
* Improved filtering for safety & factual accuracy

---

## References

* *PLACES: Prompting Language Models for Conversation Synthesis* (base research paper)
* Mistral-7B model documentation
* Hugging Face Transformers library

---

## Author

Developed as part of an **implementation study of the PLACES framework**, exploring how large language models can generate synthetic conversations that rival human-written dialogues.

---
