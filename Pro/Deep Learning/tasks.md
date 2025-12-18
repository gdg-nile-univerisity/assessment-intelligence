# Deep Learning Tasks - Pro Level

Complete **ANY TWO** of the following tasks.

---

## Task 1: Implement a Transformer from Scratch

### Objective
Build a complete Transformer architecture from scratch and apply to a task.

### Requirements
1. Implement all Transformer components:
   - Multi-head self-attention mechanism
   - Position-wise feed-forward networks
   - Positional encoding
   - Layer normalization
   - Encoder and decoder stacks
2. Apply to a specific task:
   - Machine translation, text generation, or time series
3. Training infrastructure:
   - Custom data loader with batching
   - Learning rate scheduling (warmup + decay)
   - Gradient clipping
   - Mixed precision training
4. Implement advanced features:
   - Masked attention for causal models
   - Cross-attention for encoder-decoder
   - Dropout and regularization
5. Evaluation:
   - Task-specific metrics (BLEU, perplexity, etc.)
   - Attention visualization
   - Generation quality analysis
6. Compare with baseline models
7. Achieve competitive performance on chosen task

### Hints
- Start with smaller model for debugging
- Use established tokenizers
- Monitor gradient norms
- Implement beam search for generation

---

## Task 2: Advanced Model Optimization and Deployment

### Objective
Take a trained deep learning model and optimize it for production deployment.

### Requirements
1. Start with a trained model (image classification, NLP, etc.)
2. Implement multiple optimization techniques:
   - **Quantization**: INT8 or mixed precision
   - **Pruning**: Structured or unstructured
   - **Knowledge Distillation**: Train smaller student model
   - **Neural Architecture Search** (optional)
3. For each technique:
   - Measure accuracy retention
   - Measure speedup/latency
   - Measure model size reduction
   - Measure memory usage
4. Deployment preparation:
   - Export to ONNX or TorchScript
   - Optimize for target hardware
   - Implement efficient inference pipeline
   - Batch processing optimization
5. Benchmarking:
   - Compare original vs optimized models
   - Throughput analysis
   - Latency percentiles
6. Create deployment package with API
7. Document trade-offs and recommendations

### Hints
- Use PyTorch quantization or TensorRT
- Test accuracy after each optimization
- Profile inference carefully
- Consider edge device constraints

---

## Task 3: Self-Supervised Learning Implementation

### Objective
Implement a self-supervised learning approach and demonstrate its effectiveness.

### Requirements
1. Choose and implement a self-supervised method:
   - **Contrastive Learning**: SimCLR, MoCo, or BYOL
   - **Masked Modeling**: MAE or BEiT
   - **Other**: DINO, SwAV, etc.
2. Pre-training phase:
   - Design pretext task
   - Implement augmentation strategy
   - Create efficient data pipeline
   - Train on unlabeled data
3. Fine-tuning/evaluation phase:
   - Transfer to downstream task
   - Compare with supervised baseline
   - Analyze learned representations
4. Experiments:
   - Vary amount of labeled data
   - Test on multiple downstream tasks
   - Ablation studies on key components
5. Analysis:
   - Visualize learned features
   - Compare with supervised learning
   - Data efficiency analysis
   - Transfer learning capabilities
6. Achieve comparable or better performance with less labeled data
7. Document insights about learned representations

### Hints
- Start with established datasets (CIFAR, ImageNet subset)
- Use strong augmentations for contrastive methods
- Implement momentum encoder for some methods
- Monitor training stability

---

## Evaluation Criteria

- **Correctness**: Implementation is accurate and functional
- **Code Quality**: Research-grade, well-documented code
- **Performance**: Achieves strong results
- **Innovation**: Novel insights or improvements
- **Rigor**: Thorough experimentation and analysis
- **Reproducibility**: Clear documentation for reproduction
