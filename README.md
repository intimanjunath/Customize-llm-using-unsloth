## Part A: Supervised Fine-Tuning
I have fine-tune a variety of open-weight LLMs using Unsloth AI for different specialized tasks:

- **Llama 3.1 (8B)** – Code generation & debugging assistant  
  📄 [Colab Notebook](https://drive.google.com/file/d/1dY0nmvW5cqDh9iT8q_y8zG_0VT10KaqO/view?usp=sharing)  
- **Mistral NeMo (12B)** – Customer-support chat agent  
  📄 [Colab Notebook](https://drive.google.com/file/d/1I-Axx7zxIjbhxY4_btgTXZt9NpnnLfCe/view?usp=sharing)  
- **Gemma 2 (9B)** – Human-like conversational AI  
  📄 [Colab Notebook](https://drive.google.com/file/d/1DBtPX4Jvc2sI_76sn3z1J4ZoURhyCdPG/view?usp=sharing)  
- **Phi-3 (medium)** – Math-based reasoning & problem solving  
  📄 [Colab Notebook](https://drive.google.com/file/d/13GHh5p_3D-o_M2EJ4SYgh28_la16ownR/view?usp=sharing)  

## Part B: Continued Pretraining  
**Model:** TinyLlama (Hindi specialization)  
- **Purpose:** Adapt TinyLlama to handle Hindi text by unsupervised continuation of its language model pretraining.  
- 📄 [Open in Colab](https://drive.google.com/file/d/1TN4YXabGjhG6VA4X5kl9lt6Vx5W9BIT-/view?usp=sharing)

---

## Part C: Chat Template Showcase  
**Model:** TinyLlama  
- **Includes:**  
  - Text classification via chat prompts  
  - Multi-turn conversational examples  
  - Extended context window demonstrations  
  - Joint fine-tuning on multiple datasets  
- 📄 [Open in Colab](https://drive.google.com/file/d/1NkmuS7hHyLzIX4l1rlq3gi2-9pVcs8fX/view?usp=sharing)

---

## Part D: Preference-Based Reward Modeling  
**Model:** Phi-3 Mini  
- **Techniques:**  
  - Odds-Ratio Preference Optimization (ORPO)  
  - Direct Preference Optimization (DPO)  
- **Use Case:** Train the model to rank and prefer more helpful outputs.  
- 📄 [Open in Colab](https://drive.google.com/file/d/16sxOaN_Mf0POyNTqyeM1GFTu0GjdijK2/view?usp=sharing)

---

## Part E: Training from Checkpoint  
**Model:** TinyLlama  
- **Objective:** Demonstrate how to stop and restart fine-tuning from an intermediate checkpoint.  
- 📄 [Open in Colab](https://drive.google.com/file/d/1T-BeDpEVTPFluOWXWLdkwWMqaiPoFjPS/view?usp=sharing)

---

## Part F: Mental-Health Support Chatbot  
**Model:** Phi-3 Mini  
- **Scope:** Fine-tune for empathetic, safe mental-health conversations, including dataset sourcing and safety filtering.  
- 📄 [Open in Colab](https://drive.google.com/file/d/1q1-I7Gg5JXCtd7-9PAbGfBmNdBZZ9xWu/view?usp=sharing)

---

## Part G: Export & Inference with Ollama  
**Model:** Llama 3  
- **Goal:** Convert your LoRA adapter into a GGUF format and run live inference via Ollama.  
- 📄 [Open in Colab](https://drive.google.com/file/d/1OHtx8wDypC_pJb5RoWIsjruUq5acv0Tb/view?usp=sharing)


YouTube Demo explaning : 

Playlist Description
Dive into end-to-end LLM development with Unsloth AI across two comprehensive walkthroughs:

Video 1 – Parts A–C: Supervised Fine-Tuning & Pretraining  : https://youtu.be/t0BZKt2sifM

A: Fine-tuning Llama 3.1, Mistral NeMo, Gemma 2, and Phi-3 on task-specific datasets

B: Continued Pretraining of TinyLlama for Hindi

C: Chat-Template Applications (classification, multi-turn chat, extended context, multi-dataset finetune)

--- 

Video 2 – Parts D–G: Reward Modeling, Checkpoints & Deployment : https://youtu.be/jkwhGBECcKc

D: Reward Modeling (ORPO & DPO with Phi-3 Mini)

E: Resuming Fine-Tuning from a Checkpoint (TinyLlama)

F: Mental-Health Chatbot (Phi-3 Mini)

G: Export & Inference with Ollama (Llama 3)
