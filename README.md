# DWM-exp11

As Reviews.csv file is too big so i can't upload here but you might fet from kaggel


## Table of Contents
- What is Text Summarization in NLP?
- Introduction to Sequence-to-Sequence (Seq2Seq) Modeling
- Understanding the Encoder – Decoder Architecture
- Limitations of the Encoder – Decoder Architecture
- The Intuition behind the Attention Mechanism
- Understanding the Problem Statement
- Implementing a Text Summarization Model in Python using Keras
- What’s Next?
- How does the Attention Mechanism Work?


### What is Text Summarization in NLP?
Ans:

Automatic text summarization is the task of producing a concise and fluent summary while preserving key information content and overall meaning

There are broadly two different approaches that are used for text summarization:

- Extractive Summarization
- Abstractive Summarization

![image](https://user-images.githubusercontent.com/54675828/138045627-5eeba2b1-7983-4e72-b9db-9a6b27bbc1f2.png)


#### Extractive Summarization

The name gives away what this approach does. We identify the important sentences or phrases from the original text and extract only those from the text. Those extracted sentences would be our summary. The below diagram illustrates extractive summarization:


![image](https://user-images.githubusercontent.com/54675828/138047355-a4292856-21b9-4254-9775-e59ec04a1c7f.png)

#### Abstractive Summarization
This is a very interesting approach. Here, we generate new sentences from the original text. This is in contrast to the extractive approach we saw earlier where we used only the sentences that were present. The sentences generated through abstractive summarization might not be present in the original text:


![image](https://user-images.githubusercontent.com/54675828/138047463-c3f74595-dfe4-462f-8295-a1b6ac6390fc.png)



