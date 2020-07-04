# Arabic Manuscripts Image Retrieval

This work provides three different models for image retrieval. 
The first developed model is a visual VGG19 customized deep convolutional neural network to classify the images and retrieve the ranked top similar images to a user query image. 
The second model is a textual model utilizing the attentional BiLSTM deep learning model, including both attention and batch normalization layers, to classify the text extracted from the images and then retrieve the most similar images to the user query image.
Finally, the VGG19 and the attentional BiLSTM models are fused at different fusion-levels to classify and retrieve the historical Arabic manuscripts’ images according to their both visual and textual characteristics.

