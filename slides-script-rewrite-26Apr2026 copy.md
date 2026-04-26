Yes — below is a **full rewritten version** of your 3-slide presentation and script, designed to fit the brief’s requirement for a maximum of three slides and 8–9 minutes, while making it sound like a stronger technical review rather than a general overview. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)

## Slide 1

**Title:** Machine Learning in Information Warfare: Scale, Automation, and Trust Erosion 

**Subtitle:** From manual propaganda to ML-driven influence operations 

**Slide content**
- **Definition and shift:** Information warfare is the deliberate manipulation of information to influence perception and behaviour, and machine learning has accelerated this by automating content generation, targeting, and amplification. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)
- **Operational scale:** During the Russia-Ukraine conflict, researchers identified coordinated bot activity involving more than 18,000 accounts, showing that ML-based operations can scale far beyond traditional troll farm models. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)
- **Trust impact:** Exposure to large-scale disinformation campaigns has been associated with measurable declines in public trust, including reported drops of around 10 points in institutional confidence. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)
- **Key actors:** State actors, social media platforms, defence organisations, and academic researchers all play roles either in conducting, detecting, or countering information operations. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4f1d3933-fb1a-4aae-be86-e84d7175e49d/Assignment-1-Machine-Learning_Technical-Review-Presentation-NW-Depth-PGDip-BDA-2026.docx)

**Suggested visual**
- A left-to-right process graphic: **pre-trained multilingual model → automated content generation → coordinated amplification across platforms → trust erosion**. 

**Footer citations**
Singer and Brooking, 2018; Wu, 2022; Balogun et al., 2025. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)

**Script**
“Today I will review how machine learning has transformed information warfare from labour-intensive propaganda into automated, high-velocity influence operations. Information warfare is the deliberate manipulation of information to shape perception, public behaviour, and sometimes political or military decisions. What makes the current phase different is the integration of machine learning, which automates tasks that previously required large human teams, including generating persuasive content, targeting audiences, and amplifying narratives across multiple platforms. This shift means that information operations can now be executed with far greater speed, scale, and adaptability than in earlier forms of propaganda.” [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)

“One example of this shift comes from analysis of the Russia-Ukraine conflict, where researchers identified bot farms operating more than 18,000 coordinated accounts. These were not just simple scripted bots. They increasingly relied on AI systems capable of multilingual output, allowing narratives to be spread quickly across X, Facebook, Telegram, and other platforms in forms that appeared more natural and context-aware. That matters because the strategic value of these campaigns is not just scale, but also credibility. The more human-like the content appears, the harder it becomes for both users and platforms to detect manipulation early.” [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)

“The consequences are not only technical but social. Research cited in my draft suggests that sustained exposure to disinformation campaigns can contribute to significant declines in public trust, including drops of around 10 points in confidence toward institutions. This means machine learning is not just helping to spread false content more efficiently; it is intensifying the broader psychological effects of information warfare. In other words, automation changes both the volume of manipulation and its societal impact.” [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)

“It is also important to identify the main organisations involved, because the brief asks us to consider who is implementing these techniques and who is responding. On the offensive side, state-linked actors and coordinated influence groups are central. On the defensive side, platforms such as Meta, X, and YouTube are developing moderation and detection systems, while defence organisations, intelligence communities, and academic researchers are building technical countermeasures. This sets up the central question for the review: what machine learning methods are currently being used to detect these operations, and how effective are they?” [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4f1d3933-fb1a-4aae-be86-e84d7175e49d/Assignment-1-Machine-Learning_Technical-Review-Presentation-NW-Depth-PGDip-BDA-2026.docx)

## Slide 2

**Title:** Comparative Review of ML Detection Methods 

**Subtitle:** Text, coordination behaviour, and synthetic media 

**Slide content**
Use a table like this: 

| Detection target | ML method | Input features | Performance | Main limitation |
|---|---|---|---|---|
| Bot-generated text | CNN + FastText embeddings | Word patterns, semantic vectors | 93% accuracy on benchmarked Twitter data | Weak under domain shift and new language styles |
| Coordinated behaviour | Graph-based models, inverse RL | Retweet networks, temporal activity, account interactions | Effective for coordination discovery | Requires access to network-level platform data |
| Deepfakes / synthetic media | GAN-artifact forensic detection | Frequency artefacts, visual inconsistencies | About 73% accuracy in benchmark studies | Detection lags behind improvements in generation |
| Real-time threat triage | Random Forest + TensorFlow pipelines | Text, metadata, network signals | Near-real-time identification | Can be evaded and needs retraining |

