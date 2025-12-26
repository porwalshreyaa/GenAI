# Tokenization

### What is Tokenization?
 Tokenization is a fundamental process in Natural Language Processing (NLP) that involves breaking down a stream of text into smaller units called tokens. These tokens can range from individual characters to full words or phrases, Based on how detailed it needs to be. By converting text into these manageable chunks, machines can more effectively analyze and understand human language.
> Breaking down text into smaller chunks called "tokens" (words, sub-words, sentences, characters)

#### Example

- "Chatbots are helpful."
    - tokenized by words: ["Chatbots", "are", "helpful"]
    - tokenized by characters: ["C", "h", "a", "t", "b", "o", "t", "s", " ", "a", "r", "e", " ", "h", "e", "l", "p", "f", "u", "l"]

#### Types

1. Word Tokenization:

    - text into -> individual words

2. Character Tokenization:
    
    - text into -> individual characters

3. Sub-word Tokenization:

    - text into -> individual words -> individual characters -> character pairs (most frequent pair) -> combined token -> subword units

4. Sentence Tokenization:
    - text into -> individual sentences

5. N-gram Tokenization:
    - words into -> fixed-sized chunks (size=n) of data

---

There are some advanced Tokenizer methods like - BERT Tokenization:

> "The BERT Tokenizer is a crucial component that converts raw text into numerical tokens (subwords) that BERT models understand, using the WordPiece algorithm, which splits rare words into smaller, meaningful pieces (e.g., "tokenization" -> "token", "##ization") to handle unknown words, manage vocabulary size, and capture context, preparing text for deep learning models. It adds special tokens like [CLS] and [SEP], maps tokens to IDs, and manages padding, providing a bridge between human language and AI processing."
---

### Tools and Libraries to Implement Tokenization

1. NLTK (Natural Language Toolkit) for Word and Sentence Tokenization
2. SpaCy
3. BERT Tokenizer
4. Byte-Pair Encoding (BPE) tokenizes based on the most frequent byte pairs in a text
5. Sentence Piece (an unsupervised text tokenizer and de-tokenizer) can tokenize text into sub-words

checkout the source here: [geegksforgeeks](https://www.geeksforgeeks.org/nlp/what-is-tokenization/)

---

### TikToken

- TikToken is a fast Byte-Pair Encoding Tokenizer developed by OpenAI to be used with it's models.
- Converts Text into -> Tokens (i.e. Sequence of Numbers)
- Usefull for apps in which token usage must be limited
- Rule Based Approach

source: [Medium Article](https://medium.com/thedeephub/tiktoken-vs-other-tokenizers-why-tiktoken-is-faster-7c3ec2d1c100)