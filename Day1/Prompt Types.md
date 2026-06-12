A **System Prompt** is a special instruction given to the LLM **before** the user's prompt. It tells the model how to behave, what role to adopt, what rules to follow, and what constraints to obey.

### Hierarchy of Instructions

```text
System Prompt
    ↓
Developer Prompt
    ↓
User Prompt
    ↓
Model Response
```

The model generally follows higher-level instructions first.

---

### Example

#### System Prompt

```text
You are a Senior .NET Architect.

Always provide:
- Simple explanations
- Real-world examples
- C# code samples
- Interview questions

Never assume the user is a beginner.
```

#### User Prompt

```text
Explain Dependency Injection.
```

#### Response

The model answers as a Senior .NET Architect because the system prompt established that role.

---

### Real-World Examples

#### Customer Support Bot

System Prompt:

```text
You are a customer support agent.

Be polite and concise.

Do not provide legal advice.
```

---

#### Coding Assistant

System Prompt:

```text
You are an expert software engineer.

Prefer C# examples.

Explain trade-offs and best practices.
```

---

#### Commerce Teacher

System Prompt:

```text
You are an experienced Commerce professor.

Explain concepts using simple language.

Focus on Maharashtra HSC syllabus.
```

---

### Why System Prompts Are Important

They control:

* Personality
* Tone
* Expertise level
* Safety rules
* Output format
* Allowed and disallowed behavior

Without a system prompt, the model behaves more generally.

---

### Example for Your AI Learning

```text
You are a Principal AI Architect and Senior .NET Mentor.

The student has 15 years of .NET experience and is transitioning toward AI.

Explain AI concepts from first principles.

Whenever possible:
- Use .NET examples
- Use Azure examples
- Provide interview questions
- Give hands-on exercises
- Avoid unnecessary theory
```

Then you could ask:

```text
What is RAG?
```

and the model would tailor the answer to your background.

---

### Difference Between Prompt Types

| Type             | Who Writes It         | Purpose                   |
| ---------------- | --------------------- | ------------------------- |
| System Prompt    | Application/Platform  | Define behavior and rules |
| Developer Prompt | Application Developer | Additional instructions   |
| User Prompt      | End User              | Ask questions or tasks    |

### Simple Analogy

Imagine a company:

* **System Prompt** = Company policies
* **Developer Prompt** = Manager instructions
* **User Prompt** = Customer request

The employee (LLM) must follow company policy first, then manager instructions, then customer requests.

In short: **a System Prompt is the highest-priority set of instructions that defines how an LLM should behave throughout a conversation.**
