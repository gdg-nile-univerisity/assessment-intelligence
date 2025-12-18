# Natural Language Processing Tasks - Intermediate Level

Complete **ANY TWO** of the following tasks.

---

## Task 1: Text Classification with Advanced Features

### Objective
Build a robust text classification system using advanced NLP techniques.

### Requirements
1. Choose a classification task (sentiment, topic, spam detection)
2. Implement multiple text representations:
   - TF-IDF with n-grams
   - Word embeddings (Word2Vec or GloVe)
   - Character-level features
3. Build classifiers using:
   - Traditional ML (SVM, Random Forest)
   - Neural network (LSTM or CNN for text)
4. Implement proper train/validation/test split
5. Compare model performance
6. Analyze misclassifications
7. Achieve >80% accuracy on chosen task

### Hints
- Use pre-trained embeddings when possible
- Implement cross-validation
- Handle class imbalance if present
- Use appropriate evaluation metrics

---

## Task 2: Named Entity Recognition System

### Objective
Build a system to identify and classify named entities in text.

### Requirements
1. Implement NER using:
   - Rule-based approach with patterns
   - Machine learning approach (CRF or neural)
2. Identify at least 3 entity types:
   - Person, Organization, Location, Date, etc.
3. Create labeled training data or use existing dataset
4. Implement features:
   - Word features
   - Context features
   - Part-of-speech tags
5. Evaluate using precision, recall, F1-score
6. Test on diverse text samples
7. Visualize entities in context

### Hints
- Use spaCy or NLTK for baseline
- Consider BIO tagging scheme
- Use contextual features effectively
- Handle entity boundaries carefully

---

## Task 3: Text Generation or Summarization

### Objective
Implement a system for text generation or extractive summarization.

### Requirements
1. Choose either:
   - **Text Generation**: Build a character/word-level language model
   - **Summarization**: Create an extractive summarization system
2. For Text Generation:
   - Train on a corpus
   - Implement sampling strategies
   - Generate coherent sequences
   - Control generation parameters
3. For Summarization:
   - Extract key sentences
   - Rank by importance
   - Handle redundancy
   - Maintain coherence
4. Evaluate quality (perplexity for generation, ROUGE for summarization)
5. Demonstrate with multiple examples

### Hints
- Use RNN/LSTM for generation
- For summarization, consider TextRank or sentence scoring
- Implement temperature sampling for generation
- Use position and frequency features for summarization

---

## Evaluation Criteria

- **Correctness**: System works as intended
- **Code Quality**: Well-structured, documented code
- **Performance**: Achieves good results on task
- **Analysis**: Thorough evaluation and insights
- **Innovation**: Creative approaches and improvements
