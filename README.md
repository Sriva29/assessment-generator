# 📘 Assessment Generator – Ensuring AI Doesn't Give Away the Answer

✍️ Author: Srivatsan Rangarajan

## 🎯 Project Goal

This project explores the capabilities and limitations of AI-generated assessment questions. Using ChatGPT-4.5, I generated a dataset of **500 multiple-choice questions**, producing them **10 at a time** to maintain a minimum threshold of quality and consistency.

The key focus: **evaluate the quality of questions created by AI** and identify structural flaws in the generated items—most notably, the tendency for the **correct answer to be the longest option**, creating an obvious giveaway.

In an era where AI is increasingly being used to generate assessments (often bypassing learning designers), it's critical to highlight potential pitfalls in unreviewed content.

---

## 🧠 Background & Motivation

With the growing adoption of AI in learning design, educators and SMEs are exploring AI tools to automate assessment creation. While this improves efficiency, it poses new risks in **assessment validity** and **learner fairness**.

This project was designed to:

- Stress-test GPT’s ability to generate quality questions.
- Demonstrate how **subtle flaws can undermine the integrity of assessments**.
- Show that human-in-the-loop validation is still essential, especially in high-stakes testing.

---

## 🛠️ Methodology

1. **Generation Method**:
   - Used **OpenAI’s GPT-4.5** to generate **500 questions**, in **batches of 10**.
   - Ensured each question included 4 options: 1 correct and 3 distractors.
   - Saved each batch individually to track progression and quality shifts.

2. **Observations During Generation**:
   - Despite varied prompting, GPT consistently made the correct answer the longest.
   - This reveals a pattern bias, a red flag in test item creation.

3. **Manual Review**:
   - Each batch underwent manual validation for:
     - Plausibility of distractors  
     - Balance in answer lengths  
     - Clarity and structure  

---

## 📊 Key Findings

- **95%+** of questions had **length-biased correct answers**, making them easily guessable.
- Distractors were often **vague or implausible**, reducing cognitive load required.
- While surface-level readability was high, the **pedagogical soundness was weak**.

---

## ✅ What I Did Differently

Unlike bulk AI generations, I opted to:

- Generate in **small controlled batches**  
- **Track issues systematically**  
- Emphasize **human-AI collaboration** rather than AI automation  

This process reflects **responsible AI usage** — a key value I bring to any learning and AI-based role.

---

## 🔁 Next Steps

- Experiment with **fine-tuning** the model on curated question sets that avoid answer-length bias.
- Explore using **rule-based post-processing** to randomize correct answer lengths and improve distractor plausibility.
- Contribute to open-source tools that **enhance assessment quality** in AI-assisted pipelines.

---

## 📌 Conclusion

AI has potential in assessment design—but **not without oversight**. This project illustrates that **automated does not mean accurate**, and why **learning designers remain critical** even in the age of LLMs.

By building this dataset one thoughtful batch at a time, I’ve aimed to combine **technical rigor with design sensitivity**—the hallmark of effective, ethical edtech.
"""
 
