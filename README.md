# Machine Translation, Pre-Trained Transformers, Social Media NLG, Summarisation & Data Generation

A collection of Jupyter notebooks exploring core Natural Language Processing (NLP) tasks using modern deep learning and transformer-based approaches. Each notebook is a self-contained implementation covering a distinct NLP problem — from sequence-to-sequence translation to dialogue systems and prompt engineering.

---

## Notebooks

| Notebook | Description |
|----------|-------------|
| **Neural Machine Translation** | Sequence-to-sequence neural machine translation, covering encoder–decoder architectures with attention mechanisms for translating between language pairs. |
| **Aspect-Based Sentiment Analysis with BERT** | Fine-tuning BERT for aspect-level sentiment classification, identifying sentiment polarity toward specific entities or attributes within text. |
| **Natural Language Generation with Transformer-based Language Models** | Text generation using pre-trained transformer language models, exploring decoding strategies such as greedy search, beam search, top-k, and nucleus sampling. |
| **Summarisation and Controlled Text Generation with T-5** | Abstractive summarisation and controlled generation using Google's T5 (Text-to-Text Transfer Transformer), demonstrating the text-to-text framework for multiple NLP tasks. |
| **Social Media Processing** | NLP pipelines tailored to noisy, informal social media text — including preprocessing, normalisation, and downstream analysis of user-generated content. |
| **Named Entity Recognition System** | Token-level classification for identifying and categorising named entities (persons, organisations, locations, etc.) in unstructured text. |
| **Coreference Resolution** | Resolving pronominal and nominal mentions to their referring entities within a document, maintaining coherent entity tracking across sentences. |
| **Dialogue Act Tagging** | Classifying utterances in conversational data by their communicative function (e.g., question, statement, request), a key component of dialogue understanding. |
| **End-To-End Dialogue System** | Building a complete task-oriented or open-domain dialogue system, integrating language understanding, state tracking, and response generation. |
| **Prompt Engineering** | Techniques for crafting effective prompts for large language models, including zero-shot, few-shot, chain-of-thought, and instruction-based prompting strategies. |

## Tech Stack

- **Language:** Python (Jupyter Notebooks)
- **Key Libraries:** Hugging Face Transformers, PyTorch, NLTK/spaCy, scikit-learn
- **Models:** BERT, T5, GPT-family, Seq2Seq with Attention

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/Frostie2k23/Machine-Translation-Pre-Trained-Transformers-Social-Media-NLG-Summarisation-and-Data-Generation.git
   cd Machine-Translation-Pre-Trained-Transformers-Social-Media-NLG-Summarisation-and-Data-Generation
   ```

2. **Install dependencies**
   ```bash
   pip install transformers torch datasets nltk spacy scikit-learn
   ```

3. **Run any notebook**
   ```bash
   jupyter notebook
   ```
   Open the desired `.ipynb` file and run cells sequentially.

> **Note:** Some notebooks may require a GPU for efficient training/inference. Google Colab is a convenient free option if you don't have local GPU access.

## Repository Structure

```
.
├── Aspect-Based Sentiment Analysis with BERT.ipynb
├── Coreference Resolution.ipynb
├── Dialogue Act Tagging.ipynb
├── End-To-End Dialogue System.ipynb
├── Named Entity Recognition system.ipynb
├── Natural Language Generation with Transformer-based Language Models.ipynb
├── Neural Machine Translation.ipynb
├── Prompt Engineering.ipynb
├── Social Media Processing.ipynb
├── Summarisation and Controlled Text Generation with T-5.ipynb
└── README.md
```

## License

This project is provided for educational and research purposes.

## Author

[Frostie2k23](https://github.com/Frostie2k23)
