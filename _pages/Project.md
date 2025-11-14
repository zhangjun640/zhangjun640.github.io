---
layout: archive
title: "My Projects:"
permalink: /project/
author_profile: true
---

{% include base_path %}

Pharmaceutical management system: 
======
  * Tech Stack:JavaScript, CSS, HTML, Java, Shiro
  * Led the overall project architecture design and technology selection, implementing a decoupled front-end (Vue.js) and back-end (Spring Boot) solution.
  * Designed and implemented the security framework using Apache Shiro, delivering user authentication, session management, and Role-Based Access Control (RBAC).
  * Developed and managed the core business modules, including backend APIs for drug information, supplier management, inventory (inbound/outbound), and sales statistics.
  * [GitHub Link](https://github.com/zhangjun640/Hospital-Medical-Management-System)

AI-Assisted Interview Platform:
======
  * Tech Stack: Python, PyTorch, QLoRA, Ollama, HTML, Vue 3
  * Led the creation and open-sourcing of the world's largest Chinese interview dataset (150k+ entries) by scraping tech communities and generating high-quality Q&A pairs using multiple LLMs (GPT-4o, DeepSeek), and published it on Hugging Face.
  * Directed the technology selection and fine-tuning of the AI interviewer LLM. Employed QLoRA (Unsloth) on a DeepSeek base model, training it on the custom dataset to specialize in generating interview questions, follow-ups, and automated scoring.
  * Designed and deployed the project's full-stack architecture: built the frontend application (Vue 3) integrating resume editing, AI polishing, and mock interviews; and deployed the fine-tuned model as an HTTP API service using Ollama.
  * [GitHub Link](https://github.com/zhangjun640/AI-interviewers)
  * [Dataset Link](https://huggingface.co/zhangjun640)
    
Guess the numbers game:
======
  * Tech Stack: Java, Java Swing, Java AWT, Java I/O
  * Designed and implemented the complete game logic for a "Bulls and Cows" (nAnB) guessing game, building the entire multi-window graphical user interface with Java Swing.
  * Developed a persistent user authentication and scoring system, managing user registration, login, and score ranking by reading and writing to local .txt files (Message.txt, Rank.txt).
  * Enhanced the user experience by creating custom, reusable Java Swing components (CustomButton, CustomTextField) that support background images.
  * [GitHub Link](https://github.com/zhangjun640/Guess-Number-Game)

Solitaire:
======
  * Tech Stack: Java, Java Swing, Java AWT (Graphics, Event Handling), Java I/O
  * Developed the complete game logic for Klondike Solitaire, employing a strong Object-Oriented design with a CardPile class hierarchy (Deck, Discard, Table, Suit) to manage game rules and state.
  * Built a fully interactive GUI using Java Swing, handling complex mouse drag-and-drop events for selecting and moving single or stacked cards.
  * [GitHub Link](https://github.com/zhangjun640/Solitaire)

SNP-SNP_Prediction: 
======
  * Tech Stack: Python, pandas, scikit-learn, numpy, scipy
  * Implemented a data analysis pipeline including Chi-Squared tests, T-tests, and mutual information algorithms to evaluate SNP-phenotype associations.
  * Validated findings using a scikit-learn Logistic Regression model with cross-validation; achieved a power value of 1.0 in both biallelic and triallelic models, indicating 100% accuracy in identifying all target SNP loci.
  * [GitHub Link](https://github.com/zhangjun640/SNP-SNP_Prediction)


Computational Optimization of Many Body Problems:
======
  * Project Goal: To optimize an N-body simulation program by addressing its $O(N^2)$ computational complexity.
  * Core Technologies: Utilized OpenMP for multi-core parallelization combined with SIMD (AVX/AVX512) instructions for vectorized computation.
  * Optimizations & Results: Enhanced memory efficiency through SoA layout and 64-byte alignment, achieving an 11.437x speedup on 32 cores while maintaining high computational precision.
  * [GitHub Link](https://github.com/zhangjun640/Computational-Optimization-of-Many-Body-Problems)
