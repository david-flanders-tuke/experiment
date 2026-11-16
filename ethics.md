| Ethics Governance | Part 1: Live Commons Reproduction (EEG-Human) | Part 2: Behavioural Elicitation & Simulation (EEG-Sim) |
| --- | --- | --- |
| **Approving Institution** | Curtin University (Human Research Ethics Office) | The University of Melbourne (Office of Research Ethics & Integrity) |
| **Approval Reference** | `HRE2025-0382` (InfoEd Record: 78463 / 75529) | `2026-33001-78908-3` (Project ID: 33001) |
| **Approved Project Title** | *The games researchers play: measuring collaboration in the institution* | *Improving Suboptimal Resource Management in Australian Public Services* |
| **Chief / Responsible Investigator** | Dr Karl Huang (Curtin University) | Dr Juan Pablo Franco Ulloa (Centre for Brain, Mind and Markets, UniMelb) |
| **Collaborating Investigators** | Prof Cameron Neylon, Dr Juan Pablo Franco, David Tuke Flanders (PhD Candidate & Moderator) | Dr Karl Huang, David Tuke Flanders (External Investigators, Curtin University) |
| **Primary Empirical Focus** | Live 5–7 player CPR time-allocation game among academic research teams competing for grant funding | Individual Economic Experimental Games (EEGs), psychometric profiling, and 7-agent *in silico* market calibration |
| **Target Cohorts** | Australian academic researchers (ARC grant applicants/recipients) | Public-good & shared-resource professionals (researchers, emergency services, building certifiers, insurance brokers) |

# Ethics Approval & Experimental Design Summary

## Part 1: Human-Group Reproduction Experiment (Curtin University)

* **Ethics Approval:** Curtin University HREC (`HRE2025-0382`)
* **Project Title:** *The games researchers play: measuring collaboration in the institution*

### 1.1 Methodology

This study employs a mixed-methods experimental design adapting the Cárdenas & Ostrom (2004) field experiment to modern Australian public sector institutions, e.g. University Academics and researchers . Competitive grant funding—specifically Australian Research Council (ARC) taxpayer-funded pools—and researcher time are modelled as a Common-Pool Resource (CPR) marketplace. By observing lead academic peers who share disciplinary ties, the methodology captures what Cárdenas and Ostrom term the *"context people bring into the game"* (shared norms, reputation, trust, and collegial influence).

### 1.2 Experimental Design

* **Participants & Staged Rollout:**
  * **Group Structure:** Bounded groups of $n \in [5, 7]$ English-speaking academic researchers within the same discipline or research network who have applied for or received ARC grant funding.
  * **Stage 1 (Alpha):** Trial workshops with local Curtin University research groups ($5$–$8$ participants).
  * **Stage 2 (Beta):** Workshops with research teams across Australian universities and academic conferences (conducted face-to-face using online bidding forms or remotely via Microsoft Teams).
* **Round-by-Round Action Arena (Minimum 7 Rounds, ~90 Minutes):**
  1. **Baseline Silent Bidding Rounds:** Participants independently allocate bounded time budgets across individual vs. collective research priorities without communication. Payoffs are governed by an asymmetric payoff table where aggregate over-bidding depletes the shared resource pool, operationalising scarcity and the Tragedy of the Commons.
  2. **Communication Rounds (Cheap Talk / Open Discussion):** The moderator opens structured discussion windows allowing participants to negotiate group strategies, build trust, and coordinate bids without external enforcement.
  3. **Institutional Rule & Sanction Rounds:** Collective rules and graduated policy sanctions (penalties for over-extraction/defection) are introduced—either endogenously agreed upon by the group or exogenously imposed—to test institutional remedies.
* **Post-Game Elicitation:**
  * All players complete a structured post-game online questionnaire assessing six behavioural dimensions:
    1. Reciprocity & Influence
    2. Reputation & Trust
    3. Risk & Uncertainty
    4. Motivation & Cognitive Biases
    5. Environmental/Institutional Variables
    6. Team Dynamics & Time Valuation
  * Optional 30-minute semi-structured Institutional Analysis and Development (IAD) interviews are conducted, particularly targeting statistical or behavioural outliers.

### 1.3 Proposed Data Analysis

* **Quantitative Game-Theoretic Analysis:**
  * Round-by-round individual bids $x_{i,t}$ and aggregate group extractions $\sum_{i=1}^{n} x_{i,t}$ are scored against the asymmetric payoff matrix.
  * Group and individual trajectories are benchmarked against two formal theoretical reference points:
    1. **Non-Cooperative Nash Equilibrium ($x^{\text{Nash}}$):** Self-interested equilibrium predicting resource over-depletion.
    2. **Cooperative Pareto Optimum ($x^{\text{Pareto}}$):** Joint payoff-maximising allocation preserving resource sustainability.
  * Efficiency ratios measure treatment effects across baseline, communication, and sanctioned rounds.
