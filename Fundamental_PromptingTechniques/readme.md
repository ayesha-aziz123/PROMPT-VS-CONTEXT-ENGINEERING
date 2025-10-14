# 🌟 Fundamental Prompting Techniques for AI Models

Welcome to this quick guide on **Prompt Engineering Essentials** 🧠  
Here you'll learn the *core prompting strategies* that help you get more accurate, consistent, and creative outputs from AI models.

---

## 🥇 1. Zero-Shot Prompting

**Description:**  
The most direct and simple approach — you ask the model to perform a task without giving any examples.

**Example:**  
> Classify this movie review as positive, negative, or neutral:  
> _“The visuals were breathtaking, but the story lacked depth.”_

**When to Use:**  
- Straightforward or well-defined tasks  
- When the model already understands the topic  
- For quick, one-time queries  

---

## 🧩 2. One-Shot Prompting

**Description:**  
You provide *one* example to demonstrate the format or tone of the expected response.

**Example:**  
> Translate English to French:  
>
> **English:** “Good morning, how are you?”  
> **French:** “Bonjour, comment allez-vous ?”  
>
> **English:** “Where is the train station?”  
> **French:** 

**When to Use:**  
- When you need consistency in style or structure  
- Simple transformation or translation tasks  

---

## 🎯 3. Few-Shot Prompting

**Description:**  
Provide *multiple examples* to establish a clear pattern or logic for the model to follow.

**Example:**  
> Convert customer feedback into structured JSON:  
>
> **Feedback:** “Fast delivery but rude staff.”  
> `{"delivery": "positive", "service": "negative", "overall": "mixed"}`  
>
> **Feedback:** “Amazing food and friendly waiter.”  
> `{"delivery": "positive", "service": "positive", "overall": "positive"}`  
>
> **Feedback:** “Cold pizza and long wait time.”  
> `{"delivery": "negative", "service": "negative", "overall": "negative"}`  

**Best Practices:**  
- Use **3–5 examples** for most tasks  
- Mix different cases or categories  
- Keep examples consistent and high-quality  

---

## ⚙️ 4. System Prompting

**Description:**  
Define the AI’s overall **role, tone, and rules of behavior** at the system level.  
This ensures consistent behavior across all responses.

**Example:**  
> 🗺️ *System Prompt:*  
> “You are a professional travel assistant. Always include:  
> - Main attractions  
> - Local etiquette  
> - Budget tips  
> - Best visiting seasons.”  
>
> **User:** Tell me about visiting Kyoto.

**When to Use:**  
- Building chatbots or AI assistants  
- Maintaining consistent role-based behavior  

---

## 👩‍💻 5. Role Prompting

**Description:**  
Assign the AI a specific **persona or expertise** to improve accuracy and realism.

**Example:**  
> “Act as a senior data engineer. Suggest a scalable data pipeline architecture for a SaaS application.”

**Effective Roles:**  
- 🎓 Subject Matter Experts (doctor, teacher, lawyer)  
- 🎨 Creative Roles (writer, designer, poet)  
- 📊 Analytical Roles (consultant, analyst)  
- 💬 Communication Styles (friendly tutor, formal advisor)  

---

## 🧩 6. Contextual Prompting

**Description:**  
Provide **relevant background or situational context** before asking the main question.

**Example:**  
> **Context:** You’re writing for a beginner-level tech blog.  
> Explain what an API is in **simple and relatable** language (around 200 words).  

**When to Use:**  
- Tasks needing domain or audience awareness  
- Blog writing, teaching, or client communication  

---

## 🚀 Summary

| Technique | Key Purpose | Ideal For |
|------------|--------------|------------|
| Zero-Shot | Quick, direct requests | Simple queries |
| One-Shot | Guide format with one example | Translations, transformations |
| Few-Shot | Teach pattern or logic | Classification, data structuring |
| System Prompting | Define behavior globally | Chatbots, assistants |
| Role Prompting | Add personality or expertise | Expert or creative outputs |
| Contextual Prompting | Add relevant background info | Detailed or audience-specific tasks |

---

## 💡 Tip
> Combine these techniques for **best results** — for example, use **System + Role + Contextual prompting** to build advanced, realistic AI agents.

---

### ✨ Author
**Ayesha** — Exploring advanced **AI Prompt Engineering** & practical applications in multi-agent systems.  
⭐ Star this repo if you found it useful!

