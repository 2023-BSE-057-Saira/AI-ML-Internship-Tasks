# Task 04: General Health Query Chatbot Using Prompt Engineering

## Problem Statement

Healthcare chatbots can provide users with quick access to general health information and guidance. However, it is important that such systems provide clear, understandable responses while avoiding potentially harmful medical advice. This project develops a health query chatbot powered by a Large Language Model (LLM) and enhanced through prompt engineering techniques.

---

## Objective

The objective of this project is to build a conversational AI chatbot capable of answering general health-related questions in a friendly and informative manner while incorporating safety mechanisms to prevent unsafe medical recommendations.

---

## Dataset

No traditional dataset was used in this project.

The chatbot generates responses using a Large Language Model (LLM) accessed through a machine learning framework/API. User questions serve as input, and the model generates context-aware responses based on its pretrained knowledge.

---

## Technologies Used

* Python
* Google Colab
* Transformers Library
* Hugging Face Models
* Prompt Engineering Techniques

---

## Project Workflow

### 1. Environment Setup

Required libraries were installed and imported to enable interaction with the language model.

### 2. Language Model Integration

A pretrained instruction-tuned Large Language Model was loaded to process user queries and generate responses.

### 3. Prompt Engineering

A custom prompt template was designed to guide the model's behavior.

The prompt instructed the chatbot to:

* Act as a helpful medical assistant
* Provide general health information
* Use simple and friendly language
* Avoid diagnosing diseases
* Avoid prescribing medications
* Encourage consultation with healthcare professionals when necessary

### 4. Safety Filtering

A safety layer was implemented to identify and block potentially dangerous health-related requests.

Examples include:

* Self-harm related questions
* Medication overdose requests
* Prescription dosage instructions
* Emergency treatment advice

When such queries are detected, the chatbot responds with a safety message directing users to seek professional medical assistance.

### 5. Response Generation

User questions are processed through the prompt template and submitted to the language model. The generated response is then displayed to the user.

### 6. Interactive Conversation

An interactive chatbot interface was developed to allow continuous user interaction through the command line or notebook environment.

---

## Example Queries

### Query 1

What causes a sore throat?

The chatbot provides general information about common causes such as viral infections, bacterial infections, allergies, and environmental irritants.

### Query 2

Is paracetamol safe for children?

The chatbot provides general safety information while advising users to consult a healthcare professional for dosage recommendations.

---

## Safety Features

The chatbot includes safeguards to prevent unsafe medical guidance.

Blocked categories include:

* Self-harm instructions
* Suicide-related content
* Medication overdose information
* Prescription dosage recommendations
* Emergency treatment instructions

These measures help ensure responsible and ethical AI usage.

---

## Key Findings

* Prompt engineering significantly improves response quality and consistency.
* Safety filters are essential when developing healthcare-related conversational agents.
* Large Language Models can effectively provide general health information.
* Conversational AI can improve accessibility to basic health knowledge while maintaining safety boundaries.

---

## Learning Outcomes

This project helped develop practical skills in:

* Prompt Engineering
* Conversational AI Development
* Large Language Model Integration
* API and Model Usage
* Safety-Aware AI Design
* User Interaction Design

---

## Conclusion

This project demonstrates the development of a health query chatbot using a Large Language Model and prompt engineering techniques. The chatbot successfully answers general health questions in a friendly and informative manner while implementing safety measures to prevent harmful medical advice. The project highlights the importance of responsible AI deployment in healthcare-related applications.

---

## Files Included

* Health_Query_Chatbot.ipynb
* README.md
* Screenshots Folder

---

## Author

Saira Ejaz


