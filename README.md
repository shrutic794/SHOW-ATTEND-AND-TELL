#  Show, Attend and Tell: Neural Image Caption Generator with Visual Attention

##  Overview
This project implements the **Show, Attend and Tell** model — a pioneering neural network architecture that generates **descriptive captions** for images using **visual attention mechanisms**. Unlike earlier image captioning models, this approach learns to focus on specific parts of an image while generating each word, closely mimicking how humans describe scenes.

---

##  Model Architecture
-  **CNN Encoder**: A pre-trained convolutional neural network (e.g., ResNet, Inception) encodes spatial image features.
-  **Attention Module**: At each timestep, attention weights are computed over the spatial features to selectively focus on regions of interest.
-  **LSTM Decoder**: Generates one word at a time using the attended image features and previous word context.

---

##  Features
-  Generate fluent captions for a variety of input images
-  Visualize attention heatmaps for each generated word
-  Evaluate using BLEU scores, attention entropy, and qualitative metrics
-  Compatible with custom datasets (COCO, Flickr8k/30k)

---

##  Technologies Used
- **Python**, **PyTorch**
- **Matplotlib** – For attention heatmap visualization
- **NLTK / BLEU** – For caption evaluation
- **PIL, NumPy** – Image preprocessing

---

