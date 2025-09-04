

# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

# Prompt pattern choosen:Template / Fill-in-the-blank pattern
## 📝 Prompt 1: Basic Maintenance Report
Generate a maintenance report in the following template:

Date: [Insert date]  
Equipment: [Insert equipment name]  
Location: [Insert location]  
Issue Observed: [Describe the issue]  
Action Taken: [Steps performed]  
Status: [Resolved/Pending/Requires follow-up]  
Next Scheduled Maintenance: [Insert date or remarks]

## Output
### 🛠 Maintenance Report

Date: 04-09-2025
Equipment: Air Conditioning Unit – AC-203
Location: Server Room, Block B
Issue Observed: Cooling efficiency dropped; unit was blowing warm air.
Action Taken:

Inspected air filter and condenser coils.

Found clogged filter restricting airflow.

Replaced the air filter with a new one.

Cleaned condenser coils.
Status: ✅ Resolved – Unit is functioning normally.
Next Scheduled Maintenance: 15-10-2025 (Preventive cleaning and performance check).

## 📝 Prompt 2: Detailed Report with Technician Info
Fill out the following maintenance report template:

Report ID: [Auto-generate or Insert ID]  
Date & Time: [Insert date and time]  
Technician: [Insert technician name]  
Equipment Name/ID: [Insert equipment details]  
Issue Detected: [Brief description]  
Root Cause: [Diagnosis]  
Action Taken: [Steps performed]  
Spare Parts Used: [If any]  
Final Status: [Operational/Needs Further Check]  
Remarks: [Additional notes]

## Ouput 
### 🛠 Maintenance Report

Report ID: MR-2025-0786
Date & Time: 04-09-2025, 10:30 AM
Technician: R. Kumar
Equipment Name/ID: Generator – GEN-4521
Issue Detected: Generator failed to start during routine power backup test.
Root Cause: Faulty starter motor due to prolonged wear and overheating.
Action Taken:

Checked battery voltage and fuel supply (both normal).

Inspected starter motor wiring and connections.

Replaced faulty starter motor with a new unit.

Conducted load test to confirm operation.
Spare Parts Used: Starter Motor (Model SM-10X)
Final Status: ✅ Operational – Generator started successfully and passed load test.
Remarks: Recommend monitoring starter motor temperature weekly to prevent recurrence.

## 📝 Prompt 3: Incident-Based Report
Create a maintenance report using the template below:

Incident Date: [Insert date]  
Reported By: [Name/Department]  
Equipment/Asset: [Insert equipment name or ID]  
Problem Description: [Explain issue]  
Corrective Action: [Describe maintenance performed]  
Preventive Suggestion: [How to avoid recurrence]  
Current Status: [Resolved/Pending]  
Follow-Up Required: [Yes/No]

## Output
### 🛠 Maintenance Report

Incident Date: 03-09-2025
Reported By: IT Department – Network Admin Team
Equipment/Asset: UPS System – UPS-1189
Problem Description: UPS failed to supply backup power during a short power outage, causing temporary server downtime.
Corrective Action:

Inspected UPS battery and charging circuit.

Identified degraded battery cells.

Replaced with a new 12V/9Ah battery pack.

Performed backup power test successfully.
Preventive Suggestion: Schedule quarterly battery health checks and replace batteries every 2 years to avoid sudden failures.
Current Status: ✅ Resolved
Follow-Up Required: No

## 📝 Prompt 4: Tabular Format Report Fill the following table with maintenance report details: 

## Ouput 
### 🛠 Maintenance Report (Tabular Format)

| Date     | Equipment           | Issue Description                    | Action Taken                               | Technician | Status     | Next Maintenance |
|----------|---------------------|--------------------------------------|--------------------------------------------|------------|------------|-----------------|
| 02/09/25 | Air Conditioner     | Unit not cooling properly            | Replaced clogged air filter & cleaned coils | A. Sharma  | ✅ Resolved | 15/10/25        |
| 03/09/25 | UPS – UPS-1189      | Failed to supply backup during outage | Replaced degraded battery pack              | R. Kumar   | ✅ Resolved | 03/12/25        |
| 04/09/25 | Generator – GEN-4521 | Starter motor not working             | Replaced faulty starter motor               | S. Mehta   | ✅ Resolved | 20/11/25        |
| 04/09/25 | Elevator – LIFT-07  | Jerky movement between floors         | Lubricated guide rails & reset control unit | D. Prakash | 🔄 Pending  | 06/09/25        |
# RESULT: 
The prompt for the above said problem executed successfully
