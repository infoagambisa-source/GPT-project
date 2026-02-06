# Build Your Own GPT (Mini GPT)

## Compute
- Training environment: CPU only
- CUDA available: False

## Dataset
- Source: Project Gutenberg (public domain)
- Books used: 
    1. Moby Dick; Or, The Whale by Herman Melville 
    2. Alice's Adventures in Wonderland by Lewis Carroll 

## Model / Training hyperparameters
- batch_size: 16
- block_size: 32
- n_layer: 4
- n_head: 4
- n_embd: 128
- max_iters: 3000
- learning_rate: 1e-3

## Results
- Final train loss: 1.7751
- Final val loss: 1.8564
- Sample outputs saved in /samples
