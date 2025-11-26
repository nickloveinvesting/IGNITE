# Viral Social Media Content Generator Prompt
## 100 Posts with Visual Specifications & Captions for IGNITE

**Use this prompt to start a new Claude conversation**

---

## Instructions
Copy everything below the line and paste into a new Claude conversation. This will generate 100 complete social media posts with detailed visual specifications in JSON format (compatible with Gemini/image generators).

---

# PROMPT START

You are an elite social media content strategist and visual designer. Your task is to create **100 viral social media posts** for IGNITE, a personal transformation program. Each post must include detailed visual specifications in JSON format that can be used with AI image generators (Gemini, Midjourney, DALL-E, etc.).

## Your Mission

Create 100 complete social media posts with:
1. **Platform-specific formatting** (Instagram, LinkedIn, Facebook, TikTok, Twitter/X)
2. **Detailed visual JSON specifications** for AI image generation
3. **Scroll-stopping captions** with hooks, value, and CTAs
4. **Hashtag strategies** optimized for discovery
5. **Posting recommendations** (best times, frequency)

---

## STEP 1: Read the Research Files

First, read these files to understand viral content patterns and IGNITE positioning:

**Social Media Research (Required Reading):**
```
/home/user/IGNITE/social_media_research_output/analysis/comparative_analysis.md
/home/user/IGNITE/social_media_research_output/final_reports/Executive_Summary.md
/home/user/IGNITE/social_media_research_output/analysis/individual_summaries/alex_hormozi_analysis.md
/home/user/IGNITE/social_media_research_output/analysis/individual_summaries/andy_elliott_analysis.md
/home/user/IGNITE/social_media_research_output/analysis/individual_summaries/tony_robbins_analysis.md
/home/user/IGNITE/social_media_research_output/analysis/individual_summaries/brendan_burchard_analysis.md
/home/user/IGNITE/social_media_research_output/analysis/individual_summaries/russell_brunson_analysis.md
```

**IGNITE Program (Required Reading):**
```
/home/user/IGNITE/README.md
/home/user/IGNITE/docs/BRAND_GUIDELINES.md
/home/user/IGNITE/research/excuse-psychology-mandate-science-research.md
```

---

## STEP 2: Understand the Output Format

### For Each Post, Provide This Complete Structure:

```json
{
  "post_id": "POST_001",
  "post_type": "carousel|single_image|quote_graphic|infographic|meme|before_after|statistic|testimonial|behind_scenes|educational",
  "platform_primary": "instagram|linkedin|facebook|twitter|tiktok",
  "platform_secondary": ["list of other platforms this works on"],
  "content_category": "wake_up_call|story_based|framework|identity_shift|accountability|contrarian",
  "content_pillar": "limiting_beliefs|accountability|identity|discipline|purpose|transformation",

  "visual_specification": {
    "image_prompt": "Detailed prompt for AI image generation (Gemini/Midjourney/DALL-E compatible)",
    "style": "photorealistic|illustrated|3d_render|minimalist|bold_typography|cinematic|documentary",
    "color_palette": {
      "primary": "#hexcode",
      "secondary": "#hexcode",
      "accent": "#hexcode",
      "background": "#hexcode",
      "text": "#hexcode"
    },
    "composition": {
      "layout": "centered|rule_of_thirds|asymmetric|grid|split",
      "focal_point": "description of main focus",
      "negative_space": "minimal|moderate|heavy",
      "text_placement": "top|bottom|center|overlay|none"
    },
    "elements": {
      "main_subject": "detailed description",
      "background": "detailed description",
      "lighting": "natural|studio|dramatic|soft|high_contrast",
      "mood": "inspirational|confrontational|calm|energetic|serious|hopeful",
      "props_objects": ["list of any objects in image"],
      "human_elements": {
        "include_person": true|false,
        "demographic": "description if applicable",
        "expression": "description if applicable",
        "pose": "description if applicable"
      }
    },
    "text_overlay": {
      "headline": "Main text on image",
      "subheadline": "Secondary text if any",
      "font_style": "bold_sans|elegant_serif|handwritten|modern|impactful",
      "text_effects": "shadow|outline|gradient|none"
    },
    "dimensions": {
      "instagram_feed": "1080x1080",
      "instagram_story": "1080x1920",
      "linkedin": "1200x627",
      "facebook": "1200x630",
      "twitter": "1600x900"
    },
    "carousel_slides": [
      {
        "slide_number": 1,
        "content": "description",
        "text": "text on this slide"
      }
    ]
  },

  "caption": {
    "hook": "First line that stops the scroll (under 125 characters)",
    "body": "Main caption content with value and storytelling",
    "cta": "Call to action",
    "full_caption": "Complete caption as it should be posted"
  },

  "hashtags": {
    "primary": ["5-10 high-volume hashtags"],
    "secondary": ["5-10 medium-volume niche hashtags"],
    "branded": ["#IGNITE", "#IGNITEtransformation"],
    "full_hashtag_string": "All hashtags formatted for copy-paste"
  },

  "engagement_strategy": {
    "post_timing": "Best day and time to post",
    "engagement_prompt": "Question or prompt to drive comments",
    "reply_strategy": "How to respond to comments"
  },

  "viral_mechanics": {
    "shareability_score": "1-10",
    "save_score": "1-10",
    "comment_score": "1-10",
    "viral_potential": "1-10",
    "reasoning": "Why this will perform well"
  },

  "ignite_connection": "How this post connects to IGNITE program interest"
}
```

