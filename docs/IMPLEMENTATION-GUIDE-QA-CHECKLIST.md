# IMPLEMENTATION GUIDE & QA CHECKLIST
## Pain & Vision Ledger Lead Magnet - Complete Launch System

**Document Purpose**: Step-by-step implementation guide for launching the complete Pain & Vision Ledger lead magnet system.

**Estimated Implementation Time**: 6-8 hours (first-time setup)

**Prerequisites**:
- Email service provider account (ConvertKit, ActiveCampaign, Mailchimp, etc.)
- Landing page platform (Leadpages, Unbounce, or custom hosting)
- Facebook Ads Manager access (with payment method)
- Video hosting (YouTube channel)
- File hosting (Dropbox, Google Drive, or your server)
- Design tool access (Canva Pro, Adobe Creative Suite, or alternatives)

---

## PHASE 1: PRE-LAUNCH PREPARATION (2-3 hours)

### Step 1.1: Create PDF Template

**Timeline**: 1-2 hours

**Instructions**:
1. Open Canva Pro (or Adobe InDesign)
2. Create new document: 8.5" x 11", 2 pages
3. Follow specifications in `/assets/pdf/pain-vision-ledger-pdf-template-specs.md`
4. Design Page 1: The Ledger (two-column layout)
5. Design Page 2: 28-Day Tracker + Resources
6. Add QR code linking to www.joinignite.com/apply (use QR code generator)
7. Export as PDF (Print quality, 300 DPI)
8. Verify file size < 5MB
9. Test print in black & white (ensure readability)

**Deliverable**: `Pain-Vision-Ledger-IGNITE.pdf`

**QA Checklist**:
☐ File size under 5MB
☐ All brand colors correct
☐ Fonts embedded (Inter)
☐ Print quality 300 DPI
☐ QR code tested and working
☐ No typos or errors
☐ Black & white print test passed

---

### Step 1.2: Record & Edit Video

**Timeline**: 2-3 hours (recording + editing)

**Instructions**:
1. Set up recording space (professional background, good lighting)
2. Review script in `/assets/video/pain-vision-ledger-video-script.md`
3. Practice delivery 2-3 times (aim for natural, conversational tone)
4. Record video (multiple takes if needed)
5. Edit video:
   - Add title slide at start
   - Insert ledger template images when referenced
   - Add testimonial graphics/clips
   - Include text overlays for key stats (42%, 76%, 28 days)
   - Add end screen with CTA and link
6. Export: 1080p MP4, under 500MB
7. Create thumbnail (1280 x 720 pixels, Canva)

**Deliverable**:
- Video file: `Pain-Vision-Ledger-Video.mp4`
- Thumbnail: `Pain-Vision-Ledger-Thumbnail.jpg`

**QA Checklist**:
☐ Video length: 4:45 - 5:15 minutes
☐ Audio is clear (no background noise)
☐ Lighting is professional
☐ All visuals (ledger template) are shown clearly
☐ End screen includes CTA and link
☐ Thumbnail is compelling and on-brand
☐ File size under 500MB

---

### Step 1.3: Upload Assets to Hosting

**Timeline**: 30 minutes

**Instructions**:

**PDF Hosting**:
1. Upload `Pain-Vision-Ledger-IGNITE.pdf` to Dropbox, Google Drive, or your server
2. Generate shareable link (public access, no login required)
3. Test link in incognito browser window
4. Copy link for use in emails and landing page

**Video Hosting**:
1. Upload video to YouTube
2. Settings:
   - Visibility: Unlisted (or Public if you prefer)
   - Title: "The Pain & Vision Ledger: How One Exercise Changes Everything"
   - Description: Use template from video script file
   - Tags: Add all tags from script file
   - Thumbnail: Upload custom thumbnail
3. Enable embedding
4. Copy embed code (iframe) for landing page
5. Copy direct link for email

**Deliverables**:
- PDF download link
- Video embed code
- Video direct link

