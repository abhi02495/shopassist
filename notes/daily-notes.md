***Day-1***

AI is the broad goal of machines doing tasks that need intelligence. 
Machine learning (ML) is the part of AI where a system learns patterns from data instead of following hand-written rules. 
Deep learning is ML with many-layered neural networks. 
Generative AI (GenAI) creates new content (text, images, code) instead of only predicting a label. A spam filter is classic ML: it outputs "spam" or "not spam".


***Day-2***

A neural network is layers of numbers (weights) that turn an input into an output.
**Training** shows it many examples, measures the error with a loss function, and nudges the weights to reduce it (gradient descent).
The learned weights are the model's parameters; an "8B model" has about 8 billion of them. Training is expensive and happens once at the model.
**Inference** is using the trained model to answer
**Learning** - finding the right weights and biases to solve the problem at hand
**Training** - training a machine using the Sigmoid or ReLU (Rectified Linear Unit) function


***Day-3***

LLMs read tokens, not words: pieces of words, punctuation and spaces.
Each token becomes a vector of numbers (an embedding) that captures meaning.

A **transformer** is a deep learning neural network architecture that processes sequential data (such as text or audio) by analyzing the entire sequence all at once rather than word-by-word.

It uses attention so every token can look at every other token, which is how the model knows "bank" means a riverbank in one sentence and a money bank in another. 

An LLM generates text one token at a time, each time predicting a likely next token. You pay per token, both in and out.
