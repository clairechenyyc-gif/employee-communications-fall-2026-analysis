# Employee Communications – Fall 2026 Briefing

**Video briefing (YouTube, unlisted):** [https://youtu.be/Yo8d4ew9rkA](https://youtube.com/)

This is my analysis of fall 2026 Viva Engage post performance (42 posts, Sep–Nov) for the communications leadership team.

## What I found

1. **Announcements get seen, but people don't interact with them as much.** Org-wide announcements reached a median of 68% of employees. Standard posts reached 18%. Per viewer, announcements got about half the reactions, comments and shares (3% vs 6%).
2. **Most standard posts reach fewer than 1 in 4 employees.** Important posts like fraud, phishing and AI guidance are near the bottom, at 11–14%. Posts from leaders did best. The town hall recap reached 41% and had 312 comments.
3. **The benefits enrolment announcement had high reach but a very low click rate.** It reached 71% of employees, but only 1% clicked. The reminder post reached fewer people but got almost twice as many clicks (9% click rate).

## My recommendation

Use the announcement feature for messages employees must see and act on, and measure success by clicks or completions, not views.

## What I would check next

- Whether the benefits link worked, and how employees actually enrolled
- Whether announcement reach drops as we send more of them
- The sample is small (only 7 org-wide announcements)
- 9 posts are dated after Nov 16; I re-checked without them and the results did not change

## How I did it (Excel)

I followed the Google Data Analytics process: Ask, Prepare, Process, Analyze, Share, Act.

**Process (cleaning)**
- Saved a copy and kept the original export unchanged
- Removed 1 duplicate post (C109)
- Sorted by date and flagged 9 posts dated after Nov 16 (kept, and checked separately)
- Checked for blanks: Link Clicks is blank only when there is no link, which is expected

**Analyze**
- Added three columns (P–R), because audience sizes range from 380 to 18,000, so raw counts can't be compared fairly:
  - Reach % = Unique Viewers / Target Audience Size
  - Engagement = (Reactions + Comments + Shares) / Unique Viewers
  - Click Rate = Link Clicks / Unique Viewers (posts with a link only)
- Compared org-wide posts (18,000 audience) only, and compared announcements and standard posts separately
- Used MEDIAN with FILTER (columns T–U). I checked the average too: for comments the average (33) was much higher than the median (21) because of one real outlier, the town hall recap (312 comments). I kept it and used the median.
- Findings 2 and 3 come from filtering and sorting the Reach % and Click Rate columns

## Files

| File | What it is |
|---|---|
| `Employee_Communications_Fall_2026_Analysis.xlsx` | My cleaned data, calculated columns, summary numbers (T–U) and cleaning notes (rows 46–47) |
| `Employee_Communications_Analytics_Exercise_Dataset_Original.xlsx` | The original export, unchanged (renamed only) |
| `Employee_Communications_Fall_2026_Briefing_Slides.pdf` | The slides from the video |

## Tools

I used Excel for data cleaning and calculations. I used an AI assistant (Claude) to check my approach and help prepare the charts and slides. The interpretation and recommendation are my own.
