# Task 5: Mental Health Support Chatbot (Fine-Tuned)

## Objective

The objective of this project is to develop a Mental Health Support Chatbot capable of generating empathetic and supportive responses for individuals experiencing stress, anxiety, sadness, and emotional challenges. The chatbot is fine-tuned using a pre-trained language model and an empathy-focused conversational dataset to provide emotionally aware responses.

---

## Dataset Used

**Dataset Name:** Emotion-Emotion 69K Dataset

**Description:**
The dataset contains over 64,000 emotional conversations with the following key attributes:

* Situation: User's emotional situation or concern
* Emotion: Emotional category associated with the situation
* Empathetic Dialogues: Supportive and empathetic responses
* Labels: Additional annotations

The dataset was used to train the model to understand emotional contexts and generate compassionate responses.

---

## Model Applied

**Base Model:** DistilGPT2

**Frameworks and Libraries:**

* Hugging Face Transformers
* Hugging Face Datasets
* PyTorch
* Google Colab

**Fine-Tuning Approach:**

* Converted dataset records into conversational prompt-response format.
* Tokenized text using DistilGPT2 tokenizer.
* Fine-tuned the model using Hugging Face Trainer API.
* Trained on a subset of the dataset for faster experimentation and evaluation.

---

## Implementation Steps

1. Loaded and explored the emotional dialogue dataset.
2. Cleaned and preprocessed the data.
3. Converted records into chatbot conversation format.
4. Tokenized the text using DistilGPT2 tokenizer.
5. Fine-tuned DistilGPT2 using Hugging Face Trainer API.
6. Saved the trained model.
7. Developed a command-line chatbot interface for testing.
8. Evaluated generated responses on various emotional scenarios.

---

## Key Results and Findings

* Successfully fine-tuned DistilGPT2 on an empathy-focused conversational dataset.
* The chatbot generated supportive and emotionally aware responses.
* The model demonstrated the ability to recognize emotional situations and respond appropriately.
* The project showcased practical applications of Natural Language Processing (NLP), transformer fine-tuning, and conversational AI.

### Sample User Query

**User:** I am feeling stressed because of my exams.

**Chatbot:** I understand that exams can be overwhelming. It is completely normal to feel stressed. Try taking short breaks, organizing your study schedule, and remember that your efforts matter. You are doing your best.

---

## Technologies Used

* Python
* Google Colab
* Hugging Face Transformers
* Hugging Face Datasets
* PyTorch
* DistilGPT2

---

## Conclusion

This project demonstrates how transformer-based language models can be fine-tuned to build supportive conversational agents. The Mental Health Support Chatbot provides empathetic responses and highlights the potential of AI in emotional wellness and conversational assistance applications.
