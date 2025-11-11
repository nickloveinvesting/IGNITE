# Generated Artifacts

This folder stores all generated artifacts from the 10 lead magnet prompts.

---

## Folder Structure

```
artifacts/
├── README.md (this file)
├── magnet-01-pain-vision-ledger/
├── magnet-02-archetype-quiz/
├── magnet-03-no-excuses-mandate/
├── magnet-04-seven-levels-why/
├── magnet-05-belief-system-audit/
├── magnet-06-identity-statement/
├── magnet-07-redemptive-story/
├── magnet-08-daily-discipline/
├── magnet-09-twenty-eight-day-challenge/
└── magnet-10-pain-to-power-decoder/
```

Each folder contains 6 artifacts generated from Claude AI.

---

## Artifact Types

### 1. landing-page.html
**Description:** Complete HTML landing page with inline CSS
**Size:** 300-500 lines of code
**Purpose:** Upload to Leadpages or host independently

**Contents:**
- Hero section with headline and CTA
- Problem/solution sections
- Benefits/features
- Social proof (placeholders)
- Lead capture form
- Thank-you page redirect
- Mobile-responsive design
- IGNITE brand colors and fonts

**Implementation:**
- Copy HTML into Leadpages HTML block
- OR host on custom domain
- Connect form to email platform
- Add Facebook Pixel
- Test mobile responsiveness

---

### 2. email-sequences.md
**Description:** 5-7 email nurture sequence
**Size:** 2,000-3,000 words total
**Purpose:** Load into ESP (ActiveCampaign, ConvertKit, HubSpot)

**Contents:**
- Email 1: Welcome + deliver lead magnet
- Email 2: Quick win or insight
- Email 3: Deeper value + story
- Email 4: Address objection
- Email 5-6: Introduce IGNITE program
- Email 7: Clear CTA to join IGNITE

Each email includes:
- Subject line
- Preview text
- Body copy (150-300 words)
- CTA
- Timing recommendation (1-2 days between emails)

**Implementation:**
- Copy each email into ESP
- Set up automation triggers
- Configure delays between emails
- Test delivery
- Monitor open/click rates

---

### 3. facebook-ads.md
**Description:** 3-5 ad variations with targeting specifications
**Size:** 1,000-1,500 words
**Purpose:** Create campaigns in Facebook Ads Manager

**Contents:**
Per ad variation:
- Headline (40 characters max)
- Primary text (125 characters optimized, full version included)
- Ad copy (hook, problem, solution, CTA)
- Image direction (specific guidance)
- Audience targeting (demographics, interests, behaviors)
- Budget recommendation
- Bidding strategy

**Implementation:**
- Create campaign in Ads Manager
- Set objective: Lead Generation
- Input targeting parameters
- Create ad creative (use image direction)
- Write copy (optimize for mobile)
- Set budget ($30-50/day to start)
- Launch and monitor

---

### 4. video-script.md
**Description:** Complete video script with production notes
**Size:** 800-1,200 words
**Purpose:** Record explainer video for landing page or ads

**Contents:**
- Opening hook (first 3 seconds)
- Problem agitation
- Solution introduction
- Value delivery
- CTA
- Total length: 60-120 seconds
- Shot directions (close-up, B-roll, text overlays)
- Music/tone guidance
- Graphic insert points

**Implementation:**
- Hire video producer or record yourself
- Follow shot directions
- Add text overlays as noted
- Include captions (80% watch without sound)
- Add CTA button/link
- Upload to Vimeo/YouTube
- Embed in landing page

---

### 5. pdf-template-specs.md
**Description:** PDF/workbook design specifications
**Size:** 1,500-2,500 words
**Purpose:** Hand to designer for PDF creation

**Contents:**
- Page count and dimensions
- Cover page design
- Interior layout specifications
- Content sections (what goes on each page)
- Interactive elements (fillable fields)
- Brand application (colors, fonts, logos)
- Examples/templates
- Export requirements (digital + print)

**Implementation:**
- Send specs to designer (Canva, Adobe InDesign)
- Review draft for brand alignment
- Test fillable fields (if interactive)
- Optimize file size (<10MB)
- Upload to hosting (Dropbox, Drive, S3)
- Link from landing page thank-you page

---

### 6. implementation-notes.md
**Description:** Technical setup and integration instructions
**Size:** 500-800 words
**Purpose:** Step-by-step implementation guide

**Contents:**
- Platform setup (Leadpages, Typeform, ESP)
- Integration instructions (form to email platform)
- Tracking setup (Facebook Pixel, Google Analytics)
- Email automation configuration
- Testing checklist
- Launch checklist
- Monitoring recommendations
- Troubleshooting common issues

**Implementation:**
- Follow step-by-step
- Check off each item
- Test all integrations
- Verify tracking works
- Launch when complete

---

## File Naming Convention

Use consistent naming within each magnet folder:

```
landing-page.html
email-sequences.md
facebook-ads.md
video-script.md
pdf-template-specs.md
implementation-notes.md
```

**Do not rename files** - Other documentation references these exact names.

---

## Workflow: From Generation to Implementation

### Step 1: Generate
- Run prompt in Claude AI
- Wait for complete generation (4-8 minutes)

