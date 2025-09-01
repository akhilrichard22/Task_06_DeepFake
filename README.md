# Task_06_Deep_Fake

## 🎯 Project Overview
This task explores the creation of a simple “deep fake” style interview using AI-generated voices.  
The interview is based on the **2023 Syracuse University Women’s Lacrosse statistics dataset**, which I previously cleaned and analyzed.  

The objective: transform my earlier factual narrative into an **audio Q&A interview** between a sports interviewer and an analyst.

---

## 📊 Dataset & Analysis
**Dataset:** [2023 SU Women’s Lacrosse Statistics](https://cuse.com/sports/womens-lacrosse/stats/2023)

**Preparation & Metrics:**
- Removed incomplete records
- Standardized position abbreviations (A=Attack, M=Midfield, D=Defense)
- Calculated:
  - Points = Goals + Assists
  - Shot % = (Goals / Shots) × 100

**Questions used in interview:**
1. How many games did the team play?  
2. Who were the top 3 scorers by total points?  
3. What was the team’s win-loss record?  

---

## 🎤 Interview Script
See [`script.txt`](./script.txt).

---

## 🛠️ Tools & Workflow
1. **Script Preparation**  
   - Converted dataset analysis into a Q&A interview format (3 questions).  

2. **Voice Generation (Speechify Studio)**  
   - Created a free account at [Speechify Studio](https://studio.speechify.com/scratchpad).  
   - Used free 10-minute trial.  
   - Entered the full script and added in the **Instructions** box:  
     > “Please generate 2 different voices, one for the interviewer and one for the analyst.”  
   - Speechify automatically alternated the two voices.  

3. **Export**  
   - Exported the generated audio as `deepfake_interview.mp3`.  
   - No additional editing required.  

---

## 📂 Repository Structure
