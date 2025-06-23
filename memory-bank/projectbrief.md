# Project Brief

## Core Requirements

The RAG Evaluation Framework is a modular, extensible system designed to evaluate Retrieval-Augmented Generation (RAG) systems end-to-end. The framework enables data-driven optimization of RAG systems through comprehensive evaluation and statistical comparison.

### Primary Objectives

1. **Document Processing Pipeline**
   - Parse documents from various formats (PDF, DOCX, HTML) to markdown
   - Split documents into chunks using different strategies
   - Generate embeddings and build vector databases

2. **QA Generation with Ground Truth**
   - Generate question-answer pairs with ground truth for evaluation
   - Include language identification and quality assessment
   - Filter high-quality QA pairs based on groundedness, relevance, and standalone criteria

3. **RAG System Evaluation**
   - Run RAG pipelines with different configurations
   - Evaluate results using comprehensive metrics (RAGAS + custom metrics)
   - Perform statistical comparison of different RAG configurations

4. **Modular Architecture**
   - Support multiple document parsers, splitters, LLMs, embeddings, and vector databases
   - Registry pattern for easy component extension
   - Configuration-driven pipeline execution

## Use Cases

### Primary Use Cases

1. **RAG System Benchmarking**
   - Compare different RAG implementations across standardized metrics
   - Evaluate impact of different chunking strategies on retrieval quality
   - Assess performance of various embedding models and vector databases

2. **Configuration Optimization**
   - Test different chunk sizes, overlap settings, and retrieval parameters
   - Optimize RAG system parameters based on evaluation metrics
   - Statistical validation of configuration improvements

3. **Quality Assessment**
   - Generate high-quality QA datasets with ground truth
   - Evaluate RAG system accuracy, relevance, and faithfulness
   - Multilingual content evaluation and language-aware processing

4. **Research and Development**
   - Extensible framework for implementing new RAG approaches
   - Custom metric development and evaluation
   - Component comparison and ablation studies

### Secondary Use Cases

1. **Document Processing Evaluation**
   - Compare different document parsing approaches
   - Evaluate chunking strategy effectiveness
   - Assess embedding model performance

2. **Multilingual RAG Evaluation**
   - Language identification and tracking throughout pipeline
   - Cross-lingual RAG system evaluation
   - Language-specific performance analysis

3. **Statistical Analysis**
   - T-test comparisons between RAG configurations using dedicated t-test.py script
   - Confidence interval analysis for performance metrics
   - Significance testing for system improvements with 95% confidence level
   - Support for comparing any evaluation metric column between configurations