**QA Checklist**:
☐ PDF link works (test in incognito)
☐ PDF downloads correctly (no errors)
☐ Video plays on YouTube
☐ Video embed code copied
☐ Thumbnail displays correctly
☐ Description and tags added

---

## PHASE 2: LANDING PAGE SETUP (1-2 hours)

### Step 2.1: Build Landing Page

**Timeline**: 1-1.5 hours

**Instructions**:

**Option A: Using Leadpages**
1. Log in to Leadpages
2. Create new landing page
3. Choose blank template or HTML embed option
4. Paste HTML from `/assets/landing-page/pain-vision-ledger-landing-page.html`
5. Update form integration (connect to your email service provider)
6. Replace video placeholder with YouTube embed code
7. Update all links (PDF download, form action, footer links)
8. Set page URL slug: `/pain-vision-ledger` or `/free-assessment`

**Option B: Custom Hosting**
1. Upload HTML file to your web server
2. Update form action to point to your email service provider's endpoint
3. Update video embed code
4. Update PDF download link
5. Test all functionality

**Form Integration**:
- Connect form to email service provider (ConvertKit, ActiveCampaign, etc.)
- Field 1: Email (required)
- Field 2: First Name (required)
- Form action: Your ESP's form submission endpoint
- Confirmation: Redirect to thank-you page OR show success message

**Deliverable**: Live landing page URL

**QA Checklist**:
☐ Page loads correctly on desktop
☐ Page loads correctly on mobile (responsive)
☐ All sections display properly
☐ Form submits successfully (test with real email)
☐ Form connects to email list
☐ Video embeds and plays correctly
☐ All CTA buttons link to form section
☐ Smooth scrolling works (anchor links)
☐ All copy is correct (no typos)
☐ Brand colors display correctly
☐ Footer links work (privacy, unsubscribe placeholders)

---

### Step 2.2: Create Thank-You Page (Optional)

**Timeline**: 15-30 minutes

**Instructions**:
1. Create simple thank-you page
2. Include:
   - "Success! Check your email"
   - Download link to PDF (backup)
   - Link to video (backup)
   - What to expect next (3-day email sequence)
3. Set up redirect from form submission to thank-you page

**Deliverable**: Thank-you page URL

---

## PHASE 3: EMAIL SEQUENCE SETUP (1-2 hours)

### Step 3.1: Configure Email Service Provider

**Timeline**: 1-1.5 hours

**Instructions**:

**Create Email List/Segment**:
1. Create new list or tag: "Pain-Vision-Ledger-Subscribers"
2. Add custom fields: First Name, Email
3. Set up automation trigger: Form submission from landing page

**Email 1: Welcome & Results Delivery** (Immediate)
1. Create new email in automation
2. Copy content from `/assets/emails/email-01-welcome-results-delivery.md`
3. Add personalization: `[FirstName]` merge tag
4. Insert links:
   - PDF download link (from hosting)
   - Video link (YouTube)
5. Set up footer (unsubscribe link, required by law)
6. Subject line: Choose from options in file
7. Timing: Send immediately (0 minutes delay)

**Email 2: Framework Teaching** (24 hours later)
1. Create second email in sequence
2. Copy content from `/assets/emails/email-02-framework-teaching.md`
3. Add personalization: `[FirstName]`
4. Subject line: "Why This Simple Exercise Changes Everything"
5. Timing: Send 24 hours after Email 1

**Email 3: Social Proof & IGNITE Bridge** (48 hours after Email 1)
1. Create third email in sequence
2. Copy content from `/assets/emails/email-03-social-proof-ignite-bridge.md`
3. Add personalization: `[FirstName]`
4. Add CTA button: Link to Calendly or booking system
5. Subject line: "What Happened When James Did This Exercise"
6. Timing: Send 48 hours after Email 1 (24 hours after Email 2)

**Deliverable**: 3-email automation sequence (live)

**QA Checklist**:
☐ All emails created in sequence
☐ Personalization tags work ([FirstName])
☐ All links work (PDF, video, booking)
☐ Subject lines are compelling
☐ Line breaks preserved (formatting correct)
☐ Unsubscribe link included in all emails
☐ Mobile preview looks good
☐ Desktop preview looks good
☐ Test email sent to yourself
☐ Timing is correct (0 hrs, 24 hrs, 48 hrs)
☐ Automation is activated (live)

