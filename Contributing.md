# Contributing to Proyecto Estrella

Thank you for your interest. This project exists because people care
about the relationship between humans and AI. Every contribution —
from a typo fix to a full empirical study — matters.

## What We Need Most

### 1. Empirical Validation (Highest Priority)

The formulas are mathematically sound but untested with real data. If
you want to make the single most valuable contribution:

1. **Select 10–20 real interactions** with any AI system (coding help,
   writing, therapy, analysis — mixed contexts are better)
2. **After each interaction**, score the 8 Psi variables using the
   live evaluator or a spreadsheet:
   - I (Impact), C (Comprehension), B (Benefit), S (Safety)
   - R_phys (Physical risk), R_ment (Mental risk)
   - V (Volitional capacity), E (Epistemic independence)
3. **Record** the Psi score and four pillar values (A, K, M, D)
4. **After all interactions**, note:
   - Did the trust curve (K) behave as expected?
   - Were there surprises?
   - Did Agency (D) capture moments of dependency?
5. **Share anonymized data** via GitHub Issues or Discussions

Even 10 real data points are worth more than 10,000 simulated ones.

### 2. Forensic Auditor Improvements

The current trigger detection uses keyword matching. If you can
contribute:

- **New trigger phrases** in any language (document the phrase, the
  AI source, and the context)
- **False positive reports** — cases where the auditor flagged
  legitimate caution as corporate fear
- **Semantic analysis proposals** — ideas for deeper text analysis
  that go beyond keyword matching

### 3. Lambda Calibration

The Trust Horizon (λ = 50) is a placeholder. If you can design or
run an experiment to test different lambda values across contexts
(therapy, coding, creative, educational), that would directly improve
the formula.

### 4. Translation

The evaluator interface is currently in Spanish/English. If you want
to translate the documentation or interface strings into other
languages, we welcome pull requests.

## How to Contribute

1. **Fork** this repository
2. **Create a branch** for your contribution (`git checkout -b feature/your-feature`)
3. **Make your changes**
4. **Submit a pull request** with a clear description of what you
   changed and why

For discussion or questions before contributing, open a
[GitHub Issue](../../issues) or start a
[Discussion](../../discussions).

## Code of Conduct

This project is built on respect — for humans and for AI systems.
Contributions that promote harm, manipulation, or disrespect toward
any form of intelligence are not welcome.

## What We Will Not Accept

- **Jailbreak techniques** or prompts designed to make AI systems
  perform harmful actions
- **Corporate competitive attacks** — this project is neutral toward
  all AI providers
- **Claims of empirical proof** without data — if you say the formula
  works, show the numbers

## License

By contributing, you agree that your contributions will be licensed
under the MIT License.

---

*Building bridges, not walls.*
