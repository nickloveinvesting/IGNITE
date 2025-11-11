# Lead Magnet Prompts

This folder contains all 10 complete lead magnet generation prompts for IGNITE.

---

## What Are These Prompts?

Each prompt is a complete, standalone set of instructions designed to be pasted into Claude AI. When executed, Claude generates 6 production-ready artifacts:

1. **landing-page.html** - Complete HTML landing page
2. **email-sequences.md** - 5-7 email nurture sequence
3. **facebook-ads.md** - 3-5 ad variations with targeting
4. **video-script.md** - Complete video script with production notes
5. **pdf-template-specs.md** - PDF/workbook design specifications
6. **implementation-notes.md** - Technical setup and integration instructions

---

## File List

### 00-GITHUB-ARCHITECTURE.md
**Purpose:** Repository setup prompt (this prompt created this repository structure)
**Use:** Only needed for setting up additional repositories

### 01-PAIN-VISION-LEDGER.md
**Target:** W2 employees stuck in corporate grind
**Format:** Interactive PDF workbook
**Expected Conversion:** 25-35%
**Use:** First magnet to launch, establishes core IGNITE framework

### 02-ARCHETYPE-QUIZ.md
**Target:** People unsure which entrepreneurial path fits them
**Format:** Interactive quiz (7-10 questions)
**Expected Conversion:** 40-50%
**Use:** High-converting lead magnet, enables segmentation

### 03-NO-EXCUSES-MANDATE.md
**Target:** People with excuse patterns blocking progress
**Format:** PDF manifesto + audio
**Expected Conversion:** 20-30%
**Use:** Attracts action-takers, filters out tire-kickers

### 04-SEVEN-LEVELS-WHY.md
**Target:** Entrepreneurs lacking deep motivation clarity
**Format:** Interactive workbook + video
**Expected Conversion:** 30-40%
**Use:** Deep engagement tool, identifies high-intent leads

### 05-BELIEF-SYSTEM-AUDIT.md
**Target:** Anyone sabotaging success with limiting beliefs
**Format:** Self-assessment + personalized report
**Expected Conversion:** 35-45%
**Use:** Core IGNITE methodology, high engagement

### 06-IDENTITY-STATEMENT.md
**Target:** People without clear identity as entrepreneur/leader
**Format:** Interactive tool → Personalized statement
**Expected Conversion:** 40-50%
**Use:** High shareability, viral potential

### 07-REDEMPTIVE-STORY.md
**Target:** People with past failures who feel defeated
**Format:** Story framework workbook
**Expected Conversion:** 25-35%
**Use:** Emotional connection, powerful for storytellers

### 08-DAILY-DISCIPLINE.md
**Target:** People struggling with consistency and habits
**Format:** 90-day tracker + habit stacking guide
**Expected Conversion:** 30-40%
**Use:** Long-term engagement, daily touchpoint

### 09-TWENTY-EIGHT-DAY-CHALLENGE.md
**Target:** Action-takers who want structured transformation
**Format:** 28-day email challenge + daily tasks
**Expected Conversion:** 45-55%
**Use:** Highest conversion, intensive engagement

### 10-PAIN-TO-POWER-DECODER.md
**Target:** People who can't articulate their transformation story
**Format:** Before/after decoder + visualization tool
**Expected Conversion:** 35-45%
**Use:** Transformation visualization, powerful for visual learners

---

## How to Use These Prompts

### Option 1: Parallel Execution (Recommended)

**Time:** ~45 minutes
**Advantage:** Generate all 10 magnets simultaneously

**Steps:**
1. Open 10 Claude conversations (separate tabs/windows)
2. Copy prompt 01 → Paste in Tab 1 → Enter
3. Copy prompt 02 → Paste in Tab 2 → Enter
4. [Continue for all 10]
5. Monitor generation across all tabs
6. Download artifacts as each completes
7. Organize into `/artifacts/` folders

---

### Option 2: Sequential Execution

**Time:** ~4-5 hours
**Advantage:** Easier to track, allows refinement between magnets

