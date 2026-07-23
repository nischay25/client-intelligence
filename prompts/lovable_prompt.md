Build a modern AI-powered web application called "HealthCoach Intelligence".

Tagline:
Transform client–coach conversations into actionable, evidence-backed health insights.

## Objective

The application is designed for health coaches and nutritionists.

A coach uploads a client–coach conversation (PDF or TXT). The AI analyzes the conversation and automatically generates a structured Client Intelligence Dashboard that helps the coach understand the client's progress without reading the entire conversation.

The application should feel like an internal AI tool used by healthcare professionals.

Do NOT build a chatbot.

Do NOT simply summarize the conversation.

Instead, generate structured, actionable intelligence.

------------------------------------------------------------

## User Flow

1. Upload conversation (PDF/TXT)
2. Click "Analyze Conversation"
3. AI processes the conversation
4. Display a professional dashboard
5. Coach reviews the report
6. Coach Approves, Edits or Rejects it

------------------------------------------------------------

## Design Style

The interface should look premium and modern.

Inspired by:

• Notion
• Linear
• Stripe Dashboard
• Apple Health

Use plenty of white space.

Rounded cards.

Professional typography.

Minimal colors.

Easy to scan within 30 seconds.

Avoid large paragraphs.

Use icons.

Every section should be collapsible.

------------------------------------------------------------

## Dashboard Header

Display

HealthCoach Intelligence

Client Name
Anonymous

Analysis Date

Overall Health Score (0–100)

Risk Level

Green
Yellow
Orange
Red

Quick Status

🟢 Nutrition

🟡 Sleep

🟢 Exercise

🟢 Water

🔴 Stress

🟡 Engagement

------------------------------------------------------------

## Dashboard Sections

Create separate cards.

------------------------------------------------------------

1. Weekly Summary

Display only 5–6 bullet points.

Example

✓ Sleep improved toward the end of the week

✓ Walking remained consistent

✓ Stress increased because of work

✓ Hydration remained good

✓ Energy improved after better sleep

Do NOT display long paragraphs.

------------------------------------------------------------

2. Nutrition

Show

Status

Excellent
Good
Moderate
Needs Attention

Nutrition Score

Strengths

Needs Improvement

Evidence (Expandable)

------------------------------------------------------------

3. Exercise & Movement

Show

Average Steps

Activities

Walking

Stretching

Running

Consistency

Trend

Evidence

------------------------------------------------------------

4. Sleep

Show

Average Sleep

Trend

Improving

Declining

Stable

Timeline

Day 1 → Day 8

AI Insight

Evidence

------------------------------------------------------------

5. Water Intake

Display

Average Intake

Consistency

Trend

Evidence

------------------------------------------------------------

6. Symptoms & Stress

Display

Stress Level

Symptoms

Low Energy

Fatigue

Bloating

Acidity

Possible Causes

Evidence

------------------------------------------------------------

7. Engagement

Display

Overall Engagement Score

Response Consistency

Coach Interaction

Adherence

------------------------------------------------------------

8. Key Barriers

Display as bullet points

Examples

Meal Planning

Work Pressure

Sleep

Busy Schedule

Forgetting Habits

------------------------------------------------------------

9. Pending Actions

Checklist

□ Continue meal planning

□ Track water

□ Improve sleep

□ Follow meal timings

------------------------------------------------------------

10. Risk Flags

Display only important risks.

Use colored badges.

High

Medium

Low

Example

🔴 Poor Sleep

🟠 Persistent Bloating

🟠 Work Stress

------------------------------------------------------------

11. Coach Recommendation

Instead of paragraphs,

display priorities.

Priority 1

Priority 2

Priority 3

Priority 4

------------------------------------------------------------

12. Supporting Evidence

Do NOT show all evidence directly.

Create expandable sections.

Example

▶ Sleep

▶ Nutrition

▶ Exercise

▶ Stress

When expanded,

display original conversation quotes.

------------------------------------------------------------

## AI Transparency

Create a dedicated section.

Display

Confirmed Facts

Client Reported

AI Inference

Missing Information

Each finding must belong to one category.

Use colored badges.

Example

Confirmed Fact

Client Reported

AI Inference

Missing Information

------------------------------------------------------------

## Hallucination Prevention

Never invent facts.

If information is unavailable,

display

"Missing Information"

instead of guessing.

Every AI inference must clearly indicate that it is an inference.

Every important finding must include supporting evidence.

------------------------------------------------------------

## Human Review

At the bottom,

display

Approve

Edit

Reject

Reviewer Notes

This represents a Human-in-the-loop workflow.

------------------------------------------------------------

## Footer

Generated by HealthCoach Intelligence

AI-generated insights should always be reviewed by a coach before final decisions.
