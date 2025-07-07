# Chatbot-Using-RNNs

This repository implements the End-To-End Memory Network architecture proposed in this paper(http://arxiv.org/abs/1503.08895), which introduces a neural network model with a recurrent attention mechanism over an external memory. Unlike traditional Memory Networks, this variant is trained in an end-to-end fashion, requiring minimal supervision and making it more practical for real-world applications.

While RNNs and LSTMs attempt to model long-term dependencies via internal state memory, their representations are often unstable over long sequences. LSTMs improve upon this with gated memory cells, but offer only modest gains. In contrast, End-To-End Memory Networks use a shared, external memory with learnable read/write operations. With tied weights across layers (hops), the model functions similarly to an RNN, where each hop refines the internal state through interactions with memory, culminating in a final prediction after a fixed number of steps.

Refer to the original paper for deeper insights into the model's architecture and applications.
