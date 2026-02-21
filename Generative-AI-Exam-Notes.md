# Generative AI for Beginners — Complete Exam Notes

> **Course:** Generative AI for Beginners: Fundamentals, Tools & Prompts  
> **Purpose:** Structured exam-prep notes — beginner-friendly, concept-focused, exam-oriented  
> **Note:** All key AI terms are in **bold** and explained simply.

---

## Table of Contents

1. [Introduction & Why It Matters](#1-introduction--why-it-matters)
2. [What is Generative AI?](#2-what-is-generative-ai)
3. [How Large Language Models (LLMs) Work](#3-how-large-language-models-llms-work)
4. [Real-World Use Cases](#4-real-world-use-cases)
5. [Generative AI Tools Landscape](#5-generative-ai-tools-landscape)
6. [Prompting Basics](#6-prompting-basics)
7. [Risks and Ethics](#7-risks-and-ethics)
8. [The Future of AI & Next Steps](#8-the-future-of-ai--next-steps)

---

## 1. Introduction & Why It Matters

### What This Course Is About

This course is designed for complete beginners — no coding, no math, no prior AI knowledge required. The goal is to understand what **Generative AI** is, how it works, how to use it effectively, and how to use it responsibly.

By the end, you should be able to:

- Explain what Generative AI is in simple terms
- Understand how AI systems work at a basic level
- Apply AI tools to real work tasks
- Use **prompting** techniques to get better results
- Understand the risks and ethical considerations

---

### Why Generative AI Matters Today

**Generative AI** has seen the fastest adoption of any technology in history:

- **ChatGPT** reached 100 million users in just **2 months**
- Instagram took 2.5 years, Facebook nearly 5 years to reach the same number

This is not just a trend for tech people. If you write emails, make presentations, analyze data, or communicate with customers, AI has tools that can help you work better and faster.

**Key Mindset:** AI does not replace humans — it _amplifies_ them. Just as spreadsheet software made accountants more powerful (not obsolete), AI makes skilled professionals even more valuable.

> **Example:** Accountants still exist after spreadsheets were invented. In fact, they became more valuable because they could do more complex work faster. The same applies to AI and most professions.

---

## 2. What is Generative AI?

### Simple Definition

**Generative AI** is artificial intelligence that **creates new content** — text, images, audio, video, or code — that did not exist before. The key word is _generative_: it generates (creates) something new.

> **Think of it this way:**  
> A traditional AI is like a smart librarian — it finds existing answers.  
> A **Generative AI** is like a creative collaborator — it creates something new just for you.

---

### Traditional AI vs. Generative AI

| Feature      | Traditional AI                    | Generative AI            |
| ------------ | --------------------------------- | ------------------------ |
| What it does | Analyzes, classifies, or predicts | Creates new content      |
| Example task | "Is this email spam?"             | "Write me a new email"   |
| Output       | A label or a number               | Text, image, code, audio |

---

### Types of Generative AI

- **Text Generation** — Writes emails, articles, summaries, code. Examples: _ChatGPT, Claude, Gemini_
- **Image Generation** — Creates original images from text descriptions. Example: _DALL-E, Midjourney_
- **Audio and Video Generation** — Generates human-like voices, music, video clips. Also behind **deepfakes** (AI-generated fake videos of real people — a major ethical concern)
- **Code Generation** — Writes computer programs based on your description. Example: _GitHub Copilot_

> **Important:** The lines between these types are blurring. Modern AI is becoming **multimodal** — meaning it can work with both text AND images in the same conversation.

---

### Where Generative AI Fits in AI History

Understanding the timeline helps you understand why this is a big deal:

1. **Rule-Based AI (1950s–80s):** Computers follow strict "if this, then that" rules. Rigid and limited.
2. **Machine Learning (1980s–2000s):** Instead of programming every rule, we show the computer thousands of examples and it _learns_ the patterns on its own.
   - Example: Show a computer 10,000 cat photos — it learns what a cat looks like without being told every rule.
3. **Deep Learning (2010s):** Uses **artificial neural networks** — systems loosely inspired by the human brain — to learn very complex patterns. This made image recognition, speech recognition, and translation possible.
4. **Generative AI (2017–present):** Built on deep learning, but now the AI can _create_ new content, not just recognize patterns. The key breakthrough was something called **Transformer Architecture** (2017), which revolutionized how AI processes language.

> **Key Term: Neural Network** — A system of mathematical "layers" that processes information, loosely modeled on how brain neurons connect. You don't need the technical details — just know it's the engine inside modern AI.

> **Key Term: Transformer Architecture** — The specific technical method introduced in 2017 that made modern AI language tools (like ChatGPT) possible.

---

## 3. How Large Language Models (LLMs) Work

### What is a Large Language Model?

A **Large Language Model (LLM)** is an AI system trained on a massive amount of text — billions of words from books, websites, articles, and more — so that it learns how language works.

- **"Large"** = trained on enormous amounts of data, with billions of internal settings called **parameters**
- It has learned which words tend to follow other words, which writing styles fit different contexts, and how to respond to different types of questions

> **Analogy:** Imagine someone who has read almost everything on the internet, in every book, in every newspaper. They've absorbed millions of conversations and writing styles. That's similar to what an LLM does — except through mathematics, not human reading.

> **Critical point:** An LLM does **NOT** think or understand the way we do. It has no emotions or consciousness. It is an extremely sophisticated **pattern-matching** machine.

---

### How an AI Generates an Answer (Step-by-Step)

When you type a question, three things happen:

1. **Input (Tokenization)**
   - Your text is broken into small units called **tokens** (chunks of words or characters)
   - These are converted into numbers because computers work with numbers, not letters

   > **Token** = a small chunk of text. "Hello, how are you?" might become 5–6 tokens.

2. **Processing (Neural Network)**
   - Your tokens pass through the neural network — billions of mathematical calculations across many layers
   - The AI activates the patterns it learned during training that are most relevant to your question

3. **Output (Word-by-Word Generation)**
   - The AI generates its response **one token (word) at a time**
   - It does NOT compose the full answer first — it predicts the next most likely word, then uses that to predict the next word, and so on
   - This is why you sometimes see AI "typing" its response word by word on screen

> **Key insight:** At every step, the AI is calculating **probabilities** — "what word is most likely to come next?" This makes it flexible and creative, but also means it can be confidently wrong.

---

### Key Limitations You Must Know

#### 1. Hallucination ⚠️

**Hallucination** is when an AI confidently states something that is completely false or made up. The AI does not know it is wrong — it just generates what "sounds right" based on patterns.

**Common examples of hallucinations:**

- Citing a research paper that does not exist
- Providing a statistic that sounds reasonable but is fabricated
- Attributing a quote to someone who never said it
- Getting historical dates or facts wrong

**How to protect yourself:**

- Always verify important facts, numbers, dates, and citations
- Never use AI as your sole source of truth
- Treat AI output as a **first draft that needs fact-checking**, not a final answer

#### 2. Bias

AI learns from human-created data — and that data contains human biases. The AI does not have opinions, but it **reflects and reproduces the biases in its training data**.

**Examples:**

- Associating certain professions more with one gender
- Using language that reinforces stereotypes
- Generating examples that lack diversity

**How to address it:** Review AI content critically, especially content about people or groups. Add instructions in your prompts like "use gender-neutral language" or "include diverse examples."

#### 3. Knowledge Cutoff

LLMs are trained on data up to a specific date. After that date, they do not know what happened in the world. Asking about very recent events may produce outdated or incorrect answers.

- Some tools (like Gemini and Perplexity) can search the web for current information — but many cannot
- Always check whether your tool has live internet access

#### 4. Other Limitations

- Can struggle with complex multi-step logical reasoning
- Can give **inconsistent answers** to the same question asked in slightly different ways
- Lacks genuine creativity — it **remixes patterns** rather than inventing truly original ideas
- Has no common sense or real-world understanding

---

## 4. Real-World Use Cases

### Productivity

AI is fastest to prove its value in tasks that are necessary but time-consuming:

- **Writing emails and documents** — Give AI the context, get a first draft in seconds, then revise and personalize
- **Summarizing meetings and reports** — Paste a long document and ask for key bullet points
- **Structuring ideas** — Dump scattered notes and have AI organize them into a logical outline

> **The 60/40 Rule:** AI can take you from 0 to 60% complete very quickly. The final 40% — the part that requires your real expertise, judgment, and personal touch — still comes from you.

---

### Creativity and Ideation

AI is a creative brainstorming partner, not a creative replacement:

- **Brainstorming** — Generate many diverse ideas quickly to overcome creative blocks
- **Drafting initial concepts** — Turn a rough idea into a full first draft to iterate on
- **Stress-testing ideas** — Ask AI to think of objections or different perspectives on your work

> **Honest limitation:** AI generates ideas by remixing patterns from its training. It does not have genuine originality. The best creative work still comes from humans — AI accelerates the early stages.

---

### Business Tasks

Real-world business applications with measurable results:

- **Marketing and Copywriting** — Generate multiple variations of product descriptions, email subject lines, ad copy for A/B testing
- **Customer Support** — Draft initial response templates that agents can personalize, reducing response time from 5 minutes to 1 minute
- **Data Interpretation** — Explain data insights in plain language, suggest analysis approaches for non-data scientists

---

### Practical Case Examples (Key Patterns for Exams)

Three real-world success stories all share the same winning formula:

| Pattern                                           | Why It Matters                                     |
| ------------------------------------------------- | -------------------------------------------------- |
| AI creates the first draft, humans refine it      | Quality is maintained while speed improves         |
| Clear context and instructions are always given   | Vague prompts = vague results                      |
| A defined process is built around AI use          | Structured workflows beat ad-hoc use               |
| Results are measured (time, quality, outcomes)    | Demonstrates real value, enables improvement       |
| Focus is on augmenting humans, not replacing them | People stay responsible; AI just makes them faster |

---

## 5. Generative AI Tools Landscape

### Main Categories of Tools

| Category                       | Description                                                                  | Examples                                                                 |
| ------------------------------ | ---------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| **Chat-Based Tools**           | Conversational AI where you type and it responds — general purpose, flexible | ChatGPT, Claude, Gemini, Perplexity                                      |
| **Integrated Workplace Tools** | AI built directly into software you already use                              | Microsoft Copilot (Office 365), Google Workspace AI, Notion AI, Slack AI |
| **Specialized Tools**          | AI designed for one specific task or industry                                | GitHub Copilot (code), medical imaging AI, legal document analyzers      |

---

### Tool-by-Tool Comparison

#### ChatGPT (by OpenAI)

**Best for:** Creative writing, content generation, brainstorming, explaining complex topics simply, code generation

**Strengths:**

- Very versatile — handles a huge variety of tasks
- Excellent at creative, engaging content
- Strong iterative conversation (each response builds on the last)
- Widely used with a huge community of tutorials

**Limitations:**

- Knowledge cutoff (unless web browsing is enabled)
- Can **hallucinate** confidently
- Can be verbose (over-explains)

**When to use:** Writing compelling copy, brainstorming ideas, drafting documents

---

#### Claude (by Anthropic)

**Best for:** Analyzing long documents, nuanced reasoning, complex instructions, sensitive topics

**Strengths:**

- Handles extremely long documents (up to hundreds of pages)
- More careful, thoughtful, and accurate
- Transparent about uncertainty — more likely to say "I'm not sure" rather than guess
- Maintains consistent tone and style throughout long writing projects

**Limitations:**

- Can be overly cautious or verbose
- May feel slower for simple requests (asks clarifying questions)

**When to use:** Reviewing contracts, analyzing reports, working on complex multi-part projects where accuracy matters most

---

#### Gemini (by Google)

**Best for:** Google Workspace users, research needing current information, multi-modal (text + image) tasks

**Strengths:**

- Deep integration with Gmail, Google Drive, Google Docs, Google Calendar
- Access to **real-time information** through Google Search (no knowledge cutoff problem)
- Can work with both text and images together (**multimodal**)

**Limitations:**

- Less valuable if you don't use Google Workspace
- Integration raises **privacy considerations** — you're giving AI access to your personal data

**When to use:** Research needing current info, tasks spanning your Gmail and Google Drive, image analysis

---

#### Perplexity

**Best for:** Research, fact-checking, finding current information with verifiable sources

**Strengths:**

- Combines AI conversation with **real-time web search**
- Provides **cited sources** for every claim — you can click through and verify
- Has "Focus Modes" to search only academic papers, news, videos, etc.

**Limitations:**

- Not designed for creative writing or content generation
- Cannot analyze your own documents

**When to use:** Any task where accuracy and source verification matter — research, journalism, fact-checking

---

#### DeepSeek

**Best for:** Coding tasks, mathematical reasoning, technical problem-solving

**Strengths:**

- Exceptional performance on technical tasks (code, math, logic)
- **Open-source** model — meaning the underlying code is publicly available
- Often produces production-quality code following best practices

**Limitations:**

- Weaker at creative writing and emotional/conversational warmth
- Smaller community, fewer tutorials compared to ChatGPT
- No ecosystem integration

**When to use:** Writing or debugging code, solving logic or math problems, technical documentation

---

#### Microsoft Copilot (Integrated AI)

**Best for:** Users within the Microsoft 365 ecosystem (Word, Excel, PowerPoint, Outlook, Teams)

**Key advantage — Context:** The AI is already _inside_ your document. In Word, it can read your existing 3 pages and write an executive summary. In Excel, it can create formulas and pivot tables directly in your spreadsheet — not just tell you how.

**Why companies prefer integrated AI tools:**

- **Security** — Your data stays within the company environment, not sent to external servers
- **Convenience** — No new tool to learn; AI appears in familiar software
- **Contextual awareness** — AI acts directly on your data

**Limitations:**

- Usually requires paid subscriptions
- Locked into one vendor's ecosystem
- Less flexible than standalone tools

---

### How to Choose the Right Tool

Ask yourself three questions:

1. **What type of task am I doing?**
   - Creative content → ChatGPT
   - Long document analysis → Claude
   - Research with sources → Perplexity
   - Coding/technical → DeepSeek
   - Real-time information → Gemini or Perplexity

2. **Where is my work happening?**
   - In Microsoft 365 → Copilot
   - In Google Workspace → Gemini
   - Outside these ecosystems → Standalone tool

3. **Accuracy vs. Creativity?**
   - Accuracy and verification matter most → Perplexity or Claude
   - Creative exploration → ChatGPT
   - Technical precision → DeepSeek

> **Beginner tip:** Start with one tool, learn it well, then add a second tool for a specific gap. Most effective AI users have 2–4 tools for different purposes — just like different apps on your phone.

---

## 6. Prompting Basics

### What is a Prompt?

A **prompt** is the instruction you give to an AI — what you type in the chat box.

The most important principle in this entire course:

> **The quality of what you get OUT is directly proportional to the quality of what you put IN.**

**Why prompts matter so much:** AI does not read your mind. It only responds to exactly what you say. Vague prompts activate vague patterns. Specific prompts activate specific patterns.

> **Real-world analogy:** You wouldn't tell a colleague "help me with marketing." You'd say "I need 3 email subject lines for a product launch targeting small business owners, emphasizing time savings, with an urgent but not pushy tone." The same applies to AI — but AI needs even MORE explicit context because it can't ask follow-up questions like a human colleague would.

---

### The 5-Element Prompt Framework

A reliable structure for writing effective prompts every time:

| Element     | What it means                                                                            | Example                                                                      |
| ----------- | ---------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| **Role**    | Tell the AI what persona or expertise to adopt                                           | "You are an experienced marketing consultant..."                             |
| **Context** | Provide the background: Who is involved? What's the situation? What are the constraints? | "...for a small SaaS startup with a $500 budget targeting freelancers..."    |
| **Task**    | The specific thing you want the AI to do — be concrete                                   | "...write 3 email subject lines for our product launch..."                   |
| **Format**  | How you want the output presented (bullet points, table, paragraph, word count)          | "...formatted as a numbered list with a one-line explanation for each..."    |
| **Tone**    | The voice or style: formal/casual, technical/simple, enthusiastic/neutral                | "...with an encouraging, friendly tone suitable for creative professionals." |

**Full example prompt using all 5 elements:**

> _"You are an experienced HR professional. I am writing a job description for a mid-sized tech startup hiring a marketing manager. The role is remote-first and we want to attract diverse candidates. Write a 200-word job description structured with: role overview, key responsibilities, and required skills. Use inclusive, gender-neutral language with a professional but approachable tone."_

> **Note:** You don't need all 5 elements for every prompt. For simple tasks, Task + Format may be enough. Use all 5 when you need high-quality or precise output.

---

### Good vs. Poor Prompts

**Poor prompt:**

> _"Write something about remote work."_

Why it fails: No audience specified. No length. No purpose. No tone. The AI will produce something generic and probably useless.

**Improved prompt:**

> _"Write a 300-word LinkedIn post for HR managers about the top 3 challenges of managing remote teams, with specific examples and an encouraging tone. Format as short paragraphs, not bullet points."_

Why it works: Specific audience, specific length, specific topic, specific number of points, tone given, format given.

---

**Key lesson:** AI never penalizes you for being too specific. You cannot over-communicate. However, under-communicating consistently produces poor results.

> **Prompts are an investment.** Spending 30 extra seconds writing a clear prompt saves you 5 minutes editing a vague response.

---

### Iterating and Improving Results

Even a great first prompt rarely produces a perfect result. The right mindset is:

**AI prompting is a conversation, not a one-shot question.**

**A practical workflow:**

1. Write a solid initial prompt using the framework
2. Evaluate the response critically — is it the right length? Tone? Did it cover everything?
3. Give follow-up instructions to refine

**Useful refinement phrases:**

- "Make this more concise"
- "Expand on the second point"
- "Change the tone to be more formal"
- "Add specific examples"
- "Remove the technical jargon"
- "Give me three alternative versions of this"

**The percentage mindset:**

- First prompt → gets you to ~60%
- 1–2 refinements → gets you to ~90%
- Your own final human polish → 100%

This is always faster than trying to write a perfect prompt that delivers 100% in one shot.

> **Pro tip:** Save prompts that work well. Build a personal library of effective prompts for tasks you do regularly.

---

## 7. Risks and Ethics

### Accuracy and Bias Risks

#### Hallucination (Confident Errors)

Already covered in Section 3, but it is critical enough to repeat:

- **Hallucination** = AI confidently generates false information
- The AI never signals uncertainty — it states fabrications with the same authority as facts
- Common in: citations, statistics, quotes, technical specs, historical details

**Three rules to protect yourself:**

1. **Verify critical information** before using it in any important work
2. **Ask AI to cite sources**, then check them yourself
3. **Use AI for first drafts and brainstorming** — not as a definitive source

#### Bias

AI reflects biases present in its training data. It does not hold opinions, but it can reproduce patterns that are unfair or stereotyped.

**How to address it in prompts:**

- "Use gender-neutral language throughout"
- "Include examples from diverse industries, company sizes, and geographic regions"
- When you notice bias in a response, say: "Rewrite this without gender assumptions"

---

### Data Privacy and Security

**What you should NEVER input into a public AI tool:**

- Passwords, API keys, or login credentials
- Personal identification numbers (Social Security, credit card numbers)
- Confidential business information: unreleased product plans, financial data, customer lists
- Medical records, legal documents with sensitive content
- Anything covered by a Non-Disclosure Agreement (NDA)

**Why?** Public AI tools typically send your input to external company servers, where it may be:

- Used to train future AI models
- Reviewed by human moderators
- Potentially exposed in a data breach

**Important distinction:**

- **Public AI tools** (free ChatGPT, etc.) — Your data may be used for training
- **Enterprise / Corporate AI tools** (company-deployed Copilot, etc.) — Data typically stays inside the company's environment with stronger security guarantees

**Practical anonymization:** If you need AI help with sensitive information, replace real names with placeholders ("Client A", "Employee 1"), remove identifying details, and generalize locations and dates.

> **Quick test:** If the information appearing in tomorrow's newspaper would cause problems for you or your company — don't put it in a public AI tool.

---

### When You Should NOT Use Generative AI

Understanding _when not to use_ AI is just as important as knowing _when to use_ it:

1. **Critical decisions without human expertise**
   - Medical diagnoses, legal judgments, financial investments, hiring decisions
   - AI can _inform_ these decisions, but should **never be the sole decision-maker**

2. **Zero-tolerance-for-error situations**
   - Regulatory filings, academic citations, safety documentation
   - One AI error here can have serious consequences

3. **Work requiring genuine empathy or ethical judgment**
   - Writing a message to a grieving colleague
   - Handling interpersonal conflicts
   - Making ethical decisions in gray areas
   - These require real human understanding and compassion

4. **Regulated professional fields without oversight**
   - Legal, medical, engineering, and accounting work carry professional liability
   - AI can _assist_ professionals — it cannot _replace_ their judgment and accountability

> **The intern analogy:** Think of AI as a very capable intern. Useful for drafting, research, and brainstorming — but always requiring supervision and final judgment from someone with real expertise.

> **Disclosure:** In some contexts (academic work, professional publications), you may be required to disclose that you used AI assistance. Always follow the relevant rules and standards.

---

## 8. The Future of AI & Next Steps

### How Generative AI is Changing Work

The biggest shift: **Human-AI collaboration** is becoming the standard working model.

- AI is automating **routine cognitive tasks** — the predictable, repetitive parts of knowledge work
- This frees humans to focus on **judgment, creativity, relationship-building, and strategic thinking**
- New job titles are emerging: **Prompt Engineer** (a person whose job is to design effective AI interactions)

**The new competitive advantage is not who knows the most facts.** It's who can best combine AI speed and scale with human judgment and contextual understanding.

> **The 20-year analogy:** 20 years ago, being good with computers was a differentiator. Today it's a basic expectation. AI is on the same trajectory — in 5 years, AI competence will be an assumed skill for most office roles.

**The future of work:** Humans with AI vs. Humans without AI. Your goal is to be in the first group.

---

### How to Start Using Generative AI Safely

A practical 6-step roadmap:

1. **Start small and low-stakes** — Experiment with personal projects, casual emails, or article summaries first. Build comfort before using AI for critical work.

2. **Choose one tool and learn it deeply** — Pick ChatGPT, Claude, or another tool and use it consistently for 2 weeks before jumping around.

3. **Apply the 5-element prompting framework** — Role, Context, Task, Format, Tone. Iterate. Save prompts that work.

4. **Always verify before you publish/send** — Fact-check AI claims, dates, statistics. Think of AI output as a first draft requiring expert review.

5. **Observe what works and what doesn't** — Notice which tasks produce great results and which don't. Self-awareness accelerates learning.

6. **Share and learn from others** — Talk with colleagues. Share effective prompts. Collective learning is powerful.

> **Practical habit:** Dedicate 30 minutes per week to trying something new with AI. Week 1: meeting summaries. Week 2: content brainstorming. Week 3: data analysis. Structured experimentation builds broad competence.

---

### Key Takeaways (Must-Know Summary for Exam)

These are the most important ideas from the entire course:

| #   | Key Takeaway                                                                                                                                                                |
| --- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | **Generative AI creates new content** based on patterns learned from massive data. It is powerful but requires human judgment.                                              |
| 2   | **Prompt quality determines output quality.** Specific, context-rich prompts always beat vague ones.                                                                        |
| 3   | **Different tools have different strengths.** Match the tool to the task — don't try to use one tool for everything.                                                        |
| 4   | **AI has real limitations:** hallucinations, bias, knowledge cutoffs, lack of true understanding. Work around them with verification and human oversight.                   |
| 5   | **Use AI responsibly:** protect sensitive data, don't use for critical unaided decisions, be transparent about AI use when required.                                        |
| 6   | **AI amplifies human capability, it doesn't replace human judgment.** The best AI users free themselves for creative and strategic work by letting AI handle routine tasks. |

---

## Quick Reference: Key AI Terms Glossary

| Term                           | Simple Definition                                                                                                       |
| ------------------------------ | ----------------------------------------------------------------------------------------------------------------------- |
| **Generative AI**              | AI that creates new content (text, images, audio, code)                                                                 |
| **Large Language Model (LLM)** | An AI trained on billions of words to understand and generate text                                                      |
| **Token**                      | A small unit of text (part of a word or a whole word) that AI uses internally to process language                       |
| **Parameter**                  | An internal setting in an AI model — there are billions of them, learned during training                                |
| **Hallucination**              | When AI confidently states something false or made-up                                                                   |
| **Bias**                       | When AI reproduces unfair stereotypes or skewed patterns from its training data                                         |
| **Knowledge Cutoff**           | The date after which an AI has no information about world events                                                        |
| **Prompt**                     | The instruction or question you type to an AI                                                                           |
| **Prompt Engineering**         | The skill of writing effective prompts to get better AI outputs                                                         |
| **Multimodal AI**              | AI that can process and generate multiple types of content (e.g., text AND images)                                      |
| **Deep Learning**              | An AI technique using many layers of neural networks to learn complex patterns                                          |
| **Neural Network**             | A mathematical system of interconnected layers, loosely modeled on the human brain, that AI uses to process information |
| **Transformer Architecture**   | The technical breakthrough (2017) that made modern LLMs like ChatGPT possible                                           |
| **Machine Learning**           | Teaching computers to learn patterns from examples rather than programming explicit rules                               |
| **Deepfake**                   | An AI-generated fake video or audio that makes someone appear to say or do something they did not                       |
| **Context Window**             | How much text an AI can "see" and remember in one conversation                                                          |
| **Iteration**                  | The process of refining AI output through follow-up instructions in the same conversation                               |

---

_End of Notes — Good luck on your exam!_
