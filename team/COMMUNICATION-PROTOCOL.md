# Communication Protocol

This document establishes how the team communicates, coordinates, and stays aligned on lead magnet development.

---

## Communication Channels & Usage

### 1. Slack

**Purpose:** Real-time communication, quick questions, daily updates
**Channels:**
- `#ignite-lead-magnets` - Main team channel
- `#ignite-daily-standup` - Daily status posts
- `#ignite-blockers` - Issues that need immediate attention
- `#ignite-wins` - Celebrate wins and successes

**Norms:**
- Response time: <2 hours during work hours
- Questions posted in relevant channel
- Use threads to keep conversations organized
- Major decisions documented (and posted to GitHub)

**Example Posts:**
```
#ignite-daily-standup
[Tuesday 9am] Magnet #11: Artifacts generated, QA started.
Landing page built. Email setup in progress. On track for Friday launch.
```

---

### 2. Email

**Purpose:** Formal communication, approval decisions, documentation
**Recipients:**
- Team-wide updates: ignite-team@company.com
- Individual coordination: person@company.com

**Norms:**
- Use email for formal decisions
- Always CC relevant stakeholders
- Include decision deadline in subject line
- Document outcomes in GitHub

**Email Format:**
```
Subject: [DECISION NEEDED] Magnet #12 Positioning (Deadline: Fri EOD)

To: Toby Potter
CC: Project Manager, Copywriter

Body:
Two positioning options for Magnet #12.
Recommend Option A based on market research.
Feedback needed by Friday EOD for Wednesday prompt writing.

[Details]
```

---

### 3. GitHub Issues & Pull Requests

**Purpose:** Documentation, tracking, permanent record
**Usage:**
- Feature requests: New magnet concepts
- Bug reports: Issues with artifacts or systems
- Pull requests: Code/documentation changes
- Discussions: Technical or strategic decisions

**Issue Format:**
```
Title: [Magnet #11] Fix landing page form styling

Description:
Landing page form doesn't work on mobile.
Tested on iPhone 12 and Samsung Galaxy S21.
Appears input field too narrow.

Steps to reproduce:
1. Visit landing page on mobile
2. Scroll to form
3. Try to click on name field

Expected: Field accepts input
Actual: Field unusable on mobile

Suggested fix: Use responsive design (100% width on mobile)

Assigned to: Landing Page Developer
Labels: bug, mobile, urgent
```

---

### 4. Weekly Team Sync

**Purpose:** Alignment, blockers, coordination
**Schedule:** Tuesdays 10:00am - 10:30am (30 minutes)
**Attendees:** All core team members
**Format:**
- 5 min: Quick wins from last week
- 10 min: Status updates (2 min per person)
- 10 min: Blockers & solutions
- 3 min: Next week priorities
- 2 min: Announcements

**Preparation:**
- Everyone should have update ready
- Flag blockers 24 hours in advance
- Review agenda before meeting

**Notes Template:**
```
IGNITE Lead Magnets Weekly Sync
Date: Tuesday, Nov 12, 2025
Attendees: Toby, PM, Developer, Copywriter, Email Manager, Ads Manager

WINS:
- Magnet #10 hit 3.8% landing page conversion (vs 3% target) ✅
- Email sequence testing showed 45% open rate ✅

STATUS UPDATES:
1. Prompt Engineer: Magnet #12 prompt 80% complete, research finishing
2. Landing Page Dev: 3 pages live, 2 testing minor bugs
3. Copywriter: Email revisions done, submitted for approval
4. Email Manager: 8 sequences live, testing send times
5. Ads Manager: Spending $1,500/week, ROAS 3.2:1

BLOCKERS:
- [RESOLVED] Facebook Pixel issue - fixed by Tuesday evening
- Designer delayed on PDF - rescheduled to Thursday

NEXT WEEK:
- Launch Magnet #12 tests
- Complete Magnet #13 artifact QA
- Scale successful ad campaigns

ANNOUNCEMENTS:
- Team lunch Friday (optional)
- Research repo updated with new competitor analysis
```

---

### 5. Bi-Weekly Strategy Session

**Purpose:** Deep analysis, planning, strategic decisions
**Schedule:** Thursdays 2:00pm - 3:30pm (every other week)
**Attendees:** Prompt Engineer, Project Manager, Analytics Lead, Leadership
**Format:**
- 10 min: Performance review of last magnets
- 20 min: Testing results and learnings
- 20 min: Next magnet planning & positioning
- 20 min: Optimization priorities and budget
- 10 min: Next steps and assignments

**Discussion Points:**
- Which magnets are outperforming?
- What email subject lines/ad copy work best?
- What A/B tests should we run?
- Which channels drive cheapest leads?
- What audience segments convert best?
- How do we improve underperforming magnets?

---

### 6. Monthly All-Hands

