+++
title = 'GenAI Days 2023'
date = 2024-08-11T11:19:32+02:00
draft = false
+++

## Talk at GenAI days Paris

The first edition of the Paris GenAI days gatheed many experts that built products and features using Generative AI.
I had the opportunity with may Product Manager Ben Payet to give a talk about how we've built the latest Synthesio feature using Generative AI
and how it impacted the way our clients use our SaaS.

## Video

{{< youtube 9Z8Op-1xeGM >}}

## The feature

The resented feature is Signals GenAI, I am the person who built the first bricks of the groudbreaking feature. This functionnality sits within Synthesio and aims to easethe discovery of insights from sosial data.
Ususally, the users had to "dig hard" to find the insights, to read a lot os social media posts in order to understand the diffents problematics of their clients, about the proucts, companies...
Now with Signals GenAI, actionnable insights are accessible just in a few clicks, and after a few minutes.

Signals GenAI uses a method called Retrieval Augmented Generation, also called RAG, the concept of RAG is very simple. the objective is to anwser a question,
or more generally generate text based content passed in the prommpt of a Language Model.It's mainly composed of 2 main steps:
- **Retrieval** : We first retrieve the most relevant documents that can answer the question. We end up the a top K documents, sorted by relevance.
- **Generation**: We feed the retrieved content into the context alongsie the question to answer / the task to execute.

This allows to bypass language models cutoff date (date of the data used to train the model) and to redue the hallucinations.

Is this I discuss the technicla aspects of our RAG solution, the constrains and challenges we had and how we overcome them.


