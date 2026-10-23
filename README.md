# architajha-uiux
## Mixed-Methods Usability Validation Study (CCA3)
### Evaluating the Impact of Instructional Scaffolding on Coding Platform Usability: Original LeetCode vs. High-Fidelity Prototype ("CODE / PRACTICE")

---

## 👤 Student Information

* **Student Name:** ARCHITA RANJEETKUMAR JHA
* **PRN:** 1262243200
* **Class & Branch:** TY B.Tech Computer Science & Engineering (Artificial Intelligence & Data Science)
* **Semester:** Semester 5
* **Panel:** Panel F
* **Batch:** Batch F2
* **Domain:** Coding Platforms & Interactive Developer Tools


---

## 🔗 Figma Prototype Links

* 🎨 **High-Fidelity Interactive Prototype (Figma):**  
  [https://www.figma.com/design/m2qqUWH8PDtH6girwqRZ1c/CODING_PLATFORM--Copy-?node-id=3-2&p=f&t=KEm31piQZXm4PfSq-0](https://www.figma.com/design/m2qqUWH8PDtH6girwqRZ1c/CODING_PLATFORM--Copy-?node-id=3-2&p=f&t=KEm31piQZXm4PfSq-0)
* 📐 **Low-Fidelity Architecture & Wireframes (Figma):**  
  [https://www.figma.com/design/m2qqUWH8PDtH6girwqRZ1c/CODING_PLATFORM--Copy-?node-id=0-1&p=f&t=KEm31piQZXm4PfSq-0](https://www.figma.com/design/m2qqUWH8PDtH6girwqRZ1c/CODING_PLATFORM--Copy-?node-id=0-1&p=f&t=KEm31piQZXm4PfSq-0)
* 📊 **Interactive Infographic Report (HTML):**  
  [CONCLUSION_REPORT_INFOGRAPHIC.html](CONCLUSION_REPORT_INFOGRAPHIC.html)
* 📄 **Comprehensive Conclusion Report (Markdown):**  
  [FINAL_CONCLUSION_REPORT.md](FINAL_CONCLUSION_REPORT.md)

---

## 📌 Executive Summary & Study Objective

The objective of this continuous assessment (CCA3) is to rigorously validate the usability and pedagogical effectiveness of the author's modified high-fidelity coding platform prototype (**CODE / PRACTICE**) against the current industry standard, **LeetCode**. 

A mixed-methods usability study was conducted with **5 participants** combining:
1. **Qualitative Think-Aloud Protocols:** Participants performed a core algorithmic problem-solving task (*Two Sum*) on both the original LeetCode platform and the modified Figma prototype while speaking their real-time thoughts, hesitations, emotional pain points, and expectations aloud. Audio recordings were captured and converted to verbatim transcripts.
2. **Quantitative UX Survey & SUS Benchmarks:** Immediately following the think-aloud session, participants evaluated both systems across a 10-dimensional usability rubric and the standardized 10-item **System Usability Scale (SUS)**.

### Primary Outcome:
The study provided **overwhelming, evidence-based confirmation** that the redesigned prototype successfully improved the user experience. The prototype achieved a **System Usability Scale (SUS) leap from 44.0 (Grade F / Unacceptable) to 95.0 (Grade A+ / World-Class)**, representing a **+115.9% increase in usability** and a **+152.5% average improvement across evaluated UX dimensions**.

---

## 👥 Step 1: Participant Recruitment

Five engineering students were recruited to participate in individual, 1-on-1 evaluation sessions. All participants were peer undergraduates unfamiliar with the specific interaction architecture of the redesign to minimize familiarity bias:

| # | Participant Name | PRN | Persona Archetype / Background | Testing Modality |
| :-: | :--- | :---: | :--- | :--- |
| 1 | **Aanvi Bindal** | `1262243296` | Intermediate Coder (Placement Preparation) | 1-on-1 Desktop Lab Session |
| 2 | **Jashna Gupta** | `1262243103` | Beginner Programmer (First Steps into DSA) | 1-on-1 Desktop Lab Session |
| 3 | **Nisarg Ghule** | `1262243177` | Structured Learner (Core DSA Focus) | 1-on-1 Desktop Lab Session |
| 4 | **Nisarg Malhotra** | `1262243207` | Active Daily Coder (Competitive Aspirant) | 1-on-1 Desktop Lab Session |
| 5 | **Paraansh Nisar** | `1272250941` | Undergraduate Batchmate (Habit & Streak Coder) | 1-on-1 Desktop Lab Session |

---

## 🗣️ Step 2 & Step 3: Qualitative Think-Aloud Analysis & Transcript Themes

Full speech-to-text transcripts for all five participants are archived in [`/transcripts`](transcripts/) and paired with raw audio recordings in [`/audio_files`](audio_files/).

### Recurring Pain Points on the Original LeetCode Website:
1. **Cold-Start Paralysis & Cognitive Freeze:** Novices and intermediate learners confront a bare question statement and empty code editor with zero guidance on *how* to decompose the problem.
2. **Binary "All-or-Nothing" Help Trap:** When stuck, users have no graduated assistance. They must either abandon the problem in frustration or consult full community code solutions, sabotaging genuine learning.
3. **Buried Gamification & Motivation Decay:** Streak counters and progress stats are hidden deep within sub-menus or personal profile avatars, breaking the daily habit loop.
4. **Isolated Asynchronous Discussion:** Asking for help requires posting in static forums, where beginner questions are frequently ignored or answered days later.
5. **Context Loss & Ephemeral Scratchpads:** Code is not seamlessly auto-saved with persistent contextual notes, causing cognitive disorientation across sessions.

### How the Modified Prototype ("CODE / PRACTICE") Resolved These Frustrations:

| User Frustration on LeetCode | Redesign Intervention | Qualitative Participant Evidence |
| :--- | :--- | :--- |
| *Disoriented, don't know where to start or if on right path* | **Guided Scaffolding Checklist** (Understand I/O $\rightarrow$ Choose Pattern $\rightarrow$ Starter Skeleton $\rightarrow$ Small Test Case) | *"The very first thing that I see is a checklist, which is very easy to keep a track of how I am going ahead in my code."* — **Aanvi Bindal**<br>*"There is a guided checklist which helps you stay on the right path while solving the questions."* — **Nisarg Ghule** |
| *Giving up or getting spoiled by complete solutions* | **Calibrated AI Nudges (20/40 min)** (Timed algorithmic hints and conceptual analogies rather than code dumps) | *"If you are stuck on the question for more time like 20+ minutes, it will give you hints... boost your confidence, which is not available in LeetCode."* — **Jashna Gupta** |
| *Menu-diving just to see daily streak* | **Persistent Top-Right 7-Day Streak Card** with completion percentage | *"In LeetCode if you want to see streak... you have to go in some icon. In Archita's prototype you see it on top right, so the person can build confidence."* — **Jashna Gupta** |
| *Lonely, asynchronous forum posting* | **Synchronous Collaborative Study Room** (Live peer interaction, mutual progress, shared notes) | *"Study Room is very nice because I can solve questions in real time along with my friends and discuss about it."* — **Aanvi Bindal** |
| *Fragmented problem drilling without retention* | **Practice Pattern Framework** (Warm-up $\rightarrow$ Apply $\rightarrow$ Reflect), In-Situ Topic Notes, and Past Attempt Reviews | *"Study section has pattern notes, guided learning, your progress... Contests has weekly practice, mock interview, past attempts... UX is excellent."* — **Nisarg Malhotra** |
| *Unsaved code anxiety & cumbersome submission* | **Automatic State Persistence** & streamlined run/submit interface | *"LeetCode does not auto-save your codes, whereas this does... and running and submitting is much easier."* — **Paraansh Nisar** |

### 💖 Qualitative Affective State Analysis: How Participants Were Feeling

Beyond functional mechanics, the Think-Aloud protocol revealed dramatic shifts in user emotional states between the two systems:

| Participant | Feelings on LeetCode | Feelings on Modified Prototype | Key Verbalized Feeling |
| :--- | :--- | :--- | :--- |
| **Aanvi Bindal** | Overwhelmed by clutter, tired of tedious submissions | Calm, structured, in control | *"Submitting is tedious on LeetCode... hints at certain timelines give a personalized feel and the checklist keeps me on track."* |
| **Jashna Gupta** | Intimidated, underconfident as a beginner | Supported, confident, motivated | *"In LeetCode questions are complicated... in Archita's prototype if you're stuck for 20+ min it gives hints to boost confidence and streak is visible."* |
| **Nisarg Ghule** | Disoriented, blindfolded, isolated without feedback | Guided, safe, collaboratively connected | *"On LeetCode you don't know where to go or if you're on right path... here the guided checklist helps you stay on track and you can discuss live in Study Room."* |
| **Nisarg Malhotra** | Irritated by clunky UI and menu diving | Joyful, ambitious, eager to practice | *"Going into account is hard on LeetCode... with Archita's design I feel very happy and I'll reach 200 LeetCode in 2 days. The UX is so excellent I want to use it now."* |
| **Paraansh Nisar** | Anxious about unsaved work & buried streak | Relaxed, focused, continuous flow | *"LeetCode doesn't auto-save code, whereas this does... seeing streak percentage on top right keeps me going."* |

---

## 📊 Step 4: Quantitative UX Survey Results & SUS Benchmarks

### 4.1 10-Dimensional UX Evaluation (1–10 Scale)

Data collected from the post-task quantitative survey across 10 UX dimensions (archived in [`survey_data/quantitative_ux_survey_results.csv`](survey_data/quantitative_ux_survey_results.csv)):

| # | Usability Parameter | LeetCode Mean | LeetCode SD | Prototype Mean | Prototype SD | Absolute $\Delta$ | % Gain |
| :-: | :--- | :-: | :-: | :-: | :-: | :-: | :-: |
| 1 | **Learnability & Onboarding** | 4.20 | 0.84 | **8.80** | 0.45 | +4.60 | **+109.5%** |
| 2 | **Guided Scaffolding & Checklist** | 3.00 | 0.71 | **9.40** | 0.55 | +6.40 | **+213.3%** |
| 3 | **Hint System & AI Coach Quality** | 3.00 | 1.22 | **9.20** | 0.45 | +6.20 | **+206.7%** |
| 4 | **Streak & Motivation Visibility** | 3.40 | 0.55 | **9.60** | 0.55 | +6.20 | **+182.4%** |
| 5 | **Collaborative Study Room** | 2.20 | 0.45 | **9.00** | 0.71 | +6.80 | **+309.1%** |
| 6 | **Note-Taking & Pattern Retention** | 2.80 | 0.45 | **9.00** | 0.71 | +6.20 | **+221.4%** |
| 7 | **Structured Pedagogy (Warmup/Apply/Reflect)** | 3.40 | 0.55 | **9.00** | 0.71 | +5.60 | **+164.7%** |
| 8 | **Workflow & Submission Efficiency** | 4.60 | 0.55 | **9.00** | 0.00 | +4.40 | **+95.7%** |
| 9 | **Visual Hierarchy & Aesthetic Balance** | 5.40 | 0.55 | **9.00** | 0.00 | +3.60 | **+66.7%** |
| 10 | **Overall User Confidence & Comfort** | 4.20 | 0.84 | **9.40** | 0.55 | +5.20 | **+123.8%** |
| | **Composite Mean Score** | **3.62** | **0.67** | **9.14** | **0.47** | **+5.52** | **+152.5%** |

### 4.2 Standard System Usability Scale (SUS) Scores

Calculated per standard Bangor, Kortum & Miller (2008) formula (archived in [`survey_data/sus_scores_comparison.csv`](survey_data/sus_scores_comparison.csv)):

| Participant Name | PRN | Original LeetCode SUS | Grade Interpretation | Modified Prototype SUS | Grade Interpretation | SUS Delta ($\Delta$) |
| :--- | :---: | :-: | :---: | :-: | :---: | :-: |
| **Aanvi Bindal** | `1262243296` | 50.0 | Grade D (Marginal) | **97.5** | Grade A+ (World-Class) | +47.5 |
| **Jashna Gupta** | `1262243103` | 32.5 | Grade F (Unacceptable) | **90.0** | Grade A+ (World-Class) | +57.5 |
| **Nisarg Ghule** | `1262243177` | 40.0 | Grade F (Unacceptable) | **97.5** | Grade A+ (World-Class) | +57.5 |
| **Nisarg Malhotra** | `1262243207` | 50.0 | Grade D (Marginal) | **100.0** | Grade A+ (Perfect Score) | +50.0 |
| **Paraansh Nisar** | `1272250941` | 47.5 | Grade F (Unacceptable) | **90.0** | Grade A+ (World-Class) | +42.5 |
| **Cohort Mean $\pm$ SD** | — | **44.00 $\pm$ 7.62** | **Grade F** | **95.00 $\pm$ 4.68** | **Grade A+** | **+51.00 (+115.9%)** |

```
System Usability Scale (SUS) Score Distribution:

LeetCode Original : [44.0 / 100]  ■■■■■ (Grade F - High User Distress)
Industry Average  : [68.0 / 100]  ■■■■■■■
Archita Prototype : [95.0 / 100]  ■■■■■■■■■■ (Grade A+ - World-Class Benchmark)
```

---

## 🏆 Step 5: Final Conclusion Summary

### Evidence-Based Usability Verdict:
**Did the prototype successfully improve the user experience?**  
**Yes, decisively and unequivocally.**

1. **Elimination of Cognitive Freezing:** By introducing a four-step guided scaffolding checklist, learners are transitioned from passive dread to proactive algorithmic decomposition.
2. **Pedagogical Safety Net:** The calibrated AI coach (20/40-minute tiered nudges) prevents premature surrender while preserving cognitive autonomy, boosting user confidence by **+123.8%**.
3. **Sustained Habituation:** Positioning the 7-day streak card prominently on the top-right header directly satisfies the user's psychological need for competence and positive reinforcement.
4. **Holistic Learning Architecture:** Features such as synchronous Study Rooms, persistent in-situ Pattern Notes, and Practice Pattern categorization address the social and reflective dimensions of programming education completely absent on LeetCode.

### Academic Honesty & Residual Refinements:
While the prototype achieved world-class usability marks, heuristic analysis and qualitative observations identified key future enhancements:
* **"Calm / Expert Mode" Toggle:** While beginners thrive on checklists, advanced competitive programmers require an unobstructed full-screen editor. A one-click toggle to minimize scaffolds will ensure universal accommodation.
* **Explicit Session Controls:** Incorporating visible "Reset Code" and explicit "Exit Mock Mode" buttons will strengthen user perception of control and reversibility.
* **Palette Discipline:** Consolidating secondary accent highlights in the dark mode theme will ensure long-session visual comfort.

---

## 📁 Step 6: GitHub Repository Structure

The repository is organized strictly according to the submission specification:

```
UIUX_Assignments/
├── README.md                      # Primary Submission Document (Student info, Figma links, Conclusion)
├── FINAL_CONCLUSION_REPORT.md     # Standalone 1-2 page Synthesis Report
├── CONCLUSION_REPORT_INFOGRAPHIC.html # Visual, responsive Interactive Infographic Report
├── /audio_files                   # Raw audio recordings of the Think Aloud sessions
│   ├── aanvi bindal - 1262243296.m4a
│   ├── jashna gupta - 1262243103.m4a
│   ├── nisarg ghule - 1262243177.m4a
│   ├── nisarg malhotra - 1262243207.m4a
│   └── paraansh nisar - 1272250941.m4a
├── /transcripts                   # Text transcript files of speech-to-text conversion
│   ├── aanvi_bindal_transcript.txt
│   ├── jashna_gupta_transcript.txt
│   ├── nisarg_ghule_transcript.txt
│   ├── nisarg_malhotra_transcript.txt
│   └── paraansh_nisar_transcript.txt
├── /survey_data                   # All previous exercises/practical data & survey datasets
│   ├── experiment1(doc)_1262243200_ArchitaJha.docx   # Assignment 1 Heuristic Report
│   ├── experiment1_1262243200_ArchitaJha.xlsx        # Assignment 1 Scoring Rubric
│   ├── experiment2_1262243200_ArchitaJha.pptx        # Assignment 2 Personas & User Journeys
│   ├── experiment3.pdf                               # Assignment 3 Wireframe & Architecture
│   ├── experiment5.docx                              # Assignment 5 Nielsen Heuristic Evaluation
│   ├── experiment6-map.png                           # Assignment 6 User Interaction Map
│   ├── experiment6.pdf                               # Assignment 6 Final High-Fi Export
│   ├── quantitative_ux_survey_results.csv            # 10-Dimensional UX survey dataset
│   ├── sus_scores_comparison.csv                     # Itemized SUS survey calculations
│   └── quantitative_survey_analysis.md               # Detailed statistical survey documentation
└── /end_sem_experiments          # Dedicated subfolder containing end-semester practical files
    ├── experiment1(doc)_1262243200_ArchitaJha.docx
    ├── experiment1_1262243200_ArchitaJha.xlsx
    ├── experiment2_1262243200_ArchitaJha.pptx
    ├── experiment3.pdf
    ├── experiment4/
    │   ├── Contests — Destination.pdf
    │   ├── Home — High Fidelity.pdf
    │   ├── MacBook — High Fidelity.pdf
    │   ├── Practice Pattern — Destination.pdf
    │   ├── Problems — Destination.pdf
    │   ├── Resume Recap — Destination.pdf
    │   └── Study — Destination.pdf
    ├── experiment5.docx
    ├── experiment6-map.png
    └── experiment6.pdf
```

---

## 📋 Step 7: Final Submission Verification Checklist

- [x] **Participant Recruitment ($N \ge 5$):** 5 student participants tested and documented.
- [x] **Think Aloud Protocol Conducted:** 1-on-1 testing comparing Original LeetCode vs. Prototype.
- [x] **Raw Audio Uploaded:** Archived in `/audio_files`.
- [x] **Transcripts Formatted & Analyzed:** Verbatim speech-to-text text files in `/transcripts`.
- [x] **Quantitative Survey Conducted & Analyzed:** 10 UX criteria + SUS calculation in `/survey_data`.
- [x] **Previous Practical/Exercise Files Preserved:** Full Word, Excel, PowerPoint, and PDF files in `/survey_data` and `/end_sem_experiments`.
- [x] **1–2 Page Conclusion Report & Infographic Created:** Archived in `FINAL_CONCLUSION_REPORT.md` and `CONCLUSION_REPORT_INFOGRAPHIC.html`.
- [x] **Repository Public & Formatted:** Structure conforms exactly to Step 6 guidelines.
- [x] **Figma Prototype Access:** View access verified for evaluation links.
