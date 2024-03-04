# REVERSE IMAGE SEARCH USING IMAGE CAPTIONING

### GOAL

To develop a reverse image search system using image captioning with PyTorch and Transformer, enhancing search accuracy and relevance.

### DATASET

The [`Fashion Product Images Dataset`](https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-dataset), comprising diverse images and their captions, facilitates the model to learn complex associations between visual content and textual descriptions.

### DESCRIPTION

This project employs a Transformer-based architecture for an image captioning model, which acts as the core of the reverse image search system. By generating captions for images, the system achieves a more contextually aware image search, leveraging the DuckDuckGo API for fetching similar images based on these captions.

### PROCEDURE

- Developed an Image Captioning model using PyTorch and Transformer, focusing on transfer learning for robust feature learning.
- Utilized the DuckDuckGo API for reverse image searching using the generated captions.
- Optimized the model to achieve a validation loss of 1.133 and a validation perplexity of 3.105, indicating high accuracy and reliability.

### MODELS USED

- PyTorch for model development and training.
- Transformer model for the image encoder-text decoder architecture.

### LIBRARIES NEEDED

- PyTorch
- Transformer libraries
- API integration tools for DuckDuckGo (FastAI)

### VISUALIZATION

Visualizations of the image-caption pairs and search results are provided in the accompanying Images folder.

### PERFORMANCE

The model demonstrates exceptional accuracy with a validation loss of 1.133 and a validation perplexity of 3.105 which can be further reduced with longer training.

### CONCLUSION

The project successfully integrates image captioning with reverse image search, offering a sophisticated approach to image retrieval. The use of advanced techniques like Transformer models and transfer learning significantly improves the system's effectiveness.

### FOOTER


