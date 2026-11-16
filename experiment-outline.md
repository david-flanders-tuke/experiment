# How Professionals Manage Shared Resources: Research Experiment Outline

## Overview: What is this research about?
Every day, professionals across the public sectors have to make tough choices about shared resources—whether that is public funding, emergency equipment, or critical information. Often, what is best for an individual in the short term can deplete the resource for everyone else in the long run. 

This project combines **structured decision-making games**, **follow-up interviews**, and **targeted personality questions** to understand how people cooperate, build trust, and manage shared resources under pressure. The insights gathered from real professionals are used to build and calibrate multi-agent computer simulations that test better rules and information-sharing strategies.

---

## Theoretical Foundation
This experiment adapts the Nobel Prize-winning framework developed by **Elinor Ostrom** (and extended with **Juan-Camilo Cárdenas**) on how groups successfully govern **Common Property Resources (CPRs)** without top-down control. While classic economic experiments often test university students, this study focuses on professionals who manage high-stakes shared systems in the public sector (aka municipal marketplaces).

---

## How the Experiment Works

* **Participants:** Approximately **50 professionals** total, organized into experimental markets of around **10 participants** (used to simulate classic **7-person** CPR market dynamics).
* **Session Length:** ~90 minutes per participant.
* **Three-Stage Session Flow:**
  1. **Choice-Based Scenarios (The "What"):** Participants play tailored economic games involving resource allocation, trust, and group cooperation, generating quantitative behavioral data.
  2. **Motivation Elicitation (The "Why"):** Immediately after each decision, participants answer brief qualitative interview questions explaining their reasoning and how social norms affect their choices.
  3. **Simulation Calibration & Review (Optional):** Real-world behavioral profiles are used to calibrate AI/multi-agent market simulations, and participants can optionally review the simulation outputs to validate how accurately the models reflect their actual decision-making.

---

## Part 1: Behavioural Economic Games

Participants play a curated selection of validated **Economic Experimental Games (EEGs)** tailored to their specific professional context (alongside variations such as Coordination or Signalling Games):

| Game | How It Works | What It Measures |
| :--- | :--- | :--- |
| **Dictator Game (DG)** | Player A receives a sum of money and decides how much (if any) to give to Player B, who has no say in the outcome. | Baseline altruism and generosity |
| **Ultimatum Game (UG)** | Player A proposes a split of money. Player B can accept (both get paid) or reject (neither gets anything). | Fairness norms and willingness to punish unfairness |
| **Trust Game (TG)** | Player A sends money to Player B; the amount is tripled. Player B then decides how much to return. | Trust (investor) and reciprocity (trustee) |
| **Prisoner’s Dilemma (PD)** | Two players simultaneously choose to cooperate or defect. Defecting pays more individually, but mutual cooperation beats mutual defection. | Tension between self-interest and mutual benefit |
| **Public Goods Game (PGG)** | Players contribute from a private endowment into a common pool, which is multiplied and split equally among everyone. | Willingness to contribute vs. free-riding |
| **Commons Dilemma (CD)** | Players harvest from a shared, finite pool (e.g., a fishery). Over-harvesting depletes the resource for the entire group. | Sustainable resource stewardship vs. over-exploitation |

### Example Session Walkthrough: The Dictator Game
To bridge quantitative choices with qualitative reasoning, each game follows a structured script:

1. **Scenario:** *"You are given $100. You must decide how much of this to give to another anonymous participant. This person has no say in the matter and will receive whatever amount you decide to give them. You will never meet this person, and they will never know who you are."*
2. **Initial Choice:** *"How much of the $100 would you give to the other participant?"*
3. **Motivation Follow-Up:** *"Could you briefly explain why you chose to give that specific amount? What was the primary thought process behind your decision?"*
4. **Social Norms Check:** *"Imagine I told you that in previous sessions, the average participant gave only $20. Knowing this, would you reconsider your allocation? Why or why not?"*

---

## Part 2: Personality & Attitudinal Measures

To understand *why* different people make different choices in identical scenarios, participants complete targeted, validated personality items matched specifically to the games they play:

* **HEXACO Personality Inventory (`HEXACO-PI-R`):**
  * *Honesty-Humility (H-Factor):* Sincerity, fairness, and greed avoidance.
  * *Agreeableness vs. Anger:* Tendency toward forgiveness versus retaliation ("negative reciprocity").
* **International Personality Item Pool (`IPIP-NEO`):**
  * *Trust:* General belief in the good intentions of others.
  * *Excitement-Seeking:* Appetite for risk and novelty.
* **Facet-level Measurement of Personality (`Facet MAP`):**
  * *Altruism & Fairness:* Pro-social motivation and equity sensitivity.
  * *Extrospection:* "Theory of Mind"—the tendency to model and anticipate the strategic motives of others.
  * *Risk-Aversion:* Direct preference for certainty over gamble.

---

## Part 3: Deploying Digital Twin Profiles in a Simulated Municipal Marketplace

