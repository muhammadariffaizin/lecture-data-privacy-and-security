# Week 2 – Federated Learning and Data Science

## 🎯 Objective

* Understand the concepts of federated learning on Data Science
* Implement a simulation of federated learning model using `PyTorch` and `flwr` (Flower) framework on the CIFAR-100 dataset
* Analyze the performance of the federated learning model and compare it with a centralized model

## 📚 Reading

* Jarmul – Chapter 6 (Federated Learning)
* Stallings – distributed security concepts

## 📝 Task: *Federated System Design*

Scenario:

> You are a data scientist working for a company that wants to build a prediction model using federated learning. The company has access to a large dataset (CIFAR-100) that is distributed across multiple devices. Your task is to design and implement a federated learning model using the `flwr` framework, and analyze its performance compared to a centralized model.

Students must:

1. Build a prediction model using federated learning with `flwr` framework on the CIFAR-100 dataset (https://huggingface.co/datasets/uoft-cs/cifar100)
2. Implement training model with several types of `partitioner`, identify and visualize the data and class distribution for each type, and compare performance across each type
3. Implement a centralized model using the same dataset and compare its performance with the federated learning model

## 💡 Submission

Submit a ZIP file containing:
* Notebook (.ipynb) with the implementation of the federated learning model, including data partitioning, training, and performance analysis
* A brief report (1-2 pages) summarizing the approach, results, and insights gained from the experiment

Submit at the myITS Classroom, max 11:59 PM on Sunday, June 16, 2026.