# ✅ Slide 1 — Problem Framing & ML Context

### **Slide 1: On‑screen content (minimal, examiner‑friendly)**

**Machine Learning and the Information War**  
*Detection under adversarial adaptation*

**Information warfare**

*   Strategic manipulation of beliefs, trust, and behaviour
*   Operates as a **socio‑technical system**

**Where ML is applied**

*   Text & content classification
*   Behavioural & graph‑based detection
*   Representation learning
*   Sequential optimisation (reinforcement learning)

**Core challenge**

*   Adversarial adaptation + domain shift


# ✅ Slide 2 — ML Techniques & Detection Approaches

### **Slide 2: On‑screen content**

**Detection techniques and limitations**

| Target             | ML approach                | Strength                   | Limitation                |
| ------------------ | -------------------------- | -------------------------- | ------------------------- |
| Synthetic text     | Deep learning + embeddings | High benchmark accuracy    | Sensitive to domain shift |
| Coordinated actors | Graph & network models     | More robust than text-only | Stealth coordination      |
| Deepfakes          | CNN‑based forensic models  | Detects known artefacts    | Arms race with generators |
| Operations         | Ensemble pipelines         | Analyst triage support     | Not fully autonomous      |

**Key insight:**  
Accuracy ≠ operational robustness

***

# ✅ Slide 3 — Adversarial ML, Challenges & Conclusions

*(\~2.5–3 minutes spoken)*

### **Slide 3: On‑screen content**

**Adversarial challenges**

*   Data poisoning
*   Evasion attacks
*   Model probing & imitation
*   Reinforcement learning vulnerabilities

**Design implications**

*   Continuous retraining & drift detection
*   Adversarial testing
*   Explainability & human oversight

**Conclusion**

*   ML strengthens resilience, not absolute truth
*   Best used for **decision support**, not automation

================================================================

# 🎯 Slide 1 — Plain English Script (2:45)

> This presentation reviews how machine learning is used in the information war, focusing on what it can do well and where it struggles.
>
> Information warfare is about influencing what people believe and how they behave, usually for political or strategic reasons. It is not just about fake content. It is a **system** involving attackers, social media platforms, automated accounts, and real users, all interacting with each other.
>
> Machine learning is used in several ways here. Models are trained to classify content, for example to detect misleading or machine-generated text. Graph and network methods look for coordinated behaviour across accounts. Representation learning helps models understand meaning and patterns in content. There is also growing interest in using reinforcement learning to optimise how influence campaigns are run over time.
>
> The key issue is that this is an **adversarial environment**. Attackers are constantly changing how they operate to avoid being detected. Because of this, models trained on past data often fail when they meet new patterns. This is known as **domain shift**.
>
> This creates a problem for defenders. A model might perform well in testing, but that does not guarantee it will work in the real world. So the key question is not just whether machine learning can detect disinformation, but whether it can stay effective as attackers adapt.

***

# 🎯 Slide 2 — Plain English Script (3:05)

> There are several machine learning approaches used to detect information warfare activity, and research shows they can work well in controlled settings.
>
> For example, deep learning models can detect machine-generated text by learning patterns in language. One study shows that models using FastText embeddings can accurately classify generated tweets. These models pick up subtle patterns that are hard for humans to see.
>
> However, these systems often struggle in real-world conditions. When attackers change how they write, for example by rephrasing or using new tools, the model may no longer recognise the pattern. This is a clear example of domain shift.
>
> To improve this, some methods focus on behaviour rather than content. Graph-based models look at how accounts interact, such as timing, connections, and coordination. These are often harder to fake than text alone, so they can be more robust.
>
> But they are not perfect either. Attackers can spread activity over longer periods or across different platforms, making detection harder.
>
> For deepfakes, machine learning models can detect visual or audio artefacts, but this is constantly evolving. As generation tools improve, detection becomes more difficult.
>
> In practice, organisations combine multiple methods into a single system. These systems usually support human analysts by highlighting suspicious activity rather than making final decisions.
>
> This leads to an important point: **high accuracy in testing does not mean the system will work well in the real world**. Proper evaluation needs to consider how models perform over time, on new types of data, and under deliberate evasion.

***

# 🎯 Slide 3 — Plain English Script (2:40)

> A major challenge in this field is adversarial machine learning. This means attackers are not just using machine learning, they are also trying to break it.
>
> One way they do this is through **data poisoning**, where they try to influence the data used to train or update models. For example, they might generate fake engagement or manipulate reporting systems.
>
> Another common method is **evasion**, where content is designed specifically to avoid detection. This could include rewording messages, changing style, or hiding signals that models rely on.
>
> There is also a risk that attackers can learn how detection systems work by testing them, and then create content that avoids being flagged.
>
> Reinforcement learning systems can also be affected. Research shows that these systems can be sensitive to manipulated inputs, which is a concern if they are used in decision-making.
>
> Because of these risks, detection systems need to be designed carefully. They should be retrained regularly, tested against new and adversarial data, and monitored for changes over time.
>
> Another important factor is explainability. Human analysts need to understand why a model has flagged something, especially when decisions have political or social consequences.
>
> In conclusion, machine learning is an important tool in the information war, but it does not solve the problem. Its main value is in helping humans make better decisions and manage large volumes of data. The most effective approach is to use machine learning as part of a wider system that combines technology, human judgement, and ongoing adaptation.

***
