# Process & Workflow

This document defines the step-by-step workflow for creating, testing, and launching lead magnets.

---

## Overview

The lead magnet workflow has 4 phases:

1. **Design Phase** - Create prompt and strategy
2. **Generation Phase** - Generate artifacts using Claude
3. **Quality Phase** - QA and refine artifacts
4. **Execution Phase** - Launch and optimize

---

## Phase 1: Design Phase (Weeks 1-2)

### Step 1.1: Define Magnet Concept

**Owner:** Prompt Engineer
**Time:** 4 hours
**Deliverable:** Magnet concept document

**Process:**
1. Identify target audience pain point
2. Research competitive alternatives
3. Define unique positioning/angle
4. Outline magnet format (PDF, quiz, challenge, etc.)
5. Write 1-page concept brief

**Approval Gate:**
- [ ] Concept aligned with IGNITE positioning
- [ ] Target audience clearly defined
- [ ] Competitive advantage identified
- [ ] Format decision justified

**Example Output:**
```
Magnet #11: Goal Setting Accountability
- Target: Entrepreneurs who set goals but don't achieve them
- Pain: Lack of accountability and tracking system
- Angle: Community accountability + structured framework
- Format: 90-day goal tracker + email accountability sequence
- Positioning: "The only goal system designed for entrepreneurs"
```

---

### Step 1.2: Research

**Owner:** Prompt Engineer + Market Research Analyst
**Time:** 8 hours
**Deliverable:** Research findings document

**Process:**
1. Competitive analysis: Research 5+ similar programs
2. Audience research: Interview 3-5 ideal customers
3. Platform research: Understand technical requirements
4. Psychology research: Identify key psychological triggers
5. Summarize findings in brief

**Components:**
- Competitive positioning (what gap are you filling?)
- Audience psychology (why would they engage?)
- Market validation (is demand real?)
- Technical requirements (what platform is needed?)
- Success metrics (what indicates success?)

**Approval Gate:**
- [ ] Research is based on actual market data
- [ ] Findings support magnet positioning
- [ ] Psychology principles identified
- [ ] Success metrics are measurable

---

### Step 1.3: Create Prompt

**Owner:** Prompt Engineer
**Time:** 8 hours
**Deliverable:** Completed prompt file

**Process:**
1. Open `/templates/PROMPT-TEMPLATE.md`
2. Fill in all sections with specific details
3. Reference research findings
4. Include brand guidelines integration
5. Define quality standards
6. Save to `/prompts/[number]-[NAME].md`
7. Get peer review

**Prompt Sections:**
- Executive summary
- Target audience
- Research findings
- Generation instructions for each artifact
- Quality checklist
- Success criteria

**Approval Gate:**
- [ ] Prompt follows template structure
- [ ] All 6 artifacts specified
- [ ] Brand guidelines integrated
- [ ] Quality checklist included
- [ ] Research findings referenced

---

## Phase 2: Generation Phase (Week 3)

### Step 2.1: Generate Artifacts

**Owner:** Prompt Engineer (or designated executor)
**Time:** 4-8 hours
**Deliverable:** 6 artifacts per magnet

**Process:**
1. Log into Claude (Web or API)
2. Copy the complete prompt
3. Submit prompt to Claude
4. Wait for generation (typically 5-10 minutes)
5. Download all outputs
6. Save temporarily in organized folder

**Artifact Files Generated:**
1. `landing-page.html` (300-500 lines)
2. `email-sequence.md` (2,000-3,000 words)
3. `facebook-ads.md` (1,000-1,500 words)
4. `video-script.md` (800-1,200 words)
5. `pdf-template-specs.md` (1,500-2,500 words)
6. `implementation-notes.md` (500-800 words)

**Success Criteria:**
- [ ] All 6 files generated
- [ ] No truncated content
- [ ] Formatting is readable
- [ ] File sizes reasonable

---

### Step 2.2: Organize Artifacts

**Owner:** Artifact Manager
**Time:** 1-2 hours
**Deliverable:** Properly organized artifact folder

**Process:**
1. Create folder: `/artifacts/magnet-[number]-[name]/`
2. Use folder naming: lowercase with hyphens
3. Copy each artifact into folder with correct filename:
   - `landing-page.html`
   - `email-sequence.md` or `email-sequences.md`
   - `facebook-ads.md`
   - `video-script.md`
   - `pdf-template-specs.md` or `worksheet-specifications.md`
   - `implementation-notes.md` or `implementation-summary.md`