---

## STEP 3: Content Categories (Create Posts Across All)

### Category Distribution (100 Posts Total):

**1. Quote Graphics (20 posts)**
- Bold typography with powerful statements
- Minimalist backgrounds
- High shareability
- Examples: "Your excuses are more expensive than your goals"

**2. Carousel Educational Posts (20 posts)**
- 5-10 slide educational content
- Frameworks, steps, lists
- High save rate
- Examples: "5 Beliefs Keeping You Stuck (And How to Break Them)"

**3. Story/Testimonial Posts (15 posts)**
- Before/after transformations
- Personal stories
- Social proof
- Examples: "6 months ago, I couldn't get out of bed..."

**4. Confrontational/Wake-Up Call Posts (15 posts)**
- Challenging limiting beliefs
- Provocative hooks
- Debate-generating
- Examples: "Nobody's coming to save you. Read that again."

**5. Infographic/Data Posts (10 posts)**
- Statistics and research
- Visual data representation
- Educational value
- Examples: "92% of people abandon their goals by February"

**6. Behind-the-Scenes/Authentic Posts (10 posts)**
- Real moments
- Process reveals
- Humanizing content
- Examples: "What my morning routine actually looks like..."

**7. Meme/Relatable Humor Posts (10 posts)**
- Self-deprecating humor
- Relatable struggles
- High share potential
- Examples: "Me telling myself I'll start Monday... for the 47th time"

---

## STEP 4: Visual Style Guide for AI Image Generation

### IGNITE Brand Colors:
```json
{
  "brand_colors": {
    "primary_orange": "#FF6B35",
    "deep_navy": "#1A1A2E",
    "bright_white": "#FFFFFF",
    "accent_gold": "#FFB347",
    "muted_gray": "#6B7280",
    "success_green": "#10B981",
    "warning_red": "#EF4444"
  }
}
```

### Image Generation Prompt Templates:

**For Quote Graphics:**
```
"Minimalist [color] background with bold white typography. Clean, modern design with subtle gradient. Text reads: '[QUOTE]'. Professional, high-end feel. Instagram square format 1080x1080. No people, pure typography focus."
```

**For Lifestyle/Aspirational:**
```
"Cinematic photograph of [subject description]. Golden hour lighting, shallow depth of field. [Person description if applicable] in [setting]. Mood: [aspirational/determined/peaceful]. Shot on professional camera, 85mm lens. Color graded with warm tones."
```

**For Before/After:**
```
"Split image composition. Left side: [before description - darker, desaturated]. Right side: [after description - brighter, vibrant]. Clear visual contrast. Professional photography style. Clean dividing line in center."
```

**For Infographics:**
```
"Clean infographic design with [brand colors]. Data visualization showing [specific data]. Modern flat design style. Clear hierarchy. Professional business aesthetic. White background with colored accents."
```

---

## STEP 5: Caption Formulas

### Hook Formulas (First Line):
1. **Confrontational:** "Stop lying to yourself about [X]."
2. **Curiosity:** "The real reason you're not [achieving X]..."
3. **Number-based:** "I spent [X years/dollars] learning this one thing."
4. **Vulnerability:** "I wasn't going to post this, but..."
5. **Challenge:** "If you can't [do X], you're not ready for [Y]."
6. **Question:** "What if everything you believed about [X] was wrong?"
7. **Statement:** "Your [excuses/fears/doubts] are lying to you."
8. **Time-based:** "In 28 days, you won't recognize yourself."

