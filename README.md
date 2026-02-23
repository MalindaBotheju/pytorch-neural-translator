Transformer from Scratch (PyTorch)
Overview
This project is a complete, from-scratch implementation of the original "Attention Is All You Need" Transformer architecture using PyTorch. It is trained on the Hugging Face opus_books dataset to translate English to French.

Architecture Details
I built the core components of the model without relying on pre-built Transformer libraries:

Multi-Head Attention: Scaled dot-product attention mechanisms.

Positional Encoding: Sine and cosine functions to inject sequence order.

Encoder & Decoder Stacks: Complete with residual connections and layer normalization.

Masking: Custom look-ahead and padding masks for causal autoregressive generation.

Training & Inference
Data Pipeline: Custom PyTorch DataLoaders with dynamic padding and Hugging Face tokenizers.

Decoding: Implemented a greedy decoding loop for word-by-word autoregressive translation.
