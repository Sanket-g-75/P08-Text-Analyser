# P08-Text-Analyser

## Objective
- Extract Textual Data Articles from URL and Perfom Text Analysis

## Analysis
- Positive Score
  - Calculated by assigning +1 for each word if found in the Positive Dictionary and then adding up all the values
- Negative Score
  - Calculated by assigning the value of -1 for each word if found in the Negative Dictionary and then adding up all the values.
- Polarity Score
  - determines if a given text is positive or negative in nature. It is calculated by using the formula: 
    Polarity Score = (Positive Score – Negative Score)/ ((Positive Score + Negative Score) + 0.000001
- Subjectivity Score
  - determines if a given text is objective or subjective. It is calculated by using the formula: 
    Subjectivity Score = (Positive Score + Negative Score)/ ((Total Words after cleaning) + 0.000001)
- Avg. Sentence Length
  - (number of words)/(number of sentences)
- Percentage of Complex Words
  - (number of complex words)/(number of words)
- FOG Index
  - 0.4 * (Average Sentence Length + Percentage of Complex words)
- Avg. No. of Words per Sentence
  - (total number of words)/(total number of sentences)
- Complex Word Count
  - Words in the text that contain more than two syllables
- Word Count
  - Total Cleaned Words
- Syllable per Word
  - Calculated by counting the vowels present in each word
- Personal Pronouns
  - Finding words "I", "we", "my", "ours, "us"
- Avg. Word Length
  - Sum of the total number of characters in each word/Total number of words

