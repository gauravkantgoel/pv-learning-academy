# PV Learning Academy

**Interactive pharmacovigilance training - free, open-source, zero dependencies.**

A browser-based learning platform for pharmacovigilance professionals. The first module covers **Signal Management** end-to-end: from fundamentals through detection, evaluation, action, and integrated scenarios with realistic exercises that test judgment, not just recall.

🔗 **[Launch the app →](https://gauravkantgoel.github.io/pv-learning-academy/)**

---

## What's inside

### Module 1: Signal Management

Five progressive stages, each with teaching content, interactive visuals, and a scenario-based checkpoint:

| Stage | What it covers | Interactive exercise |
|-------|---------------|---------------------|
| **Fundamentals** | What is a signal, signal vs risk, signal lifecycle | Signal ladder + lifecycle flow (→ PBRER → RMP) |
| **Detection** | Methods, disproportionality, subgroups, error review | **SDR triage table**  prioritize 8 flagged drug-event pairs |
| **Evaluation** | Chronology, confounding, plausibility, clinical coherence | **Challenge the recommendation** — agree/disagree with reasoned actions |
| **Action & Tracking** | Proportionate response, DHPC, risk minimization, monitoring | Action planner with seriousness × certainty × mechanism |
| **Scenarios** | Integrated signal management across all stages | **Branching crisis scenario** — "The Veritanib Crisis: 72 Hours" |

### Key features

- **Scenario-based checkpoints** : clinical vignettes with 4 plausible options, not obvious true/false
- **SDR triage exercise** : realistic Signal Detection Review output for a fictional kinase inhibitor (Veritanib) with ROR, CI, seriousness flags, DME/class-effect tags, and clinical context per row
- **Evaluation challenge** : sliders drive a credibility score, system recommends an action, learner must agree or disagree with structured reasoning
- **Mock ICSR narrative** : read a case, assess time-to-onset, dechallenge, confounding, and signal support
- **Branching scenario engine** : 4-step crisis simulation with consequences, scoring, and replayability
- **GVP IX regulatory mapping** : collapsible panel per stage with GVP, ICH, CIOMS references
- **Signal lifecycle visual** : shows how signals flow from detection → PBRER §16 → RMP update
- **Active recall** : write-first textareas with self-assessment before model answer reveal
- **Competency certificate** : auto-generated on completion with print/export support
- **Sticky learning design** : analogies, elaboration, dual coding, interleaving across all stages

### Upcoming modules

- Aggregate Reporting (PSUR/PBRER)
- Risk Management (RMP)
- Case Processing & E2B
- Regulatory Intelligence
- Medical Coding (MedDRA/WHODrug)

---

## Technical details

- **Single HTML file** : no build step, no framework, no server
- **Zero external dependencies** : only Google Fonts (DM Sans + Newsreader)
- **Works offline** : save the file and open it locally
- **~3,400 lines** : all content, CSS, and JavaScript in one portable file
- **LocalStorage** : progress persists across sessions (no backend)
- **Responsive** : works on desktop, tablet, and mobile
- **Print-ready** : competency panel has print-optimized CSS


## Contributing

Contributions welcome — especially:

- **New modules** (PSUR/PBRER, RMP, case processing, MedDRA coding)
- **Additional scenarios** for existing stages
- **Translations** for global PV teams
- **Accessibility improvements**
- **Bug reports** via Issues

---

## License

MIT — use it, share it, adapt it.

---

Built with care for the pharmacovigilance community.
