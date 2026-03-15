# PV Learning Academy

**Interactive pharmacovigilance training - free, open-source, zero dependencies.**

A browser-based learning platform for pharmacovigilance professionals. The first module covers **Signal Management** end-to-end: from fundamentals through detection, evaluation, action, and integrated scenarios — with realistic exercises that test judgment, not just recall.

🔗 **[Launch the app →](https://YOUR_USERNAME.github.io/pv-learning-academy/)**

---

## What's inside

### Module 1: Signal Management

Five progressive stages, each with teaching content, interactive visuals, and a scenario-based checkpoint:

| Stage | What it covers | Interactive exercise |
|-------|---------------|---------------------|
| **Fundamentals** | What is a signal, signal vs risk, signal lifecycle | Signal ladder + lifecycle flow (→ PBRER → RMP) |
| **Detection** | Methods, disproportionality, subgroups, error review | **SDR triage table** — prioritize 8 flagged drug-event pairs |
| **Evaluation** | Chronology, confounding, plausibility, clinical coherence | **Challenge the recommendation** — agree/disagree with reasoned actions |
| **Action & Tracking** | Proportionate response, DHPC, risk minimization, monitoring | Action planner with seriousness × certainty × mechanism |
| **Scenarios** | Integrated signal management across all stages | **Branching crisis scenario** — "The Veritanib Crisis: 72 Hours" |

### Key features

- **Scenario-based checkpoints** — clinical vignettes with 4 plausible options, not obvious true/false
- **SDR triage exercise** — realistic Signal Detection Review output for a fictional kinase inhibitor (Veritanib) with ROR, CI, seriousness flags, DME/class-effect tags, and clinical context per row
- **Evaluation challenge** — sliders drive a credibility score, system recommends an action, learner must agree or disagree with structured reasoning
- **Mock ICSR narrative** — read a case, assess time-to-onset, dechallenge, confounding, and signal support
- **Branching scenario engine** — 4-step crisis simulation with consequences, scoring, and replayability
- **GVP IX regulatory mapping** — collapsible panel per stage with GVP, ICH, CIOMS references
- **Signal lifecycle visual** — shows how signals flow from detection → PBRER §16 → RMP update
- **Active recall** — write-first textareas with self-assessment before model answer reveal
- **Competency certificate** — auto-generated on completion with print/export support
- **Sticky learning design** — analogies, elaboration, dual coding, interleaving across all stages

### Upcoming modules

- Aggregate Reporting (PSUR/PBRER)
- Risk Management (RMP)
- Case Processing & E2B
- Regulatory Intelligence
- Medical Coding (MedDRA/WHODrug)

---

## Technical details

- **Single HTML file** — no build step, no framework, no server
- **Zero external dependencies** — only Google Fonts (DM Sans + Newsreader)
- **Works offline** — save the file and open it locally
- **~3,400 lines** — all content, CSS, and JavaScript in one portable file
- **LocalStorage** — progress persists across sessions (no backend)
- **Responsive** — works on desktop, tablet, and mobile
- **Print-ready** — competency panel has print-optimized CSS

---

## Deploy to GitHub Pages

### Quick setup (5 minutes)

1. **Create a new repository** on GitHub named `pv-learning-academy`

2. **Upload the files:**
   ```
   pv-learning-academy/
   ├── index.html        ← the app
   ├── og-image.svg      ← social sharing preview
   └── README.md         ← this file
   ```

3. **Update the OG meta tags** in `index.html` — find and replace `YOUR_USERNAME` with your GitHub username (3 occurrences):
   ```
   og:image  → https://raw.githubusercontent.com/YOUR_USERNAME/pv-learning-academy/main/og-image.svg
   og:url    → https://YOUR_USERNAME.github.io/pv-learning-academy/
   twitter:image → same as og:image
   ```

4. **Enable GitHub Pages:**
   - Go to repository **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: **main** / root
   - Click **Save**

5. **Your app is live** at `https://YOUR_USERNAME.github.io/pv-learning-academy/`

### Custom domain (optional)

If you want `learn.yourdomain.com`:

1. Add a `CNAME` file to the repo containing: `learn.yourdomain.com`
2. In your DNS provider, add a CNAME record: `learn` → `YOUR_USERNAME.github.io`
3. In GitHub Pages settings, enter the custom domain
4. Enable "Enforce HTTPS"

---

## Social sharing preview

The `og-image.svg` generates a preview card when the link is shared on LinkedIn, Twitter, or Slack. To convert it to PNG for broader platform compatibility:

```bash
# Using Inkscape
inkscape og-image.svg --export-type=png --export-width=1200 --export-height=630 --export-filename=og-image.png

# Or screenshot at 1200×630 in a browser
```

Then update the `og:image` and `twitter:image` meta tags to point to `og-image.png`.

---

## LinkedIn post template

Here's a ready-to-use post for sharing:

> **I built a free interactive learning app for pharmacovigilance signal management.**
>
> It covers the full GVP IX workflow — from "what is a signal" to realistic crisis scenarios — with exercises that test judgment, not just definitions:
>
> 📊 SDR triage table — prioritize flagged drug-event pairs from a realistic screening output
> ⚡ Evaluation challenge — agree/disagree with the system's recommended action
> 📋 Mock ICSR narrative — assess a real-style case report
> 🔀 Branching crisis simulation — manage a hepatotoxicity signal over 72 hours
>
> No login, no install, works in any browser. Built for safety scientists, PV associates, epidemiologists, regulatory teams, and anyone preparing for PV roles.
>
> 🔗 [LINK]
>
> More modules (aggregate reporting, RMP, case processing) coming.
>
> #pharmacovigilance #drugsafety #signalmanagement #pvtraining

---

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
