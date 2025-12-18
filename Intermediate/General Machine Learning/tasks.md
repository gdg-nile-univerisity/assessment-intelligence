# General Machine Learning Tasks - Intermediate Level

Complete **ANY TWO** of the following tasks.

---

## Task 1: Ensemble Learning Implementation

### Objective
Implement and compare different ensemble learning methods.

### Requirements
1. Implement from scratch or use libraries:
   - Bagging (Random Forest)
   - Boosting (AdaBoost or Gradient Boosting)
   - Stacking
2. Apply to a classification problem
3. Compare with individual base models
4. Analyze:
   - Individual model performance
   - Ensemble performance
   - Feature importance
   - Bias-variance tradeoff
5. Visualize decision boundaries (for 2D data)
6. Achieve >85% accuracy
7. Document best practices for ensembles

### Hints
- Use diverse base models for stacking
- Tune number of estimators
- Compare training time vs performance
- Use cross-validation for evaluation

---

## Task 2: Feature Engineering and Selection

### Objective
Master feature engineering and selection techniques for ML.

### Requirements
1. Start with a dataset (kaggle or UCI repository)
2. Implement feature engineering:
   - Create polynomial features
   - Interaction features
   - Domain-specific features
   - Feature transformations
3. Apply feature selection methods:
   - Filter methods (correlation, chi-square)
   - Wrapper methods (RFE)
   - Embedded methods (Lasso, tree-based)
4. Compare model performance with different feature sets
5. Visualize feature importance
6. Document the feature engineering process
7. Show improvement over baseline

### Hints
- Start with exploratory data analysis
- Test features incrementally
- Use cross-validation to avoid overfitting
- Consider computational cost

---

## Task 3: Hyperparameter Optimization

### Objective
Implement comprehensive hyperparameter tuning for ML models.

### Requirements
1. Choose a ML algorithm (SVM, Random Forest, XGBoost, etc.)
2. Implement multiple tuning strategies:
   - Grid Search
   - Random Search
   - Bayesian Optimization
3. Define comprehensive parameter space
4. Use nested cross-validation
5. Compare tuning methods:
   - Performance achieved
   - Time taken
   - Number of iterations
6. Visualize optimization process
7. Document best parameters and final model performance

### Hints
- Start with coarse grid, then refine
- Use appropriate scoring metrics
- Consider early stopping for efficiency
- Log all trials for analysis

---

## Evaluation Criteria

- **Correctness**: Implementations work correctly
- **Code Quality**: Well-structured, documented code
- **Performance**: Achieves good results
- **Analysis**: Thorough comparison and insights
- **Best Practices**: Follows ML engineering principles
