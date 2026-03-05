# Legal Document Analyzer

## Project Overview
The Legal Document Summarization System is an NLP-based project that showcases how transformer models can be applied to automatically summarize legal documents. The project explores two different approaches:
A fine-tuned transformer model based on BART
A custom-built transformer architecture used as a proof-of-concept

These implementations highlight both the practical application of transfer learning and the challenges of training transformers from scratch for specialized domains like legal text.



## 🗂️ Dataset
The project uses a comprehensive legal document dataset from Zenodo (https://zenodo.org/records/7152317), containing:
- Indian Legal Abstracts (IN-Abs)
- Indian Legal Extendeds (IN-Ext)
- UK Legal Abstracts (UK-Abs)


## Project Achievements

The project successfully delivered:

1. A working legal document summarizer based on fine-tuned BART
2. A proof-of-concept custom transformer implementation
3. An RL-enhanced model using PPO to optimize summary quality
4. A complete legal text preprocessing pipeline
5. Integration with Hugging Face for easy model access

## Performance and Limitations

- The fine-tuned model achieves competitive performance on legal summarization tasks
- The model performs best on texts similar to its training data (Indian and UK legal documents)
- Custom transformer implementation demonstrated the challenges in training large language models from scratch
- Current limitation: Processing extremely long legal documents requires chunking strategies

## Technical Requirements

### Dependencies
- PyTorch
- Transformers
- Tokenizers
- NLTK
- RougeScore
- SacreBLEU
- Stable-Baselines3 (for RL optimization)

