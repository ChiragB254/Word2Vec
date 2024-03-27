**Word2Vec Implementation from Scratch as well as using Gensim(Word2Vec library)**

---

# Unlock the Power of Word Embeddings

Welcome to the Word2Vec implementation repository! Here, we delve into the fascinating world of Natural Language Processing (NLP) by constructing Word2Vec from the ground up. Whether you're a novice in NLP or an enthusiast looking to deepen your understanding of word embeddings, this repository is your gateway to insightful exploration and practical hands-on experience.

## Understanding Word2Vec

Word2Vec is not just a tool; it's a language transformer. By converting words into numerical vectors, it empowers machine learning and deep learning models to comprehend and process textual data efficiently.

### Two Paths to Embeddings

1. **Frequency-Based Embeddings**: From Bag of Words (BoW) to TF-IDF, we dissect the essence of words based on their occurrences and importance within a document or corpus.

2. **Prediction-Based Embeddings**: Word2Vec stands tall here, predicting words based on their contextual surroundings, capturing nuanced semantic meanings and sentiments.

## Unveiling Word2Vec's Magic

Word2Vec operates through two fundamental architectures:

1. **Continuous Bag of Words (CBoW)**: Anticipating the target word from its context words, it's like deciphering the unsaid from the said.

2. **Skip-Gram**: Fathoming context words from the given target word, akin to unveiling the hidden clues in a message.

In this repository, we illuminate the path of CBoW, shedding light on its intricacies and implementations.

### Crafting the Implementation: An Example

Let's illustrate the concept with a simple example:

Consider the vocabulary: "hello linkedin connections let's talk".

Using a sliding window algorithm, we create training data. For instance, with a window size of three:

- For the phrase "hello linkedin connections":
  - Target word: "linkedin"
  - Context words: "hello" and "connections"
- For the phrase "linkedin connections let's":
  - Target word: "connections"
  - Context words: "linkedin" and "let's"
  
We then encode these words into one-hot vectors and train a neural network to predict the target word from its context.

### Embrace the Possibilities

- CBoW dances gracefully with smaller datasets, rendering swift and precise results.
- Skip-Gram, with its broad strokes, paints vivid semantic landscapes on larger canvases of data.

## Embark on Your Journey

To embark on your Word2Vec odyssey, clone this repository, and immerse yourself in the art of word embeddings.

---

![CBow_Word2Vec](https://github.com/ChiragB254/Word2Vec/assets/42599856/0fc4322d-41be-4225-82a7-e1e439808f2f)

![Skipgram_Word2Vec](https://github.com/ChiragB254/Word2Vec/assets/42599856/456e659a-103d-433b-845e-f5a04c0610cd)

---



