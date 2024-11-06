# Cross-Lingual Transfer Learning for Indian Languages
Course Project: CSE556 (Natural Language Processing)

Contributors: Arnav Goel, Medha Hira, Siddharth Rajput, Amil Bhagat

### Overview
This project investigates cross-lingual transfer learning for low-resource Indian languages, aiming to bridge language representation gaps using task-specific models. The project leverages Multilingual BERT (mBERT) to facilitate knowledge transfer across languages by fine-tuning on data-rich languages and evaluating on data-poor ones. 

### Key Features
- **Tasks**: 
  - **Sentiment Analysis**
  - **Hate Speech Detection**
  - **Named Entity Recognition (NER)**
- **Languages**: Supports five Indian languages from two linguistic families:
  - Indo-Aryan: Bengali, Hindi, Marathi
  - Dravidian: Tamil, Telugu
- **Methodology**:
  - Zero-shot, single-language, and two-language fine-tuning approaches
  - Cross-family and intra-family transfer evaluations
  - Experimental setups for understanding the impact of dataset size on transfer learning quality

### Datasets
- **Sentiment Analysis**: IndicSentiment dataset by AI4Bharat
- **Hate Speech Detection**: Curated datasets from various sources for each language
- **Named Entity Recognition**: WikiANN multilingual dataset

### Results
The study shows promising results in intra-family and inter-family transfer, particularly in NER tasks. Fine-tuning on two languages improves cross-lingual performance, with the highest transfer observed for intra-family language pairs.

### Impact
This work aids the development of NLP tools for Indian languages, supporting applications in linguistic inclusivity.
---