**Comparative points under the table**
- Text methods are fast and accurate on known datasets, but attackers can adapt language models to reduce performance. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)
- Graph methods are often more robust because they detect coordination patterns rather than only the text itself. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)
- Synthetic media detection is an arms race because generative models evolve faster than static forensic cues. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)
- Operational systems work best as triage tools for analysts rather than fully autonomous decision-makers. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)

**Footer citations**
Sadiq et al., 2023; Minici et al., 2024; Seckin et al., 2024; Cartwright et al., 2022; Balogun et al., 2025. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)

**Script**
“This slide is the core technical review of the presentation. I have organised the literature into three main detection categories: methods that analyse text, methods that analyse coordination behaviour, and methods that detect synthetic media such as deepfakes. This structure is useful because each category solves a different detection problem and relies on different assumptions about attacker behaviour.” [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)

“The first category is bot-generated text detection. Studies in my draft point to models that combine Convolutional Neural Networks with FastText embeddings, achieving around 93 percent accuracy on benchmarked Twitter datasets. These systems work by analysing word-level patterns and semantic signals, which makes them effective for recognising repetitive or statistically unusual language associated with machine-generated content. However, a major limitation is domain shift. If an attacker fine-tunes a language model to mimic platform-specific slang, current events, or community norms, performance can decline because the detector has learned from older or narrower labelled datasets.” [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)

“The second category is behavioural or graph-based detection. This is especially important because sophisticated attackers can now generate text that looks human. Instead of asking only ‘what was said?’, graph-based systems ask ‘how is this content spreading, and who is amplifying it?’. Systems such as IOHunter use graph models and, in some cases, inverse reinforcement learning to identify patterns of coordinated inauthentic behaviour. This approach is often more robust than text-only detection because coordination structure is harder to fake consistently across a network. However, it comes with a practical limitation: it often requires access to platform-level relationship and interaction data, which independent researchers do not always have.” [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)

“The third category is synthetic media detection. Deepfakes are particularly challenging because they add visual and audio deception to the information environment. Current detection methods look for artefacts left by generation processes, such as frequency inconsistencies or upsampling traces. The studies referenced in my draft place current performance at roughly 73 percent accuracy in benchmark settings. That is useful, but not reassuring. By contrast with older static media forensics, this field is an active arms race because each new generation of synthetic media tools removes or reduces the cues detectors have learned to depend on.” [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)

“A final point is that real-world operational systems often combine multiple approaches. For example, pipelines using Random Forest and TensorFlow aim for near-real-time identification by combining text, metadata, and network signals. In practice, these systems are most valuable as triage tools that help human analysts prioritise suspicious activity quickly. They are less convincing as fully autonomous systems because they still require frequent retraining and remain vulnerable to adversarial adaptation. Overall, the literature suggests that no single method is sufficient. The strongest direction is toward combining content, behaviour, and media analysis in layered detection systems.” [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)

## Slide 3

**Title:** Adversarial Robustness, Explainability, and the Multimodal Future 

**Subtitle:** Why current systems remain vulnerable 

**Slide content**
- **Adversarial ML:** Attackers can poison training data or evade detectors by perturbing inputs, making model performance unstable in contested environments. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)
- **RL in military C2:** Reinforcement learning shows promise for strategic decision support, but current studies suggest it is highly sensitive to adversarial noise and manipulation. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)
- **Future direction 1:** Multimodal detection combining text, audio, image, and video analysis. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)
- **Future direction 2:** Explainable AI so analysts can understand why a system flagged content. 
- **Future direction 3:** More interdisciplinary integration between machine learning, psychology, and policy research. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)

**Suggested visual**
- A cycle diagram: **detector deployed → attacker adapts → model evasion/poisoning → robustness training → updated detector**. 

**Footer citations**
Duddu, 2018; Patil, 2024; Dabholkar et al., 2024a; Dabholkar et al., 2024b; Dudatyev, 2025. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)

