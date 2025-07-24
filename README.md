# simple-chatbot

# 🤖 Simple Chatbot in Python with NLP  

🚀 This is a simple chatbot built using **Python** and **NLTK (Natural Language Toolkit)**. It can handle greetings, farewells, small talk, and basic questions using **intent matching and random responses**.  

## 🔹 Features  
✅ Understands user messages using **tokenization & stemming**  
✅ Responds to **greetings, farewells, and small talk**  
✅ Uses **predefined patterns** to generate responses  
✅ Simple, **lightweight rule-based chatbot**  

---

## 📌 Installation  

### Step 1: Clone the Repository  
```bash
git clone https://github.com/yourusername/simple_chatbot.git
cd simple_chatbot

```bash
simple_chatbot/
│── chatbot.py  # Main chatbot script
│── data.py     # Contains chatbot response data

```

## Step 2: Install Dependencies
Make sure you have Python installed (3.7+ recommended). Then, install the required library:
```bash
pip install nltk
```

## 📌 Usage
Run the chatbot script:
```bash
python chatbot.py

```
💬 The chatbot will greet you and wait for your input. To exit, type **exit**.




# 📌 How It Works
## 1️⃣ Text Preprocessing
**Tokenization:** Breaks user input into words.
**Lowercasing:** Converts text to lowercase for consistency.
**Stemming:** Reduces words to their root form (e.g., "running" → "run").
## 2️⃣ Intent Mapping & Response Selection
User messages are compared to predefined patterns.
If a match is found, the chatbot selects a random response from the mapped category.
If no match is found, it returns a fallback response.

# 📂 Project Files
**chatbot.py** (Main Script)
Loads NLTK for text processing
Matches user messages with predefined patterns
Generates a response based on intent recognition
Runs the chatbot in a command-line interface
**data.py** (Response Database)
Contains predefined patterns and responses
Responses are categorized into different intents

# 📌 Example Conversation
```bash
Chatbot: Hello! I'm your friendly chatbot. Type 'exit' to end the conversation.  
You: Hi!  
Chatbot: Hey there! How can I help you today?  
You: How are you?  
Chatbot: I'm just a chatbot, but I'm doing great! 😊  
You: Bye!  
Chatbot: Goodbye! Have a wonderful day!  

```

## 🔥 Future Improvements
✅ Add Machine Learning models for better responses
✅ Use TF-IDF or Word Embeddings for improved text understanding
✅ Integrate with a Flask Web App for a GUI version


## 📌 License
This project is open-source and free to use. Feel free to contribute! 🚀

🔗 Connect with Me:
📧 Email: [aizazahmed1555@gmail.com]
📺 YouTube: [https://www.youtube.com/@yourcareerinit]