Once real-world participants complete the behavioural games (Part 1) and personality assessments (Part 2), their quantitative choices, qualitative reasoning, and psychometric traits are combined to create calibrated **Digital Twin** profiles. Rather than leaving these profiles as static survey data, the experiment places them inside a simulated **Common Property Resource Economic Experimental Game (CPR EEG)**—modeled as a **Municipal Marketplace**—to test how leaders respond to the downstream consequences of their own rules.

### 1. How the Simulated Municipal Marketplace Works
* **From Individual Profile to Multi-Agent Sandbox:** Each participant's psychometric and behavioural data forms a baseline "digital phenotype". That Digital-twin is placed into a simulated municipal environment (such as a cross-departmental reorganization, talent-sharing pool, or emergency budget allocation) alongside other AI agent archetypes—including cooperative *Guardians* and self-interested *Gollums*—each operating with their own strategies and incentives.
* **Counterfactual Biofeedback:** When a decision-maker proposes a policy (for example, mandating flat quotas or relying on temporary agency hires), the simulation fast-forwards through multi-year knock-on effects. It makes hidden systemic traps visible—such as budget depletion, staff churn, talent hoarding, etc.
* **Experimental Design:** the experiment evaluates individual leaders across multiple independent municipal crises (e.g., Traffic, Water, and Budget scenarios). The researcher first observes the participant's default policy choices (**Phase A: Baseline**), then introduces the Digital Twin simulation in a staggered sequence (**Phase B: Intervention**) to isolate how seeing counterfactual outcomes changes their thinking.
### 2. How the Researcher Measures Insights & Behavioural Shift
To verify whether interacting with the Digital Twin triggers a genuine **epistemic recalibration** (updating a leader's internal mental model rather than eliciting polite agreement), the post-simulation debrief measures four sequential indicators:

1. **Confidence Shift (Proximal Biomarker):** Using a Likert scale, the participant re-rates their confidence in their original policy choice after watching the simulation play out. A sharp drop in confidence signals that the counterfactual feedback disrupted their initial assumption.
2. **Mechanism of Action Validation:** The researcher asks the participant to pinpoint the exact simulation failure or visual feedback that broke their original mental model (e.g., recognizing that hitting a short-term metric caused long-term resource collapse), confirming that the simulation's dynamics —not external pressure— drove the shift.
3. **Real-World Commitment:** The participant identifies one existing rule, KPI, or policy in their actual workplace that they plan to rewrite to prevent a real-world Tragedy of the Commons.

### 3. Quantifying Policy Evolution with Institutional Grammar (`ADICO`)
To turn open-ended interview answers into rigorous, comparable data, the researcher parses the participant's baseline policy (Phase A) and post-simulation policy (Phase 3) using Elinor Ostrom and Sue Crawford's **Institutional Grammar Tool (`ADICO` syntax)**:

| Syntax Element | Question Answered | Baseline Policy Example (Command-and-Control) | Post-Simulation Policy Example (Incentive-Compatible) |
| :--- | :--- | :--- | :--- |
| **`[A]` Attributes** | *Who does this rule apply to?* | Department Directors | Department Directors |
| **`[D]` Deontic** | *Is it required, forbidden, or permitted?* | **Must** (Obligation) | **May** (Permission) |
| **`[I]` Aim** | *What specific action is taken?* | Surrender staff for 2 days a week | Trade staff hours into a shared "Common Pool Time" ledger |
| **`[C]` Conditions** | *When and where does it apply?* | When requested by central executive | During the quarterly KPI evaluation cycle |
| **`[O]` Or Else** | *What is the consequence?* | HR cuts their departmental training budget | Executive Board scores performance without a 1.5x systemic multiplier |

### 4. Evaluation Rubric: Grading the *In Silico* Treatment Effect
By combining confidence scores, causal reasoning, and `ADICO` shifts, each session is classified into one of three outcomes:

* **Refractory (No Shift):** Confidence drops by 0–1 points; the participant blames the simulation for being "unrealistic" and sticks to punitive, top-down rules (defective Nash equilibrium).
* **Partial Response:** Confidence drops by 2–4 points; the participant recognizes the hidden resource trap but struggles to design an alternative rule structure on their own.
* **Complete Epistemic Recalibration:** Confidence drops by 5+ points; the participant accurately diagnoses the underlying behavioural trap and independently designs a cooperative, incentive-compatible rule (`ADICO` shift from top-down coercion to a Pareto-optimal shared pool).

## Key Methodological References
* Cárdenas, J. C., & Ostrom, E. (2004). What do people bring into the game? Experiments in the field about cooperation in the commons. *Agricultural Systems*, 82(3), 307–326.
* Cárdenas, J. C. (2011). Behavioural and Experimental Economics for Environmental Policy. In J. C. J. M. van den Bergh (Ed.), *Handbook of Environmental and Resource Economics*. Edward Elgar.
* Ostrom, E., Gardner, R., & Walker, J. (1994). *Rules, Games, and Common-Pool Resources*. University of Michigan Press.
