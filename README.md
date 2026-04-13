 AI Marketing Lab 1
Overview

This project introduces the fundamentals of AI in marketing using Python. It covers basic programming concepts, data handling, decision-making logic, and the use of AI APIs in real-world business scenarios.

 Lab Setup
Step 1: Create Notebook
Open your environment (Jupyter / Colab)
Click New Notebook
Rename file to:
AI_Marketing_Lab_1
First Program
print("Welcome to AI Marketing Lab")
Explanation
print() is used to display output
It is the simplest way to interact with the system
 Step 2: Understanding Data in Python
 <img width="1539" height="672" alt="Screenshot 2026-04-13 090456" src="https://github.com/user-attachments/assets/be8542b8-3ba8-4655-9e7b-4401377ebc15" />


AI systems depend entirely on data. Before building models, we must understand how data is stored.

Example 1: Basic Data (Variables)
customer_name = "Amit"
age = 25
is_customer = True

print(customer_name, age, is_customer)
Explanation
Variable	Meaning in Business
customer_name	Customer identity
age	Demographic data
is_customer	Boolean decision
Why This Matters

Companies use such data to:

Analyze behavior
Segment customers
Predict outcomes
Example 2: List (Customer Purchases)
purchases = ["Shoes", "T-shirt", "Watch"]
print(purchases)
Explanation
A list represents multiple values
In business:
Purchase history
Browsing behavior
Real-World Connection

E-commerce platforms use this data to recommend products.

 Step 3: From Data to Decision

AI systems make decisions based on logic and conditions.

Example: Purchase Prediction Logic
income = 50000

if income > 40000:
    print("Customer likely to purchase")
else:
    print("Customer unlikely to purchase")
 Explanation
Represents a rule-based decision system
Basic form of predictive logic
 Why This is Important
Real AI models replace fixed rules
They learn patterns from data instead of hardcoding conditions Step 4: Introduction to AI APIs
Definition

An API (Application Programming Interface) allows different software systems to communicate.

 AI API

An AI API allows:

Sending input (text/data)
Receiving AI-generated output
 Why Businesses Use AI APIs
No need to build AI from scratch
Faster implementation
Scalable solutions
Examples of AI APIs
Platform	Use Case
OpenAI	Chatbots, text generation
Google AI	Content & AI models
Hugging Face	NLP & ML models
Conclusion

This lab builds a strong foundation for:

AI-based decision making
Data understanding
Real-world AI applications in marketing
