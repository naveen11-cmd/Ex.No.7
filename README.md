# Exno.7-Develop a prompt-based application tailored to their personal needs, fostering creativity and practical problem-solving skills while leveraging the capabilities of large language models.
# Register no: 212224060172
# Name : Naveen Krishna S

# Aim

To develop a prompt-based application using a Large Language Model to provide personalized assistance for academic planning, learning support, idea generation, and practical problem-solving.

---

# AI Tools Required

ChatGPT

---

# Project Used

## STUDYGENIE – AI-Powered Personal Study Assistant

STUDYGENIE is a prompt-based AI application designed to help students organize their academic activities and improve their learning process.

The application accepts a student's subject, topic, available study time, difficulty level, and learning requirements. The LLM then generates a personalized study plan, explanations, practice questions, and revision suggestions.

---

# Explanation

A prompt-based application communicates with a Large Language Model using carefully designed instructions.

The STUDYGENIE application can perform tasks such as:

* Create personalized study schedules
* Explain difficult topics
* Generate practice questions
* Summarize study topics
* Suggest revision methods
* Generate quiz questions
* Provide project ideas
* Identify weak areas
* Recommend learning strategies
* Create short notes

The experiment demonstrates how improving the prompt can produce more useful and personalized AI responses.

---

# Problem Statement

Develop a prompt-based personal study assistant that accepts a student's learning requirements and generates a customized academic plan using a Large Language Model.

The application should understand the student's requirements and provide useful learning content based on the available time, subject, difficulty level, and learning goal.

---

# Prompt-Based Application

The application is designed as an **AI Personal Study Assistant**.

### Input

The user provides:

* Subject
* Topic
* Available study time
* Current knowledge level
* Learning goal
* Preferred learning method

### Processing

```text
User Requirements
       ↓
Prompt Construction
       ↓
Large Language Model
       ↓
Personalized Analysis
       ↓
Study Plan / Learning Content
       ↓
Student
```

### Output

The application generates:

* Personalized study plan
* Topic explanation
* Important concepts
* Practice questions
* Revision schedule
* Learning tips
* Quiz questions

---

# Procedure

1. Identify a student's academic requirement.
2. Define the input information.
3. Create a basic prompt.
4. Execute the prompt using an LLM.
5. Observe the generated response.
6. Improve the prompt by adding personal context.
7. Add a specific role for the AI.
8. Add constraints and output requirements.
9. Compare the responses.
10. Create a final refined prompt.
11. Evaluate the usefulness of the final response.

---

# Selected  Scenario


The Python program is:

    def study_plan(subject, topic):
        return f"Study {topic} in {subject}, practice problems, and revise."

    subject = "Digital Electronics"
    topic = "Karnaugh Maps"

    print(study_plan(subject, topic))


Output:



Study Karnaugh Maps in Digital Electronics, practice problems, and revise.









A student has the following requirements:

| Requirement    | Details                          |
| -------------- | -------------------------------- |
| Subject        | Digital Electronics              |
| Topic          | Karnaugh Map                     |
| Available Time | 2 hours                          |
| Level          | Intermediate                     |
| Goal           | Exam preparation                 |
| Requirement    | Explanation + practice questions |


---

# Prompt 1 – Simple Prompt

## Prompt

```text
Create a study plan for learning Karnaugh Maps in 2 hours.
```

## Output

```text
2-Hour K-Map Study Plan

1. Learn the basics – 30 minutes
2. Study K-Map rules – 30 minutes
3. Solve examples – 30 minutes
4. Practice problems – 20 minutes
5. Quick revision – 10 minutes
```

### Observation

The simple prompt provides a basic schedule but does not consider the student's knowledge level or specific learning needs.

---

# Prompt 2 – Context-Based Prompt

## Prompt

```text
I am an engineering student with intermediate knowledge of Digital Electronics.
I have 2 hours to prepare Karnaugh Maps for an upcoming exam.

Create a study plan that includes:
- Basic concepts
- K-Map rules
- Solved examples
- Practice problems
- Final revision
```

## Output

### First 30 Minutes – Concepts

Study:

* Boolean expressions
* SOP and POS
* Minterms and maxterms
* Truth tables

### Next 30 Minutes – K-Map Rules

Learn:

* 2-variable K-Map
* 3-variable K-Map
* 4-variable K-Map
* Grouping rules
* Don't-care conditions

### Next 40 Minutes – Practice

Solve:

* Simple Boolean expressions
* 3-variable problems
* 4-variable problems

### Final 20 Minutes – Revision

Review important rules and solve quick questions.

### Observation

Adding personal learning information makes the response more relevant to the student's requirements.

---

# Prompt 3 – Role-Based Prompt

## Prompt

```text
Act as an experienced Digital Electronics professor and personal
study mentor.

I am an engineering student with intermediate knowledge.
I have exactly 2 hours to prepare Karnaugh Maps for an examination.

Create a focused study plan.

Include:
1. Concepts I should learn first
2. Important K-Map rules
3. Common mistakes
4. Solved examples
5. Practice questions
6. Final revision

Prioritize topics that are important for examinations.
```

## Output

### Step 1 – Fundamentals

Review Boolean algebra, SOP, POS, minterms and maxterms.

### Step 2 – K-Map Rules

Focus on:

* Adjacent cells
* Power-of-two grouping
* Largest possible groups
* Overlapping groups
* Don't-care terms

### Step 3 – Solved Examples

Practice 2-variable, 3-variable and 4-variable K-Maps.

### Common Mistakes

