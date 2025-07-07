# Writeup
# OPenCTI

## Objective
-Investigate the CaddyWiper malware campaign and the APT37 intrusion set using OpenCTI. Specifically, you’ll:

-Determine the earliest CaddyWiper sighting date from the ESET CaddyWiper March 2022 report

-Identify which MITRE ATT&CK technique CaddyWiper uses for execution

-Count how many malware-to-technique relationships exist for that execution technique

-List the three tools that leveraged that execution technique in 2016

-Find out which country APT37 is attributed to

-Enumerate the ATT&CK techniques APT37 employs for initial access

### Skills Learned

-Navigating OpenCTI Reports: Locating STIX IDs, creation dates, confidence levels, and descriptive metadata in the ESET CaddyWiper March 2022 report.

-Mapping to ATT&CK: Using the Global Kill Chain view under Knowledge → Arsenal to spot which ATT&CK technique (T1106 – Native API) CaddyWiper uses for execution.

-Relationship Analysis: Querying the attack‐pattern page to count malware relations (113 total) linked to T1106.

-Temporal Filtering: Filtering the Tools Arsenal for “uses” relationships in 2016 to extract BloodHound, Empire, and ShimRatReporter.

-Intrusion-Set Investigation: Exploring the APT37 page under Knowledge → Intrusion sets to read its origin, “North Korea” attribution, and examine its Global Kill Chain for initial-access techniques (T1189 – Drive-by Compromise, T1566 – Spearphishing Attachment).



### Tools Used

-OpenCTI Reports module for browsing and reading STIX‐formatted intelligence (ESET CaddyWiper March 2022).

-Knowledge → Arsenal → Global Kill Chain to view and filter ATT&CK techniques.

-Knowledge → Arsenal → Tools to list tool entities and filter by start/stop dates.

-Knowledge → Attack Patterns to inspect relationship counts.

-Knowledge → Intrusion Sets for APT37’s metadata and kill-chain mapping.

-Built-in search and filter functions across OpenCTI workspaces.

## Steps

---
Ref.1: Scenario
<img width="964" alt="1- scenario" src="https://github.com/user-attachments/assets/2be217f3-5b4a-4879-a1df-643ce8693cb5" />
---
Ref.2: reports (caddywiper, ESET march2022)
<img width="1256" alt="2- reports (caddywiper, ESET march2022)'" src="https://github.com/user-attachments/assets/38023e2d-b9aa-40dc-86ee-65dca6b7eb7e" />
---
Ref.3: Q1 answer
<img width="1017" alt="3- q1 answer" src="https://github.com/user-attachments/assets/71db3042-b033-4dc9-9a42-cb4672518a57" />
---
Ref.4: Question 2
<img width="428" alt="4- question 2" src="https://github.com/user-attachments/assets/1e319b8c-c4d5-481d-a707-f44745a310a8" />
---
Ref.5: knowledge tab, global kill chain, executation
<img width="1268" alt="5- knowledge tab, global kill chain, executation" src="https://github.com/user-attachments/assets/a933f181-6d46-4c12-b3c4-42659d794cfc" />
---
Ref.6: Question 2 answer
<img width="988" alt="6- question 2 answer" src="https://github.com/user-attachments/assets/27102916-98a4-4e0e-a29c-5b23e1b19987" />
---
Ref.7: Question 3
<img width="457" alt="7- question 3" src="https://github.com/user-attachments/assets/63a81c58-3e95-4125-b4ce-6396a37eca65" />
---
Ref.8: attack patterns, native api, knowledge
<img width="1275" alt="8- attack patterns, native api, knowledge" src="https://github.com/user-attachments/assets/0802b8e8-5184-47cc-9697-b01036561695" />
---
Ref.9: Question 3 answer
<img width="1037" alt="9- question 3 answer" src="https://github.com/user-attachments/assets/87d6df19-d0f1-4e42-9ad9-d498d0a16674" />
---
Ref.10: Question 4
<img width="947" alt="10- question 4" src="https://github.com/user-attachments/assets/9d4f64ca-ff40-402d-86d3-a588518bd4e4" />
---
Ref.11: native api, tools, 2016
<img width="1256" alt="11- native api, tools, 2016" src="https://github.com/user-attachments/assets/4c760a70-68e3-4702-8dd4-2b7671b8bd65" />
---
Ref.12: Question 4 answer
<img width="995" alt="12- question 4 answer" src="https://github.com/user-attachments/assets/5556a01a-3c09-4a9d-8886-1cc234300b46" />
---
Ref.13: Question 5
<img width="335" alt="13- question 5" src="https://github.com/user-attachments/assets/876f004f-af4b-435b-8f4d-7b46b81dedc7" />
---
Ref.14:  APT37 intrustion sets, description = north korea
<img width="1265" alt="14- APT37 intrustion sets, description = north korea" src="https://github.com/user-attachments/assets/02a47730-4c6e-4507-b464-84277bf8e26d" />
---
Ref.15: Question 5 answer
<img width="974" alt="15- q5 answer" src="https://github.com/user-attachments/assets/9b1b470b-c1e8-493f-a22e-803073efc403" />
---
Ref.16: Question 6
<img width="590" alt="16- question 6" src="https://github.com/user-attachments/assets/f0e4b8aa-04e7-4275-991f-1d20e6b6a271" />
---
Ref.17: knowledge, global kill chains initial access
<img width="1274" alt="17- knowledge, global kill chains initial access" src="https://github.com/user-attachments/assets/37c5d74a-9cd7-48b4-a254-984d666e4c91" />
---
Ref.18: Question 6 answer
<img width="1118" alt="18- q6 answer" src="https://github.com/user-attachments/assets/0e6b9b3f-4c73-436b-a6a5-95bb4404e8bc" />
---
























