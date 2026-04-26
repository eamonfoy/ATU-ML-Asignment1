# Slides for Presentation: Machine Learning and Information Warfare

## Slide 1: The Automated Battlefield
Focus: The shift from manual propaganda to ML-driven operations.
Heading: Machine Learning in Information Warfare: The Automation of Influence
Key Bullet Points:
- Scale of Operations: Shift from "troll farms" to AI-controlled bot networks managing 18,000+ accounts (Wu, 2022).
- The Trust Deficit: Impact of disinformation on public trust (measured ~10-point declines) (Balogun et al., 2025).
- Technological Shift: Use of pre-trained multilingual models for high-velocity narrative generation (Wu, 2022).

Visual Suggestion: A simple graphic showing a "Manual Operation" (few accounts) vs. an "ML-Driven Operation" (massive automated network).

![](images/2026-04-25-20-15-48.png)
![](images/2026-04-25-20-18-36.png)

Footer Citation: (Wu, 2022; Balogun et al., 2025).


## Slide 2: Technical Review: Algorithms & Detection Efficacy

Focus: The core technical content of your assignment. A table is the best way to show a "technical review" on one slide.

Heading: Technical Taxonomy of ML Detection Systems

Comparative Table:
| Detection Type | Primary Algorithms | Performance Metric |
| :--- | :--- | :--- |
| Machine-Generated Text | CNN + FastText Embeddings | 93% Accuracy (Sadiq et al., 2023) |
| Behavioral | Graph Foundation Models | Identifying coordination (Minici et al., 2024) |
| Synthetic Media | GAN-artifact detection | 0.73 Accuracy (Balogun et al., 2025) |
| Hostile Activities | Random Forest / TensorFlow | Near-real-time identification (Cartwright et al., 2022) |

Visual Suggestion: Use the table above. It proves you have reviewed the technical literature and understand specific metrics.

![](images/2026-04-25-20-29-46.png)

Footer Citation: (Sadiq et al., 2023; Minici et al., 2024; Cartwright et al., 2022).


## Slide 3: Vulnerabilities & Future Defense

Focus: Adversarial ML, Reinforcement Learning, and multimodal solutions.
Heading: Adversarial Vulnerabilities & The Multimodal Future
Key Bullet Points:
- Adversarial ML: Strategic interactions where attackers perturb data to "poison" or "evade" detection models (Duddu, 2018; Patil, 2024).
- Reinforcement Learning: Potential for military C2, but highly sensitive to adversarial noise (Dabholkar et al., 2024a, 2024b).
- Future Requirement: Moving toward Multimodal Detection (Video + Audio + Text) to counter hybrid warfare (Лавров & Dudatyev, 2025).

Visual Suggestion: A "Cat-and-Mouse" loop diagram showing: Detection Model $\rightarrow$ Adversarial Attack $\rightarrow$ Model Robustness Training.

![](images/2026-04-25-20-23-38.png)

Footer Citation: (Duddu, 2018; Dabholkar et al., 2024; Lavrov & Dudatyev, 2025).

-----

# Script for Presentation: Machine Learning and Information Warfare


## Slide 1: The Evolution of the Information Front: ML-Driven Disinformation

[Intro]
"Today, I will be discussing how machine learning is used in Information Warfare. War is shifting from physical combat to digital battles where there is no direct contact between enemies. In this environment, information operations have evolved beyond simple propaganda; they now involve using AI to automatically and rapidly influence how large groups of people think (Singer and Brooking, 2018). This digital space is now the main area where modern conflicts are fought."
Key research elements retained:

