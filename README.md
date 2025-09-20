# NLP Tasks

This repository contains **Python notebooks** for various **Natural Language Processing (NLP) tasks**.  

---

## Contents

### 1. Text Preprocessing with Python
**Notebook:** [NLP_TASK1.ipynb](https://github.com/sonamansuryan/NLP/blob/main/NLP_TASK1.ipynb)  

This task demonstrates **basic text preprocessing** steps for NLP:

1. **Tokenization** – Split text into individual words.  
2. **Lowercasing** – Convert tokens to lowercase.  
3. **Punctuation Removal** – Remove punctuation from tokens.  
4. **Stop Word Removal** – Filter out common words like "the", "and", "is", etc.  
5. **Stemming** – Apply a simple rule-based stemmer for common suffixes (`ing`, `ed`, `s`).  
6. **Lemmatization (Bonus)** – Map tokens to base forms using a dictionary.  

**Focus:** Cleaning, normalizing, and preparing raw text for further NLP analysis.

---

### 2. Regex Practice in Python
**Notebook:** [NLP_TASK1.ipynb](https://github.com/sonamansuryan/NLP/blob/main/NLP_TASK2.ipynb)  

This task includes **10 regex-based problems**:

1. **Extract Email Addresses** – Find all emails in text.  
2. **Validate Phone Numbers** – Check `xxx-xxx-xxxx` format.  
3. **Extract Dates** – Identify dates in `dd/mm/yyyy` or `dd-mm-yyyy`.  
4. **Find Repeated Words** – Count occurrences of words in a text.  
5. **Extract Hashtags** – Identify hashtags from social media text.  
6. **Validate Password Strength** – Check for minimum length, uppercase, lowercase, digits.  
7. **Extract URLs** – Find HTTP/HTTPS links.  
8. **Replace Multiple Spaces** – Normalize multiple spaces to single spaces.  
9. **Extract Quoted Text** – Retrieve text enclosed in quotes.  
10. **Validate IP Addresses** – Detect valid IPv4 addresses.  

*Focus:* Regex pattern matching, searching, and substitution for text analysis.

---

### 3. Coachella Tweets Data Cleaning
**Notebook:** [NLP_TASK1.ipynb](https://github.com/sonamansuryan/NLP/tree/main/NLP_TASK3)  

This task demonstrates **cleaning and extracting information from social media tweets**:

1. **Upload CSV & Create DataFrame** – Load tweet data with `pandas`.  
2. **Extract Hashtags** – Identify hashtags in each tweet.  
3. **Extract Emails** – Find email addresses mentioned.  
4. **Remove Usernames** – Delete mentions starting with `@`.  
5. **Remove Links** – Remove URLs starting with `http(s)://`.  
6. **Remove Non-ASCII Symbols** – Keep only standard ASCII characters.  
7. **Convert to Lowercase** – Normalize text.  
8. **Remove Stop Words** – Filter out common English stopwords (`nltk`).  
9. **Remove Digits** – Eliminate numbers.  
10. **Remove Special Characters** – Remove punctuation and symbols.  
11. **Save Cleaned Data** – Export cleaned tweets, hashtags, and emails to CSV.  

*Focus:* Cleaning and normalizing social media text for further text analysis.

---

**Summary:**  
This repository provides a **comprehensive introduction to text preprocessing, regex, and data cleaning**, suitable for **students, beginners in NLP, and anyone practicing text analysis with Python**.
