---

# Hackathon Briefing Document 1: AI Matching Engine

---

## Challenge Overview

### About the Organisation
The Humanitarian Leadership Academy (HLA) supports over 2 million humanitarians through their digital learning platform, **Kaya**. HLA's mission is to strengthen humanitarian response by connecting learning to real-world action.

### The Problem
There is currently no way to connect learning to real-world action. Learners complete training but struggle to find relevant jobs, mentoring, or volunteering opportunities, while local organisations cannot easily identify qualified individuals.

**Key limitations today:**
- Data is siloed across multiple disconnected systems
- Manual data collation is slow and resource-intensive
- Current workflows cannot scale to 2M+ users
- No semantic understanding—only basic keyword matching exists
- Insights are generated too late to inform recruitment or response decisions

### The Vision: Kaya Match
An AI-powered matching system that links learners with jobs, mentoring, and volunteering opportunities—turning knowledge into real-world humanitarian impact at scale.

---

## Your Mission

### Focus
Build a **proof-of-concept matching algorithm** that connects learner profiles to opportunities using synthetic data.

### Objectives
| # | Objective |
|---|-----------|
| 1 | Demonstrate **semantic matching** beyond simple keyword searches |
| 2 | Show how skills, experience, aspirations and location can be **intelligently matched** to opportunity requirements |
| 3 | Validate the **feasibility of AI-driven matching at scale** |

---

## Key Tasks

1. **Extract/Process synthetic learner profiles** including:
   - Skills
   - Completed courses
   - Experience
   - Location
   - Interests/aspirations

2. **Extract/Process synthetic opportunity records** including:
   - Jobs
   - Mentoring opportunities
   - Volunteering positions

3. **Develop matching logic** using AI/ML techniques such as:
   - Embeddings
   - Similarity scoring
   - Semantic understanding

4. **Rank and surface "best-fit" matches** with confidence scores

5. **Build a simple output/dashboard** showing match results

---

## Inputs Provided

| Input | Description |
|-------|-------------|
| Synthetic learner dataset | Sample profiles for testing |
| Synthetic opportunity dataset | Sample job/mentoring/volunteering records |
| Standardised skills/competency glossary | Shared taxonomy (aligned with Workstream 2) |

---

## Expected Outputs

| Deliverable | Description |
|-------------|-------------|
| ✅ Working matching prototype | Functional proof-of-concept |
| ✅ Ranked match results | With explainability of why matches were made |
| ✅ Documentation | Approach, logic, and technical decisions |

---

## Success Criteria

Your solution should demonstrate progress toward these metrics:
- **80%** of opportunities generating viable matches
- Measurable improvement over keyword-only matching
- Match accuracy verifiable through human review
- Clear explainability of match reasoning

---

## Technical Context

### Role of AI/GenAI
- Move beyond keyword matching to understand **meaning, skills, and context**
- Identify "best-fit" matches between individuals and opportunities
- Support localisation by surfacing local talent dynamically

### AWS Technology Focus
This prototype will help establish the foundational architecture for HLA's future data ecosystem, including Kaya Signal, AI Chatbots, and Virtual AI Coaching.

---

## Why This Matters

> *"Humanitarians complete training but struggle to find relevant opportunities, while local organisations lack timely access to qualified people."*

Your work will demonstrate how AI can bridge the gap between humanitarian learning and local action—accelerating localisation and strengthening humanitarian response globally.

---

**Good luck! Build something that turns knowledge into impact.** 🚀

---
