# NLP Lab – Unit 1 Programs

This repository contains the Unit 1 lab programs for the **Natural Language
Processing (NLP)** course, implemented in Python using **NLTK** and
**spaCy**. Each program is self-contained, well-commented, and includes a
sample output for reference.

## 📁 Repository Structure

```
NLP-Unit1-Programs/
├── 01_Tokenization/
│   └── tokenization.py
├── 02_Stemming_Lemmatization/
│   └── stemming_lemmatization.py
├── 03_StopWord_Removal/
│   └── stopword_removal.py
├── 04_POS_Tagging/
│   └── pos_tagging.py
├── 05_Parsing_Chunking/
│   └── parsing_chunking.py
├── 06_Named_Entity_Recognition/
│   └── ner.py
├── requirements.txt
└── README.md
```

## 📋 Program List

| S. No. | Program                                                   | Folder |
|--------|------------------------------------------------------------|--------|
| 1 | Tokenization of Sentences and Words using NLTK and spaCy      | `01_Tokenization` |
| 2 | Stemming and Lemmatization on Sample Text                     | `02_Stemming_Lemmatization` |
| 3 | Stop-word Removal from a Document                              | `03_StopWord_Removal` |
| 4 | Part-of-Speech (POS) Tagging of a Given Sentence               | `04_POS_Tagging` |
| 5 | Parsing and Chunking using RegEx and spaCy                     | `05_Parsing_Chunking` |
| 6 | Named Entity Recognition (NER) using spaCy                     | `06_Named_Entity_Recognition` |

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/NLP-Unit1-Programs.git
   cd NLP-Unit1-Programs
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Download the spaCy English model** (needed for programs 1, 4, 5, 6)
   ```bash
   python -m spacy download en_core_web_sm
   ```

4. **Run any program**
   ```bash
   python 01_Tokenization/tokenization.py
   ```
   NLTK data (`punkt`, `stopwords`, `wordnet`, etc.) is downloaded
   automatically the first time each script runs via `nltk.download()`.

## 🧠 Concepts Covered

- **Tokenization** – splitting text into sentences and words.
- **Stemming vs. Lemmatization** – reducing words to root/base forms.
- **Stop-word Removal** – filtering out common, low-information words.
- **POS Tagging** – labeling each word with its grammatical role.
- **Chunking** – grouping tokens into phrases (e.g., noun phrases) using
  regex rules and spaCy's dependency parser.
- **Named Entity Recognition** – detecting real-world entities such as
  people, organizations, locations, and dates.

## 🛠️ Tools & Libraries

- Python 3.x
- [NLTK](https://www.nltk.org/)
- [spaCy](https://spacy.io/)


Submitted as part of the NLP Lab – Unit 1 assignment.