**Script**
“The final part of the review focuses on the main weakness in current detection research: most systems are evaluated in relatively controlled conditions, while information warfare is an adversarial environment by design. This is where adversarial machine learning becomes central. Adversarial ML refers to situations where attackers deliberately manipulate data or inputs in order to reduce model performance. Two common attack types are poisoning, where corrupted examples are inserted during training, and evasion, where inputs are modified at inference time so they bypass detection. This means that even a model reporting strong benchmark accuracy may be much less reliable once an intelligent adversary starts optimising against it.” [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)

“This matters because all of the methods reviewed on the previous slide assume, at least to some extent, that the data distribution is stable. In real information warfare campaigns, that assumption breaks down. Attackers learn what gets flagged, adapt their language, change coordination patterns, and refine synthetic media outputs. As a result, adversarial robustness is not a side issue; it is the central technical challenge. A detector that performs well only in static testing environments may fail in exactly the operational settings where it is most needed.” 

“A related issue appears in the use of reinforcement learning for military command and control. RL methods are attractive because they can learn effective strategies in simulated environments, including complex decision spaces inspired by games and defence planning. However, the literature in my draft suggests that these systems are highly sensitive to adversarial noise and reward manipulation. In practical terms, that means an RL agent may appear effective in simulation but behave unsafely or unpredictably when confronted with deceptive or manipulated inputs. This makes over-reliance on autonomous ML systems risky in high-stakes security contexts.” [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)

“So where is the field going next? The first major direction is multimodal detection. Instead of analysing only text or only video, future systems need to combine text, audio, images, video, metadata, and behavioural signals so they can detect coordinated narratives across platforms. The second direction is explainable AI. Current systems often operate as black boxes, which is a problem for analysts, policymakers, and military users who need to justify interventions and understand why a piece of content was flagged. The third direction is interdisciplinary integration. Technical detection alone is not enough, because information warfare succeeds partly by exploiting human psychology, trust networks, and social division. Future systems will need to combine machine learning with insights from behavioural science and policy.” [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)

“To conclude, machine learning has made information warfare faster, more scalable, and more adaptive. The literature shows promising detection results across text, behaviour, and synthetic media, but it also shows that these systems remain fragile when faced with adversarial adaptation. The most convincing future direction is therefore not a single better model, but a more robust framework built around multimodal detection, explainability, and resilience under attack.” 

## Reference list

You should include a proper Harvard-style reference list in your submission materials, because the brief explicitly requires sources to be referenced using Harvard style. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4f1d3933-fb1a-4aae-be86-e84d7175e49d/Assignment-1-Machine-Learning_Technical-Review-Presentation-NW-Depth-PGDip-BDA-2026.docx)

At minimum, your final reference list should include the sources already used in your draft:
- Singer, P.W. and Brooking, E.T. (2018) *LikeWar: The Weaponization of Social Media*. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)
- Wu (2022). [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)
- Sadiq et al. (2023). [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)
- Minici et al. (2024). [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)
- Seckin et al. (2024). [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)
- Cartwright et al. (2022). [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)
- Duddu (2018). [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)
- Patil (2024). [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)
- Dabholkar et al. (2024a; 2024b). [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)
- Dudatyev (2025). [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)
- Balogun et al. (2025). [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4ea433a1-c11e-4b05-964d-71de845e1a69/slides-script-2.md)

Before submitting, verify that every citation has the correct author names, years, titles, journal or publisher details, and page ranges where needed, because incomplete references will weaken the academic quality of the presentation. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4f1d3933-fb1a-4aae-be86-e84d7175e49d/Assignment-1-Machine-Learning_Technical-Review-Presentation-NW-Depth-PGDip-BDA-2026.docx)

The rewritten version above is built to fit the assignment purpose: show understanding of the topic, demonstrate background research, identify challenges, name organisations involved, and review machine learning techniques within the three-slide, 8–9 minute limit. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/132481541/4f1d3933-fb1a-4aae-be86-e84d7175e49d/Assignment-1-Machine-Learning_Technical-Review-Presentation-NW-Depth-PGDip-BDA-2026.docx)

Would you like me to turn this now into a **clean final slide deck format**, meaning exactly what text goes on each slide versus what you say aloud?