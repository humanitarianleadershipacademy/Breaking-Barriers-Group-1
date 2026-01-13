---

# Hackathon Briefing Document 2: Opportunity Upload Interface

---

## Challenge Overview

### About the Organisation
The Humanitarian Leadership Academy (HLA) supports over 2 million humanitarians through their digital learning platform, **Kaya**. HLA's mission is to strengthen humanitarian response by connecting learning to real-world action.

### The Problem
There is currently no way to connect learning to real-world action. Partner organisations maintain independent systems for job and volunteering opportunities, with no standardised way to submit or structure this data. This fragmentation prevents learners from discovering relevant opportunities.

**Key limitations today:**
- No APIs or data pipelines link Kaya to external opportunity platforms
- Partner organisations use inconsistent formats and terminology
- Manual data processing is slow and resource-intensive
- No shared identifiers or standardised taxonomy across systems
- Current workflows cannot scale to support global partners

### The Vision: Kaya Match
An AI-powered matching system that links learners with jobs, mentoring, and volunteering opportunities—requiring standardised, structured opportunity data as its foundation.

---

## Your Mission

### Focus
Build an **interface for organisations to submit job/opportunity descriptions**, with automated feature extraction and normalisation to a standardised glossary.

### Objectives
| # | Objective |
|---|-----------|
| 1 | **Simplify opportunity submission** for partner organisations |
| 2 | **Extract key features** (skills required, location, duration, role type) from free-text descriptions |
| 3 | **Normalise extracted data** to a shared competency/skills glossary for consistent matching |

---

## Key Tasks

1. **Design a simple upload interface**
   - Web form OR API endpoint
   - User-friendly for partner organisations

2. **Implement AI-powered feature extraction** from job descriptions using:
   - NLP (Natural Language Processing)
   - GenAI techniques

3. **Map extracted skills/requirements** to a standardised glossary/taxonomy

4. **Handle edge cases:**
   - Variations in terminology
   - Synonyms
   - Ambiguous terms

5. **Output structured, normalised opportunity records** ready for the matching engine

---

## Inputs Provided

| Input | Description |
|-------|-------------|
| Sample job/opportunity descriptions | Real-world style examples for testing |
| Draft skills/competency glossary | Standardised taxonomy to map against |

---

## Expected Outputs

| Deliverable | Description |
|-------------|-------------|
| ✅ Working upload interface prototype | Functional web form or API |
| ✅ Feature extraction pipeline | AI-powered parsing of free-text |
| ✅ Normalisation pipeline | Mapping to standardised glossary |
| ✅ Structured opportunity records | Clean, consistent data ready for matching |

---

## Success Criteria

Your solution should demonstrate:
- Accurate extraction of key fields from unstructured text
- Consistent mapping to the shared skills glossary
- Graceful handling of synonyms and variations
- Clean, structured output suitable for downstream matching
- Intuitive interface for non-technical users

---

## Technical Context

### Role of AI/GenAI
- **NLP/GenAI** to parse free-text job descriptions
- Understand context and meaning, not just keywords
- Intelligently map varied terminology to standardised taxonomy
- Handle real-world messiness in opportunity descriptions

### Integration Point
Your structured output feeds directly into the **AI Matching Engine** (Workstream 1). Consistent, normalised data is essential for accurate matching.

---

## Example Transformation

**Input (free-text):**
> *"We're looking for someone with experience in emergency response, preferably in East Africa. Should be able to train local staff and have strong communication skills. 6-month commitment, remote work possible."*

**Output (structured):**
| Field | Extracted Value |
|-------|-----------------|
| Skills | Emergency Response, Training & Facilitation, Communication |
| Location | East Africa |
| Duration | 6 months |
| Work Type | Remote/Hybrid |
| Role Type | Volunteering/Consultancy |

---

## Why This Matters

> *"Local organisations lack timely access to qualified people because opportunity data isn't structured or connected."*

Your work creates the critical data pipeline that enables the entire Kaya Match vision—turning unstructured opportunity information into actionable, matchable data.

---

**Good luck! Build the bridge between opportunity and action.** 🚀
