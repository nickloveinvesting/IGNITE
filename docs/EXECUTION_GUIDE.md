# Execution Guide: Running All 10 Lead Magnet Prompts

Step-by-step instructions for generating all 10 lead magnet artifacts using Claude AI.

---

## Prerequisites

Before you begin, ensure you have:

- [x] Claude AI access (Claude Pro recommended for parallel execution)
- [x] Read `/docs/BRAND_GUIDELINES.md`
- [x] Repository cloned locally
- [x] `/artifacts` folder structure created
- [x] 2-4 hours available (parallel) or full day (sequential)

---

## Execution Option 1: Parallel (Recommended)

**Time Required:** ~45 minutes
**Advantages:** 10x faster, complete all magnets in one session
**Requirements:** Claude Pro or 10 separate Claude sessions (free tier)

### Step 1: Prepare Your Workspace

1. Open 10 browser windows/tabs
2. Navigate to [claude.ai](https://claude.ai) in each
3. Create new conversation in each tab
4. Label browser tabs for easy tracking:
   - Tab 1: "Magnet 01 - Pain & Vision"
   - Tab 2: "Magnet 02 - Archetype Quiz"
   - Tab 3: "Magnet 03 - No-Excuses"
   - [Continue for all 10]

### Step 2: Copy All Prompts

Navigate to `/prompts/` folder in your local repository.

For each magnet:
1. Open the markdown file
2. Select all content (Ctrl+A / Cmd+A)
3. Copy to clipboard
4. Keep file open for reference

### Step 3: Paste and Execute Simultaneously

**Timing matters for parallel execution:**

1. **Tab 1:** Paste `/prompts/01-PAIN-VISION-LEDGER.md` → Hit Enter
2. **Tab 2:** Paste `/prompts/02-ARCHETYPE-QUIZ.md` → Hit Enter
3. **Tab 3:** Paste `/prompts/03-NO-EXCUSES-MANDATE.md` → Hit Enter
4. [Continue for all 10 tabs]
5. **Complete all pastes within 2-3 minutes**

### Step 4: Monitor Generation Progress

**Expected generation time per magnet:** 4-8 minutes

**Monitor for:**
- ✅ All 6 artifacts generated
- ❌ Incomplete outputs
- ❌ Error messages
- ❌ Timeout warnings

**Active monitoring cycle:**
1. Check Tab 1 → Tab 2 → Tab 3 → ... → Tab 10 (30 seconds)
2. Repeat until all complete
3. Download completed artifacts immediately

### Step 5: Download and Organize Artifacts

As each conversation completes:

1. **Scroll through entire conversation** to identify all artifacts
2. **Copy each artifact** to separate file:
   - landing-page.html
   - email-sequences.md
   - facebook-ads.md
   - video-script.md
   - pdf-template-specs.md
   - implementation-notes.md

3. **Save to correct folder:**
   ```
   /artifacts/magnet-[number]-[name]/[artifact-filename]
   ```

4. **Verify completeness** before moving to next tab

### Step 6: Quality Check

For each magnet, verify:

- [ ] All 6 artifacts present and complete
- [ ] Brand colors referenced (#FF4D00, #2C3539, #FFFFFF)
- [ ] Inter font specified
- [ ] Toby Potter voice evident in copy
- [ ] No incomplete sections or truncated content
- [ ] CTAs are clear and action-oriented

**If any artifact is incomplete:**
1. Reply in that conversation: "Please complete the [artifact name] section"
2. Wait for completion
3. Download updated version

---

## Execution Option 2: Sequential

**Time Required:** ~4-5 hours
**Advantages:** Easier to track, allows for review between magnets
**Requirements:** Single Claude session

### Step 1: Prepare Single Session

1. Open [claude.ai](https://claude.ai)
2. Create new conversation
3. Title: "IGNITE Lead Magnets - Sequential Generation"
4. Keep `/artifacts` folder open in file explorer

### Step 2: Execute Magnet #1

1. Open `/prompts/01-PAIN-VISION-LEDGER.md`
2. Copy entire prompt
3. Paste into Claude conversation
4. Hit Enter
5. **Wait for complete generation** (~4-8 minutes)

### Step 3: Download and Organize

1. Scroll through conversation
2. Identify all 6 artifacts
3. Copy each to separate file
4. Save to `/artifacts/magnet-01-pain-vision-ledger/`

### Step 4: Quality Check Before Continuing

**Do not proceed to Magnet #2 until:**
- [ ] All 6 artifacts downloaded
- [ ] Files saved in correct folder
- [ ] Brand alignment verified
- [ ] No incomplete sections

### Step 5: Repeat for Magnets #2-10

**For each magnet:**
1. Clear previous conversation or start new conversation
2. Open next prompt file
3. Copy and paste
4. Generate artifacts
5. Download and organize
6. Quality check
7. Move to next magnet

**Recommended breaks:**
- After Magnet #3 (15-minute break)
- After Magnet #6 (30-minute break)
- After Magnet #9 (15-minute break)

### Step 6: Final Comprehensive Review

After all 10 magnets generated:

1. **Folder structure check:**
   ```bash
   ls artifacts/
   # Should show 10 magnet folders
   ```

2. **File count verification:**
   ```bash
   find artifacts -name "*.html" | wc -l
   # Should output: 10

   find artifacts -name "*.md" | wc -l
   # Should output: 50 (5 markdown files × 10 magnets)
   ```

3. **Visual spot-check:**
   - Open 2-3 landing pages in browser
   - Review 2-3 email sequences for voice consistency
   - Check 2-3 ads for fire orange usage

---

## Troubleshooting

### Issue: Prompt generates incomplete artifacts

**Symptoms:**
- Missing artifact(s)
- Truncated content mid-sentence
- "I apologize, let me complete that..." messages

**Solutions:**
1. **Reply immediately:** "Please complete the [missing artifact name]"
2. **If still incomplete:** "Please regenerate complete [artifact name] from scratch"
3. **If repeated issues:** Start new conversation with just that specific magnet prompt

**Prevention:**
- Use parallel execution (reduces timeout risk)
- Ensure stable internet connection
- Close unnecessary browser tabs

---

### Issue: Brand elements not matching guidelines

**Symptoms:**
- Wrong colors referenced
- Different font suggested
- Voice doesn't match Toby Potter style

**Solutions:**
1. **Minor fixes:** Edit artifacts manually using brand guidelines
2. **Major misalignment:** Reply: "Regenerate [artifact] using exact IGNITE brand: Fire #FF4D00, Charcoal #2C3539, Inter font, direct Toby Potter voice"
3. **Systematic issues:** Check if prompt file has correct brand variables

---

### Issue: Artifacts too generic or not IGNITE-specific

**Symptoms:**
- Generic coaching language
- No reference to IGNITE program
- Weak connection to target audience

**Solutions:**
1. **Reply with specifics:** "Make this more specific to IGNITE ($99/month program for W2/1099/entrepreneurs breaking free from limiting beliefs)"
2. **Add context:** "Use language that speaks to [specific target audience from magnet]"
3. **Emphasize transformation:** "Emphasize the transformation from [current pain] to [desired outcome]"

---

### Issue: Landing page HTML doesn't render correctly

**Symptoms:**
- Broken layout when opened in browser
- Missing styles
- Non-responsive mobile view

**Solutions:**
1. **Check for complete HTML:** Ensure `<!DOCTYPE html>` at start and `</html>` at end
2. **Validate HTML:** Use [validator.w3.org](https://validator.w3.org/)
3. **Request revision:** "Please provide complete, valid HTML5 with inline CSS, mobile-responsive"

---

### Issue: Quiz logic unclear in Typeform

**Symptoms:**
- Can't map questions to Typeform
- Logic jumps not defined
- Result paths ambiguous

**Solutions:**
1. **Request clarification:** "Please provide explicit logic map: Question 1 → if A then Question 3, if B then Question 2"
2. **Ask for Typeform specs:** "Format quiz structure specifically for Typeform implementation with exact logic jumps"
3. **Simplify:** "Reduce quiz to 7 questions with 3 clear result categories"

---

## Quality Assurance Checklist

Before marking generation complete, verify each magnet:

### Brand Alignment
- [ ] Fire Orange (#FF4D00) referenced for CTAs
- [ ] Charcoal (#2C3539) for body text
- [ ] Inter font specified
- [ ] Toby Potter voice evident (direct, authoritative, action-oriented)
- [ ] No corporate jargon or hedging language

### Completeness
- [ ] Landing page HTML complete and valid
- [ ] Email sequence includes 5-7 emails
- [ ] Facebook ads include 3-5 variations
- [ ] Video script includes intro, body, CTA
- [ ] PDF specs include layout, content sections, design notes
- [ ] Implementation notes cover technical setup

### Audience Alignment
- [ ] Language speaks to target audience (W2/1099/entrepreneur)
- [ ] Pain points accurately addressed
- [ ] Solution tied to IGNITE program
- [ ] Transformation promise clear
- [ ] Urgency appropriate for audience segment

### Technical Functionality
- [ ] HTML opens in browser without errors
- [ ] Links are placeholder-ready (easy to swap in real URLs)
- [ ] Email formatting includes subject lines
- [ ] Ad copy fits Facebook character limits
- [ ] PDF specs include dimensions and file requirements

### Conversion Optimization
- [ ] Headlines are compelling (not generic)
- [ ] CTAs are clear and action-oriented
- [ ] Value proposition stated within first 3 sentences
- [ ] Social proof or credibility elements included
- [ ] Friction-reducing elements present (free, instant, no credit card)

---

## Post-Generation Next Steps

Once all 10 magnets generated and quality-checked:

1. **Commit to Repository:**
   ```bash
   git add artifacts/
   git commit -m "Add generated artifacts for all 10 lead magnets"
   git push
   ```

2. **Review Implementation Priority:**
   - Read `/implementation/WEEK-1-SETUP.md`
   - Decide which 2 magnets to implement first
   - Assign team members to implementation tasks

3. **Begin Implementation:**
   - Set up Leadpages account
   - Configure email marketing platform
   - Prepare Facebook Ads Manager
   - Schedule design work for PDFs

4. **Track Progress:**
   - Update `/team/STATUS-TRACKING.md`
   - Log completion of generation phase
   - Set implementation deadlines

---

## Estimated Timeline

### Parallel Execution

| Phase | Time | Activity |
|-------|------|----------|
| Setup | 10 min | Open 10 tabs, prep workspace |
| Paste | 5 min | Copy/paste all prompts |
| Generation | 25-35 min | Wait for AI generation |
| Download | 30-45 min | Download and organize artifacts |
| QA | 15-20 min | Quality check all magnets |
| **Total** | **85-115 min** | **~1.5-2 hours** |

### Sequential Execution

| Phase | Time per Magnet | Total (10 magnets) |
|-------|-----------------|---------------------|
| Copy/Paste | 2 min | 20 min |
| Generation | 6 min | 60 min |
| Download | 5 min | 50 min |
| Organize | 3 min | 30 min |
| QA | 3 min | 30 min |
| **Total** | **19 min** | **190 min (~3.2 hours)** |

---

## Tips for Success

1. **Start with parallel execution** - It's dramatically faster and maintains momentum

2. **Download immediately** - Don't wait until all 10 are done to start downloading

3. **Use browser bookmarks** - Bookmark each tab for easy return if browser crashes

4. **Copy to text editor first** - Keep prompts in text editor as backup

5. **Take breaks in sequential** - Generation quality can suffer with fatigue

6. **Check brand alignment early** - Fix issues in Magnet #1 before generating #2-10

7. **Prepare folder structure first** - Have all 10 magnet folders created before starting

8. **Test one artifact** - Open first landing page in browser to ensure HTML is valid

9. **Document issues** - Note any recurring problems for future prompt improvements

10. **Celebrate completion** - You've just generated 500+ pages of marketing content in hours

---

**Ready to execute? Pick your approach and start generating. The faster you generate, the faster you launch. The faster you launch, the faster you grow.**
