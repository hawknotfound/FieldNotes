# Prompts and Workflows

Practical prompting tips and workflows for students using AI tools.

---

## Prompting Basics

### The formula for good prompts

```
Context + Task + Format + Constraint
```

**Example:**
> "I am a first-year engineering student in India. Explain how APIs work (Context). Write a simple explanation suitable for a beginner (Task). Use bullet points and keep it under 200 words (Format). Avoid technical jargon (Constraint)."

### Common mistakes

| Mistake | Fix |
|---|---|
| Being too vague | Add specific context and constraints |
| Asking multiple things at once | One clear request per prompt |
| Not specifying format | Tell it: "table", "bullet points", "code block" |
| Accepting wrong output | Say what is wrong and ask again |
| Not iterating | Treat the first response as a draft |

---

## Student Workflows

### Workflow 1: Learning a new topic

```
Step 1: "Explain [topic] to a beginner in simple terms"
Step 2: "Give me 5 practice problems on [topic]"
Step 3: "Check my solution: [paste solution]"
Step 4: "What are common mistakes in [topic]?"
```

### Workflow 2: Writing an assignment draft

```
Step 1: "Help me outline a 2000-word essay on [topic]"
Step 2: "Write a draft for section 2 about [subtopic]"
Step 3: "Add examples from India for [concept]"
Step 4: "Proofread this for grammar and clarity"
```

**Warning:** Do not submit AI-written assignments as your own. Use AI as a tutor and assistant, not a replacement.

### Workflow 3: Hackathon project scaffolding

```
Step 1: "I want to build [description]. Suggest a tech stack"
Step 2: "Generate boilerplate code for [framework]"
Step 3: "I need to integrate [API]. Show me how"
Step 4: "Debug this error: [paste error]"
Step 5: "Write a README for my project"
```

### Workflow 4: Research paper reading

```
Step 1: "Summarize this paper in 5 bullet points: [paste abstract]"
Step 2: "What is the main contribution of this paper?"
Step 3: "What are the limitations they mention?"
Step 4: "Explain the methodology in simple terms"
```

---

## Prompt Patterns

### Persona pattern
> "You are a senior software engineer at Google. Review my code..."

### Chain-of-thought
> "Think step by step before answering: [question]"

### Few-shot
> "Here are examples of good [output]. Now do the same for [new input]."

### Structured output
> "Return the answer as a JSON object with keys: name, date, description"

### Reverse prompt
> "What questions should I ask to understand [topic] better?"

---

## Tips for Better Results

- **Be specific about the audience** — "explain to a 12th grade student" vs "explain to a PhD researcher"
- **Ask for sources** — "provide links to official documentation"
- **Ask it to critique itself** — "what are the weaknesses in this response?"
- **Provide examples** — gives the model much better context
- **Tell it what to avoid** — "do not use technical jargon" or "do not make up statistics"

---

## Limitations to Keep in Mind

- LLMs can hallucinate — verify facts independently
- They have knowledge cutoffs — may not know recent events
- They are not good at counting, math, or logic puzzles
- Long conversations may lose context
- Code generated may contain bugs — always test
