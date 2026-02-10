---
layout: page
title: LLM-Assisted OpenSearch
description: A Cloud-Native Architecture for Human-in-Control LLM-Assisted OpenSearch in Investigative Settings.
img: assets/img/LLM-Assisted-OpenSearch.jpg
importance: 1
category: work
---

This project addresses a critical challenge in **criminal investigations**: the 
difficulty of searching through vast volumes of unstructured evidence while 
bridging the semantic gap between **natural language** investigative intent and 
technical search logic.

The project develops a **cloud-native microservices architecture** specifically 
tailored for **private cloud deployments** in investigative settings. At its core, 
the system integrates **Large Language Models (LLMs)** into a **"Human-in-Control"** 
workflow that translates natural language queries into syntactically valid 
**OpenSearch Domain-Specific Language** expressions, ensuring investigators 
maintain oversight and control throughout the search process.

A key innovation is the implementation of a **hybrid retrieval strategy** within 
**OpenSearch** that combines **BM25-based lexical search** with nested 
**semantic vector embeddings**. This dual approach leverages both traditional 
keyword matching and modern semantic understanding to improve search accuracy 
and relevance.

The project delivers a functional prototype demonstrating technical feasibility, 
establishing an architectural baseline for future empirical evaluation. A rigorous 
evaluation methodology is outlined using the **Enron email dataset** as a 
structural proxy for restricted investigative corpora, enabling validation 
without compromising sensitive law enforcement data.

This work provides a foundation for enhancing investigative capabilities through 
AI-assisted search while maintaining the essential human oversight required in 
law enforcement contexts.