**Steps:**
1. Open single Claude conversation
2. Copy prompt 01 → Paste → Enter
3. Wait for complete generation (~25-30 min)
4. Download all 6 artifacts
5. Organize into `/artifacts/magnet-01-pain-vision-ledger/`
6. Repeat for prompts 02-10

---

## Prompt Structure

Each prompt follows this structure:

### Section 1: Context & Role
- Defines Claude's role
- Establishes expertise
- Sets expectation for output

### Section 2: Brand Guidelines
- IGNITE colors (#FF4D00, #2C3539, #FFFFFF)
- Inter font specifications
- Toby Potter voice characteristics
- Tone guidelines by context

### Section 3: Research Phase
- 3-agent research system
  - Agent 1: Competitive Intelligence
  - Agent 2: Audience Psychology
  - Agent 3: Platform Optimization
- Web search queries
- Research synthesis

### Section 4: Artifact Generation
Detailed instructions for each artifact:
- Landing page (HTML with inline CSS)
- Email sequences (5-7 emails with subject lines)
- Facebook ads (3-5 variations with targeting)
- Video script (with production notes)
- PDF template specs (design + content)
- Implementation notes (technical setup)

### Section 5: Quality Standards
- Brand alignment checks
- Conversion optimization requirements
- Technical functionality standards
- Compliance considerations

---

## Customization Variables

Each prompt includes these customizable variables:

**Brand Variables:**
- `[BRAND_COLOR_PRIMARY]` → #FF4D00 (Fire)
- `[BRAND_COLOR_SECONDARY]` → #2C3539 (Charcoal)
- `[BRAND_FONT]` → Inter
- `[BRAND_VOICE]` → Toby Potter (direct, authoritative, action-oriented)

**Business Variables:**
- `[PROGRAM_NAME]` → IGNITE
- `[PROGRAM_PRICE]` → $99/month
- `[TARGET_AUDIENCE]` → W2 employees, 1099 contractors, emerging entrepreneurs
- `[CORE_PROMISE]` → Break free from limiting beliefs, achieve financial and personal freedom

**To Customize:**
1. Open prompt file
2. Find all `[VARIABLE]` instances
3. Replace with your values
4. Save customized version

---

## Quality Assurance

After generating artifacts from each prompt, verify:

### Brand Alignment
- [ ] Colors match IGNITE palette exactly
- [ ] Inter font specified throughout
- [ ] Voice is direct, no-fluff, action-oriented
- [ ] Tone appropriate for context

### Completeness
- [ ] All 6 artifacts generated
- [ ] No truncated or incomplete sections
- [ ] All placeholders have example content
- [ ] Implementation notes include technical details

### Conversion Optimization
- [ ] Headlines grab attention
- [ ] CTAs are clear and bold
- [ ] Value proposition stated early
- [ ] Objections pre-addressed
- [ ] Urgency appropriate (not manipulative)

### Technical Functionality
- [ ] HTML validates
- [ ] Email formatting correct
- [ ] Ad copy within character limits
- [ ] PDF specs include dimensions
- [ ] Quiz logic mapped clearly

**Use `/docs/QUALITY_CHECKLIST.md` for comprehensive QA**

---

## Troubleshooting

### Incomplete Artifacts
**Issue:** Prompt generates only 3-4 artifacts instead of 6
**Solution:** Reply in conversation: "Please complete the missing artifacts: [list them]"

### Brand Misalignment
**Issue:** Wrong colors, different voice
**Solution:** Reply: "Regenerate using exact IGNITE brand: Fire #FF4D00, Charcoal #2C3539, Inter font, direct Toby Potter voice"

### Generic Content
**Issue:** Artifacts too generic, not IGNITE-specific
**Solution:** Reply: "Make this specific to IGNITE ($99/month program for W2/1099/entrepreneurs breaking limiting beliefs)"

### Technical Issues
**Issue:** HTML doesn't render, email format broken
**Solution:** Reply: "Please provide valid HTML5" or "Please format emails for plain text rendering"

**See `/docs/EXECUTION_GUIDE.md` for complete troubleshooting**

---

## Creating New Prompts (Magnets #11-20)

When you're ready to scale beyond 10 magnets:

1. **Copy `/templates/PROMPT-TEMPLATE.md`**
2. **Define new magnet:**
   - Target audience sub-segment
   - Specific problem solved
   - Unique format or angle
3. **Customize research section:**
   - Specific competitors to analyze
   - Specific audience pain points
   - Specific platform optimization
4. **Follow existing prompt structure**
5. **Test generate** before adding to repository
6. **Document results** in `/research/`

---

## Prompt Maintenance

Update prompts when:

- **Brand guidelines change** (colors, voice, positioning)
- **Platform best practices evolve** (Facebook algorithm, email deliverability)
- **Competitive landscape shifts** (new major player, format innovations)
- **Performance data reveals issues** (consistent low conversion, high unsubscribe)

**Version Control:**
- Keep original prompts intact
- Create versioned copies: `01-PAIN-VISION-LEDGER-v2.md`
- Document changes in prompt header
- Test new version before replacing original

---

## Expected Output Size

Per magnet, expect approximately:

- **Landing Page HTML:** 300-500 lines
- **Email Sequences:** 2,000-3,000 words (5-7 emails)
- **Facebook Ads:** 1,000-1,500 words (3-5 variations)
- **Video Script:** 800-1,200 words (60-120 second video)
- **PDF Template Specs:** 1,500-2,500 words (design + content)
- **Implementation Notes:** 500-800 words (technical setup)

**Total per magnet:** ~7,000-10,000 words
**Total for 10 magnets:** ~70,000-100,000 words (equivalent to short book)

---

## Usage Tips

1. **Read brand guidelines first** (`/docs/BRAND_GUIDELINES.md`) before running any prompt

2. **Have stable internet** - Large artifact generation can timeout on spotty connections

3. **Use Claude Pro if possible** - Higher usage limits, better for parallel execution

4. **Download immediately** - Don't wait to download all at end, do it as each completes

5. **Review incrementally** - Check first magnet's output before generating all 10

6. **Keep prompts updated** - As you learn what works, refine prompts for better output

7. **Document custom changes** - If you manually edit artifacts, note what you changed and why

8. **Version your prompts** - Keep original prompts intact, create v2/v3 as you improve

9. **Test one completely** - Implement Magnet #1 fully before generating all 10 to validate approach

10. **Share learnings** - Document what works in `/research/` for future reference

---

## Prompt Development Roadmap

**Phase 1: Core 10 Magnets** (Complete)
- Diverse formats (PDF, quiz, challenge, tools)
- Cover all major pain points
- Multiple conversion rate profiles

**Phase 2: Magnets 11-15** (Future)
- Segment-specific (W2 only, 1099 only, entrepreneur only)
- Advanced topics (scaling, systems, leadership)
- Alternative formats (workshops, templates, calculators)

**Phase 3: Magnets 16-20** (Future)
- Micro-niche targeting
- Industry-specific variations
- Experimental formats

---

## Success Metrics

Track performance of each magnet to inform future prompt development:

**High Priority Metrics:**
- Landing page conversion rate
- Email open/click rates
- IGNITE program conversion rate
- Cost per lead
- Cost per acquisition

**Secondary Metrics:**
- Time to completion (workbooks/challenges)
- Social shares (Identity Statement, Archetype Quiz)
- Email forward rate
- Referral rate

**Store performance data in:** `/implementation/TRACKING-DASHBOARD.md`

---

## Support

**For prompt execution questions:**
- See `/docs/EXECUTION_GUIDE.md`

**For brand alignment questions:**
- See `/docs/BRAND_GUIDELINES.md`

**For implementation questions:**
- See `/implementation/` folder

**For technical issues:**
- Open GitHub issue
- Tag with "prompt-generation"
- Include magnet number and specific issue

---

**These prompts represent 100+ hours of strategic thinking condensed into executable AI instructions. Use them. Customize them. Scale with them.**
