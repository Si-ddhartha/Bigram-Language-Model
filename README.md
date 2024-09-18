# Bigram Language Model
This project is a Bigram Language Model designed to generate names based on a dataset containing around 30000 unique names. The model learns by predicting the next character in a sequence, given the current one. It uses a simple **embedding-based lookup table** to map characters to their next likely character, forming new names.

However, since this model only considers two consecutive characters at a time (bigram modeling), the generated results are often unrealistic or nonsensical. This behavior is expected from a bigram model, as it **cannot capture longer dependencies** within names, making it too simplistic for producing coherent outputs.

To improve the quality of the generated names, more advanced models such as **Recurrent Neural Networks** (RNNs) or **Transformers** could be employed. These models can capture longer sequences and more complex patterns, significantly enhancing the quality of name generation.

This project was created just to learn the fundamentals of **PyTorch** and experiment with language modeling concepts. Despite its limitations, it was a valuable exercise in understanding how simple models operate and how they can be extended to more complex architectures.
