# NLP Homework 1
**Name:** Rishik Vardhan Reddy Ummenthala
**Student ID:** 700777149
**Course:** CS5760 Natural Language Processing  

## Contents

Q1 – Regex patterns  
Q2 – Byte Pair Encoding (manual + code)  
Q3 – Bayes rule explanation  
Q4 – Add-1 smoothing calculations  
Q5 – Tokenization comparison  

All code is written in Python.

---

## Project Overview
This project explores core NLP concepts including regular expressions, 
Byte Pair Encoding (BPE) tokenization, Naive Bayes classification, 
Add-1 smoothing, and tokenization challenges in Telugu language.

---

## The Core Challenge: Telugu Tokenization
Telugu is an agglutinative language where words are composed of a root 
with multiple attached suffixes.

- **పాఠశాలల్లో** (pāṭhaśālallō): "In schools" — contains the root for 
school, plural marker, and locative case suffix.
- **ప్రకటించింది** (prakaṭin̄cindi): "Declared" — includes the verb root 
and tense/gender markers.

---

## Contents

| Question | Topic |
|---|---|
| Q1 | Regular Expression patterns |
| Q2.1 | Manual BPE on toy corpus (3 steps by hand) |
| Q2.2 | Mini BPE Learner in Python |
| Q2.3 | BPE trained on Telugu paragraph |
| Q3 | Bayes Rule explanation |
| Q4 | Add-1 Smoothing calculations |
| Q5 | Telugu Tokenization — Naive vs Manual vs Indic-NLP |

---

## Tokenization Methods Compared

| Method | Token Count | Key Observation |
|---|---|---|
| Naive | 24 | Fails to separate punctuation; keeps suffixes attached |
| Manual | 28 | Splits morphological suffixes like లో and ది |
| Indic-NLP | 27 | Effectively separates punctuation as distinct tokens |

---

## How to Run

```bash
pip install indic-nlp-library nltk
jupyter notebook NLP_HW-1.ipynb
```

All code is written in Python.
