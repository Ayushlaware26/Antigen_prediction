# 🧬 Fine-Tuning ProtGPT2 with LoRA for Antibody-Antigen Prediction

This project fine-tunes [ProtGPT2](https://huggingface.co/nferruz/ProtGPT2), a protein language model, using **LoRA (Low-Rank Adaptation)** to generate optimal antigen sequences from antibody CDR inputs. The system learns a mapping from CDRH3+CDRL3 sequences to full antibody-antigen sequences for use in computational vaccine design and synthetic biology.

---

## 🚀 Objective

The model is trained to perform the following transformation:

> **Input:** CDRH3 + CDRL3  
> **Output:** Full Antibody Sequence (including variable heavy and light chains)