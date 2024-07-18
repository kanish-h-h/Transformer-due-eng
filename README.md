# Transformer Attention Model for English to German Translation

This repository contains the implementation of a Transformer model for translating German (deu) to English (eng) using attention. 

This project is the implementation of paper : [Attention is all you need](https://arxiv.org/abs/1706.03762)

The model architecture includes components such as **cross-attention**, **decoder**, **encoder**, **feedforward**, **self-attention**, and **transformer**. 
The project model is saved at `models/` and includes visualizations for accuracy, loss, and learning rate at directory `assets/images`.
You can also find the images of architecture for **cross-attention**, **decoder**, **encoder**, **feedforward**, **self-attention**, and **transformer** within directory `assets/model architecture`.

## Installation

Clone the repository:
   ```bash
   git clone https://github.com/yourusername/transformer-deu-to-eng.git
   cd transformer-deu-to-eng
   ```

## Model Architecture
The transformer model consists of the following components:

- **Encoder**: Processes the input sequence.
![](https://github.com/kanish-h-h/Transformer-due-eng/blob/main/assets/model%20architecture/encoder.png)
- **Decoder**: Generates the output sequence.
![](https://github.com/kanish-h-h/Transformer-due-eng/blob/main/assets/model%20architecture/decoder.png)
- **Self-Attention**: Allows the model to focus on different parts of the input sequence.
![](https://github.com/kanish-h-h/Transformer-due-eng/blob/main/assets/model%20architecture/self-attention.png)
- **Cross-Attention**: Allows the decoder to focus on relevant parts of the input sequence.
![](https://github.com/kanish-h-h/Transformer-due-eng/blob/main/assets/model%20architecture/cross-attention.png)
- **Feedforward**: Adds non-linearity and complexity to the model.
![](https://github.com/kanish-h-h/Transformer-due-eng/blob/main/assets/model%20architecture/feedforward.png)
- **Transformer**: transformer itself.
![](https://github.com/kanish-h-h/Transformer-due-eng/blob/main/assets/model%20architecture/transformer.png)

## Pickle files

- **text_pairs.pickle**: For pairing text among deu and eng. 
- **vectorize.pickle**: Vectorizing each sentence.
- **posenc-2048-512.pickle**: Position encoding for the sentence.

## Learning Rate
![](https://github.com/kanish-h-h/Transformer-due-eng/blob/main/assets/images/Learning%20Rate.png)

## Position Encoding
![](https://github.com/kanish-h-h/Transformer-due-eng/blob/main/assets/images/Positional%20Encoding.png)

**PE Curves**
![](https://github.com/kanish-h-h/Transformer-due-eng/blob/main/assets/images/Positional%20Encoding%20Curves.png)

**Subplots**
![](https://github.com/kanish-h-h/Transformer-due-eng/blob/main/assets/images/Positional%20Encoding%20subplots.png)

## Loss and Accuracy
![](https://github.com/kanish-h-h/Transformer-due-eng/blob/main/assets/images/Loss%20and%20Accuracy.png)

## Acknowledgements

- The implementation is based on the paper "Attention Is All You Need" by Vaswani et al. [Attention is all you need](https://arxiv.org/abs/1706.03762)
- Thanks to the contributors of open-source libraries such as TensorFlow. 