* **Qualitative & Mixed-Methods Integration:**
  * Natural-language dialogue from Microsoft Teams recordings/transcripts, open-ended survey responses, and follow-up interviews undergo Thematic Analysis, Content & Discourse Analysis, and Natural Language Processing (NLP) (sentiment and word-frequency/text mining).
  * Qualitative Comparative Analysis (QCA), pattern matching, and triangulation link qualitative governance mechanisms (e.g., peer trust, leadership, perceived power asymmetries) directly to quantitative Pareto efficiency scores to inform research funding policy design.

---

## Part 2: Behavioural Elicitation & In Silico Simulation (University of Melbourne)

* **Ethics Approval:** The University of Melbourne OREI (`2026-33001-78908-3`)
* **Project Title:** *Improving Suboptimal Resource Management in Australian Public Services*

### 2.1 Methodology

Conducted through the Centre for Brain, Mind and Markets (Department of Finance, University of Melbourne) in collaboration with Curtin University, this study combines incentive-compatible Economic Experimental Games (EEGs), qualitative motivation elicitation, psychometric profiling, and multi-agent computational simulation.

Rather than making statistical inferences to the general population, the study treats each professional domain—academic researchers, emergency service workers, building construction certifiers/surveyors, and insurance professionals—as a bounded micro-population census. Real human decision profiles are de-identified and transformed into calibrated computational agents to simulate $7$-person CPR marketplaces (mirroring the group size of Cárdenas & Ostrom, 2004) under varying levels of information asymmetry and institutional governance.

### 2.2 Experimental Design

* **Sample Size & Combinatorial Robustness Design ($N \approx 50$ Total):**
  * Approximately $50$ professionals are recruited across sectors, structured into domain-specific pools of $m \approx 10$ participants per experimental marketplace.
  * **Why 10 participants for a 7-player game?** Calibrating $10$ distinct agent profiles for a $7$-agent simulation ($k = 7$) provides a rigorous census of a closed micro-population while enabling $\binom{10}{7} = 120$ combinatorial agent line-ups per market. Researchers systematically "swap out" individual personality and behavioural profiles to test structural robustness and sensitivity to specific behavioural archetypes (e.g., conditional cooperators vs. free-riders).
* **Two-Part Elicitation Protocol (60–90 Minutes via Qualtrics & Microsoft Teams):**
  1. **Part A — Incentive-Compatible Choice Scenarios (EEGs):** Participants make quantitative resource-allocation choices across a curated battery of validated economic games (compensated via an AUD 10 show-up fee + performance-linked payout up to AUD 150, following Cummings et al., 1995; Hertwig & Ortmann, 2001):
     * **Dictator Game (DG):** Pure altruism and baseline pro-sociality.
     * **Ultimatum Game (UG):** Strategic fairness, inequity aversion, and negative reciprocity/punishment.
     * **Trust / Investment Game (TG):** Baseline trust and trustworthiness/reciprocity.
     * **Prisoner's Dilemma (PD):** Bilateral cooperation vs. defection incentives.
     * **Public Goods Game (PGG):** Multi-player conditional cooperation and free-riding dynamics.
     * **Commons Dilemma (CD):** Shared resource extraction under depletion thresholds.
     * **Bomb Risk Game:** Risk tolerance and Prospect Theory loss-aversion framing.
  2. **Part B — Qualitative Motivation Elicitation & Psychometric Battery:**
     * Immediately following quantitative choices, structured follow-up prompts capture expectations of peers, conditional adaptation after observing low group contributions, and risk/loss framing strategies.
     * Participants complete selected, validated psychometric scales mapping personality traits to game-theoretic parameters (targeted facets from BFI-2, HEXACO-100, IPIP-30 NEO, and Facet MAP, alongside demographic controls and validated self-reported data-quality checks from Rad et al., 2018 and Wood et al., 2017).
* **In Silico Simulation & Optional Verification Interview:**
  * De-identified empirical data calibrates computational agents operating in simulated $7$-player CPR markets to test institutional rules and information-sharing regimes without exposing human systems to untested policy friction.
  * **Optional Member-Checking Follow-Up:** Participants may review the simulation outputs generated from the calibrated market and verify or critique how accurately the model reflects their reasoning.

### 2.3 Proposed Data Analysis

* **Behavioural-to-Agent Parameter Calibration:**
  * Quantitative EEG choices and psychometric facet scores are mapped across six ontological behavioural tiers: Pro-Sociality & Fairness, Trust & Dependability, Negative Reciprocity & Altruistic Punishment, Strategic Thinking ($k$-Level Reasoning), Risk Tolerance & Loss Aversion (Prospect Theory), and Conflict/Governance Style.
  * Data quality is screened using reverse-coded attention and effort items prior to agent parameterisation.
* **Computational Market & Robustness Analysis:**
  * Simulated $7$-agent CPR games evaluate system-level resource sustainability, depletion rates, information-asymmetry distortions, and institutional rule performance against Nash Equilibrium and Pareto Efficiency benchmarks.
  * **Profile-Swapping Sensitivity Analysis:** Comparing outcome distributions across combinatorial agent subsets isolates the marginal impact of specific personality traits and cognitive biases on collective resource stability.
