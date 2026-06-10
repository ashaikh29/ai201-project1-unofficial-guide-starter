# The Unofficial Guide — Project 1

> **How to use this template:**
> Complete each section *after* you've built and tested the corresponding part of your system.
> Do not write placeholder text — if a section isn't done yet, leave it blank and come back.
> Every section below is required for submission. One-liners will not receive full credit.

---

## Domain

<!-- What topic or category of knowledge does your system cover?
     Why is this knowledge valuable, and why is it hard to find through official channels?
     Example: "Student reviews of CS professors at [university] — useful because official
     course descriptions don't reflect teaching style, exam difficulty, or workload." -->

My system covers the category of knowledge regarding the course Intro to Machine Learning (CS 4375) at UT Dallas. This knowledge is valuable since it is a popular course taken by Computer Science, Data Science, Software Engineering majors, among others. It is also a difficult class for many, so having a system to help students determine which professor to take, how to study for the class is useful for their performance in the class.

---

## Document Sources

<!-- List every source you collected documents from.
     Be specific: include URLs, subreddit names, forum thread titles, or file names.
     Aim for variety — sources that together cover different subtopics or perspectives. -->

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

<!-- Describe your chunking approach with enough specificity that someone else could reproduce it.
     Include:
     - Chunk size (characters or tokens) and why that size fits your documents
     - Overlap size and why (or why not) you used overlap
     - Any preprocessing you did before chunking (e.g., stripping HTML, removing headers)
     - What your final chunk count was across all documents -->

**Chunk size:**

**Overlap:**

**Why these choices fit your documents:**

**Final chunk count:**

---

## Embedding Model

<!-- Name the embedding model you used and explain your choice.
     Then answer: if you were deploying this system for real users and cost wasn't a constraint,
     what tradeoffs would you weigh in choosing a different model?
     Consider: context length limits, multilingual support, accuracy on domain-specific text,
     latency, and local vs. API-hosted. -->

**Model used:**

**Production tradeoff reflection:**

---

## Grounded Generation

<!-- Explain how your system enforces grounding — how does it prevent the LLM from answering
     beyond the retrieved documents?
     Describe both your system prompt (what instruction you gave the model) and any structural
     choices (e.g., how you formatted the context, whether you filtered low-relevance chunks).
     Do not just say "I told it to use the documents" — show the actual instruction or explain
     the mechanism. -->

**System prompt grounding instruction:**

**How source attribution is surfaced in the response:**

---

## Evaluation Report

<!-- Run your 5 test questions from planning.md through your system and record the results.
     Be honest — a partially accurate or inaccurate result that you explain well is more
     valuable than a suspiciously perfect result. -->

| # | Question | Expected answer | System response (summarized) | Retrieval quality | Response accuracy |
|---|----------|-----------------|------------------------------|-------------------|-------------------|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Retrieval quality:** Relevant / Partially relevant / Off-target  
**Response accuracy:** Accurate / Partially accurate / Inaccurate

---

## Failure Case Analysis

<!-- Identify at least one question where retrieval or generation did not work as expected.
     Write a specific explanation of *why* it failed, tied to a part of the pipeline.

     "The answer was wrong" is not an explanation.

     "The relevant information was split across a chunk boundary, so retrieval returned
     only half the context — the model didn't have enough to answer correctly" is an explanation.

     "The embedding model treated the professor's nickname as out-of-vocabulary and returned
     results from an unrelated review" is an explanation. -->

**Question that failed:**

**What the system returned:**

**Root cause (tied to a specific pipeline stage):**

**What you would change to fix it:**

---

## Spec Reflection

<!-- Reflect on how planning.md shaped your implementation.
     Answer both questions with at least 2–3 sentences each. -->

**One way the spec helped you during implementation:**

**One way your implementation diverged from the spec, and why:**

---

## AI Usage

<!-- Describe at least 2 specific instances where you used an AI tool during this project.
     For each: what did you give the AI as input, what did it produce, and what did you
     change, override, or direct differently?

     "I used Claude to help me code" is not sufficient.
     "I gave Claude my Chunking Strategy section from planning.md and asked it to implement
     chunk_text(). It returned a function using a fixed character split. I overrode the
     chunk size from 500 to 200 because my documents are short reviews, not long guides." -->

**Instance 1**

- *What I gave the AI:*
- *What it produced:*
- *What I changed or overrode:*

**Instance 2**

- *What I gave the AI:*
- *What it produced:*
- *What I changed or overrode:*
