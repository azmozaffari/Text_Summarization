# Text_Summarization


## Overview
The summarization approaches in the literature are divided into two main branches:

### 1- Extractive summarization
In this group of methods, the LLM decides which sentence is importatnt in the text and highlight that instead of rephrasing the text.

### 2- Abstractive summarization: 
 In this group of methods, the text is divided into chunks and later each chunk is shortened then combined with other chunks' outputs , and rephrased to make the final output.

The implemented code in this project addresses the abstractuve summarization for a long text.

I have used langchain and huggingface libraries to implement the chunking algorithm and use the summarization pipeline to summarize and lated combine the chunks to make the final output.
