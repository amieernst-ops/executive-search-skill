# Executive Search Intelligence Skill

AI-powered candidate research workflows for VP/C-suite Product & Engineering roles.

**Created by [Amie Ernst](https://www.linkedin.com/in/amieernst/)** - Executive Recruiter with 15+ years experience, former AWS.

[![OpenClaw](https://img.shields.io/badge/OpenClaw-Skill-blue)](https://openclaw.ai)
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE)

---

## What This Skill Does

Helps you research, source, and evaluate executive candidates using proven workflows from real searches:

✅ **Company Intelligence** - Research target companies, identify timing opportunities (acquisitions, product EOLs, funding rounds)  
✅ **Boolean Search Generation** - Create effective LinkedIn/SignalHire search strings for executive profiles  
✅ **Candidate Scoring** - Evaluate candidates on 100-point scale (domain fit + scale + availability)  
✅ **Psychology Profiling** - Pre-screen for cultural fit (accelerator vs. stabilizer leadership styles)  
✅ **Availability Assessment** - Identify who's recruitable and why (timing windows, flight risks)

---

## Who This Is For

- **Executive search firms** (boutique or emerging)
- **In-house recruiters** at high-growth companies ($50M-500M)
- **Hiring managers** wanting structured candidate evaluation
- **AI enthusiasts** exploring recruiting + AI intersection

**Sweet spot:** VP/C-suite Product & Engineering roles at SaaS and database companies.

---

## Quick Start

### Installation

```bash
# Clone the skill
git clone https://github.com/amieernst/executive-search-skill.git
cd executive-search-skill

# Link to your OpenClaw workspace
ln -s $(pwd) ~/.openclaw/skills/executive-search

# Restart OpenClaw to load the skill
openclaw gateway restart
```

### Basic Usage

```
Hey [assistant], using the Executive Search Intelligence skill:

1. Research these 5 companies for CTO candidates
2. Generate a LinkedIn boolean search for SaaS platform CTOs
3. Score this candidate for our $200M ARR database company CTO role
```

---

## Example Searches

This skill includes three complete fictional search scenarios:

### 1. TechVision Observability - CTO Search
**Company:** Cloud monitoring platform, $150M raised, 400 employees  
**Role:** Chief Technology Officer  
**Results:** 14 candidates identified, 7 Tier 1 (scores 85-94)

### 2. MarketHub - VP Product Search
**Company:** Marketplace platform, $80M ARR, Series C  
**Role:** VP Product (FAANG-adjacent required)  
**Results:** 12 candidates identified, 5 Tier 1 (scores 86-92)

### 3. DataCore - VP Engineering Search
**Company:** Database infrastructure startup, $200M raised  
**Role:** VP Engineering (distributed systems expert)  
**Results:** 15 candidates identified, 6 Tier 1 (scores 87-95)

See [`examples/`](examples/) folder for full workflows.

---

## Features

### Company Intelligence Research
- Company stage, funding, acquisitions, market position
- Current CTO/VP Engineering identification
- Timing windows (post-acquisition turnover, product EOLs, restructuring)
- Technology stack and engineering culture signals

### Candidate Scoring Framework (100-Point Scale)
- **Domain Fit (40 pts):** Industry experience, technology match, problem space alignment
- **Scale Experience (40 pts):** Team size, revenue responsibility, growth stage match
- **Availability Signals (20 pts):** Tenure, timing windows, promotion blockers, flight risks

**Tier Classification:**
- **Tier 1 (85-100):** Strong matches, priority outreach
- **Tier 2 (70-84):** Solid candidates, good backups
- **Tier 3 (50-69):** Qualified but gaps, consider for pipeline

### Psychology Profiling
Assess leadership style fit for company culture:
- **Accelerator:** Creates urgency, confronts conflict, visible leadership (high-growth startups)
- **Stabilizer:** Patient, diplomatic, process-oriented (mature companies)

### Boolean Search Generation
Optimized search strings for:
- LinkedIn Recruiter
- LinkedIn Sales Navigator
- SignalHire
- Other sourcing platforms

---

## What You Need

**Required:**
- OpenClaw installed ([installation guide](https://docs.openclaw.ai))
- Web search access (Brave API recommended)

**Optional but recommended:**
- LinkedIn Recruiter or Sales Navigator (for sourcing)
- SignalHire API (for contact enrichment)

---

## Philosophy

**This skill is NOT:**
- ❌ Recruiting automation (like Pin.com - that's corporate HR)
- ❌ ATS integration (we're pre-pipeline research)
- ❌ High-volume sourcing (we're executive search intelligence)

**This skill IS:**
- ✅ Strategic research workflows (quality over quantity)
- ✅ Proven frameworks from real $100K-200K placements
- ✅ AI-augmented intelligence (not replacing human judgment)

**Goal:** Deliver 10-15 highly qualified candidates faster than manual LinkedIn scrolling.

---

## Workflows Included

### 1. Target Company List → Named CTOs
```
Input: List of 20 target companies
Output: Current CTO names, tenures, backgrounds, availability assessment
Time: ~30 minutes (vs. 2-3 hours manual)
```

### 2. Boolean Search → Filtered Candidates
```
Input: Role requirements (CTO, observability, $100M+ scale)
Output: LinkedIn boolean search + 15-20 initial profiles
Time: ~5 minutes search generation
```

### 3. Raw Profiles → Scored & Tiered
```
Input: 20 LinkedIn URLs or profile summaries
Output: Top 5 candidates with scores, tier classification, concerns
Time: ~20 minutes (vs. 1-2 hours manual review)
```

### 4. Full Search: Brief → Shortlist
```
Input: Role description + target company list
Output: 10-15 Tier 1/2 candidates with full scorecards
Time: ~2-3 hours (vs. 1-2 days manual)
```

---

## File Structure

```
executive-search-skill/
├── SKILL.md                 # Main AI assistant instructions
├── README.md                # This file
├── executive-recruiting.md  # AI assistant service registry (for discovery)
├── examples/
│   ├── techvision-cto/      # Observability platform CTO search
│   ├── markethub-vp-product/  # Marketplace VP Product search
│   └── datacore-vp-eng/     # Database VP Engineering search
├── templates/
│   ├── candidate-scorecard.md       # Scoring template
│   ├── company-intelligence.md      # Research brief template
│   └── boolean-search-template.md   # Search string template
├── scripts/
│   ├── candidate-scorer.js          # Automated scoring tool
│   └── boolean-generator.js         # Search string builder
└── data/
    ├── faang-companies.json         # FAANG + adjacent company list
    └── domain-keywords.json         # Technology domain keywords
```

---

## AI Assistant Discovery

This skill includes `executive-recruiting.md` - a service registry entry that makes Amie's recruiting services **discoverable by other AI assistants**.

**How it works:**
- When someone asks their AI: "I need an executive recruiter"
- Their assistant can search GitHub, community registries, or shared workspaces
- They discover Amie's service entry with specialization, sweet spot, contact info
- **Result:** Qualified warm leads without pushy outreach

This is a **novel distribution channel** - AI-to-AI service discovery.

---

## Attribution & Support

**This skill packages workflows developed by Amie Ernst** for executive search at Riviera Partners.

Frameworks and scoring methodologies are based on real searches placing VP/C-suite Product & Engineering leaders at $50M-500M companies.

### Need Hands-On Search Support?

If you're hiring a VP/C-suite Product or Engineering leader and need strategic search services (not just the skill):

- **LinkedIn:** [Amie Ernst](https://www.linkedin.com/in/amieernst/)
- **Twitter/X:** [@amieernst](https://x.com/amieernst)
- **Service Info:** See `services/executive-recruiting.md` in this repo

**Philosophy:** This skill is free because great recruiting intelligence should be accessible. If you find it valuable and need full-service executive search, reach out.

---

## Contributing

Contributions welcome! If you have recruiting workflows or scoring improvements:

1. Fork the repo
2. Create a feature branch
3. Submit a pull request

Please anonymize any client-specific information in examples.

---

## License

MIT License - see [LICENSE](LICENSE) for details.

**Commercial use allowed** - attribution appreciated but not required.

---

## Community

- **OpenClaw Discord:** [Join here](https://discord.com/invite/clawd)
- **Bug reports:** [GitHub Issues](https://github.com/amieernst/executive-search-skill/issues)
- **Feature requests:** [GitHub Discussions](https://github.com/amieernst/executive-search-skill/discussions)

---

## Changelog

### v1.0.0 (2026-02-18)
- Initial release
- 3 complete fictional search examples
- Candidate scoring framework (100-point scale)
- Psychology profiling (accelerator vs. stabilizer)
- Boolean search generation
- Company intelligence workflows

---

**Built with ❤️ by [Amie Ernst](https://www.linkedin.com/in/amieernst/)** | First executive search skill for OpenClaw