---

### Step 3.2: Set Up Strategy Call Booking

**Timeline**: 15 minutes

**Instructions**:
1. Create Calendly event (or use existing booking system)
2. Event name: "IGNITE Strategy Call"
3. Duration: 20 minutes
4. Description: "Review your Pain & Vision Ledger results and determine if IGNITE is right for you"
5. Questions to ask:
   - "Have you completed the Pain & Vision Ledger?"
   - "What's your biggest stuck pattern right now?"
6. Copy booking link
7. Update Email 3 CTA button with link

**Deliverable**: Calendly link (or booking link)

---

## PHASE 4: FACEBOOK ADS SETUP (1-2 hours)

### Step 4.1: Create Ad Visuals in Canva

**Timeline**: 1 hour

**Instructions**:

**Ad Image 1: Problem Recognition**
1. Create 1200 x 628 pixel design in Canva
2. Follow specs in `/assets/ads/facebook-ad-variation-01-problem-recognition.md`
3. Design split image (stuck vs clarity)
4. Add text overlay: "SEE YOUR COST"
5. Export as PNG or JPG (high quality)

**Ad Image 2: Curiosity + Specificity**
1. Create 1200 x 628 pixel design
2. Follow specs in `/assets/ads/facebook-ad-variation-02-curiosity-specificity.md`
3. Design cost calculator theme
4. Export as PNG or JPG

**Ad Image 3: Social Proof + Aspiration**
1. Create 1200 x 628 pixel design
2. Follow specs in `/assets/ads/facebook-ad-variation-03-social-proof-aspiration.md`
3. Include testimonial + stats
4. Export as PNG or JPG

**Deliverables**: 3 ad images

**QA Checklist**:
☐ All images 1200 x 628 pixels
☐ Text under 20% of image (Facebook guideline)
☐ Brand colors used correctly
☐ Images are high quality (not pixelated)
☐ Text is readable on mobile
☐ Images exported and saved

---

### Step 4.2: Create Facebook Ads in Ads Manager

**Timeline**: 45 minutes - 1 hour

**Instructions**:

**Campaign Setup**:
1. Log in to Facebook Ads Manager
2. Create new campaign
3. Objective: Lead Generation
4. Campaign name: `IGNITE-LM01-PainVisionLedger-Testing`
5. Budget optimization: Off (testing individual ad sets)

**Ad Set 1: Problem Recognition**
1. Create new ad set
2. Name: `US-CA-UK-AU_Age25-55_CareerDev_V1`
3. Follow targeting specs from variation 1 file
4. Budget: $50-100/day (testing)
5. Schedule: Continuous
6. Placements: Automatic (or manual as specified)

**Ad 1 Creative**:
1. Create new ad
2. Name: `ProblemRecognition-Image01-GetFramework`
3. Upload Ad Image 1
4. Headline: Copy from variation 1 file (60 chars max)
5. Primary text: Copy from variation 1 file (125 chars max)
6. CTA button: "Learn More" with text "Get the Framework"
7. Destination: Landing page URL

**Repeat for Ad Sets 2 & 3**:
- Follow same process for variations 2 and 3
- Use respective targeting, copy, and images
- Adjust budgets as specified

**Deliverable**: 3 active Facebook ad variations

**QA Checklist**:
☐ All 3 ad sets created
☐ Targeting is correct for each
☐ Budgets set correctly ($50-100/day testing)
☐ All ad copy matches specifications
☐ Headlines under 60 characters
☐ Primary text under 125 characters
☐ All images uploaded correctly
☐ CTA buttons configured
☐ Landing page URLs correct
☐ Exclusions added (current members)
☐ Ads submitted for review
☐ Payment method confirmed

---

## PHASE 5: PRE-LAUNCH TESTING (1 hour)

### Step 5.1: End-to-End Funnel Test

**Timeline**: 30 minutes

