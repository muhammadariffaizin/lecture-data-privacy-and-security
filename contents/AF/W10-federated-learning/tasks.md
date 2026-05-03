# Week 9 – Federated Learning and Data Science

## 🎯 Objective

* Understand the basic workflow of federated learning
* Run a simple `flwr` (Flower) simulation with a ready-made PyTorch example
* Visualize how data is split across clients and note the impact on training

## 📚 Reading

* Jarmul – Chapter 6 (Federated Learning)
* Stallings – distributed security concepts

## 📝 Task: *Federated Learning Basics*

Scenario:

> You are a data scientist working for a company that wants to build a prediction model using federated learning. The company has access to a dataset that is distributed across multiple devices. Your task is to run a small federated learning experiment with `flwr`, visualize how data is distributed, and summarize what you observe.

Students must:

1. Open the student notebook and run the setup cells to create the Flower project
2. Run a centralized-like baseline (single client)
3. Run a federated simulation (multiple clients)
4. (Optional) Change one run setting (for example, number of rounds or learning rate) and run again
5. Write 4-6 short sentences comparing the runs (accuracy/loss trend and runtime)

## 📦 Dataset ideas (optional)

You are not required to change datasets for this task. These are ideas for future projects:

* Fashion-MNIST (containing 10 classes of clothing items) - `zalando-datasets/fashion_mnist`
* EMNIST (containing 47 classes of handwritten characters) - `emnist`
* KMNIST (containing 10 classes of Japanese characters) - `kmnist`
* CIFAR-10 (containing 10 classes of general objects) - `cifar10`
* CIFAR-100 (containing 100 classes of general objects) - `cifar100`
* SVHN (containing 10 classes of house numbers) - `svhn_cropped`
* USPS (containing 10 classes of handwritten digits) - `usps`
* CelebA (containing 40 classes of celebrity attributes) - `celeba`
* FEMNIST (containing 62 classes of handwritten characters from different writers) - `femnist`
* Shakespeare (containing text data from Shakespeare's plays) - `shakespeare`
* Sent140 (containing 140,000 tweets with sentiment labels) - `sent140`
* AG News (containing news articles from the AG News dataset) - `ag_news`
* IMDB Reviews (containing movie reviews with sentiment labels) - `imdb`
* UCI Adult (containing demographic and employment data) - `adult`

## 💡 Submission

Submit a ZIP file containing:
* Notebook (.ipynb) with your runs, plots, and short notes
* A short report (half to one page) summarizing your results and insights

Submit at the myITS Classroom, max 11:59 PM on Sunday, May 6, 2026.