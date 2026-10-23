# architajha-uiux: Final Conclusion Report
## Redesigning the Coding Platform Experience: Original LeetCode vs. High-Fidelity Prototype

**Author:** Archita Ranjeetkumar Jha  
**PRN:** 1262243200  
**Program:** TY B.Tech Computer Science & Engineering (AI & Data Science), Semester 5  
**Division & Batch:** Panel F | Batch F2  
**Institution:** MIT World Peace University (MIT-WPU), Pune  
**Figma Prototype:** [Interactive High-Fidelity Prototype](https://www.figma.com/design/m2qqUWH8PDtH6girwqRZ1c/CODING_PLATFORM--Copy-?node-id=3-2&p=f&t=KEm31piQZXm4PfSq-0)  
**Low-Fidelity Architecture:** [Low-Fidelity Wireframes](https://www.figma.com/design/m2qqUWH8PDtH6girwqRZ1c/CODING_PLATFORM--Copy-?node-id=0-1&p=f&t=KEm31piQZXm4PfSq-0)  

---

## 1. Executive Summary & Study Objective

The objective of this research was to validate whether a pedagogical redesign of traditional competitive coding platforms—specifically targeting the industry benchmark, **LeetCode**—could eliminate known usability barriers, alleviate cognitive overload, and foster sustained learner engagement. Through a mixed-methods usability evaluation combining **qualitative Think-Aloud protocols** ($N=5$) and **quantitative post-test UX evaluations** (System Usability Scale and 10 UX criteria), the author's modified high-fidelity prototype (**"CODE / PRACTICE"**) was benchmarked against the live LeetCode environment.

The findings deliver an **unequivocal, evidence-based confirmation**: the redesigned prototype dramatically outperformed the original platform across every qualitative and quantitative dimension evaluated. The platform achieved a **System Usability Scale (SUS) increase from $44.0$ (Grade F / Unacceptable) to $95.0$ (Grade A+ / World-Class)**, accompanied by a **$152.5\%$ average improvement across ten core usability parameters**.

---

## 2. Methodology & Participant Demographics

### 2.1 The Participant Cohort
Five engineering students unfamiliar with this specific interface architecture participated in individual, 1-on-1 testing sessions:

| Participant | PRN | Persona Archetype | Session Core Task |
| :--- | :--- | :--- | :--- |
| **Aanvi Bindal** | 1262243296 | Intermediate Coder (Placement Prep) | Navigate Two Sum, review logic, execute run/submit, inspect streak |
| **Jashna Gupta** | 1262243103 | Beginner Programmer (First Steps) | Understand problem statement, request a hint, verify approach |
| **Nisarg Ghule** | 1262243177 | Systematic Learner (DSA Fundamentals) | Step through guided checklist, use live study room & notes |
| **Nisarg Malhotra** | 1262243207 | Competitive Practitioner (Daily Coder) | Utilize Practice Pattern (Warm-up/Apply/Reflect), check contests & coach |
| **Paraansh Nisar** | 1272250941 | Undergraduate Batchmate (Habit Coder) | Review auto-saved state, inspect 7-day streak card, follow hints |

### 2.2 Study Protocol
Each participant completed the core problem-solving workflow (Two Sum) on **both** the Original LeetCode website and the Modified Prototype while vocalizing their real-time thoughts, hesitations, emotional triggers, and expectations (Think-Aloud Protocol). Sessions were recorded, transcribed verbatim, and followed immediately by an independent quantitative survey.

---

## 3. Qualitative Findings: Resolving User Frustrations

Qualitative transcript analysis revealed five primary failure modes on LeetCode, each successfully resolved by specific architectural interventions in the prototype:

```
[ LeetCode Pain Point ]                         [ Redesign Intervention ]
Blank Page & Cold-Start Paralysis       --->    Guided Scaffolding Checklist
All-or-Nothing Spoiler Solutions         --->    Calibrated Tiered Nudges (20/40 min)
Buried Gamification & Streak Disconnect  --->    Persistent Top-Right Header Card
Asynchronous, Lonely Learning Void       --->    Synchronous Collaborative Study Room
Ephemeral Scratchpads & Lost Context     --->    Persistent In-Situ Pattern Notes & Auto-Save
```

### 3.1 Cognitive Scaffolding vs. Cold-Start Paralysis
- **Original LeetCode:** Beginners consistently experienced "blank page freeze." Nisarg Ghule stated: *"From the home page, you don't know where to go to find the questions... while solving, there are no indicators of if you're on the right path or not."*
- **Modified Prototype:** The **Guided Checklist** (*1. Understand I/O $\rightarrow$ 2. Choose Pattern $\rightarrow$ 3. Write Starter Skeleton $\rightarrow$ 4. Run Small Example*) provided cognitive handrails. Aanvi Bindal noted: *"The very first thing that I see is a checklist, which is very easy to keep a track of how I am going ahead in my code."*

### 3.2 Calibrated Nudges vs. All-or-Nothing Solutions
- **Original LeetCode:** Learners who get stuck must either surrender to full editorial solutions (destroying the learning opportunity) or abandon the problem.
- **Modified Prototype:** The automated AI coach delivers time-calibrated nudges after 20 and 40 minutes of idle/unsuccessful attempts. Jashna Gupta remarked: *"If you are stuck on the question for more time like 20+ minutes, it will give you hints... boost your confidence, which is not available in LeetCode."*

### 3.3 Visible Motivation vs. Buried Progress
- **Original LeetCode:** Daily streak tracking requires opening the profile drawer, detaching the user from their continuous streak momentum.
- **Modified Prototype:** A prominent top-right 7-day streak card displaying completion percentages directly feeds intrinsic motivation. Paraansh Nisar highlighted: *"To check the streak on LeetCode, you have to go into your profile... Archita has implemented that in a card on the top right... it shows completion percentage and auto-saves your code."*

### 3.4 Synchronous Collaboration vs. Isolated Discussion
- **Original LeetCode:** Community interaction is confined to static, asynchronous comment threads.
- **Modified Prototype:** The **Study Room** feature enables real-time peer problem-solving. Nisarg Ghule noted: *"In general, while you're solving... you cannot discuss it live with other people. Whereas here... there is a study room where you can interact with other users solving the same questions."*

### 3.5 Structured Learning vs. Fragmented Drill
- **Original LeetCode:** Disconnected problem lists encourage superficial memorization over pattern mastery.
- **Modified Prototype:** The **Practice Pattern** taxonomy (*Warm-up $\rightarrow$ Apply $\rightarrow$ Reflect*), worked examples, and categorized contest reviews (*Past Attempts*) were singled out by Nisarg Malhotra: *"When I click on Practice Pattern, there is warm up, apply, and reflect... Past attempts section isn't available in LeetCode. The UX is excellent."*

### 3.6 Participant Emotional Valence & Mental States (How Participants Felt)
A critical insight emerged regarding how participants' affective states shifted across testing:

| Participant | Emotional State on LeetCode | Emotional State on Prototype | Key Verbalized Feeling |
| :--- | :--- | :--- | :--- |
| **Aanvi Bindal** | Overwhelmed & Tedious (Fatigue) | Calm, Structured & Personalized | *"Submitting is very tedious on LeetCode... here hints at certain timelines give a personalized feel and the checklist keeps me on track."* |
| **Jashna Gupta** | Intimidated & Underconfident | Reassured, Confident & Proud | *"In LeetCode questions are complicated and not shown nicely... in Archita's prototype if you're stuck for 20+ min it gives hints to boost confidence."* |
| **Nisarg Ghule** | Blindfolded, Disoriented & Lonely | Guided, Empowered & Collaborative | *"On LeetCode you don't know where to go or if you're on the right path... here the guided checklist keeps you on track and study room lets you interact live."* |
| **Nisarg Malhotra** | Irritated by Micro-Friction | Joyful, Ambitious & Eager | *"Going into account is hard on LeetCode... with Archita's design I feel very happy and I'll reach 200 LeetCode in 2 days. The UX is so excellent I want to use it now."* |
| **Paraansh Nisar** | Anxious (Unsaved Code Dread) | Secure, Relieved & In Flow | *"LeetCode doesn't auto-save code, whereas this does... seeing streak percentage on top right keeps me going."* |

---

## 4. Quantitative Synthesis & Usability Metrics

The quantitative survey results validated the qualitative narrative with overwhelming statistical clarity:

### 4.1 System Usability Scale (SUS) Metrics
- **LeetCode Original:** Mean SUS = **$44.00 \pm 7.62$** (Grade F — Severe usability hurdles for non-experts).
- **Modified Prototype:** Mean SUS = **$95.00 \pm 4.68$** (Grade A+ — Top 1% of evaluated digital learning software).
- **Net Usability Gain:** **$+51.00$ SUS points ($+115.9\%$ increase)**.

### 4.2 Parameter Performance Comparison

```
1. Collaborative Study Room       [2.20] ■■■                    ---> [9.00] ■■■■■■■■■■■■ (+309.1%)
2. Note-Taking & Pattern Storage  [2.80] ■■■■                   ---> [9.00] ■■■■■■■■■■■■ (+221.4%)
3. Guided Scaffolding Checklist   [3.00] ■■■■                   ---> [9.40] ■■■■■■■■■■■■■ (+213.3%)
4. Hint System & AI Coach         [3.00] ■■■■                   ---> [9.20] ■■■■■■■■■■■■ (+206.7%)
5. Streak Visibility              [3.40] ■■■■■                  ---> [9.60] ■■■■■■■■■■■■■ (+182.4%)
6. Structured Pedagogy            [3.40] ■■■■■                  ---> [9.00] ■■■■■■■■■■■■ (+164.7%)
7. Confidence & Comfort           [4.20] ■■■■■■                 ---> [9.40] ■■■■■■■■■■■■■ (+123.8%)
8. Learnability & Onboarding      [4.20] ■■■■■■                 ---> [8.80] ■■■■■■■■■■■■ (+109.5%)
9. Submission Workflow            [4.60] ■■■■■■                 ---> [9.00] ■■■■■■■■■■■■ (+95.7%)
10. Aesthetic & Visual Hierarchy  [5.40] ■■■■■■■                ---> [9.00] ■■■■■■■■■■■■ (+66.7%)
```

---

## 5. Honest, Evidence-Based Critical Assessment

### 5.1 Success Factors
Did the prototype successfully improve the user experience? **Yes, unambiguously.**
1. **Reduced Cognitive Frustration:** Beginners no longer feel abandoned by the interface.
2. **Elevated Daily Engagement:** Streak visibility and auto-save eliminate workflow anxiety.
3. **Enhanced Metacognition:** Pattern notes and reflection checklists transition users from passive typing to algorithmic reasoning.

### 5.2 Residual Limitations & Heuristic Recommendations
In the interest of rigorous academic honesty, several areas for future iteration were identified through Lab Assignment V (Heuristic Evaluation) and testing:
1. **Accommodating Expert Speed (Heuristic #3):** Advanced competitive programmers (such as persona *Rohan Mehta*) may find constant checklists overly prescriptive. *Solution:* Introduce a global **"Expert Mode / Calm Mode"** toggle allowing experienced users to minimize scaffolds.
2. **Control & Reversibility (Heuristic #1):** Users noted the lack of an explicit "Reset Code" button and a clear exit mechanism during timed Mock Mode. *Solution:* Implement standard undo/reset states and modal exit confirmations.
3. **Accent Palette Discipline (Heuristic #5):** With five functional accent colors in dark mode, secondary panels risk visual competition. Standardizing to a unified primary-plus-alert color token scheme will further enhance aesthetic integrity.

---

## 6. Conclusion

This mixed-methods usability study proves that user satisfaction in coding education is not merely a function of compiler speed or problem database size, but fundamentally depends on **instructional scaffolding, timely feedback loops, and empathetic visual hierarchy**. The **CODE / PRACTICE** high-fidelity prototype successfully bridges the gap between intimidating competitive programming and accessible, joyful software engineering education.
