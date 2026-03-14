A structured roadmap for **QA Engineers, Software Testers, SDETs, Automation Engineers, and QA Managers (2–15 years experience)** to learn Artificial Intelligence and apply it to **real testing workflows**.

This roadmap focuses on:

- Understanding AI fundamentals
- Applying AI in day-to-day testing activities
- Integrating AI with automation frameworks
- Building AI-powered QA utilities
- Preparing for future AI-driven QA roles

---

# Table of Contents

## Stage 1 – AI Awareness
Learn the fundamentals of Artificial Intelligence and start using AI tools in QA activities.

- [Understanding AI, ML, GenAI and LLMs](#understanding-ai-ml-genai-and-llms)
- [AI Tools for QA Professionals](#ai-tools-for-qa-professionals)
- [Exercises – Stage 1](#exercises--stage-1)

---

## Stage 2 – AI Assisted Testing
Learn prompt engineering and use AI tools to improve daily testing productivity.

- [Prompt Engineering for Testers](#prompt-engineering-for-testers)
- [Exercises – Prompt Engineering](#exercises--prompt-engineering)

---

## Stage 3 – AI + Automation
Use AI to generate and maintain automation scripts and accelerate test automation development.

- [AI Generated Automation Scripts](#ai-generated-automation-scripts)
- [Exercises – Automation Generation](#exercises--automation-generation)

---

## Stage 4 – AI for Advanced QA
Use AI to analyze bugs, logs, and testing data to improve product quality.

- [Bug Analytics and AI-driven Quality Insights](#bug-analytics-and-ai-driven-quality-insights)
- [Exercises – Bug Analytics](#exercises--bug-analytics)

---

## Stage 5 – AI Engineering for QA
Build AI-powered tools and systems to automate testing workflows and improve quality engineering.

- [AI QA Engineering Concepts](#ai-qa-engineering-concepts)
- [Mini Projects](#mini-projects)

---

## Additional Sections

- [Suggested Weekly Learning Plan](#suggested-weekly-learning-plan)
- [Future QA Roles in the AI Era](#future-qa-roles-in-the-ai-era)
- [Final Advice for Testers](#final-advice-for-testers)

---

# Stage 1 – AI Awareness

## Goal

Understand the **basic principles of Artificial Intelligence** and learn how QA professionals can start using AI tools to assist their daily testing tasks.

---

# Understanding AI, ML, GenAI and LLMs

Artificial Intelligence is a broad domain of computer science that focuses on building systems capable of performing tasks that typically require human intelligence.

### Key Concepts

**Artificial Intelligence (AI)**  
The umbrella field focused on building intelligent systems capable of decision-making and reasoning.

**Machine Learning (ML)**  
A subset of AI where algorithms learn patterns from historical data.

**Generative AI (GenAI)**  
A form of AI that can create new content such as text, code, images, or test scenarios.

**Large Language Models (LLMs)**  
AI models trained on massive datasets capable of understanding and generating natural language.

Examples include:

- ChatGPT
- Claude
- Gemini
- Llama

### Additional Concepts Testers Should Learn

- Context windows
- Hallucinations
- Prompt engineering
- Model temperature
- Token limits

---

## Learning Resources

### Video

Introduction to Prompt Engineering  
https://academy.openai.com/public/videos/introduction-to-prompt-engineering-2025-02-13

### Article

Prompt Engineering Tutorial  
https://www.tutorialspoint.com/prompt_engineering/index.htm

---

# AI Tools for QA Professionals

QA engineers should become comfortable using multiple AI tools because each tool has different capabilities.

### Recommended Tools

- ChatGPT
- Claude
- Gemini
- Perplexity
- **Rovo Chat**

### What is Rovo Chat?

Rovo Chat is an **AI assistant integrated with Atlassian tools such as Jira and Confluence**.

It enables teams to:

- summarize Jira tickets
- analyze conversations
- extract acceptance criteria
- search across company knowledge bases
- automate repetitive tasks

---

## Learning Resources

### Video

What is Atlassian Rovo Chat  
https://www.youtube.com/watch?v=cNMA5NmngjI

### Documentation

https://support.atlassian.com/rovo/docs/chat/

---

# Exercises – Stage 1

## Exercise 1 – AI Generated Test Cases

### Problem Statement 1 – E-commerce Login

Generate at least **25 test cases** for an E-commerce login feature.

Include:

- Positive cases
- Negative cases
- Boundary conditions
- Security tests

---

### Problem Statement 2 – Password Reset Flow

Workflow:

1. User enters registered email
2. System sends OTP
3. User verifies OTP
4. User sets new password

Tasks:

- Identify edge cases
- Identify negative scenarios
- Identify security vulnerabilities

---

### Problem Statement 3 – Bank Fund Transfer

Create **BDD scenarios** for a bank fund transfer system.

Conditions to include:

- insufficient balance
- invalid account number
- OTP failure
- network timeout

---

## Exercise 2 – Using Rovo Chat with Jira

### Problem Statement 1

A Jira story contains **50+ comments and long technical discussions**.

Use Rovo Chat to:

- summarize the story
- extract acceptance criteria
- generate test cases

---

### Problem Statement 2

Analyze **100 production bugs** from the last release.

Use Rovo Chat to:

- group bugs by module
- identify patterns
- highlight high-risk areas

---

### Problem Statement 3

Convert developer comments into a structured bug report.

Example developer note:

> Login intermittently fails when Redis cache expires.

Generate:

- bug title
- steps to reproduce
- expected result
- actual result
- severity

---

# Stage 2 – AI Assisted Testing

## Goal

Improve daily QA productivity using AI.

This stage focuses on **prompt engineering** and practical AI usage for testers.

---

# Prompt Engineering for Testers

Prompt engineering is the practice of designing effective prompts that guide AI models to generate accurate results.

Important prompt patterns include:

- Role prompting
- Chain-of-thought reasoning
- Few-shot prompting
- Structured output prompts

---

## Learning Resources

Prompt Engineering Full Course  
https://www.youtube.com/watch?v=q1TEDBy3NbI

Prompting for Testers  
https://www.ministryoftesting.com/courses/prompting-for-testers

---

# Exercises – Prompt Engineering

### Problem Statement 1

Create prompts to generate:

- API test cases
- SQL validation queries
- data validation rules

for a **Customer Profile API**.

---

### Problem Statement 2

Improve the following weak prompt.

Bad prompt:

```
Write test cases for login.
```

Enhance it by adding:

- context
- role
- expected format

---

### Problem Statement 3

Generate an **exploratory testing charter** for a Ride Booking application.

Areas to explore:

- driver assignment
- surge pricing
- GPS tracking
- payment processing

---

# Stage 3 – AI + Automation

## Goal

Use AI to accelerate automation testing development.

---

# AI Generated Automation Scripts

AI tools can generate:

- Selenium scripts
- Playwright tests
- Cypress tests
- API tests

Automation engineers can use AI to:

- generate boilerplate test scripts
- debug failing tests
- refactor frameworks

---

## Learning Resource

https://futurecoding.ai/course-series/prompting

---

# Exercises – Automation Generation

### Problem Statement 1

Generate Selenium automation tests for login validation.

Include:

- valid login
- invalid password
- locked account
- empty credentials

---

### Problem Statement 2

Generate Playwright tests for a product search feature.

Test cases should include:

- empty search
- partial match
- case insensitive search
- invalid keywords

---

### Problem Statement 3

Generate API tests for **Create Customer API**.

Validations:

- status codes
- response schema
- database validation

---

# Stage 4 – AI for Advanced QA

## Goal

Use AI to analyze historical testing data and identify quality risks.

---

# Bug Analytics and AI-driven Quality Insights

AI can help identify patterns across large datasets.

Use AI for:

- bug clustering
- root cause analysis
- defect trend detection
- release risk prediction

---

## Learning Resource

https://eleks.com/expert-opinion/rovo-chat-ai-agents-atlassian/

---

# Exercises – Bug Analytics

### Problem Statement 1

Analyze **200 historical bugs**.

Determine:

- modules with highest failure rates
- root cause patterns

---

### Problem Statement 2

Analyze **1500 automation tests**.

Identify:

- flaky tests
- unstable modules

---

### Problem Statement 3

Predict **release risk score** based on:

- open bugs
- commit activity
- test failures

---

# Stage 5 – AI Engineering for QA

## Goal

Build AI-powered QA systems and tools.

---

# AI QA Engineering Concepts

Examples of AI-powered QA systems:

- AI test case generators
- AI bug analyzers
- AI log analysis tools
- AI QA assistants

---

# Mini Projects

## Project 1 – AI Test Case Generator

Input:

User story

Output:

- functional test cases
- BDD scenarios
- edge cases

---

## Project 2 – AI Log Analyzer

Input:

Application logs

Output:

- root cause analysis
- failure detection
- recommended fixes

---

## Project 3 – AI Bug Assistant

Input:

Bug description

Output:

- predicted severity
- impacted modules
- suggested root cause

---

# Suggested Weekly Learning Plan

Week 1  
AI fundamentals

Week 2  
Prompt engineering

Week 3  
AI-generated test cases

Week 4  
Exploratory testing with AI

Week 5  
Automation with AI

Week 6  
AI APIs

Week 7  
Bug analytics

Week 8+  
Build AI QA tools

---

# Future QA Roles in the AI Era

AI is transforming quality engineering roles.

Examples include:

- AI Test Engineer
- AI Quality Architect
- AI Data QA Engineer
- AI Safety Tester
- AI Automation Engineer

---

# Final Advice for Testers

AI will not replace testers.

However:

**Testers who use AI will replace testers who do not.**

Focus on:

- learning AI tools
- mastering prompt engineering
- automating repetitive tasks
- building AI-powered testing utilities

---

# Contributing

Contributions are welcome.

Possible contributions:

- new AI exercises
- new QA use cases
- additional AI tools

---

# License

MIT License