# Project: Analysis of Dataset - Most Common English Words

## Overview:

This project involves analyzing a dataset of English words, specifically focusing on their length, numerical values, and derived ratios. The dataset is sourced from [enable1.txt](https://github.com/dolph/dictionary/blob/master/enable1.txt) and is loaded into a pandas DataFrame for analysis.

## Dependencies:
Python, Pandas

## Dataset Information:

The dataset contains two main columns:
1. **Value:** Numerical values associated with each word.
2. **Char Count:** The character count (length) of each word.

The total number of entries in the dataset is 172,821.

## Analysis Tasks:

### 1. Descriptive Statistics:

- The dataset's basic statistics include mean, standard deviation, minimum, maximum, and quartiles for both 'Value' and 'Char Count.'

### 2. Specific Queries:

- Identify the value of a specific word: 'microspectrophotometries.'
- Determine the highest possible value of a word.
- Find words with a specific character count and value: 7 characters and a value of 87.
- Identify words with specific values: "pinfish," "glowing," "enfold," "microbrew."
- Determine the word with the maximum value in the dataset.
- Find the most common value and mode in the 'Value' column.
- Identify the shortest word with a specific value: 274.

### 3. Derived Metrics:

- Create a new column, 'Ratio,' representing the 'Value Ratio' (Value/Char Count) for each word.
- Determine the maximum value of the 'Ratio.'
- Identify the word with the highest 'Ratio.'
- Find the number of words with a 'Ratio' of 10.
- Determine the maximum value of words with a 'Ratio' of 10.

### 4. Advanced Queries:

- Identify the lowest character count for words with a specific value: 260.
- Find all words with a character count greater than the average character count.

## Instructions for Running the Code:

1. Ensure you have Python installed on your machine.
2. Install the required libraries using `pip install pandas`.
3. Download the dataset file from [enable1.txt](https://github.com/dolph/dictionary/blob/master/enable1.txt).
4. Adjust the file path in the code to match the location of your downloaded file.
5. Run the code step by step or in its entirety.

## Conclusion:

This project provides insights into the characteristics of common English words, including their lengths, numerical values, and derived ratios. The analysis is performed using the pandas library in Python, and the code is documented for clarity and reproducibility.

Feel free to explore further analyses or modify the code based on your specific requirements.
