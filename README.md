# trustlens.ai



## Project Idea: TrustLens AI

**Tagline:** *"Before you trust it, verify it."*

### Problem Statement

People receive hundreds of forwarded messages, videos, images, calls, emails, and articles every day. Most users lack the tools to determine whether the information is trustworthy, manipulated, misleading, or fraudulent.

This leads to:

* Financial scams
* Fake news
* Deepfake videos
* Phishing attacks
* Panic caused by misinformation
* Identity theft

### Solution

A web application that assigns a **Digital Trust Score (0–100)** to any piece of information.

Users can:

* Paste text messages
* Upload images
* Upload videos
* Paste article links
* Analyze call transcripts
* Upload screenshots

The system evaluates credibility and provides explanations.

---

## Core Features

### 1. Text Verification

User pastes:

> "The government is giving ₹50,000 to all citizens. Register now."

AI checks:

* Suspicious language
* Emotional manipulation
* Unsupported claims
* Known scam patterns

Output:

```
Trust Score: 18/100
Risk Level: High

Reasons:
✓ Urgent call-to-action
✓ No official source
✓ Similar scam patterns detected
```

---

### 2. Image Analysis

Upload image.

AI checks:

* Reverse image search (future feature)
* AI-generated image indicators
* Metadata inconsistencies
* Edited regions

Output:

```
Trust Score: 62/100

Potential manipulation detected.
Image appears digitally altered.
```

---

### 3. Video Verification

Upload video.

AI:

* Extracts frames
* Transcribes speech
* Checks for deepfake indicators
* Verifies claims made in video

---

### 4. Article Verification

Paste URL.

AI checks:

* Domain credibility
* Bias indicators
* Fact consistency
* Source transparency

Output:

```
Trust Score: 83/100

Sources cited.
Author information available.
Low misinformation risk.
```

---

### 5. Scam Call Analyzer

Upload recording or transcript.

AI detects:

* Fraud language
* OTP requests
* Bank impersonation
* Urgency tactics

Output:

```
Trust Score: 12/100

Possible Scam:
• Requested OTP
• Claimed bank account suspension
• High-pressure language
```

---

## Trust Score Formula

```
Source Credibility      30%
Evidence Quality        25%
Language Patterns       20%
Fact Consistency        15%
Manipulation Signals    10%
```

Final Score:

```
90-100 → Highly Trustworthy
70-89  → Likely Reliable
50-69  → Uncertain
30-49  → Suspicious
0-29   → High Risk
```

---

## Tech Stack (24-Hour Hackathon Friendly)

### Frontend

* React
* Tailwind CSS

### Backend

* FastAPI or Node.js

### AI

* OpenAI API or open-source LLM
* OCR for screenshots
* Speech-to-text for calls/videos

### Database

* Firebase or Supabase

---

## Unique Feature That Could Impress Judges

### Community Verification Layer

Users can vote:

✔ Verified

❌ Misleading

⚠ Needs Fact Check

The AI score combines with community feedback.

Example:

```
AI Trust Score: 76

Community Confidence:
89% Verified

Final Score:
82
```

---

### Why this could win

Most teams build:

* Chatbots
* Study planners
* Generic AI assistants

This project tackles:

* Fake news
* Deepfakes
* Online scams
* Information trust

These are major global problems, and the demo is easy: upload a suspicious message or image and instantly show a trust score with explanations.

A polished MVP with text + image analysis + trust scoring is completely achievable in 24 hours and can make a memorable hackathon project.