* **Qualitative Thematic & Verification Analysis:**
  * Recorded interviews are transcribed via Microsoft Teams, de-identified, and thematically coded to link stated cognitive heuristics with observed quantitative choices—capturing dynamic, state-dependent adaptation rather than static behavioural labels.
  * Feedback from optional post-simulation follow-up interviews provides qualitative validation (member checking) of simulation fidelity.

---

## Ethical Governance, Privacy & Data Stewardship

To uphold research integrity across both universities and protect participants, reviewers, and open-science users, the following safeguards are enforced across all workflows:

1. **Voluntary Informed Consent & Power-Dynamic Protections:**
   * Written Plain Language Statements (PLS) and signed Consent Forms are completed prior to data collection.
   * In group settings (Part 1), individual consent channels and post-game coercion checks ensure collegial or workplace hierarchies do not pressure individuals into participating. In Part 2, no researchers hold teaching/grading authority over student participants, eliminating dependent relationships.
2. **Rigorous De-Identification & Open-Science Archiving:**
   * Personal identifiers are separated and stripped from transcripts, survey matrices, and gameplay logs before statistical analysis or computational agent calibration.
   * Under Part 2's Extended Consent provisions, only fully de-identified datasets and aggregated simulation parameters are retained for reproducible research repositories—never raw identifiable interview recordings.
3. **Enterprise Data Security:**
   * **Curtin University (`HRE2025-0382`):** Identifiable/re-identifiable working files and archival backups are stored exclusively on Curtin's secure enterprise R: drive and OAIC-compliant Australian cloud infrastructure; virtual sessions use university-approved Microsoft Teams.
   * **University of Melbourne (`2026-33001-78908-3`):** Survey instruments run on university-licensed Qualtrics, transcriptions are processed via University-approved Microsoft Teams, and research records are managed on password-protected University of Melbourne research storage servers restricted to named investigators.

---

## Key Methodological References

* Cárdenas, J.-C., & Ostrom, E. (2004). *What do people bring into the game: experiments in the field about cooperation in the commons* (CAPRi Working Paper No. 32). International Food Policy Research Institute (IFPRI).
* Cárdenas, J.-C. (2011). Behavioural and Experimental Economics for Environmental Policy. In *Handbook of Environmental and Resource Economics*. Edward Elgar.
* Cummings, R. G., Harrison, G. W., & Rutström, E. E. (1995). Homegrown Values and Hypothetical Surveys: Is the Dichotomous Choice Approach Incentive-Compatible? *The American Economic Review*, 85(1), 260–266.
* Hertwig, R., & Ortmann, A. (2001). Experimental practices in economics: A methodological challenge for psychologists? *Behavioral and Brain Sciences*, 24(3), 383–403.
* Kahneman, D., & Tversky, A. (1979/2013). Prospect Theory: An Analysis of Decision under Risk. *Econometrica*, 47(2), 263–291.
* Ostrom, E. (1990). *Governing the Commons: The Evolution of Institutions for Collective Action*. Cambridge University Press.
* Ostrom, E., Gardner, R., & Walker, J. (1994). *Rules, Games, and Common-Pool Resources*. University of Michigan Press.
* Rad, M. S., Martingano, A. J., & Ginges, J. (2018). Toward a psychology of *Homo sapiens*: Making psychological science more representative of the human population. *PNAS*, 115(45), 11401–11405.
* Soto, C. J., & John, O. P. (2017). The next Big Five Inventory (BFI-2): Developing and assessing a hierarchical model with 15 facets to enhance bandwidth, fidelity, and predictive power. *Journal of Personality and Social Psychology*, 113(1), 117–143.
* Wood, D., Harms, P. D., Lowman, G. H., & DeSimone, J. A. (2017). Response speed and response consistency as mutually validating indicators of data quality in online samples. *Social Psychological and Personality Science*, 8(4), 454–464.

---

## Ethics Contacts & Independent Inquiries

* **Part 1 — Curtin University Human Research Ethics Committee (HREC):**
  * **Reference:** `HRE2025-0382` | **Chief Investigator:** Dr Karl Huang (`Karl.Huang@curtin.edu.au`) | **Moderator:** David Tuke Flanders (`David.Flanders@postgrad.curtin.edu.au`)
  * **Independent Ethics Contact:** Curtin University Human Research Ethics Office (`HREC@curtin.edu.au`)
* **Part 2 — The University of Melbourne Office of Research Ethics and Integrity (OREI):**
  * **Reference:** `2026-33001-78908-3` | **Responsible Researcher:** Dr Juan Pablo Franco Ulloa (`jpfranco@unimelb.edu.au`)
  * **Independent Ethics Contact:** Research Integrity Administrator, Office of Research Ethics and Integrity, The University of Melbourne (`research-integrity@unimelb.edu.au` | Tel: +61 3 8344 1376)
