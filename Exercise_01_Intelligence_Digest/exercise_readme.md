# Exercise: Intelligence Digest Builder

### 1. Training Objective
Officers will learn how to use AI to synthesize fragmented, multi-source intelligence data into a concise, actionable summary. The focus is on identifying patterns and key threats within a high-volume information environment.

### 2. Task for Officers
Convert the raw intelligence log into a **30-second operational briefing** for the Brigade Commander. The briefing must highlight the most critical threats and provide a clear assessment of the next 6 hours.

### 3. AI Prompt to Use
> "ACT AS A BRIGADE INTELLIGENCE OFFICER (S-2). BASED ON THE LOG ENTRIES PROVIDED, GENERATE A 30-SECOND OPERATIONAL BRIEFING FOR THE COMMANDER. THE BRIEFING MUST USE THE 'BLUF' (BOTTOM LINE UP FRONT) METHOD, HIGHLIGHTING THE THREE MOST CRITICAL TRENDS/THREATS, AND CONCLUDE WITH AN ASSESSMENT OF THE ENEMY'S LIKELY ACTION IN THE NEXT 6 HOURS. THE TONE MUST BE PROFESSIONAL, CONCISE, AND MILITARY-GRADE."

### 4. Step-by-Step Exercise Instructions
*   **Step 1:** Introduce the "Silent Guardian" scenario and the influx of data.
*   **Step 2:** Provide the raw log entries to the officers (found in `data_readme.md`).
*   **Step 3:** Ask officers to input the log data and the AI prompt into the LLM.
*   **Step 4:** Review the output for brevity and accuracy.
*   **Step 5:** Facilitate a discussion on whether the AI correctly identified the correlation between the "Bridge," the "NGO Vehicles," and the "Sandstorm."

### 5. Example AI Output
**Commander, BLUF:** We assess a high probability of a coordinated insurgent attack or sabotage targeting the MSR Green bridge within the next 4-6 hours, timed with an incoming sandstorm that will ground our air support.

**Key Points:**
1.  **Imminent Sabotage:** SIGINT and patrol reports confirm targeting of the Sector 7 bridge; structural tampering has already begun.
2.  **Covert Infiltration:** NGO-style vehicles are moving unchecked, potentially transporting the 'strangers' reported in Al-Kut for a coordinated strike.
3.  **Environmental Hazard:** A severe sandstorm at 1900Z will eliminate our ISR and CAS capabilities, creating a window of opportunity for the enemy while our long-range comms are failing.

**Assessment:** Enemy intends to isolate FOB Sentinel by destroying the Sector 7 bridge under the cover of the sandstorm, preventing logistics resupply and ground reinforcement.

### 6. Learning Outcome
Officers will understand how AI can "connect the dots" across different intelligence disciplines (SIGINT, HUMINT, RECCE) to identify a cohesive enemy plan that might be missed when viewing logs individually.

### 7. Instructor Debrief
*   **Point 1:** How did the AI handle the 'noise'? (e.g., the water supply vs. the bridge threat).
*   **Point 2:** Discuss the risks of relying on AI for "connect-the-dots" analysis—could it "hallucinate" a connection that isn't there?
*   **Point 3:** Emphasize that AI saves time in drafting, but the officer must verify the grid coordinates and source reliability.
