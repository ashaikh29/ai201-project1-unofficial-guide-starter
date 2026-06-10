# Project 1 Planning: The Unofficial Guide

> Write this document before you write any pipeline code.
> Your spec and architecture diagram are what you'll use to direct AI tools (Claude, Copilot, etc.) to generate your implementation — the more specific they are, the more useful the generated code will be.
> Update the Retrieval Approach and Chunking Strategy sections if you change your approach during implementation.
> Update this file before starting any stretch features.

---

## Domain

<!-- What domain did you choose? Why is this knowledge valuable and hard to find through official channels? -->
My system covers the category of knowledge regarding the course Intro to Machine Learning (CS 4375) at UT Dallas. This knowledge is valuable since it is a popular course taken by Computer Science, Data Science, Software Engineering majors, among others. It is also a difficult class for many, so having a system to help students determine which professor to take, how to study for the class is useful for their performance in the class.



---

## Documents

<!-- List your specific sources: URLs, subreddit names, forum threads, or file descriptions.
     Aim for at least 10 sources that together cover different subtopics or perspectives within your domain. -->

| # | Source | Type | URL or file path |
|---|--------|------|-----------------|
| 1 |Reddit- r/utdallas |post: How hard is CS 4375 - Introduction to Machine Learning? |https://www.reddit.com/r/utdallas/comments/m86sy2/how_hard_is_cs_4375_introduction_to_machine/ |
| 2 |Reddit- r/utdallas |post: Having trouble in CS 4375 Machine Learning with Ruozzi | https://www.reddit.com/r/utdallas/comments/16c3hl8/having_trouble_in_cs_4375_machine_learning_with/ |
| 3 |Reddit- r/utdallas |post: CS 4375 Introduction to Machine Learning Difficulty |https://www.reddit.com/r/utdallas/comments/ypvsmb/cs_4375_introduction_to_machine_learning/ |
| 4 |Reddit- r/utdallas |post: Rishabh Iyer or Tahrima Rahman for CS 6375 (4375 UG)?? |https://www.reddit.com/r/utdallas/comments/1jshcq1/rishabh_iyer_or_tahrima_rahman_for_cs_6375_4375_ug/ |
| 5 |UT Dallas Catalog |Official Course Description | https://catalog.utdallas.edu/2025/undergraduate/courses/cs4375|
| 6 |UT Dallas |Course Syllabus: Karen Mazidi |https://dox.utdallas.edu/syl103830 |
| 7 |UT Dallas |Course Syllabus: Feng Chen |https://dox.utdallas.edu/syl149237 |
| 8 |UT Dallas |Course Syllabus: Nicholas Ruozzi |https://personal.utdallas.edu/~nrr150130/cs4375/2025fa/index.html |
| 9 |UT Dallas |Course Syllabus: Anurag Nagar |https://dox.utdallas.edu/syl95444 |
| 10 |Courseicle |Professor Review on Anurag Nagar |https://www.coursicle.com/utdallas/professors/Anurag+Nagar/ |

---

## Chunking Strategy

<!-- How will you split documents into chunks?
     State your chunk size (in tokens or characters), overlap size, and explain why those
     numbers fit the structure of your documents.
     A review-heavy corpus warrants different chunking than a long FAQ. -->

**Chunk size:**

**Overlap:**

**Reasoning:**

---

## Retrieval Approach

<!-- Which embedding model are you using (e.g., all-MiniLM-L6-v2 via sentence-transformers)?
     How many chunks will you retrieve per query (top-k)?
     If you were deploying this for real users and cost wasn't a constraint, what tradeoffs
     would you weigh in choosing a different embedding model — context length, multilingual
     support, accuracy on domain-specific text, latency? -->

**Embedding model:**

**Top-k:**

**Production tradeoff reflection:**

---

## Evaluation Plan

<!-- List your 5 test questions with their expected correct answers.
     Questions should be specific enough that you can judge whether the system's response
     is right or wrong. "What are good dining halls?" is too vague.
     "What do students say about wait times at [dining hall name] during lunch?" is testable. -->

| # | Question | Expected answer |
|---|----------|-----------------|
| 1 | | |
| 2 | | |
| 3 | | |
| 4 | | |
| 5 | | |

---

## Anticipated Challenges

<!-- What could go wrong? Name at least two specific risks with reasoning.
     Consider: noisy or inconsistent documents, missing source attribution, off-topic
     retrieval, chunks that split key information across boundaries. -->

1.

2.

---

## Architecture

<!-- Draw a diagram of your pipeline showing the five stages:
     Document Ingestion → Chunking → Embedding + Vector Store → Retrieval → Generation
     Label each stage with the tool or library you're using.
     You can use ASCII art, a Mermaid diagram, or embed a sketch as an image.
     You'll use this diagram as context when prompting AI tools to implement each stage. -->

---

## AI Tool Plan

<!-- For each part of the pipeline below, describe:
     - Which AI tool you plan to use (Claude, Copilot, ChatGPT, etc.)
     - What you'll give it as input (which sections of this planning.md, which requirements)
     - What you expect it to produce
     - How you'll verify the output matches your spec

     "I'll use AI to help me code" is not a plan.
     "I'll give Claude my Chunking Strategy section and ask it to implement chunk_text()
     with my specified chunk size and overlap" is a plan. -->

**Milestone 3 — Ingestion and chunking:**

**Milestone 4 — Embedding and retrieval:**

**Milestone 5 — Generation and interface:**