**Instructions**:
1. Visit landing page (desktop)
2. Submit form with test email
3. Verify:
   - Email 1 arrives immediately
   - PDF download link works
   - Video link works
   - Email formatting looks good
4. Wait 24 hours, verify Email 2 arrives
5. Wait another 24 hours, verify Email 3 arrives
6. Test all links in all emails
7. Test booking link in Email 3

**Mobile Testing**:
1. Visit landing page on mobile device
2. Submit form (different test email)
3. Verify mobile experience is good
4. Check emails on mobile device

**Deliverable**: Completed test with notes

**QA Checklist**:
☐ Landing page loads on desktop
☐ Landing page loads on mobile
☐ Form submits successfully
☐ Email 1 arrives immediately
☐ Email 2 arrives 24 hours later
☐ Email 3 arrives 48 hours later
☐ All links in emails work
☐ PDF downloads correctly
☐ Video plays correctly
☐ Booking link works
☐ Emails look good on desktop
☐ Emails look good on mobile
☐ No broken links anywhere
☐ No typos or errors found

---

### Step 5.2: Facebook Ads Preview & Testing

**Timeline**: 15 minutes

**Instructions**:
1. Use Facebook's "Preview" feature in Ads Manager
2. Preview all 3 ads on:
   - Mobile feed
   - Desktop feed
   - Instagram (if using)
3. Verify images display correctly
4. Verify copy is readable
5. Click "See Preview" and test click-through to landing page

**QA Checklist**:
☐ All ads display correctly in preview
☐ Images are not pixelated
☐ Text is readable on mobile
☐ CTA buttons are visible
☐ Click-through goes to correct landing page
☐ No errors or issues in preview

---

## PHASE 6: LAUNCH (30 minutes)

### Step 6.1: Activate All Systems

**Timeline**: 15 minutes

**Launch Checklist**:
☐ Landing page is live (public URL)
☐ Email automation is activated
☐ PDF is hosted and accessible
☐ Video is uploaded and public/unlisted
☐ Facebook ads are approved and running
☐ All links tested one final time
☐ Analytics tracking set up (Google Analytics, Facebook Pixel, etc.)

**Go-Live Steps**:
1. Final check of all systems
2. Activate Facebook ads (if paused)
3. Share landing page URL (optional: announce to existing audience)
4. Monitor first 24 hours closely

---

### Step 6.2: Monitor Initial Performance

**Timeline**: Ongoing (first 3-5 days critical)

**What to Monitor**:

**Landing Page**:
- Visitors (traffic)
- Opt-in rate (target: 28-35%)
- Bounce rate (should be low)

**Email Sequence**:
- Open rates (target: 35-40%)
- Click-through rates (target: 8-12%)
- Unsubscribe rate (should be low, <1%)

**Facebook Ads**:
- CTR (target: 2.5-4.5% depending on variation)
- CPC (target: $0.50-$1.00)
- CPL (target: $2.00-$5.00)
- Frequency (keep under 2-3 in first week)

**Strategy Call Bookings**:
- Applications from Email 3 (target: 25-30%)
- Show-up rate (target: 60-70%)

**Deliverable**: Daily performance reports (first week)

---

## PHASE 7: OPTIMIZATION (Week 2+)

### Step 7.1: Analyze Performance & Optimize

**Timeline**: Ongoing

**Optimization Triggers**:

**Landing Page**:
- If opt-in rate < 20%: Change headline, simplify copy, or reduce form friction
- If bounce rate > 60%: Improve page load speed, check mobile experience

**Email Sequence**:
- If open rate < 30%: Test new subject lines
- If click rate < 5%: Improve CTAs, add more value in emails

**Facebook Ads**:
- If CTR < 2%: Test new ad copy or images
- If CPL > $5: Narrow targeting, test different audiences, or pause underperforming ads
- If frequency > 3: Expand audience size or create new creative

**Strategy Call Conversion**:
- If application rate < 20%: Strengthen Email 3 social proof, add urgency
- If show-up rate < 50%: Send reminder emails, improve booking confirmation