(Singer and Brooking, 2018), which refers to [LikeWar: The Weaponization of Social Media](https://www.google.com/search?kgmid=/g/11f3vr407p&q=Rewrite+this+in+plain+English+as+I%27m+a+masters+student+who+is+giving+a+presentation+on+the+subject+of+Machine+learning+and+the+Information+war.+I+am+going+to+give+a+series+of+paragraphs+and+ask+that+it+be+translated+in+to+plain+English,+however+keeping+the+research+angle+and+Harvard+style+references+as+this+is+critical%0A%0AFirst+paragraph:%0A%0A%22Today,+I%E2%80%99m+presenting+a+technical+review+of+machine+learning+in+the+context+of+Information+War.+As+we+move+from+conventional+kinetic+warfare+to+asymmetric,+contactless+conflicts,+the+digital+domain+has+become+the+primary+battlefield.+Information+operations+are+no+longer+just+about+%27propaganda%27;+they+are+about+the+automated,+high-velocity+manipulation+of+public+perception+using+artificial+intelligence.%22), 

[The Problem Landscape]
"Information warfare uses machine learning to do things that used to take a lot of people and hard work. For example, during the start of the conflict between Ukraine and Russia, security experts found 'bot farms' that ran over 18,000 accounts to spread fear and fake threats (Wu, 2022). These aren't just basic computer programs anymore; attackers now use advanced AI that speaks multiple languages to write comments that sound like real people. This helps them control public opinion on sites like X and Facebook (Wu, 2022). This trend has led to a major loss of trust, with research showing that public confidence can drop by nearly 10 points after a big wave of fake news (Balogun et al., 2025)."

[Literature Trends]
"My look at the latest research shows two big changes. First, we now see 'AI-controlled bots'—fake accounts that use advanced AI to have realistic conversations (Sadiq et al., 2023). Second, researchers are combining public data with machine learning to find 'pivotal amplifiers.' These are the most influential accounts that help fake news spread the fastest (Balogun et al., 2025). Current projects, like those for the Canadian Armed Forces, are building systems that can spot these attacks almost as they happen. By using tools like TensorFlow and Random Forest, they are moving from just studying what happened in the past to stopping attacks before they spread (Cartwright et al., 2022)."



## Slide 2: Technical Review: How Algorithms Find the Fakes

[The Core Technical Content]
"In this part of the review, I’ve grouped machine learning tools into three main areas: looking at the content, looking at behavior, and spotting fake media (like deepfakes). Let’s look at the specific math-based tools currently leading the field."

[Content & NLP Techniques]
"First, for spotting AI-written text, older methods are being replaced by 'deep learning.' A great example is combining Convolutional Neural Networks with FastText. By looking at the small patterns in how words are put together, these models are 93% accurate at telling a bot’s tweet from a human's (Sadiq et al., 2023). Older tools just counted how often words appeared, but these new models can actually pick up on the hidden meanings and emotions that bots use to sound like us."

[Behavioral & Graph-Based Analysis]
"But the text isn't everything. Modern attackers are smart and can write 'clean' messages that trick text filters. To stop them, we look at how they act. New systems like 'IOHunter' use 'Graph Models' to find coordinated fake behavior (Minici et al., 2024). These systems don't just read the post; they look at how it is being boosted by others. By using Inverse Reinforcement Learning, researchers can actually figure out the 'goal' or 'reward' a bot is programmed to chase, which looks very different from how a real person naturally interacts online (Minici et al., 2024; Seckin et al., 2024)."

[Detecting Synthetic Media]
"Finally, we have to talk about fake videos and images. Deepfakes are a major tool for causing social trouble. Technically, we catch these by looking for tiny mathematical errors—like weird 'chessboard' shadows—left behind by the AI that created them (Wu, 2022). While current detection models are about 73% accurate, we know we need more flexible systems because AI-generated fakes are getting better every day (Balogun et al., 2025)."

## Slide 3: Challenges, Ethics, and the Path Forward

[The Arms Race]
"The biggest technical hurdle we face is something called 'Adversarial Machine Learning.' Think of this as a high-stakes game where the attacker purposefully messes with data to trick our AI models (Duddu, 2018). In Information War, attackers use 'poisoning attacks'—putting bad data into the system while it's learning—or 'evasion attacks' to sneak past our defenses (Patil, 2024). This creates a 'cat-and-mouse' game where our defenses must be strong enough to handle an enemy that is constantly learning and fighting back."

[Reinforcement Learning in C2]
"Interestingly, the same AI techniques used to win complex video games like StarCraft are now being used for military Command and Control (C2) (Dabholkar et al., 2024). While these AI 'agents' are great at finding winning strategies in simulations, research shows they can easily be confused by 'noise' or fake data injected by an enemy (Dabholkar et al., 2024a, 2024b). This highlights a major danger: we cannot over-rely on AI in critical situations unless it has been specifically trained to handle these types of attacks."

[Conclusion & Future Outlook]
"To conclude, the future of defense is 'multimodal detection.' This means building systems that can analyze video, audio, and text all at once to spot propaganda across different platforms (Лавров & Dudatyev, 2025). However, technology isn't the only answer. We need to bridge the 'interdisciplinary gap' by using psychology to understand why people are ready to believe fake news in the first place (Лавров & Dudatyev, 2025). Moving forward, our goal is 'Explainable AI'—systems that don't just find a fake, but can actually show a human commander the evidence so they can make an informed decision. Thank you for your time."


