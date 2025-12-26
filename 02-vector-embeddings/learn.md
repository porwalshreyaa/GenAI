# Vector Embeddings

## What are Vector Embeddings?

Vector embedding are 'digital fingerprints' or 'numerical representations' of words or other pieces of data. Each object is transformed into a list of numbers called a vector. These vectors captures properties of the object in a more manageable and understandable form for machine learning models.

- numerical representations (lists of numbers) = vectors
- object = data points that express different types of data

### What are Vectors?
- A vector is a one dimensional array of numbers containing multiple scalars of the same type of data.
- Vectors represents properties, features in a more machine understandable way.
#### Example:
- The weather model might represent the low, mean and high temperatures of that single day in vector form as (25, 30, 33).
- Each scalar component is a feature/dimension.

> Vector embeddings are numerical representations of data points that express different types of data, including nonmathematical data such as words or images, as an array of numbers that machine learning (ML) models can process.

#### Vectors vs Embeddings:
- they are not the same thing.
- An embedding is any numerical representation of data that captures its relevant qualities. The data is embedded in n-dimensional space.
- data doesn’t have to be embedded as a vector, specifically, in theory. But usually, in ML, the embeddings are vectors and vectors are embeddings.

### Uses
- Compare Similarities
- Clustering (group related data)
- Perform Arithmetic operations
- Feed machine understandable data

### types
1. Word Embedding:
    - a numeric representation (vector) of a word in a lower-dimensional space. 
    - Capture semantic information and also their contextual relationship to other words (syntactic information)
2. Sentence Embedding: 
    - finding the semantic meaning of entire phrases or sentences rather than individual words. 
    - They are generated with SBERT or other variants of sentence transformers.
3. Image Embedding: 
    - transforms images into numerical representations through which our model can perform- 
        - image search, 
        - object recognition, 
        - and image generation.
4. Multimodel Embedding:
    - Multimodal embedding combines different types of data models into a shared embedding space.

#### How does a Vector Embedding work?
It transforms a data point, such as a word, sentence or image, into an n-dimensional array of numbers representing that data point’s features. This is achieved by training an embedding model on a large data set relevant to the task at hand or by using a pretrained model.

- Example:
    <img src="https://media.geeksforgeeks.org/wp-content/uploads/20240104185157/emoji.png"/>



sources:
- [geeksforgeeks](https://www.geeksforgeeks.org/nlp/what-are-vector-embeddings/)
- [IBM](https://www.ibm.com/think/topics/vector-embedding#1003835712)