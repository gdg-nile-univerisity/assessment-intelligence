# Data Science Tasks - Pro Level

Complete **ANY TWO** of the following tasks.

---

## Task 1: Causal Inference for Business Decisions

### Objective
Apply causal inference methods to determine the true effect of interventions.

### Requirements
1. Choose a causal question:
   - Marketing campaign effectiveness
   - Product feature impact
   - Policy intervention effect
2. Implement multiple causal methods:
   - **Propensity Score Matching**
   - **Difference-in-Differences**
   - **Regression Discontinuity Design** (if applicable)
   - **Instrumental Variables** (if applicable)
   - **Causal forests or meta-learners**
3. Data requirements:
   - Observational or quasi-experimental data
   - Proper treatment and control groups
   - Relevant covariates
4. Validation:
   - Check overlap/common support
   - Balance tests
   - Placebo tests
   - Sensitivity analysis
5. Heterogeneous treatment effects:
   - Analyze subgroup effects
   - Identify who benefits most
6. Statistical inference:
   - Confidence intervals
   - Robustness checks
7. Business recommendations:
   - Quantify causal effect
   - Calculate ROI
   - Provide actionable insights
8. Document assumptions and limitations

### Hints
- Use libraries like DoWhy, EconML, or CausalML
- Carefully check assumptions
- Visualize treatment effects
- Consider confounding variables

---

## Task 2: Advanced Feature Engineering at Scale

### Objective
Build a comprehensive feature engineering system for complex datasets.

### Requirements
1. Work with large, complex dataset:
   - Multiple data sources
   - Time-series components
   - High cardinality features
2. Implement advanced feature types:
   - **Time-based**: lags, rolling stats, seasonality
   - **Aggregations**: group statistics, ratios
   - **Interactions**: polynomial, custom combinations
   - **Embeddings**: categorical encodings
   - **Target encoding** with proper CV
   - **Text/NLP features** (if applicable)
3. Feature generation pipeline:
   - Automated feature generation
   - Feature validation
   - Memory-efficient processing
4. Feature selection:
   - Multiple selection methods
   - Stability selection
   - Recursive feature elimination
   - Feature importance aggregation
5. Feature monitoring:
   - Importance tracking
   - Drift detection
   - Correlation analysis
6. Engineering at scale:
   - Efficient computation
   - Caching strategies
   - Parallelization
7. Demonstrate improvement:
   - Compare with baseline
   - Ablation studies
   - Feature contribution analysis
8. Document feature catalog

### Hints
- Use Featuretools or custom pipeline
- Monitor memory usage
- Implement proper CV for target encoding
- Cache expensive computations

---

## Task 3: Kaggle-Style Competition Solution

### Objective
Build a complete, competitive solution for a complex ML problem.

### Requirements
1. Choose a challenging problem:
   - Kaggle competition (past or active)
   - Similar complexity problem
2. Full pipeline implementation:
   - Exploratory data analysis
   - Data cleaning and validation
   - Advanced feature engineering
   - Model selection and tuning
   - Ensemble building
   - Post-processing optimization
3. Advanced techniques:
   - Cross-validation strategy
   - Pseudo-labeling or semi-supervised learning
   - Adversarial validation
   - Target encoding with smoothing
   - Model stacking (2-3 levels)
4. Model diversity:
   - Use 5+ different model types
   - Optimize each thoroughly
   - Ensemble intelligently
5. Optimization:
   - Custom loss functions
   - Threshold optimization
   - Prediction calibration
6. Documentation:
   - Detailed EDA insights
   - Feature engineering rationale
   - Model selection reasoning
   - Lessons learned
7. Achieve top-tier performance:
   - Top 10% on public leaderboard equivalent
8. Create reproducible pipeline

### Hints
- Study winning solutions
- Implement thorough CV strategy
- Focus on feature engineering
- Don't overfit to public leaderboard

---

## Evaluation Criteria

- **Correctness**: Rigorous methodology
- **Code Quality**: Production-ready implementation
- **Performance**: Excellent results
- **Innovation**: Creative approaches
- **Rigor**: Proper validation and testing
- **Documentation**: Comprehensive analysis and insights