* Making diagonal groups
* Creating groups with incorrect sizes
* Missing possible larger groups
* Incorrectly handling don't-care terms

### Practice

Solve at least five K-Map problems.

### Final Revision

Review grouping rules and important shortcuts.

### Observation

The role-based prompt generates a more focused response because the AI is instructed to act as a subject expert and mentor.

---

# Prompt 4 – Advanced Structured Prompt

## Prompt

```text
You are an AI Personal Study Assistant for engineering students.

Create a personalized 2-hour study plan for Karnaugh Maps.

Student information:
- Academic level: Engineering student
- Knowledge level: Intermediate
- Subject: Digital Electronics
- Topic: Karnaugh Maps
- Available time: 2 hours
- Goal: Examination preparation

Follow these steps:

1. Identify the prerequisite concepts.
2. Divide the available time into learning sections.
3. Prioritize important examination topics.
4. Include short explanations.
5. Include common mistakes to avoid.
6. Provide practice questions.
7. Include a final revision session.
8. Use simple language.
9. Do not include topics outside Karnaugh Maps.
10. Make the plan realistic for exactly 2 hours.

Use this output format:

Study Goal
Prerequisites
Time Schedule
Important Concepts
Common Mistakes
Practice Questions
Final Revision
```

---

# Advanced Prompt Output

## Study Goal

Understand Karnaugh Maps and confidently solve Boolean simplification problems in an examination.

## Prerequisites

Before starting K-Maps, revise:

* Boolean algebra
* Logic gates
* SOP and POS
* Minterms and maxterms

## Time Schedule

| Time        | Activity              |
| ----------- | --------------------- |
| 0–20 min    | Review prerequisites  |
| 20–45 min   | Learn K-Map structure |
| 45–70 min   | Study grouping rules  |
| 70–100 min  | Solve examples        |
| 100–115 min | Practice questions    |
| 115–120 min | Final revision        |

## Important Concepts

* 2-variable K-Map
* 3-variable K-Map
* 4-variable K-Map
* Grouping
* Don't-care conditions
* SOP simplification
* POS simplification

## Common Mistakes

* Incorrect grouping
* Diagonal grouping
* Using invalid group sizes
* Missing larger groups
* Incorrect variable elimination

## Practice Questions

1. Simplify a 3-variable Boolean expression using K-Map.
2. Solve a 4-variable SOP problem.
3. Simplify an expression containing don't-care conditions.

## Final Revision

Spend the final five minutes reviewing grouping rules, common mistakes, and important formulas.

### Observation

The advanced structured prompt provides the most personalized and organized response because it specifies the student's background, available time, goal, restrictions, procedure, and required output format.

---

# Comparison of Prompt Outputs

| Feature            | Simple | Context-Based | Role-Based | Advanced Structured |
| ------------------ | ------ | ------------- | ---------- | ------------------- |
| Basic Study Plan   | Yes    | Yes           | Yes        | Yes                 |
| Personal Context   | No     | Yes           | Yes        | Yes                 |
| Expert Guidance    | No     | No            | Yes        | Yes                 |
| Time Optimization  | Basic  | Good          | Very Good  | Excellent           |
| Common Mistakes    | No     | No            | Yes        | Yes                 |
| Practice Questions | No     | Yes           | Yes        | Yes                 |
| Structured Output  | Basic  | Good          | Very Good  | Excellent           |
| Personalization    | Low    | Medium        | High       | Very High           |
| Overall Usefulness | Good   | Very Good     | Very Good  | Excellent           |

---

# Analysis

The experiment shows that prompt quality directly affects the usefulness of the AI-generated response.

The simple prompt generates only a general study schedule.

The context-based prompt improves the response by providing information about the student's subject, knowledge level, available time, and goal.

The role-based prompt produces more expert-oriented guidance by assigning the AI the role of a Digital Electronics professor and study mentor.

The advanced structured prompt provides the most useful result because it combines personal information, specific instructions, constraints, step-by-step requirements, and a defined output format.

Therefore, the advanced prompt is the most suitable for integration into the STUDYGENIE personal study assistant.

---

# Final Refined Prompt

```text
You are STUDYGENIE, an AI Personal Study Assistant designed for
engineering students.

Analyze the student's learning requirements and create a
personalized study plan.

Student Details:
- Subject: [Subject]
- Topic: [Topic]
- Academic Level: [Level]
- Current Knowledge: [Beginner/Intermediate/Advanced]
- Available Time: [Time]
- Learning Goal: [Goal]

Perform the following:

1. Identify required prerequisite concepts.
2. Prioritize the most important topics.
3. Divide the available time effectively.
4. Explain difficult concepts using simple language.
5. Identify common mistakes.
6. Provide suitable practice questions.
7. Include a revision session.
8. Adapt the plan to the student's knowledge level.
9. Do not include unnecessary topics.
10. Keep the plan realistic and achievable.


```


# Result

The prompt-based **STUDYGENIE – AI Personal Study Assistant** was successfully designed using a Large Language Model.The experiment demonstrated that progressively improving prompts results in more personalized, structured and useful responses.

The final refined prompt can be used as the core prompt for a personal academic assistant that supports study planning, concept learning, revision and practice.

# Conclusion

This experiment demonstrated how Large Language Models can be used to develop personalized prompt-based applications.The quality of the output improved when additional context, role instructions, constraints, personal requirements and structured output formats were added to the prompt.

The developed STUDYGENIE application demonstrates how prompt engineering can transform a general AI chatbot into a practical personal learning assistant that supports creativity, learning and problem-solving.
