# Multi-Agent-Systems
Designing, developing and deploying multi agent systems

Topics covered in this project:
- Building a Multi Agent System
- Managing AI Agents at different scales (scaling systems)
- Evaluating Agent System's performance

# Module 1
## Foundation of AI Agents
3 Importent Pillars:
1) Easy to Build
2) Reliable
3) Easy to Manage and Scale

### What are AI Agents?
AI Systems that can decide what happens next in order to achieve a goal.
The ability of an LLM to make reasonable choices, instead of just generating content. In short, to have cognition ability.

AI controls the application flow.

Cognition, Real Time, Self Healing (fixes something if it breaks), Self Improvement (learn from what it does)

#### How do AI Agents differ from classic LLMs?
LLMs have an ability to create (write emails, create images, evaluate reports. generate videos)

AI Agents have the ability to decide (what tools and data to use, how to recover from failures)


### Use Cases of AI Agents
Does the use case favor complexity or precision.

Spectrum of Agency:
       LLM -> Agent -> Crew
Low Agency --------> High Agency



## What makes an AI Agent intelligent?

1) Traditional AI Systems:
You have features and labels to train your model on. The more training samples you have, the better the model understands the correlation between the the features and the target variable. 

2) LLMs
Prompt = Features
The prompt that you provide itself act as the features. And the answer provided by the model is the predicted answer or response to the input. 
Hence, better the prompt, better the output you can expect.

Traditional Strongly Typed Software
You know what you provide as an input, you know the transformations and you have a deterministic output.

In agentic systems (LLMs), you can provide any input, the transformations are partially a black box and you can only expect the data that may be outputted.
What goes into the LLM (input) heavily impacts how it responds.


**Context Engineering:**
Deciding the best possible input to get the required output.
Optimizing the input

Components of Context Engineering:
1) System Prompts - provide guidence on how LLMs should behave
2) Clear instructions
3) Role Playing 
4) Memory
5) Tools 

So to create a job listing:
Input: Job Role
Agent Roles: Researcher, Writer, Editor
Output: Job Posting
