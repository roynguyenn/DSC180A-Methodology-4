# DSC 180A Methodology Assignment 4

**Name:** Royce Nguyen
**Email:** ron005@ucsd.edu  
**Section:** Honda Capstone
**Mentor:** Ryan Lingo

---

**What is the most interesting topic covered in your domain this quarter?**

The most interesting topic covered are knowledgebases. There are so much to evaluate or test out with knowledgebases, a lot of different architectures and implementations of knowledgebases. We have yet to find out which is the "best" but its something we are actively trying out. Lots of models/embeddings lots of ways to retrieve information, different ways of ranking embeddings, different embedding models, RAG methods, and evaluation pipelines. 


**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

I'd like to investigate something adjacent to knowledgebases: agent orchestration. Specifically, I want to see whether using multiple agents (for example, one that rewrites queries, one that retrieves, and one that checks the answer) answers queries better than a single retrieval pipeline, and how to measure that difference.


**What is a potential change you'd make to the approach taken in your current Quarter 1 Project?**

In Q1, we currently have a pipeline where we retrieval documents from a google drive, we then use agents to summarize this information, then we embed the information, then we use a variety of ways to rank that information and use it for the user query. I'd change this by adding extra agents or changing how the existing agent uses the knowledgebase, and by evaluating the options more systematically, so that the whole pipeline lines up around one goal: a tool that is useful and effective for its users.

**What other techniques would you be interested in using in your project?**

I'd be interested in multi-agent orchestration, retrieval evaluation metrics, and long-term memory for personalization. A interesting idea I had in mind is to apply this to a physical setting. A personalized helper robot for elderly or disabled people, backed by a knowledgebase of that person's history and agents that act on it.
