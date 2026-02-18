# README for IML Project

## Project Overview

The **IML Project** consists of multiple phases, each focusing on a different aspect of machine learning and secure computations. The project spans tasks related to **Boltzmann Machines**, **Secure Learning**, **Gibbs Sampling**, **ElGamal encryption**, **Secure Addition**, **Multi-Layer Perceptrons (MLP)**, and more. The aim of the project is to provide hands-on experience with machine learning algorithms and secure computation techniques.

The project is divided into several phases, each with specific tasks and challenges to be addressed.

## Phase 1: Introduction to Machine Learning

### Key Components:
- **Boltzmann Machines (RBM)**: Understanding the basics of Boltzmann machines and implementing them to learn data distributions.
- **Secure RBM**: Implementing a secure version of the Boltzmann machine, where the model ensures privacy by encrypting the data using the **ElGamal encryption** algorithm.

### Tasks:
1. Implement and train a basic RBM.
2. Implement the **Secure Boltzmann Machine (SecureRBM)** with encryption using the ElGamal algorithm.
3. Perform **Secure Addition** to combine the results of two parties securely.

### Tools and Libraries:
- Python programming language.
- Libraries: `numpy`, `matplotlib`, `sympy`, `sklearn`.

## Phase 2: Secure Learning and GMM

### Key Components:
- **Gibbs Sampling**: Understanding and implementing Gibbs sampling for hidden and visible neuron updates in a **Boltzmann Machine**.
- **Gaussian Mixture Model (GMM) using Expectation Maximization (EM)**: Implementing a GMM using the EM algorithm to model complex data distributions.
- **Secure GMM**: Extending the GMM model to work in a secure setting using encryption.

### Tasks:
1. Implement **Gibbs Sampling** for Boltzmann machines.
2. Implement and train a **GMM using EM** algorithm.
3. Apply encryption techniques to implement **Secure GMM**.

### Tools and Libraries:
- Python, `PyTorch`, `matplotlib`, `scikit-learn`, `numpy`.

## Phase 3: Advanced ML Models

### Key Components:
- **Linear Regression and Logistic Regression**: Understanding and implementing both linear and logistic regression models for data analysis.
- **Support Vector Machines (SVM)**: Implementing an SVM model for classification tasks.
- **Multi-Layer Perceptrons (MLP)**: Understanding and implementing a simple neural network for classification and regression tasks.

### Tasks:
1. Implement **Linear Regression** and **Logistic Regression** models.
2. Implement **Support Vector Machines (SVM)** for classification.
3. Implement **Multi-Layer Perceptrons (MLP)** and train it on classification tasks.

### Tools and Libraries:
- Python, `scikit-learn`, `matplotlib`, `tensorflow`.

## Phase 4: Secure Addition and ElGamal

### Key Components:
- **Secure Addition**: Securely adding numbers from two parties using ElGamal encryption.
- **ElGamal Encryption**: Implementing and understanding the ElGamal encryption and decryption algorithms.

### Tasks:
1. Implement **ElGamal encryption** and **decryption** (both partial and final).
2. Use **Secure Addition** to securely compute sums.
3. Implement **Secure Addition** in the context of machine learning, ensuring privacy in computations.

### Tools and Libraries:
- Python, `sympy`, `matplotlib`.

## Running the Code

### Phase 1:
1. Install the necessary dependencies by running:
    ```bash
    pip install -r requirements.txt
    ```

2. Open the Jupyter notebooks:
    - `IML_SecureRBM.ipynb` for the Secure RBM implementation.
    - `Secure_Addition.ipynb` for the Secure Addition algorithm.

3. Run the cells sequentially to implement and evaluate each model.

### Phase 2 and Beyond:
Follow the same steps to run the respective notebooks:
- `IML_Project_Phase1.ipynb`
- `GMM_using_EM.ipynb`
- `PCA_and_Kmeans.ipynb`
- `IML_phase2-part1.ipynb`

## Results and Evaluation

- **Phase 1**: Evaluate the SecureRBM performance using metrics such as accuracy and encryption efficiency.
- **Phase 2**: Evaluate the GMM model using log-likelihood and classification performance.
- **Phase 3**: Evaluate regression and classification models using standard performance metrics (e.g., MSE, accuracy).

Visualizations and plots are included to help analyze the models’ behavior and performance.

## Conclusion

This project provided hands-on experience with unsupervised and supervised learning techniques, focusing on Boltzmann machines, GMM, and secure computation methods. It also allowed for exploration of machine learning models and their secure implementations, applying encryption and secure addition protocols to ensure privacy in computations.

## References

- **Boltzmann Machines**: [Wikipedia - Boltzmann Machine](https://en.wikipedia.org/wiki/Boltzmann_machine)
- **Gibbs Sampling**: [Wikipedia - Gibbs Sampling](https://en.wikipedia.org/wiki/Gibbs_sampling)
- **ElGamal Encryption**: [Wikipedia - ElGamal](https://en.wikipedia.org/wiki/ElGamal_encryption)
- **Secure RBM**: [Secure RBM Paper](http://link-to-paper.com)
- **Gaussian Mixture Model (GMM)**: [Wikipedia - Gaussian Mixture Model](https://en.wikipedia.org/wiki/Mixture_model)