4. Create README.md in folder (see template)
5. Commit to git

**Folder Structure Example:**
```
artifacts/magnet-11-goal-setting-accountability/
├── README.md
├── landing-page.html
├── email-sequence.md
├── facebook-ads.md
├── video-script.md
├── pdf-template-specs.md
└── implementation-notes.md
```

**Approval Gate:**
- [ ] All 6 files present
- [ ] File names match convention
- [ ] Folder name lowercase with hyphens
- [ ] README created
- [ ] Committed to git

---

## Phase 3: Quality Phase (Week 4)

### Step 3.1: Brand Alignment Check

**Owner:** Copywriter + Brand Manager
**Time:** 2-3 hours
**Deliverable:** QA report with feedback

**Process:**
1. Review each artifact against `/docs/BRAND_GUIDELINES.md`
2. Check color usage (#FF4D00, #2C3539, #FFFFFF)
3. Verify Inter font specified
4. Evaluate voice (Toby Potter style)
5. Assess tone appropriateness
6. Document all issues
7. Provide specific improvement suggestions

**Brand Alignment Checklist:**
- [ ] Colors match IGNITE palette
- [ ] Inter font used for typography
- [ ] Voice matches Toby Potter (direct, action-oriented)
- [ ] Tone appropriate for context
- [ ] No jargon or corporate speak
- [ ] All copy uses active voice
- [ ] Messaging consistent across artifacts

**Issues Documentation:**
Create issues like:
```
Landing Page Title Issue
- Current: "Discover Your Goal Setting Potential"
- Problem: Passive, not action-oriented
- Suggestion: "Set Goals. Actually Achieve Them."
- Severity: High (headline sets tone)
```

---

### Step 3.2: Content Quality Check

**Owner:** Copywriter
**Time:** 2-3 hours
**Deliverable:** Content revision notes

**Process:**
1. Read each artifact carefully
2. Check for:
   - Grammar and spelling
   - Clarity and conciseness
   - Logic flow
   - CTA effectiveness
   - Objection handling
   - Emotional resonance
3. Flag areas for improvement
4. Suggest specific revisions
5. Document all feedback

**Content Quality Checklist:**
- [ ] No grammatical or spelling errors
- [ ] Copy is clear and concise
- [ ] Logic flow is coherent
- [ ] CTAs are bold and specific
- [ ] Objections addressed
- [ ] Emotional triggers present
- [ ] Story structure (if applicable)

---

### Step 3.3: Technical Verification

**Owner:** Landing Page Developer + Artifact Manager
**Time:** 1-2 hours
**Deliverable:** Technical QA report

**Process:**
1. Validate HTML for landing page
   - W3C validation: https://validator.w3.org/
   - Check for errors and fix
2. Test email formatting
   - Preview in multiple email clients
   - Check mobile rendering
3. Review Facebook ad specs
   - Character counts within limits
   - Targeting specifications clear
4. Review video script production notes
   - Camera/lighting instructions clear
   - Graphics overlay points marked
5. Review PDF specs completeness
   - Dimensions specified
   - Color mode defined
   - Font files listed
6. Review implementation notes
   - Step-by-step instructions
   - No missing steps
   - Links to resources valid

**Technical Checklist:**
- [ ] HTML validates (0 errors)
- [ ] Email responsive design
- [ ] Ad copy within character limits
- [ ] Video script production-ready
- [ ] PDF specs comprehensive
- [ ] Implementation instructions clear

---

### Step 3.4: Refine Based on Feedback

**Owner:** Copywriter + Artifact Manager
**Time:** 2-4 hours
**Deliverable:** Revised artifacts

**Process:**
1. Gather all feedback from QA team
2. Prioritize issues (critical > high > medium > low)
3. Implement critical and high issues immediately
4. Schedule medium/low issues for optimization
5. Update artifacts in `/artifacts/` folder
6. Document all changes
7. Commit to git

**Change Documentation:**
```
- Landing page title: Changed to "Set Goals. Actually Achieve Them."
- Email #2: Restructured to address accountability objection
- Facebook ads: Increased urgency in CTA ("Join This Week")
- Video script: Added production notes for B-roll placement
```

---

### Step 3.5: Final Approval

**Owner:** Prompt Engineer (final decision authority)
**Time:** 30 minutes - 1 hour
**Deliverable:** Approval sign-off

**Process:**
1. Review all QA feedback and revisions
2. Test artifacts if needed
3. Compare to original prompt requirements
4. Verify quality standards met
5. Make final pass if needed
6. Sign off for launch readiness
7. Update `/artifacts/README.md` status

**Final Approval Checklist:**
- [ ] Brand alignment: 95%+ match
- [ ] Content quality: 90%+ clarity
- [ ] Technical: 100% working
- [ ] Completeness: All 6 artifacts
- [ ] Ready to implement

**Status Update in `/artifacts/README.md`:**
```
| 11 | Goal Setting Accountability | ✅ Complete | 6 files | Ready to Launch |
```

---

## Phase 4: Execution Phase (Weeks 5-8)

### Step 4.1: Landing Page Implementation

**Owner:** Landing Page Developer
**Time:** 4-6 hours
**Deliverable:** Live landing page

**Process:**
1. Choose platform (Leadpages, custom domain, etc.)
2. Import HTML artifact
3. Connect form to email platform
4. Add Facebook Pixel
5. Test form submission
6. Test mobile responsiveness
7. Set up analytics
8. Deploy to live domain
9. Verify live

**Implementation Checklist:**
- [ ] HTML imported successfully
- [ ] Form fields work
- [ ] Email integration confirmed
- [ ] Pixel firing correctly
- [ ] Mobile design responsive
- [ ] Analytics tracking
- [ ] Page live and accessible

---

### Step 4.2: Email Sequence Setup

**Owner:** Email Manager
**Time:** 3-4 hours
**Deliverable:** Automated email sequence

**Process:**
1. Create email campaign in ESP
2. Import email sequence artifact
3. Set up personalization tokens
4. Create automation trigger (form submission)
5. Set timing between emails
6. Configure list segments
7. Test email delivery
8. Preview in multiple clients
9. Activate automation

**Email Setup Checklist:**
- [ ] All emails imported
- [ ] Personalization configured
- [ ] Automation triggered correctly
- [ ] Timing set (1-2 days between)
- [ ] Segmentation tags configured
- [ ] Deliverability tested
- [ ] Automation live

---

### Step 4.3: Facebook Ads Campaign

**Owner:** Ads Manager
**Time:** 4-6 hours
**Deliverable:** Facebook ads campaign

**Process:**
1. Create campaign in Ads Manager
2. Set objective: Lead Generation
3. Audience: Create audiences per ad specs
4. Create ad variations from artifact
5. Design ad creative (hire designer if needed)
6. Set budget: $30-50/day to start
7. Configure conversion tracking
8. Set A/B testing parameters
9. Launch campaign

**Ads Campaign Checklist:**
- [ ] Campaign created
- [ ] Audiences configured
- [ ] Ads created
- [ ] Creative sourced
- [ ] Budgets set
- [ ] Conversion tracking
- [ ] Campaign live

---

### Step 4.4: Video Production

**Owner:** Video Producer
**Time:** 8-12 hours
**Deliverable:** Hosted video with embed code

**Process:**
1. Review video script production notes
2. Plan production (location, equipment, talent)
3. Shoot video (or hire videographer)
4. Edit video (add text overlays, captions)
5. Export for web (MP4, optimized)
6. Upload to Vimeo or YouTube
7. Create embed code
8. Add to landing page
9. Test playback

**Video Production Checklist:**
- [ ] Script reviewed
- [ ] Production planned
- [ ] Video shot
- [ ] Edited and optimized
- [ ] Captions added
- [ ] Uploaded to platform
- [ ] Embed code working

---

### Step 4.5: PDF Lead Magnet Design

**Owner:** Designer
**Time:** 6-8 hours
**Deliverable:** Downloadable PDF

**Process:**
1. Review PDF specs from artifact
2. Create layout in Adobe InDesign or Canva
3. Apply IGNITE branding
4. Create fillable form fields (if needed)
5. Export as PDF
6. Optimize file size (<10MB)
7. Upload to Dropbox, Google Drive, or S3
8. Generate shareable link
9. Add to landing page thank-you page

**PDF Design Checklist:**
- [ ] Specs followed
- [ ] Branding applied
- [ ] Fields functional (if interactive)
- [ ] File size <10MB
- [ ] Quality checked
- [ ] Uploaded
- [ ] Download link working

---

### Step 4.6: Launch Coordination

**Owner:** Project Manager
**Time:** 2-3 hours
**Deliverable:** All systems live and tested

**Process:**
1. Verify all systems ready:
   - [ ] Landing page live
   - [ ] Form submissions working
   - [ ] Email automation confirmed
   - [ ] Facebook ads running
   - [ ] Video embedded
   - [ ] PDF downloadable
2. Conduct end-to-end test:
   - Submit test form
   - Confirm email received
   - Verify PDF download
   - Check Facebook Pixel
3. Monitor for first 24 hours
4. Address any issues immediately
5. Notify team of live status
6. Begin performance monitoring

**Launch Checklist:**
- [ ] All systems verified
- [ ] End-to-end test complete
- [ ] No errors found
- [ ] Team notified
- [ ] Monitoring active

---

### Step 4.7: Performance Monitoring

**Owner:** Analytics Lead + Project Manager
**Time:** 1-2 hours daily (ongoing)
**Deliverable:** Daily performance reports

**Process:**
1. **Daily:** Monitor key metrics
   - Form submissions
   - Email open/click rates
   - Facebook ad performance
   - Cost per lead
2. **Every 3 days:** Check for technical issues
   - Landing page errors
   - Form failures
   - Email delivery problems
3. **Weekly:** Full performance analysis
   - Conversion rates vs. benchmarks
   - Identify optimization opportunities
   - Report to team
4. **Monthly:** Comprehensive ROI analysis
   - Total leads generated
   - Cost per lead
   - IGNITE conversion rate
   - Revenue generated

**Monitoring Metrics:**
- Landing page traffic
- Form conversion rate
- Email open/click rates
- Cost per lead
- Facebook ROAS
- Downstream IGNITE conversions

---

## Timeline Example

### Magnet #11 Development Timeline

| Week | Phase | Owner | Deliverable |
|------|-------|-------|-------------|
| 1 | Design | Prompt Engineer | Magnet concept + research |
| 1-2 | Design | Prompt Engineer | Completed prompt |
| 3 | Generate | Prompt Engineer | 6 artifacts |
| 3 | Organize | Artifact Manager | Artifacts folder |
| 4 | QA | Copywriter/Brand | QA report |
| 4 | Refine | Copywriter | Revised artifacts |
| 5 | Landing Page | Dev | Live landing page |
| 5 | Email | Email Manager | Automation live |
| 6 | Ads | Ads Manager | Campaign running |
| 6 | Video | Producer | Video embedded |
| 7 | PDF | Designer | PDF downloadable |
| 7 | Launch | PM | All systems live |
| 8+ | Monitor | Analytics | Performance reports |

**Total Timeline:** 6-8 weeks from concept to launch

---

## Handoff Process

When passing work between roles:

### Handoff Template

```
TO: [Next Role]
FROM: [Current Role]
DEADLINE: [Date]

DELIVERABLE:
- What is being handed off?
- Where is it located?

CONTEXT:
- What work was done?
- What decisions were made?
- What should they know?

NEXT STEPS:
- What should they do?
- What should they check?
- What's the approval gate?

QUESTIONS:
- Ask any clarifying questions now
```

### Example: Artifact Manager → Copywriter

```
TO: Copywriter
FROM: Artifact Manager
DEADLINE: Friday EOD

DELIVERABLE:
- Magnet #11 artifacts in /artifacts/magnet-11-goal-setting/
- All 6 files present and organized
- README created

CONTEXT:
- Artifacts generated 2 days ago
- Minimal touch-ups needed (mostly formatting)
- All content looks strong

NEXT STEPS:
- Brand alignment review
- Copy refinement for Toby voice
- QA report by Friday
- Return revised artifacts for final approval

QUESTIONS:
- Is the email sequence too long at 2,800 words?
```

---

## Communication During Process

### Status Updates
- **Project Manager sends daily 1-line status** (Slack or email)
- **Weekly team sync** (30 min, Tuesday 10am)
- **Issues escalated within 24 hours**

### Document Changes
- **All changes committed to git** with descriptive message
- **Change log in artifact README**
- **Email team when major revisions complete**

### Feedback Loop
- **QA feedback within 24 hours of receiving work**
- **Revisions completed within 48 hours**
- **Final approval within 24 hours of revisions**

---

## Troubleshooting Common Issues

| Issue | Cause | Solution |
|-------|-------|----------|
| Artifacts incomplete | Prompt didn't generate fully | Re-run prompt with tweaks |
| HTML errors | Validation issues | Fix with developer, test |
| Email deliverability | List issues or sender reputation | Check ESP guidelines, warm up |
| Low form conversions | Landing page issue | A/B test headlines/copy |
| High CPL | Audience targeting | Test different audiences |
| Low email opens | Subject lines | A/B test subject lines |

---

**Clear process = Faster execution = Better results.**
