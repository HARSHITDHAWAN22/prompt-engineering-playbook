# Prompt Engineering Fundamentals

## 1. What is Prompt Engineering?

Prompt engineering is the skill of writing clear and structured instructions
so that a large language model (LLM) gives the output we actually want.

Instead of changing the model itself, we change **how we talk to it**.

In simple words:
> Prompt engineering is about asking the right question in the right way.

Even very powerful models can fail if the prompt is poorly written.

---

## 2. Why Prompt Engineering Is Important

LLMs do not understand intent the way humans do.
They respond only to the text they are given.

A good prompt helps to:
- Get more accurate answers
- Improve reasoning quality
- Reduce random or hallucinated outputs
- Control tone, depth, and format
- Make responses consistent across runs

In real-world GenAI applications, prompt engineering acts as a **control layer**
between the user and the model.

---

## 3. Main Parts of a Prompt

Most effective prompts contain a few common elements.

### 3.1 Role Instruction
This tells the model *who it should behave as*.

Example:

You are a senior software engineer.  
This sets the expected experience level and tone of the response.

---

### 3.2 Task Description  
The task clearly tells the model what it needs to do.

Explain overfitting in machine learning.

When the task is clear, the model is less likely to guess or go off-topic.

---

### 3.3 Context  
Context tells the model who the answer is meant for.

Explain it to a beginner.

This helps the model adjust language and depth.

---

### 3.4 Constraints  
Constraints control the output and keep it focused.

Do not use formulas.  
Limit the answer to 5 points.

This avoids unnecessary or overly long responses.

---

### 3.5 Output Format  
Output format defines how the answer should look.

Return the answer in bullet points.

This is especially useful in real applications.

---

## 4. What Makes a Prompt Good?
A good prompt is clear, focused, and easy to understand.  
If the output is confusing, the prompt usually needs improvement.

---

## 5. Good vs Bad Prompt

Bad prompt:  
Explain machine learning.

Good prompt:  
Explain machine learning to a beginner in 5 simple bullet points.

---

## 6. Prompt Engineering vs Model Training
In prompt engineering, we guide the model using better instructions.  
In model training, we change model weights using data and time.

Prompt engineering is faster and cheaper for most use cases.

---

## 7. Common Mistakes
- Writing vague prompts  
- Asking multiple tasks at once  
- Not defining output format  

---

## 8. Key Takeaways
- Prompt engineering is a core GenAI skill  
- Clear prompts lead to better outputs  
- Small changes can make a big difference  

---

## 9. Next Step
Next, learn basic prompting techniques and practice regularly.

