# Contributing to IGNITE Lead Magnets Repository

Thank you for your interest in contributing to the IGNITE Lead Magnets repository. This document provides guidelines for contributing changes, improvements, and new lead magnet prompts.

## Table of Contents

1. [Code of Conduct](#code-of-conduct)
2. [How to Contribute](#how-to-contribute)
3. [Repository Structure Guidelines](#repository-structure-guidelines)
4. [Documentation Standards](#documentation-standards)
5. [Prompt Development Guidelines](#prompt-development-guidelines)
6. [Pull Request Process](#pull-request-process)
7. [Review Requirements](#review-requirements)
8. [Style Guide](#style-guide)

---

## Code of Conduct

### Our Standards

- **Professional**: Maintain professional communication at all times
- **Respectful**: Treat all contributors with respect
- **Collaborative**: Foster collaborative problem-solving
- **Quality-Focused**: Prioritize quality over speed
- **Brand-Aligned**: Ensure all contributions align with IGNITE brand guidelines

### Unacceptable Behavior

- Harassment or discriminatory language
- Publishing others' private information
- Trolling, insulting, or derogatory comments
- Other conduct that violates professional standards

---

## How to Contribute

### Types of Contributions

1. **Bug Reports**: Report issues with existing prompts or documentation
2. **Feature Requests**: Suggest new lead magnets or functionality
3. **Documentation Improvements**: Enhance clarity, fix typos, add examples
4. **New Prompts**: Create prompts for lead magnets #11-20+
5. **Template Enhancements**: Improve reusable templates
6. **Research Additions**: Add competitive analysis or case studies

### Before You Start

1. **Check Existing Issues**: Search for existing issues or pull requests
2. **Review Brand Guidelines**: Read `/docs/BRAND_GUIDELINES.md` thoroughly
3. **Understand Structure**: Familiarize yourself with repository organization
4. **Discuss Major Changes**: Open an issue to discuss significant changes before implementation

---

## Repository Structure Guidelines

### Folder Organization

All contributions must follow the established folder structure:

```
/docs          - Documentation files only
/prompts       - Lead magnet generation prompts
/artifacts     - Generated outputs (organized by magnet)
/templates     - Reusable templates
/research      - Research and analysis
/implementation- Implementation guides
/team          - Team collaboration documents
```

### Naming Conventions

**Prompts:**
- Format: `[number]-[NAME-IN-CAPS].md`
- Example: `11-GOAL-SETTING-FRAMEWORK.md`
- Must be sequential (11, 12, 13, etc.)

**Documentation:**
- Format: `[PURPOSE-DESCRIPTION].md`
- Example: `QUALITY-CHECKLIST.md`
- Use ALL CAPS for file names
- Use hyphens to separate words

**Artifacts:**
- Create new folder: `/artifacts/magnet-[number]-[name]/`
- Use lowercase with hyphens for folder names
- Example: `/artifacts/magnet-11-goal-setting-framework/`

**Templates:**
- Format: `[TYPE]-TEMPLATE.[extension]`
- Example: `PROMPT-TEMPLATE.md`
- Use ALL CAPS for "TEMPLATE"

---

## Documentation Standards

### Markdown Formatting

- Use ATX-style headers (`#` not underlines)
- Include table of contents for documents >500 words
- Use code blocks with language specification
- Use bullet points for lists (not numbered unless sequence matters)
- Bold key terms on first use
- Use horizontal rules (`---`) to separate major sections

### Writing Style

- **Voice**: Direct, action-oriented, no fluff (Toby Potter style)
- **Tone**: Professional but conversational
- **Tense**: Present tense for instructions
- **Person**: Second person ("you") for user-facing docs
- **Clarity**: Short sentences, clear language, no jargon

### Examples

**Good:**
```markdown
## Create Landing Page

1. Open Leadpages
2. Select "Drag & Drop Builder"
3. Import HTML from artifact
4. Customize headline and CTA
5. Publish to custom domain
```

**Bad:**
```markdown
## Creating Your Landing Page

One might want to consider opening Leadpages, where you will possibly find the Drag & Drop Builder option which could be utilized for importing your HTML...
```

---

## Prompt Development Guidelines

### Creating New Lead Magnet Prompts

When creating a new prompt (magnets #11-20+), follow this structure:

#### 1. Header Section
- Clear title
- Target audience definition
- Problem solved
- Expected deliverables

#### 2. Research Phase
- Competitive intelligence instructions
- Audience psychology research
- Platform optimization research

#### 3. Generation Instructions
- Landing page specifications
- Email sequence structure
- Facebook ad requirements
- Video script guidelines
- PDF/tool specifications

#### 4. Brand Guidelines Integration
- Reference IGNITE colors (#FF4D00, #2C3539, #FFFFFF)
- Specify Inter font usage
- Include Toby Potter voice examples
- Define tone for different contexts

#### 5. Quality Checklist
- Verification criteria
- Testing requirements
- Optimization guidelines

### Using the Template

Start with `/templates/PROMPT-TEMPLATE.md` and customize:

```markdown
# [MAGNET NAME]

**Magnet Number:** [11-20+]
**Target Audience:** [Specific segment]
**Problem Solved:** [Specific pain point]
**Format:** [PDF/Quiz/Tool/Challenge/etc.]

[Continue following template structure...]
```

### Testing Your Prompt

Before submitting:

1. **Run it through Claude**: Generate all 6 artifacts
2. **Verify completeness**: Check all required outputs are generated
3. **Check brand alignment**: Ensure colors, fonts, voice match guidelines
4. **Test artifacts**: Validate HTML, test quiz logic, review copy
5. **Document results**: Note any issues or improvements needed

---

## Pull Request Process

### Before Submitting

1. **Create Feature Branch**: Branch from `main` using naming convention
   - Format: `feature/[type]-[brief-description]`
   - Example: `feature/prompt-goal-setting-framework`

2. **Make Changes**: Follow all guidelines above

3. **Test Thoroughly**: Verify all changes work as expected

4. **Update Documentation**: Update README if adding new magnet

5. **Write Clear Commit Messages**:
   ```
   Add Goal Setting Framework prompt (Magnet #11)

   - Created complete prompt following template
   - Generated and tested all 6 artifacts
   - Updated main README with magnet overview
   - Added artifact folder structure
   ```

### Submitting Pull Request

1. **Title Format**: `[Type] Brief description`
   - Examples: `[Prompt] Add Goal Setting Framework`
   - Examples: `[Docs] Improve Brand Guidelines clarity`
   - Examples: `[Fix] Correct typo in Week 1 Setup guide`

2. **Description Template**:
   ```markdown
   ## Summary
   Brief description of changes

   ## Type of Change
   - [ ] New prompt
   - [ ] Documentation update
   - [ ] Bug fix
   - [ ] Template enhancement
   - [ ] Research addition

   ## Changes Made
   - Bullet point list of specific changes

   ## Testing Performed
   - How you verified the changes work

   ## Brand Alignment
   - How changes align with IGNITE brand

   ## Related Issues
   - Link to related issues (if any)
   ```

3. **Request Review**: Tag appropriate reviewers

---

## Review Requirements

### Review Criteria

All pull requests will be reviewed for:

1. **Brand Alignment**
   - Colors match IGNITE palette
   - Typography follows Inter font specifications
   - Voice matches Toby Potter style
   - Tone appropriate for context

2. **Completeness**
   - All required artifacts generated
   - Documentation thorough
   - No missing sections

3. **Quality**
   - Clear, actionable copy
   - No grammatical errors
   - Proper markdown formatting
   - Links work correctly

4. **Structure**
   - Follows repository organization
   - Naming conventions correct
   - Files in appropriate folders

5. **Functionality**
   - Prompts generate expected outputs
   - Links and references valid
   - Instructions work as written

### Review Timeline

- **Initial Review**: Within 2 business days
- **Follow-up**: Within 1 business day after changes
- **Approval**: Within 1 business day after all requirements met

### Addressing Feedback

1. Review all comments thoroughly
2. Make requested changes
3. Respond to each comment indicating action taken
4. Request re-review when ready

---

## Style Guide

### Voice and Tone

**IGNITE Brand Voice: Toby Potter Style**

**Do:**
- Be direct and clear
- Use active voice
- Focus on action
- Challenge the reader
- Be authoritative

**Don't:**
- Use corporate jargon
- Hedge with "maybe", "possibly", "try"
- Be overly polite
- Use passive voice
- Beat around the bush

**Examples:**

❌ "You might want to consider creating a lead magnet..."
✅ "Create a lead magnet that solves a specific problem."

❌ "It could be beneficial to test your landing page..."
✅ "Test your landing page. Track conversions. Optimize what doesn't work."

❌ "We invite you to explore the possibilities..."
✅ "Pick a magnet. Execute it. Launch this week."

### Color Usage

**Primary: Fire Orange (#FF4D00)**
- CTAs, headlines, accent elements
- Use for urgency and action

**Secondary: Charcoal (#2C3539)**
- Body text, backgrounds, structure
- Use for authority and stability

**Tertiary: White (#FFFFFF)**
- Backgrounds, contrast, spacing
- Use for clarity and focus

### Typography

**Font:** Inter (Google Fonts)
**Weights:** 400 (Regular), 600 (Semi-Bold), 700 (Bold)

**Hierarchy:**
- H1: 48px, Bold (700)
- H2: 36px, Semi-Bold (600)
- H3: 24px, Semi-Bold (600)
- Body: 16px, Regular (400)
- CTA: 18px, Bold (700)

---

## Questions?

If you have questions about contributing:

1. **Check Documentation**: Review `/docs` folder first
2. **Open an Issue**: Ask questions in GitHub Issues
3. **Team Slack**: Post in #ignite-lead-magnets channel
4. **Email**: contact@ignite-program.com (for private inquiries)

---

## License

By contributing to this repository, you agree that your contributions will be subject to the proprietary license governing this repository. All intellectual property rights belong to IGNITE.

---

**Thank you for contributing to IGNITE's growth!**
