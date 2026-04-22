# Week 9 – Privacy-Aware Machine Learning with Differential Privacy

## 🎯 Objective

* Understand the concepts of Differential Privacy and its application to Machine Learning
* Implement privacy-preserving training using `Opacus` with Differentially Private Stochastic Gradient Descent (DP-SGD)
* Analyze the trade-off between model accuracy and privacy budget (ε)
* Compare privacy-aware models with non-private baseline models

## 📚 Reading

* Jarmul – Chapter 5 (Differential Privacy)
* Opacus Documentation: https://opacus.ai/
* Original DP-SGD Paper concepts

## 📝 Task: *Privacy-Preserving Model Design*

Scenario:

> You are a Data Privacy Engineer working for a healthcare company that wants to build a predictive model using sensitive medical data. The company must comply with privacy regulations while maintaining model accuracy. Your task is to implement a privacy-preserving deep learning model using Differential Privacy (DP-SGD), analyze the privacy-accuracy trade-off, and compare it with a non-private baseline.

Students must:

1. Implement a baseline model without privacy protection on CIFAR-10 dataset, measuring accuracy and training dynamics
2. Implement a privacy-preserving model using `Opacus` with DP-SGD on the same CIFAR-10 dataset
3. Experiment with multiple privacy budgets (ε values: 0.5, 1.0, 2.0, 5.0, 10.0), track epsilon evolution during training, and visualize the privacy-accuracy trade-off curve
4. Implement privacy mechanisms at different stages:
   - Per-sample gradient calculation
   - Gradient clipping with different norms
   - Gaussian noise addition
5. Compare and analyze:
   - Model accuracy vs. privacy budget (ε)
   - Training dynamics (loss convergence) under different privacy levels
   - Performance metrics at each privacy level
   - Privacy-utility trade-off characteristics

## 💡 Submission

Submit a ZIP file containing:
* **Notebook (.ipynb)** with complete implementation including:
  - Baseline model (non-private) training and evaluation
  - Privacy-aware model using DP-SGD
  - Privacy budget tracking and visualization
  - Trade-off analysis between accuracy and privacy
  - Comparative performance plots
* **Report (2-3 pages)** summarizing:
  - Theoretical background on DP-SGD and privacy budget management
  - Implementation details and hyperparameter choices
  - Privacy-accuracy trade-off analysis with visualizations
  - Insights and recommendations for privacy-utility balance
  - Discussion on when and why to use different privacy levels

## 📊 Expected Deliverables

1. ✅ Baseline model accuracy and training curves
2. ✅ Privacy-aware models with ε ∈ {0.5, 1.0, 2.0, 5.0, 10.0}
3. ✅ Privacy budget (ε) evolution plot during training
4. ✅ Privacy-Accuracy trade-off curve
5. ✅ Comparative analysis table
6. ✅ Model configurations (learning rate, gradient clipping norm, batch size, epochs)

## 🔍 Grading Criteria

* **Correctness (30%)**: Proper implementation of DP-SGD and privacy tracking
* **Analysis (30%)**: Insightful exploration of privacy-accuracy trade-offs
* **Visualization (20%)**: Clear and informative plots and comparisons
* **Documentation (20%)**: Detailed report with clear explanations

## 📤 Submission

Submit at myITS Classroom, max 11:59 PM on Sunday, May 25, 2026.