**Purpose:** Full team alignment, celebrating wins, strategic direction
**Schedule:** Last Friday of month, 3:00pm - 4:30pm (90 minutes)
**Attendees:** Entire IGNITE team (not just lead magnets)
**Format:**
- 15 min: Monthly results review (revenue, leads, ROI)
- 15 min: Team wins and celebrations
- 20 min: Key learnings and insights
- 15 min: Strategic priorities for next month
- 15 min: Q&A and open discussion
- Remaining: Informal networking

**Monthly Report Template:**
```
NOVEMBER 2025 IGNITE LEAD MAGNETS REPORT

SUMMARY:
- Total leads generated: 2,847 (target: 2,500)
- Cost per lead: $4.20 (target: $5.00)
- IGNITE enrollments: 287 (target: 250)
- Revenue: $28,490 (target: $25,000)

BY MAGNET:
[Table with performance by magnet]

TOP PERFORMERS:
1. Magnet #9 (28-Day Challenge): 1,205 leads, 18% IGNITE conversion
2. Magnet #1 (Pain Vision): 890 leads, 12% IGNITE conversion

KEY LEARNINGS:
1. Video-enabled landing pages convert 40% better
2. Personalized email sequences drive 3x higher IGNITE conversion
3. Audience targeting by income level (>$100k) reduces CPL by 35%

NEXT MONTH:
1. Launch Magnets #12-14
2. Optimize underperforming Magnets #2, #6, #8
3. Test new ad creative angles

CHALLENGES:
- Designer availability limiting PDF production
- Facebook ad costs rising (platform-wide)
```

---

## Decision-Making Framework

### Who Decides What, When, How

#### Fast Decisions (<24 hours)
**Examples:** Daily optimization, small copy changes, tool selection

**Process:**
1. Post in Slack `#ignite-blockers`
2. Tag relevant owner
3. Owner responds with decision/recommendation
4. Document in GitHub issue (if significant)
5. Proceed

**Response Time:** <2 hours during work hours

---

#### Medium Decisions (1-3 days)
**Examples:** Magnet positioning, A/B testing priorities, budget allocation

**Process:**
1. Email decision stakeholders with options
2. Include pros/cons analysis
3. Include decision deadline (usually next business day)
4. Collect feedback via email replies
5. Owner decides with input
6. Document decision in GitHub issue
7. Implement and communicate

**Response Time:** <24 hours from request

---

#### Major Decisions (3-7 days)
**Examples:** New magnet concepts, major strategy shifts, significant budget changes

**Process:**
1. Schedule bi-weekly strategy session to discuss
2. Present options with research backing
3. Get team input and feedback
4. Leadership makes final decision
5. Document in GitHub discussion
6. Team alignment sync call if needed
7. Implement with clear owners and timelines

**Response Time:** By next strategy session (max 3-7 days)

---

## Escalation Process

### When Something Goes Wrong

**Level 1: Individual Contributors**
- Report issue to direct manager/project manager
- Provide: What happened, impact, suggested solution
- Expected response: <4 hours

**Level 2: Role Leads**
- If unresolved after 4 hours, escalate to role lead
- Role lead works to resolve within 24 hours
- Expected response: 24 hours

**Level 3: Project Manager**
- If unresolved after 24 hours, escalate to PM
- PM coordinates cross-functional solution
- Expected response: 24 hours

**Level 4: Leadership**
- If unresolved after 48 hours, escalate to Toby
- Leadership makes final decision/allocates resources
- Expected response: 24 hours

**Example Escalation:**
```
1. Developer reports: "Landing page HTML error"
   - Tries to fix for 1 hour
   - Slack posts in #ignite-blockers

2. QA catches during testing
   - Tags landing page developer
   - Developer has 4 hours to fix

3. If not fixed by then:
   - Project Manager gets involved
   - May reassign to different developer
   - May adjust timeline

4. If still not resolved:
   - Leadership decides: fix now, defer, or workaround
```

---

## Documentation Requirements

### Every Significant Decision Must Be Documented

**What needs to be documented:**
1. What decision was made?
2. Why (what was the reasoning)?
3. Who made it?
4. When was it made?
5. Any alternatives considered?
6. Impact/outcome?

**Where to document:**
- GitHub issue/PR: Technical decisions
- GitHub discussion: Strategic decisions
- Email thread: Email approval trail
- Meeting notes: Verbal decisions

**Example:**
```
ISSUE: Landing page conversion optimization
Created by: Analytics Lead
Date: Nov 15, 2025

DECISION:
Change landing page headline from "Discover Your True Potential"
to "Stop Feeling Stuck. Start Getting Results."

REASONING:
A/B test showed 35% higher CTR with direct, action-oriented headline.
Aligns with market research on target audience language preferences.
Matches Toby Potter voice guidelines.

MAKER: Copywriter (approved by PM)
IMPACT: +12% form conversion rate on Magnet #9

DOCUMENTED: GitHub Issue #247
```

