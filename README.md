Build an AI RAG Assistant Using LangChain
Project tasks and deliverables

Scenario
Imagine you work as a consultant for Quest Analytics, a small but fast-growing research organization.

In today’s fast-paced research environment, the sheer volume of scientific papers can be overwhelming, making it nearly impossible to stay up-to-date with the latest developments. 

The researchers at Quest Analytics have been struggling to find the time to examine countless documents, let alone extract the most relevant and insightful information. 

You have been hired to build an AI RAG assistant that can read, understand, and summarize vast amounts of data, all in real time. Follow the below tasks to construct the AI-powered RAG assistant to optimize the research endeavors at Quest Analytics.

The LLM used for the following tasks can be ‘mistralai/mixtral-8x7b-instruct-v01’ sourced from watsonx.ai API.

Task 1: Load document using LangChain for different sources (10 points)

(This task corresponds with Exercise 1 in the lab “Load Documents Using LangChain for Different Sources” from Module 1)

Capture a screenshot (saved as pdf_loader) that displays both the code used and the first 1000 characters of the content after loading the paper 
link
. 

Task 2: Apply text splitting techniques (10 points)

(This task corresponds with Exercise 2 in the lab, “Apply text splitting techniques to enhance model responsiveness.”)

Submit a screenshot (saved as ‘code_splitter.png’) that displays the code used to split the following LATEX code and its corresponding results.

latex_text = """

    \documentclass{article}

    \begin{document}

    \maketitle

    \section{Introduction}

    Large language models (LLMs) are a type of machine learning model that can be trained on vast amounts of text data to generate human-like language. In recent years, LLMs have made significant advances in various natural language processing tasks, including language translation, text generation, and sentiment analysis.

    \subsection{History of LLMs}

The earliest LLMs were developed in the 1980s and 1990s, but they were limited by the amount of data that could be processed and the computational power available at the time. In the past decade, however, advances in hardware and software have made it possible to train LLMs on massive datasets, leading to significant improvements in performance.

\subsection{Applications of LLMs}

LLMs have many applications in the industry, including chatbots, content creation, and virtual assistants. They can also be used in academia for research in linguistics, psychology, and computational linguistics.

\end{document}

"""
