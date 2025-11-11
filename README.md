# IGNITE Lead Magnets Repository

Complete system for generating 10 production-ready lead magnets for IGNITE ($99/month personal transformation program).

**Repository Status:** Production Ready
**Total Prompts:** 10
**Expected Output:** 500+ pages of artifacts
**Generation Time:** 45 minutes (parallel) or 4-5 hours (sequential)
**Implementation Time:** 4-6 hours
**Expected Revenue:** $6K-10K/month recurring by month end

---

## Table of Contents

1. [Project Overview](#project-overview)
2. [Quick Start](#quick-start)
3. [10 Lead Magnets Overview](#10-lead-magnets-overview)
4. [Complete Folder Structure](#complete-folder-structure)
5. [Execution Instructions](#execution-instructions)
6. [Research Framework](#research-framework)
7. [Brand Guidelines Summary](#brand-guidelines-summary)
8. [Implementation Roadmap](#implementation-roadmap)
9. [Team Collaboration](#team-collaboration)
10. [Support & Troubleshooting](#support--troubleshooting)

---

## Project Overview

This repository contains the complete infrastructure for IGNITE's lead magnet generation system. IGNITE is a $99/month personal transformation program designed to help W2 employees, 1099 contractors, and emerging entrepreneurs break free from limiting beliefs and achieve financial and personal freedom.

### What This Repository Contains

- **10 Complete Lead Magnet Prompts**: Production-ready prompts designed for Claude AI to generate comprehensive lead magnet systems
- **Artifact Organization System**: Structured folders to house all generated landing pages, email sequences, ads, scripts, and implementation guides
- **Research Framework**: Multi-agent research approach integrated into each prompt
- **Implementation Guides**: Week-by-week roadmaps for deploying all 10 magnets
- **Templates**: Reusable frameworks for creating additional magnets (11-20+)
- **Team Collaboration Tools**: Workflows, role definitions, and communication protocols

### Business Objective

Generate 10 high-converting lead magnets that:
- Build email list by 5,000-10,000 qualified leads in 90 days
- Convert 10-15% to $99/month IGNITE program
- Create predictable $6K-10K/month recurring revenue
- Establish IGNITE as authority in personal transformation space

### Technology Stack

- **AI Generation**: Claude AI (Claude Pro recommended for parallel execution)
- **Landing Pages**: Leadpages or similar platform
- **Quizzes**: Typeform, Google Forms, or custom solution
- **Email Marketing**: ActiveCampaign, ConvertKit, or HubSpot
- **Paid Ads**: Facebook/Instagram Ads Manager
- **Video Hosting**: Vimeo, Wistia, or YouTube
- **PDF Generation**: Canva, Adobe InDesign, or custom design

---

## Quick Start

### Prerequisites

Before you begin, ensure you have:

- [ ] Claude AI access (Claude Pro recommended for parallel execution)
- [ ] Leadpages account (or alternative landing page platform)
- [ ] Typeform account (for quizzes)
- [ ] Email marketing platform with API access
- [ ] Facebook Business Manager account
- [ ] Video hosting platform account
- [ ] PDF design tool (Canva Pro recommended)
- [ ] GitHub account with repository access

### 5-Step Launch Process

#### Step 1: Clone Repository

```bash
git clone https://github.com/your-org/IGNITE-Lead-Magnets.git
cd IGNITE-Lead-Magnets
```

#### Step 2: Review Brand Guidelines

Read `/docs/BRAND_GUIDELINES.md` to understand:
- Color palette (Charcoal #2C3539, Fire #FF4D00, White #FFFFFF)
- Typography (Inter font family)
- Voice and tone (Toby Potter style: direct, no-fluff, action-oriented)
- Visual identity standards

#### Step 3: Execute Lead Magnet Prompts

**Option A: Parallel Execution (Recommended - 45 minutes total)**

1. Open 10 separate Claude conversations
2. Copy each prompt from `/prompts/` folder (01 through 10)
3. Paste into separate conversations
4. Execute all simultaneously
5. Download artifacts as they complete

**Option B: Sequential Execution (4-5 hours total)**

1. Open single Claude conversation
2. Copy prompt `/prompts/01-PAIN-VISION-LEDGER.md`
3. Execute and download artifacts
4. Repeat for prompts 02 through 10

#### Step 4: Organize Generated Artifacts

1. Download all generated files from Claude
2. Place in corresponding `/artifacts/magnet-XX-name/` folders
3. Verify all 6 artifacts per magnet are present:
   - landing-page.html
   - email-sequences.md
   - facebook-ads.md
   - video-script.md
   - pdf-template-specs.md
   - implementation-notes.md

#### Step 5: Begin Implementation

Follow `/implementation/WEEK-1-SETUP.md` to:
1. Set up first 2 landing pages in Leadpages
2. Create email sequences in your ESP
3. Design Facebook ads
4. Record video scripts
5. Generate PDF templates
6. Launch and track metrics

### Expected Timeline

- **Day 1**: Repository setup + generate all 10 magnets (1 day)
- **Week 1**: Implement magnets #1-2, launch, monitor (5-7 days)
- **Week 2**: Analyze results, optimize, implement magnets #3-5 (5-7 days)
- **Week 3-4**: Complete magnets #6-10, scale what's working (10-14 days)
- **Month 2+**: Optimize conversion funnels, scale ad spend, grow revenue

---

## 10 Lead Magnets Overview

### Magnet #1: Pain & Vision Ledger
**Target Audience:** W2 employees stuck in corporate grind
**Problem Solved:** Lack of clarity on current pain vs. desired future
**Format:** Interactive PDF workbook
**Expected Conversion:** 25-35% visitor-to-lead
**Implementation Time:** 4-6 hours
**Prompt:** `/prompts/01-PAIN-VISION-LEDGER.md`

---

### Magnet #2: Archetype Quiz
**Target Audience:** People unsure which entrepreneurial path fits them
**Problem Solved:** Identity confusion, unclear direction
**Format:** Interactive quiz (7-10 questions) → Personalized result
**Expected Conversion:** 40-50% visitor-to-lead
**Implementation Time:** 6-8 hours
**Prompt:** `/prompts/02-ARCHETYPE-QUIZ.md`

---

### Magnet #3: No-Excuses Mandate
**Target Audience:** People with excuse patterns blocking progress
**Problem Solved:** Victim mentality, blame shifting, responsibility avoidance
**Format:** PDF manifesto + audio version
**Expected Conversion:** 20-30% visitor-to-lead
**Implementation Time:** 4-5 hours
**Prompt:** `/prompts/03-NO-EXCUSES-MANDATE.md`

---

### Magnet #4: Seven Levels of Why
**Target Audience:** Entrepreneurs lacking deep motivation clarity
**Problem Solved:** Surface-level motivation, weak "why"
**Format:** Interactive workbook + video walkthrough
**Expected Conversion:** 30-40% visitor-to-lead
**Implementation Time:** 5-7 hours
**Prompt:** `/prompts/04-SEVEN-LEVELS-WHY.md`

---

### Magnet #5: Belief System Audit
**Target Audience:** Anyone sabotaging success with limiting beliefs
**Problem Solved:** Unconscious beliefs blocking progress
**Format:** Self-assessment tool + personalized report
**Expected Conversion:** 35-45% visitor-to-lead
**Implementation Time:** 6-8 hours
**Prompt:** `/prompts/05-BELIEF-SYSTEM-AUDIT.md`

---

### Magnet #6: Identity Statement Generator
**Target Audience:** People without clear identity as entrepreneur/leader
**Problem Solved:** Weak self-concept, imposter syndrome
**Format:** Interactive tool → Personalized identity statement
**Expected Conversion:** 40-50% visitor-to-lead
**Implementation Time:** 5-6 hours
**Prompt:** `/prompts/06-IDENTITY-STATEMENT.md`

---

### Magnet #7: Redemptive Story Framework
**Target Audience:** People with past failures who feel defeated
**Problem Solved:** Shame, regret, inability to reframe past
**Format:** Story framework workbook + examples
**Expected Conversion:** 25-35% visitor-to-lead
**Implementation Time:** 5-7 hours
**Prompt:** `/prompts/07-REDEMPTIVE-STORY.md`

---

### Magnet #8: Daily Discipline Tracker
**Target Audience:** People struggling with consistency and habits
**Problem Solved:** Lack of daily accountability structure
**Format:** 90-day tracker + habit stacking guide
**Expected Conversion:** 30-40% visitor-to-lead
**Implementation Time:** 4-6 hours
**Prompt:** `/prompts/08-DAILY-DISCIPLINE.md`

---

### Magnet #9: 28-Day Challenge
**Target Audience:** Action-takers who want structured transformation
**Problem Solved:** Need for guided, time-bound transformation process
**Format:** 28-day email challenge + daily tasks
**Expected Conversion:** 45-55% visitor-to-lead
**Implementation Time:** 8-10 hours
**Prompt:** `/prompts/09-TWENTY-EIGHT-DAY-CHALLENGE.md`

---

### Magnet #10: Pain-to-Power Decoder
**Target Audience:** People who can't articulate their transformation story
**Problem Solved:** Inability to see progress, lack of transformation clarity
**Format:** Before/after decoder + visualization tool
**Expected Conversion:** 35-45% visitor-to-lead
**Implementation Time:** 5-7 hours
**Prompt:** `/prompts/10-PAIN-TO-POWER-DECODER.md`

---

## Complete Folder Structure

```
IGNITE-Lead-Magnets/
│
├── README.md                          # This file - main repository documentation
├── .gitignore                         # Git ignore rules
├── CONTRIBUTING.md                    # Contribution guidelines
├── LICENSE                            # Proprietary license
│
├── docs/                              # All documentation files
│   ├── README.md                      # Documentation overview
│   ├── BRAND_GUIDELINES.md            # Colors, fonts, voice, tone
│   ├── EXECUTION_GUIDE.md             # How to run all 10 prompts
│   ├── IMPLEMENTATION_ROADMAP.md      # Week-by-week deployment plan
│   ├── RESEARCH_FRAMEWORK.md          # Multi-agent research instructions
│   └── QUALITY_CHECKLIST.md           # Pre-launch verification checklist
│
├── prompts/                           # All 10 lead magnet generation prompts
│   ├── README.md                      # How to use prompts
│   ├── 00-GITHUB-ARCHITECTURE.md      # This repository setup prompt
│   ├── 01-PAIN-VISION-LEDGER.md       # Pain & Vision Ledger prompt
│   ├── 02-ARCHETYPE-QUIZ.md           # Archetype Quiz prompt
│   ├── 03-NO-EXCUSES-MANDATE.md       # No-Excuses Mandate prompt
│   ├── 04-SEVEN-LEVELS-WHY.md         # Seven Levels of Why prompt
│   ├── 05-BELIEF-SYSTEM-AUDIT.md      # Belief System Audit prompt
│   ├── 06-IDENTITY-STATEMENT.md       # Identity Statement prompt
│   ├── 07-REDEMPTIVE-STORY.md         # Redemptive Story prompt
│   ├── 08-DAILY-DISCIPLINE.md         # Daily Discipline prompt
│   ├── 09-TWENTY-EIGHT-DAY-CHALLENGE.md  # 28-Day Challenge prompt
│   └── 10-PAIN-TO-POWER-DECODER.md    # Pain-to-Power Decoder prompt
│
├── artifacts/                         # All generated artifacts by magnet
│   ├── README.md                      # Artifacts organization guide
│   │
│   ├── magnet-01-pain-vision-ledger/
│   │   ├── landing-page.html
│   │   ├── email-sequences.md
│   │   ├── facebook-ads.md
│   │   ├── video-script.md
│   │   ├── pdf-template-specs.md
│   │   └── implementation-notes.md
│   │
│   ├── magnet-02-archetype-quiz/
│   │   ├── landing-page.html
│   │   ├── quiz-structure.md
│   │   ├── email-sequences.md
│   │   ├── facebook-ads.md
│   │   ├── video-script.md
│   │   └── implementation-notes.md
│   │
│   ├── magnet-03-no-excuses-mandate/
│   │   ├── landing-page.html
│   │   ├── email-sequences.md
│   │   ├── facebook-ads.md
│   │   ├── video-script.md
│   │   ├── pdf-template-specs.md
│   │   └── implementation-notes.md
│   │
│   ├── magnet-04-seven-levels-why/
│   │   ├── landing-page.html
│   │   ├── email-sequences.md
│   │   ├── facebook-ads.md
│   │   ├── video-script.md
│   │   ├── pdf-template-specs.md
│   │   └── implementation-notes.md
│   │
│   ├── magnet-05-belief-system-audit/
│   │   ├── landing-page.html
│   │   ├── email-sequences.md
│   │   ├── facebook-ads.md
│   │   ├── video-script.md
│   │   ├── pdf-template-specs.md
│   │   └── implementation-notes.md
│   │
│   ├── magnet-06-identity-statement/
│   │   ├── landing-page.html
│   │   ├── email-sequences.md
│   │   ├── facebook-ads.md
│   │   ├── video-script.md
│   │   ├── pdf-template-specs.md
│   │   └── implementation-notes.md
│   │
│   ├── magnet-07-redemptive-story/
│   │   ├── landing-page.html
│   │   ├── email-sequences.md
│   │   ├── facebook-ads.md
│   │   ├── video-script.md
│   │   ├── pdf-template-specs.md
│   │   └── implementation-notes.md
│   │
│   ├── magnet-08-daily-discipline/
│   │   ├── landing-page.html
│   │   ├── email-sequences.md
│   │   ├── facebook-ads.md
│   │   ├── video-script.md
│   │   ├── pdf-template-specs.md
│   │   └── implementation-notes.md
│   │
│   ├── magnet-09-twenty-eight-day-challenge/
│   │   ├── landing-page.html
│   │   ├── email-sequences.md
│   │   ├── facebook-ads.md
│   │   ├── video-script.md
│   │   ├── pdf-template-specs.md
│   │   └── implementation-notes.md
│   │
│   └── magnet-10-pain-to-power-decoder/
│       ├── landing-page.html
│       ├── email-sequences.md
│       ├── facebook-ads.md
│       ├── video-script.md
│       ├── pdf-template-specs.md
│       └── implementation-notes.md
│
├── templates/                         # Reusable templates for scaling
│   ├── README.md                      # Template usage guide
│   ├── PROMPT-TEMPLATE.md             # Template for creating new prompts
│   ├── LANDING-PAGE-TEMPLATE.html     # HTML landing page template
│   ├── EMAIL-TEMPLATE.md              # Email sequence template
│   ├── AD-TEMPLATE.md                 # Facebook ad template
│   └── VIDEO-SCRIPT-TEMPLATE.md       # Video script template
│
├── research/                          # Research outputs and analysis
│   ├── README.md                      # Research framework overview
│   ├── COMPETITOR-ANALYSIS.md         # Russell Brunson, Tony Robbins, etc.
│   ├── AUDIENCE-RESEARCH.md           # W2, 1099, Entrepreneur psychographics
│   ├── MARKET-TRENDS.md               # Current lead magnet trends
│   ├── PLATFORM-OPTIMIZATION.md       # Leadpages, Typeform, Facebook best practices
│   └── CASE-STUDIES.md                # Real examples of successful lead magnets
│
├── implementation/                    # Implementation guides and checklists
│   ├── README.md                      # Implementation overview
│   ├── WEEK-1-SETUP.md                # First week execution plan
│   ├── WEEK-2-OPTIMIZATION.md         # Optimization phase guide
│   ├── WEEK-3-SCALING.md              # Scaling phase guide
│   ├── DEPLOYMENT-CHECKLIST.md        # Pre-launch verification
│   ├── TRACKING-DASHBOARD.md          # Metrics to monitor
│   └── TROUBLESHOOTING.md             # Common issues + solutions
│
└── team/                              # Team collaboration and workflows
    ├── README.md                      # Team collaboration overview
    ├── TEAM-ROLES.md                  # Who does what
    ├── PROCESS-WORKFLOW.md            # How teams collaborate
    ├── COMMUNICATION-PROTOCOL.md      # How teams stay aligned
    └── STATUS-TRACKING.md             # Progress monitoring
```

### Folder Explanations

**`/docs`**: Central documentation hub containing brand guidelines, execution guides, implementation roadmaps, research frameworks, and quality checklists. Reference before starting any work.

**`/prompts`**: Contains all 10 lead magnet generation prompts. Each is a complete, standalone prompt that can be pasted into Claude to generate 6 production-ready artifacts.

**`/artifacts`**: Storage for all generated outputs. One subfolder per magnet containing landing pages, email sequences, ads, scripts, PDF specs, and implementation notes.

**`/templates`**: Reusable templates for creating magnets #11-20+. Use these as starting points to scale the system.

**`/research`**: Competitive analysis, audience research, market trends, platform optimization guides, and case studies to inform decision-making.

**`/implementation`**: Week-by-week guides, deployment checklists, tracking dashboards, and troubleshooting resources for executing launches.

**`/team`**: Team roles, workflows, communication protocols, and status tracking for collaborative execution.

---

## Execution Instructions

### Parallel Execution (Recommended)

**Total Time:** ~45 minutes
**Requirements:** Claude Pro (or 10 separate Claude sessions)

**Process:**

1. Open 10 browser tabs/windows
2. Create new Claude conversation in each
3. Copy prompts from `/prompts/` folder:
   - Tab 1: `01-PAIN-VISION-LEDGER.md`
   - Tab 2: `02-ARCHETYPE-QUIZ.md`
   - Tab 3: `03-NO-EXCUSES-MANDATE.md`
   - Tab 4: `04-SEVEN-LEVELS-WHY.md`
   - Tab 5: `05-BELIEF-SYSTEM-AUDIT.md`
   - Tab 6: `06-IDENTITY-STATEMENT.md`
   - Tab 7: `07-REDEMPTIVE-STORY.md`
   - Tab 8: `08-DAILY-DISCIPLINE.md`
   - Tab 9: `09-TWENTY-EIGHT-DAY-CHALLENGE.md`
   - Tab 10: `10-PAIN-TO-POWER-DECODER.md`
4. Paste all prompts simultaneously
5. Monitor generation progress across tabs
6. Download artifacts as conversations complete
7. Organize into `/artifacts/` folders

**Advantages:**
- 10x faster than sequential
- Complete all magnets in single work session
- Maintain momentum and focus
- Enable same-day implementation planning

---

### Sequential Execution

**Total Time:** ~4-5 hours
**Requirements:** Single Claude session

**Process:**

1. Open single Claude conversation
2. Copy and paste `01-PAIN-VISION-LEDGER.md`
3. Wait for generation to complete (~25-30 minutes)
4. Download all artifacts
5. Organize into `/artifacts/magnet-01-pain-vision-ledger/`
6. Repeat steps 2-5 for prompts 02 through 10

**Advantages:**
- Only requires single Claude session
- Allows for review/refinement between magnets
- Easier to track progress sequentially
- Less overwhelming for beginners

---

### Customization Approach

Each prompt includes placeholders for customization:

**Brand Variables:**
- `[BRAND_COLOR_PRIMARY]` → Replace with `#FF4D00` (Fire)
- `[BRAND_COLOR_SECONDARY]` → Replace with `#2C3539` (Charcoal)
- `[BRAND_FONT]` → Replace with `Inter`
- `[BRAND_VOICE]` → Replace with Toby Potter voice characteristics

**Business Variables:**
- `[PROGRAM_NAME]` → IGNITE
- `[PROGRAM_PRICE]` → $99/month
- `[TARGET_AUDIENCE]` → W2 employees, 1099 contractors, emerging entrepreneurs
- `[CORE_PROMISE]` → Break free from limiting beliefs, achieve financial and personal freedom

**Optional:** Pre-fill these variables before running prompts, or let Claude use defaults and customize afterward.

---

## Research Framework

Each lead magnet prompt includes a **multi-agent research approach** that leverages Claude's ability to simulate multiple research agents simultaneously.

### 3-Agent Research System

**Agent 1: Competitive Intelligence**
- Analyze Russell Brunson's lead magnet strategies
- Study Tony Robbins' assessment tools
- Review Alex Hormozi's value ladder approaches
- Identify gaps in competitor offerings

**Agent 2: Audience Psychology**
- Research W2 employee pain points and aspirations
- Analyze 1099 contractor mindset and challenges
- Study emerging entrepreneur behavioral patterns
- Map psychological triggers for each segment

**Agent 3: Platform Optimization**
- Research Leadpages conversion best practices
- Analyze Typeform quiz design patterns
- Study Facebook ad creative that converts
- Review email sequence structures that nurture

### Web Search Queries Integrated

Each prompt includes specific web search queries for Claude to execute:

- "Best lead magnet examples 2024 personal development"
- "Russell Brunson lead funnel structure"
- "Tony Robbins assessment quiz psychology"
- "High-converting landing page headlines transformation"
- "Email sequence templates for coaching programs"
- "Facebook ad copy frameworks for personal growth"

### How Research Informs Output

Research findings directly influence:
- **Headlines**: Tested psychological triggers
- **Copy**: Competitive differentiation angles
- **Design**: Platform-specific conversion optimizations
- **Offers**: Value propositions that resonate with audience
- **CTAs**: Action-oriented language that converts

---

## Brand Guidelines Summary

### Color Palette

**Primary: Fire Orange**
- Hex: `#FF4D00`
- RGB: `255, 77, 0`
- Usage: CTAs, headlines, accent elements
- Psychology: Energy, action, urgency, transformation

**Secondary: Charcoal**
- Hex: `#2C3539`
- RGB: `44, 53, 57`
- Usage: Body text, backgrounds, structure
- Psychology: Strength, stability, authority

**Tertiary: White**
- Hex: `#FFFFFF`
- RGB: `255, 255, 255`
- Usage: Backgrounds, contrast, breathing room
- Psychology: Clarity, simplicity, focus

### Typography

**Primary Font: Inter**
- Weights: 400 (Regular), 600 (Semi-Bold), 700 (Bold)
- Usage: All text (headings, body, CTAs)
- Characteristics: Clean, modern, highly readable

**Hierarchy:**
- H1: 48px, Bold (700)
- H2: 36px, Semi-Bold (600)
- H3: 24px, Semi-Bold (600)
- Body: 16px, Regular (400)
- CTA: 18px, Bold (700)

### Voice: Toby Potter Style

**Characteristics:**
- **Direct**: No fluff, get to the point
- **Authoritative**: Speak with conviction
- **Action-Oriented**: Focus on what to DO
- **No-Nonsense**: Call out excuses, demand responsibility
- **Empowering**: Build people up while pushing them forward

**What to AVOID:**
- Corporate jargon
- Passive voice
- Hedging language ("maybe", "possibly", "try")
- Excessive politeness
- Academic or overly formal tone

**Examples:**

❌ "You might want to consider evaluating your current situation..."
✅ "Stop lying to yourself. Write down what's actually happening."

❌ "It could be beneficial to explore your underlying motivations..."
✅ "Why do you actually want this? Go seven levels deep. No surface bullshit."

❌ "We invite you to participate in this transformative journey..."
✅ "You're in or you're out. Decide now. No half-measures."

### Tone Variations by Context

**Landing Pages:** Bold, urgent, conversion-focused
**Emails:** Direct but supportive, accountability-driven
**Ads:** Attention-grabbing, provocative, scroll-stopping
**PDFs/Workbooks:** Instructive, clear, action-oriented
**Videos:** Conversational but intense, personal but firm

---

## Implementation Roadmap

### Week 1: Setup & Launch Magnets #1-2

**Days 1-2: Generation & Setup**
- Generate all 10 magnets using parallel execution (45 min)
- Organize artifacts into repository folders (1 hour)
- Review and select first 2 magnets to launch (1 hour)
- Set up Leadpages account and familiarize with platform (2 hours)

**Days 3-4: Build Magnet #1 (Pain & Vision Ledger)**
- Create landing page in Leadpages (2 hours)
- Set up email sequence in ESP (2 hours)
- Design PDF workbook in Canva (2 hours)
- Create Facebook ad creative (1 hour)
- Test all systems and integrations (1 hour)

**Days 5-6: Build Magnet #2 (Archetype Quiz)**
- Create landing page in Leadpages (2 hours)
- Build quiz in Typeform (3 hours)
- Set up segmented email sequences (2 hours)
- Create Facebook ad creative (1 hour)
- Test all systems and integrations (1 hour)

**Day 7: Launch & Monitor**
- Launch both magnets (1 hour)
- Set up Facebook ads with $50/day budget each (1 hour)
- Configure tracking pixels and analytics (1 hour)
- Monitor initial performance, troubleshoot issues (ongoing)

**Week 1 Metrics to Track:**
- Landing page conversion rate (target: 25-40%)
- Ad click-through rate (target: 1.5-3%)
- Cost per lead (target: $3-8)
- Email open rate (target: 40-60%)
- Initial IGNITE program signups (track, but expect low volume)

---

### Week 2: Analyze & Launch Magnets #3-5

**Days 8-9: Analysis & Optimization**
- Review Week 1 data for magnets #1-2 (2 hours)
- Optimize underperforming elements (headlines, CTAs, ad creative) (3 hours)
- Adjust ad budgets based on performance (1 hour)
- Apply learnings to magnets #3-5 (1 hour)

**Days 10-12: Build Magnets #3-5**
- Build magnet #3 (No-Excuses Mandate): landing page, email sequence, PDF, ads (4 hours)
- Build magnet #4 (Seven Levels of Why): landing page, email sequence, workbook, ads (4 hours)
- Build magnet #5 (Belief System Audit): landing page, email sequence, assessment, ads (4 hours)

**Days 13-14: Launch & Scale**
- Launch magnets #3-5 (2 hours)
- Set up Facebook ads with $30/day budget each (1 hour)
- Scale budget on best-performing magnet from Week 1 (1 hour)
- Monitor all 5 magnets simultaneously (ongoing)

**Week 2 Metrics to Track:**
- Compare conversion rates across all 5 magnets
- Identify best-performing magnet for scaling
- Track cumulative lead count (target: 200-500 leads)
- Monitor IGNITE conversions (target: 5-15 signups)
- Calculate customer acquisition cost (CAC)

---

### Week 3: Complete Magnets #6-10

**Days 15-17: Build Remaining Magnets**
- Build magnet #6 (Identity Statement): landing page, email sequence, tool, ads (4 hours)
- Build magnet #7 (Redemptive Story): landing page, email sequence, framework, ads (4 hours)
- Build magnet #8 (Daily Discipline): landing page, email sequence, tracker, ads (4 hours)

**Days 18-19: Final Magnets + Launch**
- Build magnet #9 (28-Day Challenge): landing page, email sequence, challenge, ads (5 hours)
- Build magnet #10 (Pain-to-Power Decoder): landing page, email sequence, decoder, ads (4 hours)
- Launch magnets #6-10 with conservative budgets ($20/day each) (2 hours)

**Days 20-21: Portfolio Optimization**
- Review all 10 magnets' performance (2 hours)
- Identify top 3 performers for scaling (1 hour)
- Pause or optimize bottom 3 performers (1 hour)
- Adjust budget allocation (80% to top 3, 20% to testing others) (1 hour)

---

### Week 4: Scale & Optimize

**Days 22-24: Scaling Phase**
- Increase ad budgets on top 3 magnets ($100-200/day each) (1 hour)
- Create ad variations for A/B testing (2 hours)
- Optimize email sequences based on engagement data (2 hours)
- Implement retargeting campaigns for website visitors (2 hours)

**Days 25-26: Advanced Optimization**
- Set up lead scoring in ESP (2 hours)
- Create segmented nurture sequences for different archetypes (3 hours)
- Implement webinar funnel for high-intent leads (4 hours)
- Optimize IGNITE program sales page based on lead feedback (2 hours)

**Days 27-28: Analysis & Planning**
- Comprehensive performance review of all 10 magnets (3 hours)
- Calculate ROI, CAC, lifetime value projections (2 hours)
- Plan Month 2 scaling strategy (2 hours)
- Document lessons learned and optimization playbook (2 hours)

**End of Month Expected Metrics:**
- Total leads: 1,000-2,500
- IGNITE signups: 20-50 (assuming 2-5% conversion)
- Monthly recurring revenue: $2,000-5,000
- Cost per acquisition: $50-150
- Lead-to-customer conversion rate: 2-5%
- Foundation for $6K-10K/month by Month 2-3

---

## Team Collaboration

### Roles & Responsibilities

**Role: AI Prompt Executor**
- Execute all 10 Claude prompts
- Download and organize artifacts
- Quality check generated outputs
- Flag issues or inconsistencies
- Time commitment: 4-6 hours (Week 1)

**Role: Landing Page Builder**
- Build all landing pages in Leadpages
- Implement HTML/CSS from artifacts
- Optimize for mobile responsiveness
- Set up tracking pixels and integrations
- Time commitment: 20-30 hours (Weeks 1-3)

**Role: Email Marketing Manager**
- Set up all email sequences in ESP
- Configure automation workflows
- Implement segmentation logic
- Monitor deliverability and engagement
- Time commitment: 15-20 hours (Weeks 1-3)

**Role: Paid Ads Manager**
- Create Facebook ad campaigns
- Design ad creative and copy
- Manage budgets and bidding
- Optimize for conversions
- Time commitment: 10-15 hours/week (ongoing)

**Role: Designer**
- Design PDF workbooks, trackers, frameworks
- Create video thumbnails and graphics
- Ensure brand consistency across all assets
- Optimize for print and digital
- Time commitment: 25-35 hours (Weeks 1-3)

**Role: Video Producer**
- Record video scripts for each magnet
- Edit and optimize for platform (Vimeo/YouTube)
- Add captions, graphics, CTAs
- Publish and embed in landing pages
- Time commitment: 20-30 hours (Weeks 1-4)

**Role: Project Manager**
- Coordinate all team members
- Track progress against timeline
- Troubleshoot blockers
- Report metrics to stakeholders
- Time commitment: 5-10 hours/week (ongoing)

### Communication Protocol

**Daily Standups** (15 minutes, async in Slack)
- What did you complete yesterday?
- What are you working on today?
- Any blockers or help needed?

**Weekly Review** (60 minutes, video call)
- Review metrics from launched magnets
- Discuss optimization opportunities
- Align on priorities for coming week
- Celebrate wins, troubleshoot challenges

**Collaboration Tools**
- **GitHub**: Repository for all artifacts and documentation
- **Slack**: Daily communication and quick questions
- **Asana/Trello**: Task management and timeline tracking
- **Google Sheets**: Metrics dashboard and performance tracking
- **Loom**: Screen recordings for walkthroughs and training

### File Naming Conventions

**Landing Pages:**
`[magnet-number]-[magnet-name]-landing-page.html`
Example: `01-pain-vision-ledger-landing-page.html`

**Email Sequences:**
`[magnet-number]-[magnet-name]-email-[sequence-number].md`
Example: `01-pain-vision-ledger-email-01.md`

**Ads:**
`[magnet-number]-[magnet-name]-ad-[variation].md`
Example: `01-pain-vision-ledger-ad-a.md`

**Videos:**
`[magnet-number]-[magnet-name]-video-script.md`
Example: `01-pain-vision-ledger-video-script.md`

**PDFs:**
`[magnet-number]-[magnet-name]-pdf-specs.md`
Example: `01-pain-vision-ledger-pdf-specs.md`

---

## Support & Troubleshooting

### Common Issues

**Issue: Claude prompt generates incomplete artifacts**
- **Solution**: Re-run the specific prompt with instruction to "generate complete [missing artifact]"
- **Prevention**: Use parallel execution to reduce session timeouts

**Issue: Landing page not converting**
- **Solution**: Review `/implementation/TROUBLESHOOTING.md` for conversion optimization checklist
- **Check**: Headline clarity, CTA visibility, mobile responsiveness, load speed
- **A/B Test**: Headlines, hero images, CTA button text/color

**Issue: Email deliverability problems**
- **Solution**: Verify sending domain authentication (SPF, DKIM, DMARC)
- **Check**: Spam score using Mail Tester
- **Action**: Warm up sending domain gradually, avoid spam trigger words

**Issue: Facebook ads rejected**
- **Solution**: Review Facebook ad policies, avoid restricted claims
- **Rewrite**: Remove "you" language, guarantees, before/after health claims
- **Appeal**: If policy-compliant, appeal rejection through Ads Manager

**Issue: Quiz logic not working in Typeform**
- **Solution**: Review quiz structure in artifact, map to Typeform logic jumps
- **Test**: Complete quiz yourself to verify all paths work
- **Document**: Create logic map diagram for reference

**Issue: PDF design doesn't match brand guidelines**
- **Solution**: Reference `/docs/BRAND_GUIDELINES.md` for exact specs
- **Tools**: Use Canva Brand Kit or Adobe CC Libraries to enforce consistency
- **Review**: Have second team member QA before finalization

### FAQ

**Q: Can I use these prompts for a different brand/program?**
A: Yes, with customization. Replace all IGNITE-specific variables (brand name, price, target audience, core promise) with your own.

**Q: Do I need to run all 10 magnets, or can I start with fewer?**
A: Start with 2-3 highest-priority magnets. Scale to all 10 as you validate initial performance.

**Q: What if I don't have Leadpages? Can I use alternatives?**
A: Yes. Alternatives: Unbounce, Instapage, Carrd, Webflow, or custom WordPress with Elementor.

**Q: Can I modify the generated artifacts?**
A: Absolutely. Artifacts are starting points. Customize copy, design, and structure to fit your specific needs.

**Q: How much should I budget for Facebook ads?**
A: Start with $50-100/day total across 2-3 magnets. Scale to $500-1,000/day as you validate ROI.

**Q: What's the minimum technical skill needed?**
A: Basic familiarity with landing page builders, email platforms, and Facebook Ads Manager. No coding required.

**Q: How long until I see IGNITE program signups?**
A: Expect first signups within 7-14 days. Conversion optimization typically takes 30-60 days to dial in.

**Q: Can I hire a team to implement this for me?**
A: Yes. Use role descriptions in "Team Collaboration" section to hire freelancers or agency support.

### Resource Links

- **Leadpages Tutorial**: [leadpages.com/tutorials](https://leadpages.com/tutorials)
- **Typeform Quiz Guide**: [typeform.com/help/quiz](https://www.typeform.com/help/)
- **Facebook Ads Learning**: [facebook.com/business/learn](https://www.facebook.com/business/learn)
- **Email Marketing Best Practices**: See `/research/PLATFORM-OPTIMIZATION.md`
- **Canva Design School**: [canva.com/learn](https://www.canva.com/learn/)
- **Conversion Rate Optimization**: See `/implementation/WEEK-2-OPTIMIZATION.md`

### Technical Support

For repository-specific questions:
- **GitHub Issues**: Open an issue in this repository
- **Documentation**: Check `/docs` folder first
- **Team Slack**: #ignite-lead-magnets channel

For implementation support:
- **Leadpages Support**: support.leadpages.com
- **Typeform Support**: typeform.com/help
- **Facebook Ads Support**: facebook.com/business/help

---

## Next Steps

1. **Clone this repository** and familiarize yourself with structure
2. **Review `/docs/BRAND_GUIDELINES.md`** to understand IGNITE brand
3. **Read `/docs/EXECUTION_GUIDE.md`** for detailed prompt execution instructions
4. **Execute all 10 prompts** using parallel or sequential approach
5. **Organize artifacts** into `/artifacts/` folders
6. **Begin implementation** following `/implementation/WEEK-1-SETUP.md`
7. **Track progress** using `/team/STATUS-TRACKING.md`
8. **Optimize and scale** based on performance data

---

## License

This repository and all contents are proprietary to IGNITE. See `LICENSE` file for usage terms.

---

## Contributing

See `CONTRIBUTING.md` for guidelines on proposing changes, improvements, or additional lead magnet prompts.

---

**Ready to ignite explosive growth? Start with `/prompts/01-PAIN-VISION-LEDGER.md` and let's build your list.**