---

## Feedback Culture

### How We Give & Receive Feedback

**Feedback Principles:**
- ✅ Specific and actionable
- ✅ Focused on work, not person
- ✅ Delivered quickly (within 24 hours of work)
- ✅ In private for sensitive feedback
- ✅ Public for wins and successes

**Feedback Format:**

**Example: What Worked**
```
Magnet #10 Email Sequence - Great Work!
- Subject lines hook readers immediately (45% open rate!)
- Progression from problem → solution → offer logical
- CTAs are bold and specific ("Click here to apply")
- Personalization tags increase relevance
```

**Example: What Needs Improvement**
```
Magnet #11 Landing Page - Revision Needed
Feedback: Copy tone is too formal for target audience
Specific issue: "Engage in a transformative journey" doesn't match voice
Suggestion: "Stop waiting. Start your transformation this week."
Research: Target audience uses action-oriented, direct language (per interviews)
Priority: High - affects conversion rate
Timeline: Update by Wednesday EOD
```

---

## Meeting Effectiveness Standards

### Meetings Should Be:
- ✅ **Scheduled in advance** (unless urgent)
- ✅ **Have clear agenda** (shared 24 hours before)
- ✅ **Start and end on time** (respect everyone's time)
- ✅ **Have prepared participants** (read background before)
- ✅ **Focus on outcomes** (decisions, actions, next steps)
- ✅ **Have notes** (documented within 24 hours)
- ✅ **Have clear action items** (owners, deadlines)

### Meeting Decline Policy
- If you're not needed: **Just decline**
- If you have conflict: **Let organizer know immediately**
- If you can't attend: **Send someone else or provide written update**

---

## Remote Work Communication

### Async-First Approach
Since team members work across time zones:
- Post updates to Slack (not Slack messages)
- Use GitHub for decisions (not Slack threads)
- Document decisions in writing
- Don't expect immediate responses
- Use email for anything that needs follow-up

### Time Zone Considerations
If team spans time zones:
- Rotate meeting times monthly
- Record all meetings for async review
- Use "working agreements" on response times
- Async decisions with 24-48 hour feedback window

---

## Conflict Resolution

### When Team Members Disagree

**Level 1: Direct Discussion**
- 1-on-1 conversation to understand different perspectives
- Find common ground
- Try to reach agreement
- Timeline: <24 hours

**Level 2: Mediation**
- If no agreement, bring in Project Manager as mediator
- PM hears both sides
- PM proposes solution
- Timeline: <48 hours

**Level 3: Leadership Decision**
- If still unresolved, escalate to Toby
- Toby hears both sides
- Toby makes final decision
- Team commits to decision even if disagreed
- Timeline: <72 hours

**Example:**
```
Developer: "We need 2 more weeks for landing page optimization"
PM: "We're launching in 5 days, optimization can wait"

→ Team discuss tradeoffs and concerns
→ Realize optimization would improve conversion by estimated 8%
→ PM decides: Launch on schedule, optimize Week 2
→ Everyone commits and moves forward
```

---

## Communication During Crisis

### If Something Goes Wrong (Campaign broken, data lost, etc.)

**Immediate (within 30 minutes):**
1. Person discovering issue: Post in Slack #ignite-blockers with:
   - What is broken?
   - When was it discovered?
   - What's the impact?
2. Escalate to Project Manager immediately
3. PM activates response team

**Stabilization (within 1-2 hours):**
1. Identify root cause
2. Implement quick fix if possible
3. Or take system offline if necessary
4. Keep stakeholders updated every 30 minutes

**Resolution (ongoing):**
1. Fix underlying issue
2. Test thoroughly
3. Implement with monitoring
4. Conduct post-mortem meeting within 48 hours

**Post-Mortem Meeting:**
- What happened?
- Why did it happen?
- How do we prevent it next time?
- What's the action item?
- Who's responsible?

---

## Communication Checklist

Before starting work on any magnet:
- [ ] Read the prompt in `/prompts/`
- [ ] Review relevant research in `/research/`
- [ ] Check project status in GitHub
- [ ] Understand your specific deliverable
- [ ] Know who hands off to you next
- [ ] Have their contact info
- [ ] Know the deadline

When handoff is ready:
- [ ] Artifacts are organized
- [ ] Documentation is complete
- [ ] Message the next person
- [ ] Provide context and questions
- [ ] Make yourself available for questions
- [ ] Track their progress until handoff complete

---

## Questions About Communication?

- **Unclear who to contact?** Ask Project Manager
- **Not sure what channel to use?** Check this guide then ask PM
- **Need faster response?** Use Slack + email + direct call
- **Having conflict?** Follow resolution process above
- **Need to suggest change to protocol?** Post in Slack #ignite-ideas

---

**Clear communication = Clear execution. Clear execution = Results.**
