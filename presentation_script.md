# Video Presentation Script — Week5_Presentation_KelvinMoruri.mp4
*(Rehearsal aid — not itself a submission file. Record yourself reading/adapting this on camera or with screen-share of the notebook/report.)*

**Target length: 5–7 minutes**

---

### 1. Opening (30 sec)
"Good morning — I want to walk you through what we found investigating the throughput drop across our four regional depots. I'll keep this to context, insight, and the action I'm recommending, and then I'll take your questions."

### 2. Context (45 sec)
"We looked at 100 days of daily throughput across Mombasa, Nairobi, Kisumu, and Eldoret — January through April. This started because our system-wide average throughput was down, and I needed to find out whether that was normal variation or something we needed to act on."

### 3. Insight — walk through the timeline chart (90 sec)
"Here's the key chart. [Show Figure 1 / chart_04]. This is Nairobi's daily throughput with a 7-day rolling average. You can see it's stable, then on February 1st it drops and stays down — about 40% lower than before. That's not a bad day, that's a new baseline. The other three depots, over the same period, stayed within their normal range."

### 4. Evidence — Pareto and correlation (90 sec)
"To make sure I wasn't chasing the wrong depot, I ran a Pareto analysis [show Figure 2 / chart_05] — Nairobi alone accounts for the large majority of our total network loss. Then I checked the two obvious alternative explanations: weather and scheduled maintenance. Both came back with essentially zero correlation to throughput — 0.01 for temperature, -0.02 for maintenance. So this isn't the weather, and it isn't our maintenance schedule. That points to something localized and mechanical inside the Nairobi facility itself."

### 5. Action (45 sec)
"My recommendation is three-fold: send an inspection team to Nairobi this week to check for valve or pump issues, schedule the repair once confirmed, and add an automated alert to our pipeline so if this happens again at any depot, we catch it within 48 hours instead of weeks."

### 6. Anticipated Skeptical Question — build this into the video (60–90 sec)
**Say the question out loud, then answer it:**

"Now, I expect the question — 'this looks like it could just be normal fluctuation, why spend budget on an emergency crew?' Fair question. But look at the rolling average again — this isn't noise, it's a step change that hasn't recovered in over two months. And Nairobi is responsible for the large majority of our total network loss, not a small share. The cost of a short inspection is small compared to what we're already losing every week we wait."

### 7. Close (15 sec)
"Happy to take any other questions — and the full analysis and report are in the shared repo if you want to dig into the numbers yourself."

---

**Delivery tips:**
- Have the notebook or the two report charts (chart_04, chart_05) visible on screen while you talk through them.
- Say numbers out loud (don't just point at the chart) — a director skimming won't necessarily read every axis label.
- Keep the "anticipated pushback" segment explicit — the rubric specifically grades how you handle objections, so don't skip stating the question before answering it.
