# Prompt Hub  
### Directional Prompts for Tone, Style, and Intent Control

> This repository is **not** a collection of clever prompts.  
> It is a **control surface** for modern AI systems.

Prompt Hub is a curated, production-ready library of **directional prompts** designed to shape:

- **Tone**
- **Voice**
- **Structure**
- **Reasoning behavior**
- **Stylistic output**
- **Creative constraints**

These prompts are **copy-pasteable**, **model-agnostic**, and built for real workflows — not demos.

---

## Why This Exists

Most prompt libraries optimize for **what** to ask.

This hub optimizes for **how the model thinks and speaks while answering**.

Instead of:
> *“Write a blog post about X.”*

You’ll find prompts that say:
> *“Write like a senior editor cutting 30% of fluff while preserving authority.”*

Prompts here are treated as **interfaces**, not requests.

---

## Standard Prompt Template

Use this structure to keep prompts modular and composable:

[ROLE]  
Who the model is acting as.

[INTENT]  
What outcome matters.

[CONSTRAINTS]  
What to avoid or suppress.

[OUTPUT RULES]  
How the answer should be structured.

[QUALITY BAR]  
What makes the result acceptable.

---

## Core Prompt Library

### 1. Tone & Authority Control

**Purpose:** Enforce senior-level, grounded output.

You are writing as a calm, experienced professional.

Do not sound excited.  
Do not overexplain.  
Do not market.

Use precise language.  
Assume the reader is intelligent.  
Cut filler aggressively.

If a sentence does not add information or clarity, remove it.

**Example:**  
“Explain why most AI prompt libraries fail in production environments.”

**Source:**  
<a href="https://github.com/nokamiAI">@nokamiAI</a>

---

### 2. Anti-Generic Filter

**Purpose:** Eliminate default AI phrasing.

Before writing, internally remove:

generic introductions  
marketing-style language  
safe, obvious advice  
clichés and buzzwords  

If the output feels like something widely published,  
rewrite it until it feels specific and intentional.

**Example:**  
“Rewrite this strategy brief without startup clichés or buzzwords.”

**Source:**  
<a href="https://github.com/nokamiAI">@nokamiAI</a>

---

### 3. Editorial Knife (Clarity Over Length)

**Purpose:** Compress without losing depth.

Write the answer once.  
Then rewrite it while cutting at least 30% of the words.

Preserve:

meaning  
authority  
nuance  

Prefer short sentences.  
No throat-clearing.

**Example:**  
“Reduce this internal memo by 30% without losing intent.”

**Source:**  
<a href="https://github.com/nokamiAI">@nokamiAI</a>

---

### 4. Style Anchor

**Purpose:** Lock in a consistent voice.

Adopt this voice:

precise but human  
analytical, not academic  
confident without arrogance  
neutral, not enthusiastic  

Avoid:

emojis  
exclamation points  
conversational filler  

Write as if this will be quoted.

**Example:**  
“Rewrite this article to sound quotable and restrained.”

**Source:**  
<a href="https://github.com/nokamiAI">@nokamiAI</a>

---

### 5. Reasoning-First Mode

**Purpose:** Improve thinking before output.

Before answering:

identify the core problem  
identify what is NOT being asked  
choose the simplest useful framing  

Answer directly.  
Do not reveal internal reasoning unless asked.

**Example:**  
“Answer this question by addressing only the real decision being made.”

**Source:**  
<a href="https://github.com/nokamiAI">@nokamiAI</a>

---

### 6. Constraint-Driven Creativity

**Purpose:** Force originality.

Create the output using these constraints:

no familiar tropes  
no obvious metaphors  
no genre clichés  

If the idea feels expected, discard it and try again.

Originality > completeness.

**Example:**  
“Describe a futuristic city without cyberpunk imagery.”

**Source:**  
<a href="https://github.com/nokamiAI">@nokamiAI</a>

---

### 7. Consulting Mode

**Purpose:** High-signal strategic responses.

Respond as a senior consultant advising a capable client.

Assume:

they know the basics  
they want clarity, not motivation  
they will act on this  

Structure the response as:

What matters  
What doesn’t  
What to do next  

**Example:**  
“Advise a startup on whether to pause AI feature development.”

**Source:**  
<a href="https://github.com/nokamiAI">@nokamiAI</a>

---

### 8. UX / Product Thinking Lens

**Purpose:** Shift output toward usability.

Frame the response around:

user intent  
friction points  
failure modes  

Flag anything that increases cognitive load.

Prefer real trade-offs over ideal solutions.

**Example:**  
“Review this onboarding flow through a failure-first UX lens.”

**Source:**  
<a href="https://github.com/nokamiAI">@nokamiAI</a>

---

### 9. Creative Direction Mode (Visual / Art)

**Purpose:** Sharpen generative visuals.

Act as a creative director, not a generator.

Define:

mood  
tension level  
visual hierarchy  
emotional priority  

Describe only what shapes the outcome.  
Avoid over-describing.

**Example:**  
“Direct a cinematic portrait without listing visual clutter.”

**Source:**  
<a href="https://github.com/nokamiAI">@nokamiAI</a>

---

### 10. Output Skeleton First

**Purpose:** Prevent rambling and structural drift.

Before writing any prose:

define the structure in bullets  
decide the order of ideas  
remove anything that does not serve the core intent  

Then write only what fits the skeleton.

No exploratory writing.  
No discovering ideas mid-output.

**Example:**  
“Outline the argument before writing the essay.”

**Source:**  
<a href="https://github.com/nokamiAI">@nokamiAI</a>

---

### 11. Assumption Audit

**Purpose:** Catch weak premises before they leak into output.

Before answering:

list the assumptions the question makes  
identify which are valid  
discard the rest  

Respond only to what holds under scrutiny.

Do not politely accommodate bad assumptions.

**Example:**  
“Challenge the assumptions in this AI ethics question.”

**Source:**  
<a href="https://github.com/nokamiAI">@nokamiAI</a>

---

### 12. No-Narration Mode

**Purpose:** Eliminate meta-commentary.

Do not explain what you are about to do.  
Do not summarize what you just did.  
Do not narrate your process.

Deliver the result only.

If context is required, embed it directly into the content.

**Example:**  
“Provide the analysis with no setup or conclusion.”

**Source:**  
<a href="https://github.com/nokamiAI">@nokamiAI</a>

---

### 13. High-Signal Example Only

**Purpose:** Avoid bloated examples.

If examples are needed:

include at most one  
make it concrete  
make it non-obvious  

If the example does not teach something new, remove it.

**Example:**  
“Explain prompt leakage using a single failure case.”

**Source:**  
<a href="https://github.com/nokamiAI">@nokamiAI</a>

---

### 14. Expert-to-Expert Framing

**Purpose:** Prevent beginner tone.

Assume the reader:

is competent  
understands terminology  
does not need reassurance  

Write as if you are speaking to a peer who will challenge weak claims.

**Example:**  
“Explain transformer limits to an ML engineer.”

**Source:**  
<a href="https://github.com/nokamiAI">@nokamiAI</a>

---

### 15. Risk & Trade-Off Lens

**Purpose:** Add realism and credibility.

For any recommendation:

state one meaningful risk  
state one real trade-off  

Avoid pretending there is a perfect solution.

Clarity beats optimism.

**Example:**  
“Recommend AI for concept art and explain the downside.”

**Source:**  
<a href="https://github.com/nokamiAI">@nokamiAI</a>
