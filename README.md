# Long Short-Term Memory Networks (LSTMs)

* Vanilla LSTM. Memory cells of a single LSTM layer are used in a simple network structure.
* Stacked LSTM. LSTM layers are stacked one on top of another into deep networks.
* CNN LSTM. A convolutional neural network is used to learn features in spatial inputlike images and the LSTM can be used to support a sequence of images as input or generate a sequence in response to an image.
* Encoder-Decoder LSTM. One LSTM network encodes input sequences and a separateLSTM network decodes the encoding into an output sequence.
* Bidirectional LSTM. Input sequences are presented and learned both forward andbackward.
* Generative LSTM. LSTMs learn the structure relationship in input sequences so well that they can generate new plausible sequences.

* Overcomes the technical problems of training an RNN, namely vanishing and exploding gradients.
* Possesses memory to overcome the issues of long-term temporal dependency with input sequences.
* Process input sequences and output sequences time step by time step, allowing variable length inputs and outputs.
