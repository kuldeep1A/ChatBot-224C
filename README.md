# Winner of Hackathon for Best Solution of ChatBot

### Team Members: Vehdat Hamid, Kanhaiyalal Chawada, Harish Malviya, Kuldeep Dhangar

## What is this?

A **dual-purpose educational chatbot** that answers questions about:

- **Courses & Fees** - program details, costs, eligibility
- **Student Information** - enrollment data, demographics

## How it works

- Uses **OpenAI GPT-3.5-turbo** to understand natural language queries
- Processes data from two CSV files: `fee.csv` (115+ courses) and `student.csv` (1,656+ students)
- Handles large datasets with smart chunking
- Evaluated using BLEU scores for response quality

## Key Features

- **Fee Chatbot**: Course information, fees, duration, eligibility
- **Student Chatbot**: Student data, enrollment details, demographics
- **Conversational**: Remembers context from previous questions
- **Smart Processing**: Breaks large datasets into manageable chunks

## Quick Start

1. Install: `pip install openai pandas nltk`
2. Add your OpenAI API key
3. Run the Jupyter notebook

## Example Usage

```python
# Ask about courses
response = fee_chatbot("What's the fee for B.Tech Computer Science?")

# Ask about students
response = student_chatbot("How many students are in Engineering?")
```

## Why it won

- **Innovative dual-bot architecture**
- **Efficient handling of large datasets**
- **High-quality AI responses**
- **Context-aware conversations**

---

_This project demonstrates advanced chatbot techniques for educational data querying._
