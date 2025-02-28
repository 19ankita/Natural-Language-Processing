# Sentiment Analysis Using BERT

## 📌 Introduction
This repository focuses on **Sentiment Analysis** using a **pretrained BERT model**. The project utilizes **PyTorch** and **Hugging Face Transformers** to classify textual data into various emotional states based on remarks. The dataset is an **annotated CSV file** containing labeled sentiment data.

## 📊 Dataset
- The dataset consists of **textual remarks** labeled with different **emotional states**.
- It has been **preprocessed** to be suitable for the **BERT model**.
- Data is split into **training and validation** sets for model evaluation.

## 🔍 Model & Framework
- **Pretrained Model:** BERT (Bidirectional Encoder Representations from Transformers)
- **Frameworks Used:**
  - **PyTorch** for deep learning computations
  - **Hugging Face Transformers** for leveraging the pretrained BERT model

## 🚀 Project Outline
The project follows a structured workflow to ensure systematic implementation:

### **Task 1: Introduction**
- Overview of sentiment analysis and the role of transformers like BERT.

### **Task 2: Exploratory Data Analysis (EDA) and Preprocessing**
- Understanding dataset distribution and cleaning text data.
- Tokenization and handling missing values.

### **Task 3: Training/Validation Split**
- Splitting dataset into **training and validation** sets.
- Ensuring balanced class distribution.

### **Task 4: Loading Tokenizer and Encoding Data**
- Utilizing **BERT tokenizer** to encode the textual data.
- Padding and truncation to maintain consistency in input sizes.

### **Task 5: Setting Up BERT Pretrained Model**
- Initializing **BERT-base-uncased** model.
- Fine-tuning BERT for sentiment classification.

### **Task 6: Creating Data Loaders**
- Converting datasets into **PyTorch Dataloaders** for efficient batch processing.

### **Task 7: Setting Up Optimizer and Scheduler**
- Using **AdamW optimizer** to fine-tune BERT.
- Implementing **learning rate scheduler** to stabilize training.

### **Task 8: Defining Performance Metrics**
- **Accuracy, Precision, Recall, and F1-score** for evaluation.
- Utilizing **confusion matrix** to assess model predictions.

### **Task 9: Creating Training Loop**
- Implementing **training and validation loops**.
- Monitoring **loss and accuracy** over epochs.

### **Task 10: Loading and Evaluating the Model**
- Loading the trained model.
- Running sentiment predictions on new data.


## 📌 Acknowledgments
**Sentiment Analysis with BERT on Coursera** (https://www.coursera.org/projects/sentiment-analysis-bert).
- **Hugging Face Transformers** for providing the pretrained BERT model.
- **PyTorch** for deep learning utilities.
- **Jupyter Notebook** for interactive model training and evaluation.

---

