> This document provides extended references, notes, and clarifications used throughout the Coding for Compassion project. It supports transparency and traceability for all conceptual claims and frameworks.

## Update: 2025-04-04 15:50:07

### Feature: Source Footnotes for Online Data

**Overview:**  
In our user-driven research strand, we developed a feature for AI-generated responses that includes footnotes with source links when retrieving data from online sources. This enhances transparency, user trust, and the ability to verify facts independently.

**Context & Development Path:**  
This capability emerged through iterative work within longform conversational threads, with increasing emphasis on accuracy, transparency, and external validation. While not system-wide, it represents an experimental application of retrieval-augmented generation where the footnote format mimics academic or journalistic citation.

**Why It Matters:**  
This approach:
- Allows users to trace specific claims to source material
- Enhances factual reliability and reproducibility
- Models a responsible precedent for AI disclosure practices

**Format Details:**  
Footnotes include:
- [Message index]: e.g., `[3]`
- [Search result index]: e.g., `:13`
- [Link text or description]: e.g., `†source`
- Structured as: `【3:13†source】`

This method supports ethical research workflows, particularly in use cases like grant writing, public documentation, and platform accountability.

---

