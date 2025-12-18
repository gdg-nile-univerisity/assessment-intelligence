# Computer Vision Tasks - Pro Level

Complete **ANY TWO** of the following tasks.

---

## Task 1: Advanced Object Detection System

### Objective
Implement a modern object detection system using state-of-the-art architectures.

### Requirements
1. Implement or fine-tune an advanced detector:
   - YOLO (v5/v8), Faster R-CNN, or EfficientDet
   - Multi-scale detection
   - Handle various object sizes
2. Custom dataset preparation:
   - Data annotation/augmentation
   - Class imbalance handling
   - Train/val/test splits
3. Training pipeline:
   - Transfer learning from COCO/ImageNet
   - Advanced augmentation strategies
   - Learning rate scheduling
   - Model checkpointing
4. Evaluation:
   - mAP calculation at different IoU thresholds
   - Per-class performance analysis
   - Speed/accuracy trade-offs
5. Optimization for inference:
   - Model quantization or pruning
   - Batch processing
   - Real-time performance analysis
6. Deploy demo application
7. Achieve >70% mAP on validation set

### Hints
- Use established frameworks (MMDetection, Detectron2)
- Start with pre-trained weights
- Monitor GPU memory usage
- Profile inference speed

---

## Task 2: Semantic Segmentation for Complex Scenes

### Objective
Build a semantic segmentation system for complex real-world images.

### Requirements
1. Implement advanced segmentation architecture:
   - U-Net, DeepLab, or HRNet
   - Encoder-decoder structure
   - Multi-scale processing
2. Handle challenging scenarios:
   - Multiple object classes
   - Overlapping objects
   - Varying lighting conditions
3. Training strategy:
   - Use pre-trained backbone
   - Implement focal loss or similar
   - Data augmentation for segmentation
   - Handle class imbalance
4. Evaluation metrics:
   - Mean IoU per class
   - Pixel accuracy
   - Boundary accuracy
5. Post-processing:
   - CRF refinement
   - Morphological operations
6. Visualize segmentation masks overlaid on images
7. Achieve >75% mean IoU

### Hints
- Use established datasets (Cityscapes, ADE20K)
- Implement weighted loss for rare classes
- Use mixed precision training
- Consider multi-task learning

---

## Task 3: Vision Transformer Implementation

### Objective
Implement and experiment with Vision Transformer (ViT) architectures.

### Requirements
1. Implement Vision Transformer:
   - Patch embedding layer
   - Multi-head self-attention
   - Position embeddings
   - Classification head
2. Compare with CNN baselines:
   - ResNet or EfficientNet
   - Same dataset and training regime
   - Analyze differences
3. Implement advanced techniques:
   - Data augmentation strategies (RandAugment, MixUp)
   - Regularization (dropout, stochastic depth)
   - Optimization tricks
4. Analysis:
   - Attention visualization
   - Feature representation comparison
   - Data efficiency study
   - Computational cost analysis
5. Experiment with variants:
   - Different patch sizes
   - Model scaling
   - Hybrid architectures (CNN + Transformer)
6. Achieve competitive accuracy (>85% on CIFAR-10/100)
7. Document findings and insights

### Hints
- Start with smaller models for experimentation
- ViT requires more data or strong augmentation
- Use pre-trained weights when available
- Visualize attention maps for interpretability

---

## Evaluation Criteria

- **Correctness**: System works correctly and reliably
- **Code Quality**: Production-ready, well-documented code
- **Performance**: State-of-the-art or competitive results
- **Innovation**: Novel approaches or insights
- **Deployment**: Practical considerations and optimizations
- **Documentation**: Comprehensive analysis and findings
