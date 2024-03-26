# Bach Harmonies: A Deep Learning Approach to Generating Chorale Music

## Project Overview

"Bach Harmonies" is a deep learning project designed to generate new music inspired by the chorales of Johann Sebastian Bach. Utilizing a dataset of 382 Bach chorales, this project employs sequence-to-sequence recurrent neural networks (RNNs) to predict musical chords and generate novel chorale sequences.

## Motivation

The motivation behind "Bach Harmonies" lies in the challenge of capturing the complexity and beauty of Bach's compositions through machine learning. This project aims not only to create music that maintains the stylistic elements of Bach's chorales but also to explore the potential of neural networks in understanding and replicating classical music composition techniques.

## Technical Details

### Technologies Used

- Python
- TensorFlow and Keras for deep learning
- Pandas and NumPy for data manipulation

### Dataset

The dataset comprises 382 chorales by Johann Sebastian Bach, with each chorale consisting of 100 to 640 chords. Each chord is represented by four integers corresponding to musical notes, facilitating the training of the neural network models.

### Model Architecture

The project uses a sequence-to-sequence RNN model with GRU layers and embeddings to predict the next chord in a sequence. The model's architecture is designed to handle the temporal nature of music, learning the patterns and dependencies between successive chords.

### Challenges and Learnings

One of the main challenges was dealing with the variable lengths of chorales and efficiently encoding musical information for the neural network. Through this project, significant insights were gained into sequence prediction problems, data preprocessing for deep learning, and the application of RNNs to creative domains like music generation.

## Getting Started

To replicate or build upon this project, you will need:

1. Python 3.x and pip
2. Dependencies: TensorFlow, Keras, Pandas, NumPy
3. The Bach chorales dataset (instructions for downloading and preprocessing are included in the notebook)

### Installation

Install the required Python libraries using:

```bash
pip install tensorflow keras pandas numpy
```

## Usage

The project is encapsulated in a Jupyter Notebook that walks through the dataset preparation, model training, and music generation process. To generate new music:

1. Train the model using the provided dataset.
2. Use the model to predict new chords and compile them into a chorale.
3. Convert the numerical chord representations back into music (MIDI or a similar format) for playback.

## Future Work

Future directions include exploring more complex models, such as Transformer networks, to capture deeper musical structures and experimenting with different representations of musical data to enhance the quality of generated compositions.

## License

This project is open-sourced under the MIT License.

## Acknowledgments

Special thanks to the creators of the TensorFlow and Keras libraries for providing the tools essential for this project's development, and to Johann Sebastian Bach, whose timeless compositions made this project possible.