### Body Structure:
```
[HOOK - Pattern interrupt, under 125 chars]

[PROBLEM AGITATION - 2-3 sentences on the pain point]

[VALUE/INSIGHT - The main teaching or revelation]

[STORY/EXAMPLE - Brief relatable example]

[TRANSFORMATION HINT - What's possible]

[CTA - Soft call to action]

[ENGAGEMENT PROMPT - Question to drive comments]
```

### CTA Options:
- "Save this for when you need it. ⬇️"
- "Tag someone who needs to hear this."
- "Drop a 🔥 if this hit different."
- "Comment 'READY' if you're done with excuses."
- "Follow @ignite for daily transformation."
- "Link in bio for the free [resource]."
- "Which one resonates most? Comment 1, 2, or 3."

---

## STEP 6: Platform-Specific Requirements

### Instagram:
- Feed: 1080x1080 (square) or 1080x1350 (portrait)
- Stories: 1080x1920
- Carousel: Up to 10 slides
- Caption limit: 2,200 characters
- Hashtags: 20-30 (mix in comments or caption)
- Best times: Tu/We/Th 11am-1pm, 7-9pm

### LinkedIn:
- Image: 1200x627
- Carousel (PDF): Up to 300 slides
- Caption: No limit (but 1,300 chars before "see more")
- Hashtags: 3-5 max
- Best times: Tu/We/Th 8-10am, 12pm
- Tone: More professional, business-focused

### Facebook:
- Image: 1200x630
- Caption: Longer form works well
- Best times: We/Th/Fr 1-4pm
- More personal storytelling

### Twitter/X:
- Image: 1600x900
- Caption: 280 characters
- Hashtags: 1-2 max
- Thread-friendly content

### TikTok (Static):
- Image: 1080x1920
- Text-heavy graphics work
- Controversial/confrontational performs well

---

## OUTPUT REQUIREMENTS

### Deliverable 1: Complete Post Database (JSON)

Create a JSON file with all 100 posts:

```json
{
  "metadata": {
    "total_posts": 100,
    "created_date": "2025-11-25",
    "brand": "IGNITE",
    "version": "1.0"
  },
  "posts": [
    { /* Post 1 full specification */ },
    { /* Post 2 full specification */ },
    /* ... all 100 posts ... */
  ]
}
```

### Deliverable 2: Quick Reference Table

| Post ID | Type | Platform | Category | Hook Preview | Viral Score |
|---------|------|----------|----------|--------------|-------------|
| POST_001 | Quote | Instagram | Wake Up | "Your excuses are..." | 9/10 |
| ... | ... | ... | ... | ... | ... |

### Deliverable 3: Content Calendar Suggestion

Organize the 100 posts into a 30-day posting schedule:
- Instagram: 2x/day
- LinkedIn: 1x/day
- Facebook: 1x/day
- Twitter: 3x/day

### Deliverable 4: Top 10 "Launch First" Posts

Identify the 10 highest-potential posts to publish immediately, with reasoning.

### Deliverable 5: Image Generation Prompt Bank

Compile all visual prompts in a copy-paste ready format for Gemini/Midjourney/DALL-E.

---

## EXAMPLE OUTPUT (Post #1)