### Step 2: Download
- Copy each artifact from Claude conversation
- Paste into separate file
- Save with correct filename in correct folder

### Step 3: Organize
- Verify all 6 files present in magnet folder
- Check file naming matches convention
- Commit to git repository

### Step 4: Review
- Read through all artifacts
- Verify brand alignment
- Check for completeness
- Flag any issues

### Step 5: Customize
- Update placeholder URLs
- Add real testimonials (if available)
- Refine copy based on brand voice
- Optimize for your specific audience

### Step 6: Implement
- Follow implementation-notes.md
- Build landing page
- Set up email sequences
- Create Facebook ads
- Produce video
- Design PDF

### Step 7: Launch
- Test all systems
- Verify tracking
- Launch ads
- Monitor performance

---

## Artifact Customization

### Minimal Customization (Quick Launch)
- Replace placeholder URLs with real links
- Add real email address and phone number
- Update [COMPANY_NAME] placeholders
- Add real social media links

**Time:** 30 minutes per magnet

### Moderate Customization (Recommended)
- All minimal customizations
- Refine headlines based on A/B test ideas
- Add real testimonials/social proof
- Customize examples for your audience
- Optimize email subject lines

**Time:** 2-3 hours per magnet

### Heavy Customization (Optimize)
- All moderate customizations
- Rewrite sections in your exact voice
- Create custom graphics/branding
- Add unique case studies
- Build advanced segmentation
- Create multiple variations for testing

**Time:** 5-8 hours per magnet

**Recommendation:** Start with minimal, launch quickly, optimize based on data.

---

## Version Control

As you customize artifacts:

1. **Keep originals intact**
   - Don't overwrite generated files
   - Create `landing-page-v2.html` for customized versions

2. **Track changes**
   - Document what you changed and why
   - Note performance impact of changes

3. **Git commit frequently**
   ```bash
   git add artifacts/magnet-01-pain-vision-ledger/
   git commit -m "Customize Magnet 01 landing page headlines"
   git push
   ```

---

## Quality Assurance

Before implementing any artifact, verify:

### Brand Alignment
- [ ] IGNITE colors used correctly
- [ ] Inter font specified
- [ ] Voice matches Toby Potter style
- [ ] Tone appropriate for context

### Technical Quality
- [ ] HTML validates (landing page)
- [ ] Email formatting correct
- [ ] Ad copy within character limits
- [ ] Video script includes production notes
- [ ] PDF specs include dimensions

### Conversion Optimization
- [ ] Headlines grab attention
- [ ] Value proposition clear
- [ ] CTAs bold and specific
- [ ] Objections addressed
- [ ] Friction minimized

**Use `/docs/QUALITY_CHECKLIST.md` for comprehensive QA**

---

## Artifact Performance Tracking

Track which artifacts perform best:

**Landing Pages:**
- Conversion rate by magnet
- Best-performing headlines
- Mobile vs. desktop performance
- A/B test results

**Email Sequences:**
- Open rates by email #
- Click rates by email #
- Unsubscribe rate by magnet
- IGNITE conversion rate by sequence

**Facebook Ads:**
- CTR by ad variation
- Cost per lead by magnet
- Best-performing ad copy angle
- Best-performing audience segment

**Videos:**
- View completion rate
- Click-through to landing page
- Production cost vs. performance

**Store data in:** `/implementation/TRACKING-DASHBOARD.md`

---

## Common Issues & Solutions

### Issue: Artifacts feel too generic
**Solution:** Add specific examples, case studies, and testimonials from IGNITE members

### Issue: HTML doesn't render correctly
**Solution:** Validate HTML at validator.w3.org, fix errors, test in multiple browsers

### Issue: Email sequences too long
**Solution:** Cut fluff, keep emails 150-300 words, focus on one idea per email

### Issue: Facebook ads get rejected
**Solution:** Review Facebook ad policies, remove guarantees/claims, appeal if compliant

### Issue: Video script too complex to produce
**Solution:** Simplify to talking head format, focus on message over production value

### Issue: PDF specs unclear for designer
**Solution:** Find reference examples, create mockup in Google Docs, show designer

---

## Backup and Security

**Backup Strategy:**
- All artifacts committed to Git (version controlled)
- Secondary backup to Google Drive or Dropbox
- Local copy on team members' machines

**Security:**
- No credentials or API keys in artifacts
- No personally identifiable information
- Use environment variables for sensitive data
- Follow `.gitignore` rules

---

## Scaling Beyond 10 Magnets

When creating Magnets #11-20:

1. **Create new folder:** `artifacts/magnet-11-[name]/`
2. **Follow same structure:** 6 artifacts per magnet
3. **Maintain naming convention:** Same filenames as magnets 1-10
4. **Update this README:** Add new magnet to folder list
5. **Track performance:** Document what works vs. what doesn't

---

## Next Steps

1. Generate all 10 magnet artifacts using prompts in `/prompts/`
2. Download and organize into respective folders
3. Quality check using `/docs/QUALITY_CHECKLIST.md`
4. Customize based on level (minimal/moderate/heavy)
5. Implement following `/implementation/WEEK-1-SETUP.md`
6. Launch and track performance
7. Optimize based on data

---

**These artifacts are your marketing engine. Generate them. Customize them. Launch them. Grow with them.**
