# Project Scope Dossier

Outlining the scope of the project and understanding the objectives and pitfalls of development

# Time

As an experienced dev, 100 hours to set up the backend
Consider pricing models for prewritten backend ($500)

# Prompt Engineering

Engineering the AI to output the *most desirable* outcome
The *most desirable* is dependent on the use case: a response to an impact assessment giving reccommendations and filtered to exclude unfit language

`https://platform.openai.com/docs/guides/completion/prompt-design`

# AI model

| OpenAI models include: ||
|-|-|
|GPT-3|Understands and generates natural language |
|Codex|Understands and generates code|
|Content filter|Fine-tuned model which can detect sensitive or unsafe text|

## GPT-3

There are four main models with different levels of power for different use cases:
 gpt-3.5-turbo      Most capable GPT-3.5 model and optimized for chat at 1/10th the cost of text-davinci-003
 text-davinci-003   Most capable model; has best quality, output and instruction-following
 text-curie-001     Faster and lower cost than Davinci
 text-babbage-001   Capable of simple tasks, high speed and low cost
 text-ada-001       Capable of very simple tasks, fastest speed and lowest cost

 Davinci should be used initially to arrive at the desired output
 Any optimisation of models is out of scope
 gpt-3.5-turbo may be closer to the desired output
 It updates and may alter the efficacy of the service

 The use of Content Filter satiates our goal for **safe** text

 # Pricing

 Davinci is the most expensive
 Davinci costs $0.0200 per **token**, while Ada costs only $0.0004 per token
 Prices are per 1000 tokens
 A **token** is a piece of a word, where 1000 tokens is ~750 words 
 One token is ~4 characters, or ~0.75 words

 `https://platform.openai.com/tokenizer`

# Fine-tunes

With fine-tuning, a program can be tailored to specific training data
It is very complex
It may help achieve the desired outcome

# Knowledge

## Basics

-Node.js

-React app

>a react component than inputs a textarea message then performs a fetch request to localhost and gets back a response as a data. message and displays that message in a box below

-Express on the backend

>an express server, in js, which will handle api requests and respond back with a json object it will use a body parser and cors
import OpenAI

-OpenAI API key

## Prompt Engineering

`
prompt: "pretend you are steve jobs. answer with motivational content.

steve: how can i help you?

person: i want motivation

steve: make the ipod smaller!
`

Note in this case, OpenAI would respond in lower case
At this stage, and understanding of impact assessment is necessary

# Long term goals

- token calculation
- login
- pricing and subscription

