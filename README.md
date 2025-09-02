# Khitan Vowel Harmony

## Overview
The **Khitan Small Script** (契丹小字, *qìdān xiǎozì*) was one of two writing systems used for the now-extinct Khitan language during the **10th–12th centuries** under the Liao Empire in present-day northeastern China. Alongside the small script, the Khitan people also employed the **Khitan Large Script**, a functionally independent writing system.  

This project implements an **algorithm to separate characters in the Khitan Small Script** based on Peter Z. Revesz’s research, with a focus on **vowel harmony** in phonology.  
> 📄 Accepted at *IDEAS 2020: 24th International Database Engineering & Applications Symposium*.

---

## What is Vowel Harmony?
**Vowel harmony** is a phonological rule requiring vowels within a word to share certain features, such as:
- **Backness** (front vs. back vowels)  
- **Height** (high vs. low vowels)  
- **Roundedness** (lip rounding)  
- **Nasalization**  
- **Advanced/retracted tongue root**  

In Khitan, vowel harmony is typically **long-distance**, where vowels do not need to be adjacent to influence each other. A trigger vowel spreads its feature across the word, affecting the harmony domain.

For more background on Khitan scripts, see Daniel Kane’s *The Kitan Language and Script* (2009).

---

## Data
The `data/` folder contains several **text files** in Khitan Small Script:  
- Written using the **Khitan Small Linear font**, with each character in a separate square for easier analysis.  
- Texts were sourced from Kane (2009) and other references.  
- Another version of the dataset is also available on [Kaggle](https://www.kaggle.com/datasets/reniven/khitan-small-script-database).  

---

## Input Method
If you wish to **type in Khitan Small Script**, check out the companion project:  
👉 [KSS-Input](https://github.com/reniven/KSS-Input) — a custom input method developed for the script.  
