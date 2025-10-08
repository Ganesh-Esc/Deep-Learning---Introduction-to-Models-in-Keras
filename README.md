# Keras API Deep Dive: Sequential, Functional, and Sub-classing

[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)](https://keras.io/)

A hands-on lab designed to teach you how to build deep learning models in Keras using its three powerful APIs: Sequential, Functional, and Model Sub-classing.

---

## 📖 Lab Overview

This lab provides a comprehensive guide to the different ways you can define a neural network architecture in Keras. By the end of this exercise, you will not only know *how* to use each API but, more importantly, *when* to choose one over the others based on your project's complexity and requirements.

### 🎯 Learning Objectives

After completing this lab, you will be able to:

* **Understand Different API Use Cases:**
    * **Sequential API:** Recognize when to use this simple, elegant API for building linear stacks of layers. Ideal for straightforward, common network architectures.
    * **Functional API:** Know how to leverage its flexibility for creating complex models with non-linear topology, such as multi-input/multi-output models, shared layers, and directed acyclic graphs (DAGs). 
* **Build Custom Models via Sub-classing:**
    * Master the art of creating fully customized, research-level models by inheriting from the `tf.keras.Model` class. This approach provides maximum control by allowing you to define your own forward pass logic.

---

## 🛠️ Lab Structure

The notebook is divided into three distinct parts, each focusing on one of the Keras APIs:

1.  **Part 1: The Sequential API**
    * Build a simple, feedforward neural network for a standard classification or regression task.
2.  **Part 2: The Functional API**
    * Construct a more intricate model, such as one with multiple inputs and outputs, to understand its power and flexibility.
3.  **Part 3: Model Sub-classing**
    * Implement a custom model from scratch by defining its layers in `__init__` and its forward pass logic in the `call` method.

---

