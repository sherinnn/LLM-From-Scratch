# Learning how Large Language Models work from scratch

This repo is a personal journey to understand and implement the core building blocks behind modern LLMs starting from the basics and gradually moving toward more advanced concepts.

Instead of relying on direct libraries, I wanted to focus on:
- understanding why things work
- implementing everything from scratch
- building strong intuition 

---

## Learning Roadmap

1. Basic Attention → intuition 
2. QKV Attention → mathematical formulation  
3. Causal Attention → autoregressive behavior  
4. Multi-Head Attention → richer representations  
5. GPT-style Model → full system  



## Video Explanations

### Self-Attention (Q, K, V)

[![Understanding Attention](https://img.youtube.com/vi/A-NtNQD-FBQ/0.jpg)](https://youtu.be/A-NtNQD-FBQ)

**What this explains:**
- What is Q,K,V and how are they computed  
- How attention scores are calculated  
- How weighted outputs are formed  

---

### Multi-Head + Causal Attention

[![Understanding Multi Head Attention](https://img.youtube.com/vi/liCVwT-95is/0.jpg)](https://youtu.be/liCVwT-95is)

**What this explains:**
- Why multiple heads are needed  
- How different heads learn different patterns  
- Causal masking (no future leakage)  
- How GPT-style attention works  

---

## Project Structure


- 1_simplified_self_attn_mechanism.ipynb → Basic intuition
- 2_self_attn_trainable_weights.ipynb → QKV attention
- 3_causal_self_attention.ipynb → Masked attention
- 4_multi_head_attention.ipynb → Multi-head attention concept
- 5_multi_head_attn_weight_splits.ipynb → Multi-head attention with parallel processing of heads
---

## Progress

- ✅ Basic Self-Attention 
- ✅ Self Attention with k,q,v
- ✅ Causal self attention mechanism
- ✅ Multi head attention - basic
- ✅ Multi head attention with parallel processing
- ✅ Mini GPT-style model (https://github.com/sherinnn/LLM-Architecture)

