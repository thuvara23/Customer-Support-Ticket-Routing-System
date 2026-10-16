# 🎟️ Customer-Support-Ticket-Routing-System

An automated Natural Language Processing (NLP) pipeline built with Python and spaCy to intelligently classify and route customer support tickets to the appropriate departments.

## 💡 Overview

Customer support teams spend countless hours manually sorting and tagging tickets. This project automates that workflow by analyzing incoming customer messages and routing them to the correct team (**Billing, Technical, Refund, or Sales**) based on semantic meaning and rule-based keyword matching.

## 🛠️ Key Features

*   🧠 **Understanding Meaning (Semantic Similarity):** The AI reads the ticket and calculates how closely the meaning matches each department's past tickets.
*   🔍 **Spotting Keywords (Rule-Based Matcher):** It scans for specific trigger words (like "login" or "charged twice") to give extra points to the right department.  
*   🏷️ **Extracting Details (NER):** It automatically highlights useful facts for the human agent, like prices, companies, and dates.
*   🏆 **Picking the Winner (Ranking):** It adds up the points from the meaning and the keywords to choose the best department. 
*   ⚠️ **Playing it Safe (Manual Review):** If the AI isn't sure, or if two departments have almost identical scores, it stops guessing and hands the ticket to a human.   
*   🗂️ **Sorting into Buckets (Multi-category):** The system is set up to route messages into four specific teams: Billing, Tech, Refund, and Sales. 

## 💻 Tech Stack

*   🐍 **Language:** Python  
*   📖 **NLP Library:** spaCy (`en_core_web_md` model)   
*   ⭕ **Environment:** Jupyter Notebook

## 🚀 Installation & Setup

**1️⃣ Clone the repository:**
```bash
git clone [https://github.com/thuvara23/ticket-routing-system.git](https://github.com/thuvara23/Customer-Support-Ticket-Routing-System))
cd ticket-routing-system

```

**2️⃣ Install the required dependencies:**

```bash
pip install spacy

```

**3️⃣ Download the spaCy language model:**

```bash
python -m spacy download en_core_web_md

```

**4️⃣ Run the Project:**
Open the Jupyter Notebook file to execute the pipeline and test custom tickets.

## 📂 Project Structure

```text
customer-support-ticket-routing/
│
├── Customer Support Ticket Routing .ipynb
└── README.md

```

```

```