---

### Step 7.2: Scaling Strategy

**Timeline**: After 5-7 days of good performance

**When to Scale**:
- CPL consistently under $4
- CTR consistently above 2.5%
- Opt-in rate consistently above 25%
- Email engagement healthy (35%+ opens)

**How to Scale**:
1. Identify best-performing ad variation
2. Increase budget by 20-30% every 3 days
3. Create new creative variations (new images, copy)
4. Expand to new audiences (lookalikes, interest stacking)
5. Test new countries (Canada, UK, Australia)
6. Consider retargeting (people who visited but didn't opt in)

**Deliverable**: Scaling plan based on performance data

---

## QUALITY ASSURANCE: MASTER CHECKLIST

### LANDING PAGE
☐ Headline is specific and compelling
☐ Uses Toby Potter voice (direct, no fluff)
☐ Specific benefits included (not vague)
☐ Form has only 2 fields (email, first name)
☐ Email field comes first
☐ CTA button is fire gradient color
☐ Mobile responsive (tested)
☐ All brand colors used correctly (#121212, #C84A00, #FF6A00)
☐ Testimonials are specific and credible
☐ Copy flows logically (problem → insight → solution → CTA)
☐ Video embed code works
☐ Loading speed optimized (under 3 seconds)
☐ All internal links work (anchor links to form)
☐ Footer links included (privacy, unsubscribe)
☐ Analytics tracking installed

### EMAILS
☐ Subject lines are compelling and personalized
☐ Body uses short paragraphs (8-12 words per sentence)
☐ Every sentence drives action or emotion
☐ CTAs are clear and specific
☐ [FirstName] personalization included
☐ Professional formatting (line breaks preserved)
☐ Unsubscribe link in footer (all emails)
☐ Reply-to email is correct
☐ Tested on mobile and desktop email clients
☐ All links work (PDF, video, booking)
☐ Email 1 sends immediately
☐ Email 2 sends 24 hours later
☐ Email 3 sends 48 hours later (72 hours after opt-in)

### FACEBOOK ADS
☐ Headlines under 60 characters (all variations)
☐ Body copy under 125 characters (all variations)
☐ Each variation has different angle/hook
☐ Image specs: 1200 x 628 pixels
☐ Images follow detailed Canva specifications
☐ Text under 20% of image
☐ CTAs are action-oriented
☐ Targeting is specific for each variation
☐ Exclusions added (current IGNITE members)
☐ Budget set correctly ($50-100/day testing)
☐ Ads approved by Facebook

### VIDEO SCRIPT
☐ Uses Toby Potter voice (direct, conversational, authoritative)
☐ Timing is 4:45 - 5:15 (approximately 625 words)
☐ Includes specific examples (not abstract)
☐ Emotional beats are clear (hook, problem, mechanism, vision, proof, CTA)
☐ Transitions between sections are natural
☐ CTA is clear and specific
☐ Visual notes detailed for editor
☐ Video recorded professionally
☐ Audio is clear (no background noise)
☐ Lighting is professional
☐ Edited with template images shown
☐ End screen includes CTA and link
☐ Uploaded to YouTube
☐ Thumbnail created and uploaded
☐ Description and tags added

### PDF TEMPLATE
☐ Layout is clean and uncluttered
☐ Instructions are clear and concise
☐ Writing lines large enough for handwriting
☐ Branding is consistent (IGNITE logo, colors)
☐ Print-ready quality (300 DPI)
☐ File size under 5MB
☐ Both pages included (Ledger + Tracker)
☐ QR code works (tested)
☐ Black & white print test passed
☐ Hosted and download link works

### OVERALL QUALITY
☐ All assets use same brand colors consistently
☐ All copy uses Toby Potter voice consistently
☐ All target audience segments clear
☐ All CTAs align (no conflicting messaging)
☐ All mention IGNITE as next step
☐ All are production-ready (no placeholders)
☐ All include implementation notes

---

## SUCCESS METRICS: 30-DAY TARGETS

Based on research benchmarks:

**Landing Page**:
- **Traffic**: 500-1,000 visitors (from ads)
- **Opt-in rate**: 28-35%
- **Total leads**: 150-250

**Email Sequence**:
- **Open rate**: 35-40% (Email 1), 30-35% (Emails 2-3)
- **Click-through rate**: 8-12%
- **Applications**: 25-30% of leads (38-75 applications)

**Facebook Ads**:
- **CTR**: 2.5-4.5% (depending on variation)
- **CPC**: $0.50-$1.00
- **CPL**: $2.00-$5.00
- **Ad spend**: $1,500-$3,000 (at $50-100/day)

**Strategy Calls**:
- **Booking rate**: 25-30% (from Email 3)
- **Show-up rate**: 60-70%
- **Close rate**: 40-50%

**IGNITE Enrollment**:
- **Total enrollments**: 15-38 (from 38-75 applications)
- **First month revenue**: $1,485-$3,762 (at $99/month)
- **Recurring monthly**: $1,485-$3,762/month ongoing

---

## TROUBLESHOOTING GUIDE

### Issue: Low landing page opt-in rate (<20%)

**Possible Causes**:
- Headline not compelling enough
- Too much copy (overwhelming)
- Form friction (too many fields)
- Page load speed slow
- Mobile experience poor

**Solutions**:
- A/B test new headlines (use research pain points)
- Simplify copy (shorter paragraphs)
- Remove unnecessary form fields (keep only email + name)
- Optimize images (compress)
- Test on multiple mobile devices

---

### Issue: Low email open rates (<25%)

**Possible Causes**:
- Subject lines not compelling
- Sending at wrong time
- Email landing in spam
- No personalization

**Solutions**:
- Test new subject lines (add [FirstName], create curiosity)
- Change send time (9-10 AM local time often best)
- Check spam score, improve sender reputation
- Add personalization tokens

---

### Issue: High Facebook CPL (>$5)

**Possible Causes**:
- Targeting too broad
- Ad creative not resonating
- Landing page poor experience
- Audience saturated (high frequency)

**Solutions**:
- Narrow targeting (age, interests)
- Test new ad images and copy
- Improve landing page opt-in rate
- Expand audience size or create new campaigns

---

### Issue: Low strategy call bookings (<20%)

**Possible Causes**:
- Email 3 not compelling enough
- CTA not clear
- No urgency
- Poor social proof

**Solutions**:
- Strengthen social proof in Email 3
- Add urgency (limited spots, deadline)
- Make CTA more prominent (button vs link)
- Add testimonial video

---

## NEXT STEPS AFTER LAUNCH

**Week 1**:
- Monitor daily metrics closely
- Fix any issues immediately
- Gather initial feedback from leads

**Week 2-3**:
- Analyze performance data
- Implement optimizations
- Begin scaling best-performing ads

**Week 4**:
- Review 30-day metrics against targets
- Calculate ROI and CAC (customer acquisition cost)
- Plan for ongoing campaigns

**Month 2+**:
- Scale successful campaigns
- Create additional creative variations
- Test new audiences and markets
- Optimize conversion rates throughout funnel

---

## SUPPORT & RESOURCES

**Asset Locations**:
- Research Brief: `/docs/RESEARCH-SYNTHESIS-BRIEF.md`
- Landing Page: `/assets/landing-page/pain-vision-ledger-landing-page.html`
- Emails: `/assets/emails/email-01.md`, `email-02.md`, `email-03.md`
- Ads: `/assets/ads/facebook-ad-variation-01.md`, `02.md`, `03.md`
- Video: `/assets/video/pain-vision-ledger-video-script.md`
- PDF: `/assets/pdf/pain-vision-ledger-pdf-template-specs.md`

**External Tools**:
- Canva Pro: https://www.canva.com
- Leadpages: https://www.leadpages.com
- ConvertKit: https://convertkit.com
- Calendly: https://calendly.com
- Facebook Ads Manager: https://business.facebook.com/adsmanager
- Google Analytics: https://analytics.google.com

---

END OF IMPLEMENTATION GUIDE
