# Exercise: Situation Report (SITREP) Generator (Indian Army Context)

### 1. Training Objective
Officers will practice using AI to transform a chaotic, high-pressure streams of operational updates (Op logs, RT traffic, Medical reports) into a structured, professional **E-Sitrep** or a General Staff format report. The focus is on prioritizing life-saving decisions (CASEVAC) amid tactical distractions.

### 2. Task for Indian Staff Officers
You are the **Adjutant** or the **GSO-2 (Ops)** at a Battalion Headquarters. You are receiving a deluge of information from the encounter site at Hajipura (found in `data_readme.md`). The Sector Commander (Brigadier) has called and wants a structured SITREP on his desk in 5 minutes.

**Your Task:**
1.  Read the raw logs and transcripts.
*   Identify the most critical information: Enemy status, Casualty status, Civil unrest level, and Logistics bottlenecks.
*   Structure the SITREP using standard Indian Army serials (Call Sign, DTG, Situation-Enemy/Own, Personnel, Equipment, Intentions).

### 3. AI Prompt to Use
> "ACT AS AN ADJUTANT OF A RASHTRIYA RIFLES BATTALION. BASED ON THE PROVIDED ENCOUNTER LOGS, GENERATE A FORMAL MILITARY SITREP FOR THE SECTOR COMMANDER. USE THE STANDARD INDIAN ARMY SERIALS (A TO J) INCLUDING: CALL SIGN, DTG, SITUATION (ENEMY), SITUATION (OWN), PERSONNEL STATUS (INCLUDING CASEVAC), LOGISTICS STATUS, AND COMMANDER'S INTENTIONS. THE TONE MUST BE CLINICAL, PRECISE, AND HIGHLIGHT THE URGENT NEED FOR AIR CASEVAC AND THE RISK OF CIVILIAN UNREST."

### 4. Step-by-Step Exercise Instructions
*   **Step 1:** Distribute the Hajipura encounter logs (`data_readme.md`).
*   **Step 2:** Instruct participants to highlight three "Urgent Decisions" BEFORE running the AI.
*   **Step 3:** Have officers input the logs and the AI prompt.
*   **Step 4:** Compare the AI's "Commander's Intentions" section with the officer's own tactical plan.
*   **Step 5:** Facilitate a discussion: Did the AI correctly prioritize the bleeding Havildar over the stuck fuel tanker?

### 5. Example AI Output (Project E-Sitrep Format)
**TO: HQ SECTOR RR**
**FROM: 15 RR (KUMAON)**
**DTG: 101400K APR 26**
**SITREP SERIAL: 004/APR/26**

**A. CALL SIGN:** TIGER-15 (15 RR)
**B. SITUATION (ENEMY):** 2-3 HCT (including Abu Hamza and Sajid) cordoned in house at Grid UR 5560 2230. Firefight ongoing. Use of automatic weapons/UBGL confirmed.
**C. SITUATION (OWN):** Alpha/Bravo Coy in inner cordon. Ghatak Platoon on standby for final intervention. CASO launched at 0400h.
**D. PERSONNEL STATUS:** 1x Havildar GSW (Shoulder). Condition stable but blood loss significant. **URGENT AERIAL CASEVAC REQUIRED.**
**E. CIVILIAN SITUATION:** High unrest. 200+ crowd at site. 500+ blocking NH-44. 1x Civilian injury by stray bullet. State Police/CRPF managing outer cordon.
**F. LOGISTICS/POL:** First-line ammo resupply and POL tanker delayed due to NH-44 blockage and civilian interference. Current ETA: +2 hours.
**G. INTENTIONS:**
   1. Execute surgical intervention by Ghatak Platoon before sunset to prevent night breakout.
   2. Establish landing zone (LZ) for Cheetah Helicopter at BHQ for air CASEVAC.
   3. Divert 1x Platoon to secure Rear BHQ against advancing mob.

### 6. Learning Outcome
Officers will recognize how AI can act as a "Filter"—scrubbing through radio chatter and log entries to produce a report that is already 90% ready for the General's signature, saving precious minutes in a CASEVAC window.

### 7. Instructor Debrief
*   **The "Human-in-the-Loop":** Discuss why the officer must still verify the Grid references produced by the AI (AI might hallucinate a grid if handwriting or speech-to-text is blurry).
*   **Terminology:** Discuss how terms like "Ghatak," "Naka," "JCO," and "CASO" help the AI understand the severity of the situation better than generic Western military terms.
*   **Moral Decision:** Did the AI suggest a way to handle the civilian crowd? If not, why?
