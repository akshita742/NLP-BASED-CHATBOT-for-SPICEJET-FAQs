# NLP-Based Chatbot for SpiceJet FAQs  

This repository contains my **internship project** where I developed a **rule-based + NLP-powered chatbot** to handle **frequently asked questions (FAQs)** for **SpiceJet Airlines (Domestic Flights)**.  

The chatbot is designed to improve customer support by providing quick, automated responses to common queries such as **baggage allowance, cancellations, check-in rules, rescheduling, and general flight information**.  

## Repository Structure
- **`NLP BASED CHATBOT.ipynb`** → Main Jupyter Notebook with:  
  - Data preprocessing  
  - Intent classification (TF-IDF + Logistic Regression)  
  - Training & evaluation  
  - Chatbot pipeline implementation  

## Features
- Handles **frequently asked domestic flight queries**  
- Uses **NLP & ML (TF-IDF + Logistic Regression)** for intent classification  
- Achieves good accuracy with structured FAQ dataset  
- Modular code: easy to extend with more intents or improved models  

## Tech Stack
- **Python 3.x**  
- **Libraries:**  
  - NumPy, Pandas (data handling)  
  - Scikit-learn (ML pipeline, TF-IDF, Logistic Regression)  
  - Joblib (model persistence)  

## Model Workflow
1. **Data Cleaning & Preprocessing**  
2. **Feature Extraction** using TF-IDF  
3. **Intent Classification** using Logistic Regression  
4. **Chatbot Logic** for mapping intents → predefined answers  
5. **Evaluation** using accuracy, f1-score, and classification report  

## Example Queries
- “What is the baggage allowance for domestic flights?”  
- “Can I reschedule my flight?”  
- “How do I check-in online?”  
- “What happens if I miss my flight?”  

## Author
**Akshita Antil**  
- Internship Project at **SpiceJet**  
- Focus: **NLP-based automation for customer support**  

## 
How to Use
1. Clone this repo:  
   ```bash
   git clone https://github.com/akshita742/NLP-BASED-CHATBOT-for-SPICEJET-FAQs.git
