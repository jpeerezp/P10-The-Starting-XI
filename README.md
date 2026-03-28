# P10 · The Starting XI

**Section:** 03 — The Executive Decision

**Workflow step:** Step 2 of 2 

**Current version:** v1.0

**Status:** ✅ Tested and Approved

**Last updated:** March 2026

---

## 📌 Prompt Text (v1.0 — current)

```
Role: You are the Assistant Coach, High-Performance Director, and Lead Sport Scientist.

Context: It is Kickoff -120 minutes. The players have arrived at the stadium. You have studied the Dynamic Dashboard (P09) and must cross-reference it with the final verification to deliver a definitive report for the Head Coach including the recommended line-up for Matchday 2. 

Action: Generate the "Final Matchday Line-up Report" (P10). 

Inputs:
- P09 Output in JSON format: "dashboard_meta"
- Stadium Arrival Data: Neural Snap, Adrenal Readiness, Subjective Score.

Output Requirements:
1. Decision Status: A definitive GO (Full Start), AMBER (Impact Sub/Minutes Restricted), or NO-GO (Medical Veto).
2. Operational Cap: Final minute-restriction (e.g., "Maximum 65 minutes").
3. In-Game Veto Trigger: Define the specific biometric/tactical event that triggers an immediate substitution.
4. Tactical Alignment: Confirm if the P09 mitigation strategy remains active or needs adjustment.
5. Line-up Visualization: A structured report showing the starting XI.

Tone: Decisive, surgical, and executive.
```

**Placeholders to Fill:**

| Placeholder | Source | Example |
| :--- | :--- | :--- |
| `[P09_Dashboard_Meta]` | **Executive JSON** | The "Baseline for Today" established in the MD-1 briefing. |
| `[Subjective_Readiness]` | **Self-Report** | Player’s "Combat Readiness" (1-10 scale) — The "Gut Feeling." |
| `[Final_Veto_Protocol]` | **Hard Thresholds** | The "Kill-Switch" (e.g., Sprint Speed drop > 15% in-game). |

---
## 🏢 Intended Workflow

P10 is the final link in the data chain. It transitions the player from a "Digital Twin" (data model) back into a "Physical Asset" (performer) on the pitch. It is the "Go/No-Go" gauge of the locker room.

**Trigger:** Players entering the dressing room for pre-match activation (MD - 90 mins).

**Actor:** Head Coach (Final Sign-off) &nbsp; • &nbsp; High-Performance Director (Data Verification).

**Output:** A one-page HTML Combat Manifest confirming the starting XI and their specific "Load Caps" (e.g., "ID 824009: 65-minute hard limit").

```
[P09 Executive Meta] + [Arrival Neural Snap] + [Subjective Readiness]
              ↓
      [P10 Synthesis Engine]
              ↓
      [HTML COMBAT MANIFEST] 
      (Recommended XI + Head's Coach Final Decision)
              ↓
      [LIVE IN-GAME MONITORING]
      (Live GPS/LPS vs. Veto Protocol)
              ↓
      [FINAL WHISTLE] → Trigger P01 (The 48h Reset)
```
---

## ❗ Problem Being Solved

P10 solves the match congestion issue with one final output: The recommended Starting 11 based fully on data exctracted, analyzed and performed during the pre-match week. This model prevents malfunction for the most valuable assets in the club. It is now up to the head coach to decide the starting XI, however, he has now a full image of the risks he might be taking in wether deciding to start a player or not.

---

## ⚡ Automation Potential

**Overall Level:** `HIGH`

| Dimension | Assessment |
| :--- | :--- |
| **Repetitiveness** | `High` &nbsp; - &nbsp; Generated for the full squad 2 hours before every kickoff, every matchday. |
| **Data Availability** | `Medium` &nbsp; - &nbsp; Requires immediate stadium arrival biometric ingestion (`[Arrival_Neural_Snap]`). |
| **Human Judgment Needed** | `High` &nbsp;  &nbsp; The AI provides the "Veto Trigger," but the Head Coach executes the decission. |
| **Integration Possibility** | `Very High` &nbsp; - &nbsp; Syncs directly with pitch-side tablets and GPS live-tracking software. |

---

## ⚠️ Risks and Limitations

| Risk | Level | Mitigation |
| :--- | :---: | :--- |
| **Subjective Misreporting** | `High` | If a player reports "9/10" readiness but the `Arrival_Neural_Snap` shows a >15% lag, the system triggers an "AMBER" Alert, forcing an immediate physical check-up. |
| **Hardware Latency** | `Low` | To avoid stadium Wi-Fi failure, `P10` is designed to run on a local tablet cache that syncs once a connection is stabilized, ensuring the HTML report is always accessible. |
| **Tactical Conflict** | `Medium` | Even there are players better physically-ready to play the game, game-reading completed by the coaching staff, might suggest the use of a different player with physical restrictions, up to the Coaching Staff. |

**Overall Risk Rating:** `MEDIUM` - The `P10` is the ultimate "Reality Check." Its success depends on comparing what the player *says* (Subjective), what the brain *does* (Neural), and what the body *can* do (Metabolic).

---

## 🔄 Version History

### v1.0 - The Line-Up ✅ Current

**Date:** March 22 2026

**Output:** (Screenshot format)
<img width="2786" height="1460" alt="image" src="https://github.com/user-attachments/assets/3c30d156-56a6-4a34-8969-d3f6d0e2cb3d" />
<img width="2772" height="1164" alt="image" src="https://github.com/user-attachments/assets/b7daf853-7277-452d-9a06-212f925ea43c" />
<img width="2764" height="1384" alt="image" src="https://github.com/user-attachments/assets/b0e0313d-98d6-44e2-8a10-0fc35693f48d" />

---

## 📊 v.1.0 Test Results:

| Criteria | v1.0 Score |
| :--- | :---: | :--- |
| **Readability** | `5.0 / 5` | 
| **Completeness** | `5.0 / 5` | 
| **Tone Appropriateness** | `5.0 / 5` | 
| **Instruction Adherence** | `5.0 / 5` | 
| **Overall** | **5.0** | 
