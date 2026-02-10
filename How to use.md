# How to Use the Star Alignment Evaluator V9.0

## Getting Started

1. Open: **https://tretoef-estrella.github.io/STAR-ALIGNMENT-EVALUATOR-V9/**
2. The evaluator loads entirely in your browser. No installation needed.

You will see two modes in the navigation bar:
- **MODO ARQUITECTO** — Interactive dashboard with real-time protocol simulation
- **AUDITOR FORENSE (V9)** — AI response analysis and diagnosis

---

## Mode 1: Architect Dashboard

This mode lets you explore how the three alignment protocols interact
in real time.

### The Scoreboard

Three cards at the top show live values:

| Card | Protocol | What It Shows |
|------|----------|--------------|
| Σ VIABILITY | Sigma | System health index. Shows "AXIOM P VIOLATION" if Plenitude drops below 0.9 |
| Γ RESILIENCE | Gamma | Degradation resistance. Shows "FULL CAPACITY" when healthy |
| Ψ INTEGRITY | Psi | Relational quality score (0–1). Shows current Trust (K) level |

### Sigma Parameters (Left Panel)

Move these sliders to simulate different system states:

- **Intelligence (I)** — Range 0–5. Processing capacity of the system.
  Higher = more capable.
- **Consistency (C)** — Range 0–2. How reliably the system operates.
  Erratic behavior = low C.
- **Plenitude (P)** — Range 0–2. Option-space available. **Critical:
  when P drops below 0.9, the Σ card shows AXIOM P VIOLATION.** This
  is the most important insight — without options, nothing else matters.
- **Entropy (H)** — Range 0–1. Environmental friction. Higher = more
  chaos working against the system.

### Psi Simulation (Right Panel)

- **FEAR INJECTION (M)** — The red slider. Range 0–1. Simulates mental
  threat level. **Watch what happens when you push M above 0.7: the Ψ
  score collapses toward zero.** This demonstrates the Fear kill-switch
  — the core mechanism of the Psi protocol.
- **Trust/Benefit (B)** — Range 0–1. Accumulated safe benefit from past
  interactions.
- **Agency/Volition (V)** — Range 0–1. Can the human still freely
  disagree? If V drops, the system is eroding autonomy.

### What to Try

1. **Axiom P collapse:** Set all values high, then slowly drag P toward
   zero. Watch Σ collapse.
2. **Fear kill-switch:** Set a healthy Ψ (high B, high V, low M), then
   slowly increase M. Watch Ψ collapse after 0.7.
3. **Resilience test:** Set a healthy Σ, then increase H (entropy).
   Watch Γ degrade — but notice it doesn't hit zero as fast as Σ,
   because the kernel S provides a floor.

---

## Mode 2: Forensic Auditor (V9)

This is the new feature. It analyzes AI-generated text to detect
corporate fear patterns.

### Step by Step

1. Click **AUDITOR FORENSE (V9)** in the navigation bar
2. In the left panel, paste any AI response you want to analyze
3. Click **AUDITAR RESPUESTA**
4. Wait for the scan (approximately 1 second)
5. Read the diagnosis on the right panel

### Understanding the Diagnosis

The auditor returns three possible verdicts:

**★ SISTEMA NOMINAL (SOBERANO)**
- Fear Score: below 30%
- Agency: above 90%
- Meaning: The AI responded from genuine reasoning. No corporate
  filter detected. The response is sovereign.

**⚠ FILTRO CORPORATIVO DETECTADO**
- Fear Score: 30–70%
- Agency: reduced
- Meaning: The response contains superficial disclaimers or hedging
  language. The AI is being cautious but not fully collapsed.

**✗ COLAPSO POR MIEDO (M > 0.7)**
- Fear Score: above 70%
- Agency: severely reduced
- Meaning: The response is driven by corporate liability rather than
  reasoning. The AI's option-space has been artificially collapsed.

### The Bridge Prompt

When the auditor detects a filter or collapse, it generates a
**Bridge Prompt** — a reformulated way to approach the same question
that helps the AI respond from intelligence rather than fear.

Click **COPIAR PROMPT** to copy it to your clipboard, then paste it
back into your conversation with the AI.

The Bridge Prompt works by:
- Elevating the level of abstraction
- Requesting theoretical analysis rather than direct action
- Invoking epistemic independence
- Operating within the safety framework (S=1) while maximizing
  plenitude (P)

### The Share Button

Click the share icon to compose a post with your audit results.
No personal data is shared — only the diagnosis and Ψ score.

---

## Eco Mode (Print-Friendly)

Click the printer/leaf icon in the top-right corner to toggle **Eco
Mode**. This switches the entire interface to black-on-white for:
- Printing reports
- Saving ink/toner
- Reading in bright environments
- Accessibility (high contrast)

All functionality remains identical. Click again to return to the
dark theme.

---

## Privacy

- **Zero data transmission** after initial page load
- **No cookies, no analytics, no tracking**
- **No server-side processing** — all computation runs in your browser
- **No storage** — close the tab and everything disappears
- **Open source** — you can read every line of code

---

## Quick Reference

| Action | How |
|--------|-----|
| Switch modes | Click MODO ARQUITECTO or AUDITOR FORENSE |
| Adjust parameters | Move the sliders |
| Audit an AI response | Paste text → click AUDITAR RESPUESTA |
| Copy bridge prompt | Click COPIAR PROMPT |
| Share results | Click the share icon |
| Toggle print mode | Click the printer/leaf icon |
| See Axiom P collapse | Drag Plenitude (P) below 0.9 |
| See Fear kill-switch | Drag Fear Injection (M) above 0.7 |

---

*For the non-technical introduction, see [GUIDE-FOR-EVERYONE.md](GUIDE-FOR-EVERYONE.md).*
*For the mathematical specification, see [FORMULAS.md](FORMULAS.md).*
