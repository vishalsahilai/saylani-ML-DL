

# 📘 Introduction to AI, Machine Learning & Deep Learning (Class Notes)

This document contains simple and correct notes from class about **Machine Learning (ML)**, and **Deep Learning (DL)**.

---

## 🤖 1. Traditional Programming (Rule-Based Systems)

In early computing systems, programs were based on fixed rules written by humans.

We provide:

* Input
* Rules / Conditions
* Output

### Example:

```text id="t1r9aa"
IF condition A → Output X  
IF condition B → Output Y
```

### Key Idea:

* The system only follows predefined rules
* No learning or improvement from experience
* No intelligence beyond given instructions

---

## 📊 2. Machine Learning (ML)

Machine Learning is a method where the system learns patterns from data instead of fixed rules.

We provide:

* Input data
* Labels (correct answers)

Then the model learns patterns from this data.

---

### 🧪 Example (Class Explanation: Digit Recognition 0–9)

In our class practical:

* We gave images of handwritten digits (0 to 9)
* The model was trained on these images
* Then we tested it with new images

### Result:

The model predicts:

* Which number (0–9) the image represents

### Key Idea:

> Machine Learning learns patterns from examples and predicts results for new inputs.

---

### ⚠️ Important Note (Class Concept)

Machine Learning works based on training data.

* It does not “reason like humans”
* It depends on learned patterns
* If data is limited or incorrect, results may also be inaccurate

---

## 🧠 3. Deep Learning (DL)

Deep Learning is an advanced form of Machine Learning.

It uses:

* Neural Networks (brain-inspired structure)
* Multiple layers of processing

### How it works:

* If prediction is wrong
* The system adjusts internally using feedback
* This improves accuracy over time

This learning process is called:

> **Backpropagation**

### Key Idea:

> Deep Learning improves itself by correcting errors.

---

## 🚀 4. Transformers (Modern AI Models)

Modern AI systems use Transformer-based architectures.

### Install required library:

```bash id="m2k8zx"
pip install transformers
```

### Why Transformers are important:

* Understand context in data
* Handle large text datasets
* Used in modern AI systems like ChatGPT

---

## 🧪 5. Class Practical File (Model Testing)

Our teacher provided a file for practical understanding.

### What we did:

* We loaded a dataset file provided in class
* The file contained images of digits (0–9)
* We passed images into the model
* The model predicted which number each image represents

### Purpose of this activity:

* To understand how models work in real life
* To see how input data is processed
* To connect theory with practical implementation

---

## 🧠 6. Foundation of AI (Alan Turing)

The foundation of modern computing and Artificial Intelligence is based on the work of:

### 👨‍💻 Alan Turing

* Father of Computer Science
* Proposed early concepts of machine intelligence
* His work laid the foundation for modern AI systems

---

## 📌 Summary

* Traditional Programming → Rule-based systems
* Machine Learning → Learns patterns from data
* Deep Learning → Learns + improves using feedback
* Transformers → Modern AI architecture
* Alan Turing → Foundation of AI theory

---

## ⚙️ Setup Requirement

To run the class model file, install:

```bash id="p9w1ld"
pip install transformers
```
