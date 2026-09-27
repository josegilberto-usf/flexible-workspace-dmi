# Flexible Workspace Digital Maturity Assessment
**USF Digital Transformation — Group 12**[cite: 3, 4]

An interactive diagnostic instrument designed to evaluate enterprise capability across the flexible workspace and coworking industry[cite: 3]. The tool benchmarks an operator's ability to navigate master lease liabilities, elastic occupancy commitments, and automated space-as-a-service operations across five core capability dimensions[cite: 3, 4].

---

## Live Assessment Tool
Deployed via GitHub Pages:  
**`https://<your-username>.github.io/<your-repo-name>/`**

---

## Maturity Framework & Capability Dimensions

The diagnostic assesses an operator's operational state across five independent capability dimensions from Stage 1 (*Ad Hoc*) to Stage 5 (*Optimized*)[cite: 3]:

| # | Dimension | Scope & Diagnostic Focus |
|---|---|---|
| 1 | **Workspace & Portfolio Data**[cite: 3] | How operators collect and connect occupancy, lease, and financial data across locations[cite: 3]. Evaluates progression from manual headcounts to real-time sensor streams and automated margin-at-risk dashboards[cite: 3, 4]. |
| 2 | **Member Digital Experience**[cite: 3] | How digitally coworking members join, book, access, and renew their space[cite: 3]. Evaluates self-service autonomy from paper sign-ups to unified mobile platforms with SCIM enterprise provisioning[cite: 3, 4]. |
| 3 | **Workspace Operations Automation**[cite: 3] | How much of an operator’s access, cleaning, maintenance, and energy use runs automatically[cite: 3]. Tracks advancement from paper work orders to predictive vendor dispatching and dynamic IoT BMS controls[cite: 3, 4]. |
| 4 | **AI-Enabled Portfolio Intelligence**[cite: 3] | How operators use AI and analytics for space pricing, demand forecasting, and site selection[cite: 3]. Assesses progression from static rate cards to live dynamic pricing, churn early warnings, and macro absorption models[cite: 3, 4]. |
| 5 | **Digital Operating Model**[cite: 3] | Whether governance, skills, and change management can scale digital tools[cite: 3]. Evaluates IT alignment from an ad-hoc cost center to cross-functional product squads and audited ROI capital governance[cite: 3, 4]. |

---

## Maturity Stages

Dimension maturity is scored on an explicit 1.0 to 5.0 scale[cite: 3]:

* **Stage 1 (1.0–1.9) — Ad Hoc:** Operations rely on manual routines, paper logs, and disconnected legacy spreadsheets; digital capabilities are absent or fragmented[cite: 3].
* **Stage 2 (2.0–2.9) — Emerging:** Isolated digital tools and regional pilots exist, but definitions vary and processes require heavy human coordination[cite: 3].
* **Stage 3 (3.0–3.9) — Developing:** Systematic, centralized tools are deployed across core hubs; data models and workflows remain siloed between departments[cite: 3, 4].
* **Stage 4 (4.0–4.5) — Integrated:** Unified digital platforms link physical facilities directly to financial reporting, automated operations, and verified change management[cite: 3].
* **Stage 5 (4.6–5.0) — Optimized:** Algorithmic closed-loop systems continuously execute dynamic pricing, space allocation, and predictive facility adjustments with automated governance[cite: 3, 4].

---

## Strategic Interpretation Profiles

Rather than evaluating isolated scores, the diagnostic interprets holistic score patterns to prescribe targeted interventions[cite: 3]. Profiles evaluate sequentially (first match applies)[cite: 3]:

1. **Digital Starting Line (Pattern: All dimensions < 2.5):** The operator runs on spreadsheets and manual coordination with no shared digital foundation[cite: 3].  
   *Next Action:* Appoint one digital owner with a 90-day mandate to standardize utilization tracking at every location[cite: 3].
2. **Digital Frontrunner (Pattern: All dimensions ≥ 4.0):** Every capability is mature and integrated; additional internal efficiency yields diminishing returns[cite: 3].  
   *Next Action:* Launch an occupancy-analytics product sold directly to enterprise clients managing hybrid workforces[cite: 3].
3. **Building on Sand (Pattern: Portfolio Data ≥ 1.0 below all other dimensions):** Digital apps, automation, and AI models operate on fragmented, untrusted foundational data[cite: 3].  
   *Next Action:* Pause new AI initiatives and consolidate booking, access, and lease records into a single platform with shared data definitions[cite: 3].
4. **Digitalized but Not Transforming (Pattern: Member Experience ≥ 3.5 and AI Intelligence ≥ 1.5 lower):** Customer touchpoints appear digital, but member usage data is not fed into core revenue, forecasting, or expansion decisions[cite: 3].  
   *Next Action:* Leverage member booking telemetry to pilot algorithmic demand forecasting and dynamic pricing in one market for one quarter[cite: 3].
5. **Execution Gap (Pattern: Operating Model ≥ 1.0 below all other dimensions):** Technical platforms exist but stall after regional rollouts due to lack of ownership, digital skills, and change governance[cite: 3].  
   *Next Action:* Establish a cross-functional governance council with named owners, clear decision rights, and dedicated change management budgets per deployment[cite: 3].

---

## Technical Specifications

* **Single-File Architecture:** Fully self-contained inside `index.html`—runs client-side in any modern web browser without requiring a backend server or runtime dependencies[cite: 2].
* **Deterministic Scoring Engine:** Questions carry explicit integer weights (1–5) aggregated into true dimension averages; ties follow deterministic index sorting[cite: 2, 4].
* **Dynamic Visualization:** Responsive radar chart dynamically generated via Chart.js (CDN), visualizing multidimensional maturity boundaries in real time[cite: 2].
* **No Storage Footprint:** Operates completely in-memory with no cookies, tracking scripts, or local storage overhead[cite: 2].

---

## Group Roles & Deliverables

* **Member A — Framework Designer:** Capability dimensions, Stage 1–5 descriptions, and strategic Interpretation Guide[cite: 3].
* **Member B — Question Author:** 15 observable, leveled diagnostic indicators and Question Design Rationale (400–600 words)[cite: 4].
* **Member C — Tool Builder:** Single-file HTML/CSS/JavaScript application, Chart.js radar integration, and automated profile scoring engine[cite: 2].