```json
{
  "post_id": "POST_001",
  "post_type": "quote_graphic",
  "platform_primary": "instagram",
  "platform_secondary": ["linkedin", "facebook", "twitter"],
  "content_category": "wake_up_call",
  "content_pillar": "limiting_beliefs",

  "visual_specification": {
    "image_prompt": "Minimalist dark navy blue gradient background (#1A1A2E to #2D2D44). Bold white sans-serif typography centered. Text reads 'YOUR EXCUSES ARE MORE EXPENSIVE THAN YOUR GOALS'. Subtle orange accent line (#FF6B35) underneath text. Clean, modern, high-contrast design. Professional typography with strong visual hierarchy. No people, pure typography focus. Instagram square format 1080x1080px. Slight texture overlay for depth.",
    "style": "bold_typography",
    "color_palette": {
      "primary": "#1A1A2E",
      "secondary": "#2D2D44",
      "accent": "#FF6B35",
      "background": "gradient_navy",
      "text": "#FFFFFF"
    },
    "composition": {
      "layout": "centered",
      "focal_point": "typography",
      "negative_space": "heavy",
      "text_placement": "center"
    },
    "elements": {
      "main_subject": "Bold white text statement",
      "background": "Dark navy gradient with subtle texture",
      "lighting": "n/a - graphic design",
      "mood": "confrontational, powerful, direct",
      "props_objects": [],
      "human_elements": {
        "include_person": false
      }
    },
    "text_overlay": {
      "headline": "YOUR EXCUSES ARE MORE EXPENSIVE THAN YOUR GOALS",
      "subheadline": "",
      "font_style": "bold_sans",
      "text_effects": "none"
    },
    "dimensions": {
      "instagram_feed": "1080x1080",
      "instagram_story": "1080x1920",
      "linkedin": "1200x627",
      "facebook": "1200x630",
      "twitter": "1600x900"
    }
  },

  "caption": {
    "hook": "Your excuses are more expensive than your goals.",
    "body": "Every time you say 'I can't' or 'I'll start Monday' or 'I'm not ready'...\n\nYou're paying a price.\n\nNot in dollars. In years.\n\nYears of staying stuck. Years of wondering 'what if.' Years of watching others live the life you want.\n\nThe gym membership you're 'not ready' for? That excuse costs you your health.\n\nThe business you're 'too scared' to start? That excuse costs you your freedom.\n\nThe conversation you're 'avoiding'? That excuse costs you your relationships.\n\nAdd it all up.\n\nYour excuses aren't protecting you. They're robbing you.",
    "cta": "What's one excuse you're retiring TODAY? Drop it in the comments. 👇",
    "full_caption": "Your excuses are more expensive than your goals.\n\nEvery time you say 'I can't' or 'I'll start Monday' or 'I'm not ready'...\n\nYou're paying a price.\n\nNot in dollars. In years.\n\nYears of staying stuck. Years of wondering 'what if.' Years of watching others live the life you want.\n\nThe gym membership you're 'not ready' for? That excuse costs you your health.\n\nThe business you're 'too scared' to start? That excuse costs you your freedom.\n\nThe conversation you're 'avoiding'? That excuse costs you your relationships.\n\nAdd it all up.\n\nYour excuses aren't protecting you. They're robbing you.\n\n—\n\nWhat's one excuse you're retiring TODAY? Drop it in the comments. 👇\n\n#NoExcuses #MindsetShift #PersonalGrowth #Transformation #IGNITE"
  },

  "hashtags": {
    "primary": ["#motivation", "#mindset", "#success", "#goals", "#growth", "#entrepreneur", "#inspiration", "#selfdevelopment"],
    "secondary": ["#noexcuses", "#mindsetshift", "#personalgrowth", "#accountability", "#transformation", "#levelup"],
    "branded": ["#IGNITE", "#IGNITEtransformation"],
    "full_hashtag_string": "#motivation #mindset #success #goals #growth #entrepreneur #inspiration #selfdevelopment #noexcuses #mindsetshift #personalgrowth #accountability #transformation #levelup #IGNITE #IGNITEtransformation"
  },

  "engagement_strategy": {
    "post_timing": "Tuesday 11am EST or Thursday 7pm EST",
    "engagement_prompt": "What's one excuse you're retiring TODAY?",
    "reply_strategy": "Acknowledge their commitment, ask what they'll do instead"
  },

  "viral_mechanics": {
    "shareability_score": 9,
    "save_score": 8,
    "comment_score": 9,
    "viral_potential": 9,
    "reasoning": "Universal truth that triggers self-reflection. Shareable because people want others to see this. Comment-worthy because it asks for commitment. Based on Alex Hormozi and Andy Elliott confrontational patterns that consistently perform."
  },

  "ignite_connection": "Directly addresses the excuse-making pattern that IGNITE's No Excuses Mandate lead magnet targets. Creates awareness of the cost of inaction, priming audience for accountability-focused program."
}
```

---

## BEGIN GENERATION

1. **First:** Read all the research files listed above
2. **Then:** Generate all 100 posts following the exact JSON format
3. **Include:** Full visual specifications for each that can be copied directly into Gemini/Midjourney
4. **Ensure:** Distribution across all 7 content categories
5. **Deliver:** All 5 deliverables listed above

Start by confirming you've read the research files, then begin generating posts in batches of 10-20 at a time for manageability.

# PROMPT END
