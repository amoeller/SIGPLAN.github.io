---
layout: default
title: "Objectives of OOPSLA"
---

This page contains guidance for current and future OOPSLA RC chairs, compiled from the experiences of previous chairs.

**Also See:**

- [Practices of PLDI](http://www.sigplan.org/sites/default/files/PracticesofPLDI.pdf)
- [Principles of POPL](/Conferences/POPL/Principles)
- [The Functioning of ICFP](https://www.icfpconference.org/TheFunctioningofICFP.pdf)
- [How to Run SPLASH](/Conferences/SPLASH/HowToSPLASH)

*Started by [Alex Potanin](https://potanin.github.io/) and [Bor-Yuh Evan Chang](https://plv.colorado.edu/bec/) (OOPSLA 2024 RC co-chairs). Revised by [Shriram Krishnamurthi](https://cs.brown.edu/~sk/) and [Sukyoung Ryu](https://plrg.kaist.ac.kr/ryu) (OOPSLA 2025 RC co-chairs) and [Anders M&oslash;ller](https://cs.au.dk/~amoeller/) and [I&#x15F;&#x131;l Dillig](https://www.cs.utexas.edu/~isil/) (OOPSLA 2026 RC co-chairs). We expect further input from [Ilya Sergey](https://ilyasergey.net/) and [Nadia Polikarpova](https://cseweb.ucsd.edu/~npolikarpova/) (OOPSLA 2027 RC co-chairs).*

**Important:** All documents related to OOPSLA must be stored on the [SPLASH Google Drive](https://drive.google.com/drive/folders/0APXWu4PPnVzBUk9PVA) provided by SIGPLAN, in the folder for the relevant year. This ensures continuity across years and that future chairs can access prior materials. Do not use personal storage or other shared drives for official OOPSLA documents.

* TOC
{:toc}

## General Advice

- We recommend **2 RC co-chairs** for OOPSLA.
- As a starting point, plan for **approximately 1 Associate Chair (AC) per 50 papers in each round**; adjust for the expected level of editorial oversight and for revisions.
- Submission volumes are high and vary substantially between rounds and years: approximately 150 in R1 and 250 in R2 in 2024, 151 and 439 in 2025 (590 total), and 227 and 380 in 2026 (607 total). R1 2026 was roughly 1.5x the size of R1 2025. Do not assume that R2 will always be twice the size of R1 or that the next year will necessarily be larger. Plan RC and AC capacity with a margin for unexpected submissions and revisions.
- See the [OOPSLA 2026 CfP](https://2026.splashcon.org/track/oopsla-2026) as the most recent reference.
- See also the [SPLASH GC Notes (How to Make a SPLASH)](/Conferences/SPLASH/HowToSPLASH).
- Consider running a Shadow PC, as [ICSE has done](https://conf.researchr.org/track/icse-2025/icse-2025-shadow-research-track-program-committee).

## Steering Committees

There is a **SPLASH SC** (splash-sc@googlegroups.com) and, created in the aftermath of OOPSLA 2025, an **OOPSLA SC** (oopsla-sc@googlegroups.com) consisting of recent chairs. The SPLASH SC includes chairs of Onward!, etc. Some questions benefit from diverse input (use the SPLASH SC), but others are best served by asking people close to OOPSLA itself (use the OOPSLA SC). Some matters are simply not the business of non-OOPSLA folk.

## Forming the Review Committee

- Use the principle of **approximately 1 paper to review per week**. This is a very reasonable load; too much more may result in excessive subreviewing and a decline in quality. This principle suggests the RC size.
- With 600+ submissions across two rounds (as in 2025 and 2026), that means 1800+ reviews. At 15 reviews per person, that means **120+ RC members is the minimum**. We recommend aiming for even more, similar to or exceeding POPL/PLDI, but be aware you are competing with those conferences for reviewers from a limited pool.
- Use [PC Miner](https://github.com/pcminer-tools/pcminer) to identify potential RC members (expect 2--3 OOPSLA papers to qualify someone for an RC invitation).
- Get the previous chairs' spreadsheet of RC members from the SPLASH Google Drive.
- Follow the [SIGPLAN guidelines](/Resources/Guidelines/ProChair/).
- Bring some SE people, but be aware of competition with ICSE/FSE/ASE. Time your invitations well, as people often refuse "because they only want to be on one PC per year".
- Actively seek out women academics by going through CS departments and previous author lists to increase diversity.
- Officially, there is a **vetting process by the SC**: you cannot just invite people directly. The SC must first approve your nominations (less to scrutinize every choice, more to check for people who have been sanctioned, etc.). In addition, **SIGPLAN also needs to approve**. Bake time into your schedule for this.
- OOPSLA is in intense competition with other conferences for RC members. **Get your RC invites out early.** The 2026 chairs started planning in November 2024 and sent the first RC invitations in early February 2025; POPL was sending its PC invitations at the same time.
- A public **self-nomination form** (advertised on social media) produced useful candidates in 2026. Recent graduates are more likely to accept and often write thorough reviews; balance them with senior, well-calibrated reviewers with broad expertise.
- Use a **response form** for invitations that also collects the email address of the invitee's HotCRP account.
- **Avoid members (RC or AC) who are only available for one round** where possible; every special case creates extra work for the chairs. If you accept such cases, or agree to reduced loads (e.g., for someone taking on a major chairing role), record them in a single place and make sure they are passed on to TPMS.
- Identify **thin areas** early. In 2026, quantum papers were hard to assign because very few RC members had the expertise, and extra reviewers had to be recruited after submission.
- **Keep recruiting for R2 during R1.** In 2026, new RC invitations were sent during R1; Reserve Reviewers and self-nominations are good sources.
- A very private document restricted to RC chairs only is maintained with notes on the selection of Associate Chairs (ACs) as potential future RC candidates. Consult this internal document on the SPLASH Google Drive (or via the SPLASH/OOPSLA SC) when forming your RC.

## Reviewer Policies and Attestations

Be aware of the [SIGPLAN Review Policy](/Resources/Policies/Review/).

The RC signup form should require every invited reviewer to read and attest, as a **forced-choice question**, to two rules. This applies to all reviewers, including [Reserve Reviewers](#reserve-reviewers) --- capture the attestation at registration time.

> Serving on the OOPSLA Review Committee means following the two rules below. Please confirm you have read them and will follow them.
>
> 1. **Confidentiality of submissions.** Submitted papers, and the reviews on them, are confidential. Do not share a submission with anyone outside the review process; the one exception is light, well-attributed use of a sub-reviewer with the RC Chairs' approval. Furthermore, do not upload or paste a submission, or any part of its content, into any external or hosted AI/LLM service.
>
> 2. **Integrity of reviews.** As a reviewer, you are expected to personally read, evaluate, and form judgments about submissions. AI tools should not be used as substitutes for your expertise or judgment. AI may be used to correct spelling, grammar, and presentation, and to improve the clarity of reviewer-written text (provided that confidentiality is ensured). You remain fully responsible for the contents of your reviews, including any text that has been edited or generated with AI assistance.
>
> &#9675; I have read both rules and I agree to follow them.<br>
> &#9675; I have a question or concern about one of these. Please contact me before my appointment is finalised.

Rule 2 is worded for consistency with the [SIGPLAN Review Policy](/Resources/Policies/Review/) and the [ACM peer review policy](https://www.acm.org/publications/policies/peer-review).

### Joint Reviews with Students or Postdocs

> For training and educational purposes, RC members may jointly write a review with a student or postdoc, but this **must** be cleared with the RC chair first to ensure no conflicts. The RC member must still take full responsibility for the final review and for online discussion of the submission.

### Guidance to Reviewers

***Review quality:***
Explicitly communicate expectations for constructive, detailed, and technically grounded reviews. Reviewers should evaluate papers based on their contributions, correctness, and clarity, rather than personal preferences or narrow views of what belongs at OOPSLA. Discourage gatekeeping, excessive nitpicking, and rejecting papers merely because the idea appears simple, a proof is not mechanized, an artifact is not released, or the reviewer would have approached the problem differently.
Ask reviewers to clearly identify questions that could change their evaluation during the author response period. Reviews should help authors understand what needs to be improved, not merely justify a recommendation.

***Author response handling:***
Require every reviewer to read the author response and explicitly acknowledge it in their review. If the response changes their assessment, they should update their comments and score. If it does not, they should briefly explain why the main concerns remain unresolved, particularly when the authors have provided a substantial response. This expectation should be communicated at the beginning of the discussion period and reinforced through reminders.

### Suspected AI-Generated Reviews

Authors and ACs will occasionally suspect that a review was largely AI-generated. It is rarely possible to prove this, and using AI to polish a reviewer's own text is allowed under Rule 2 above, so avoid turning such cases into a witch hunt. In 2026, the approach was: the AC takes a look; if the review does look AI-generated (or is otherwise inadequate), the AC asks the reviewer to revise it and refers them to the [ACM peer review policy](https://www.acm.org/publications/policies/peer-review). When contacting a reviewer about a complaint, do not reveal which authors or paper raised the concern if it can be avoided.

## Choosing Associate Chairs

Think of an AC as **the chair of a mini-conference**. You are subdividing OOPSLA into a bunch of mini-venues, each headed by an AC. Ultimately the buck stops with you, but this mental model helps in choosing ACs.

- **Reliability** (timeliness, responsiveness) is the most important criterion. Choose people you trust and have prior contact with.
- Choose **reasonable individuals**. No matter how accomplished, if they routinely dismiss certain areas (anti-theory, anti-numbers, etc.), that is unhealthy and unfair to authors.
- Choose people who are **somewhat experienced and at least mid-career**:
  - They will have experience with how review processes work. Someone who has barely served on a PC/RC is not well poised to help run one.
  - There will be situations where authors complain, fairly or unfairly. The AC must have the confidence to not back down when that is the appropriate course of action. Junior people may feel intimidated or feel their careers threatened (sooner or later, authors will find out who the AC is).
- Tell your ACs that the buck stops with you, not them. You have their back, and they are welcome to escalate issues to you and get themselves out of the line of fire.
- We did not use formal area chairs in 2025 and 2026. In 2026, ACs were chosen to give broad area coverage, but papers were not routed strictly by area: areas do not receive proportional submissions. There is no harm in trying to align papers with ACs, but some papers every AC handles will be outside their areas.
- Make your expectations of **responsiveness** explicit: ACs should reply promptly to questions from the chairs, reviewers, and authors. Ask ACs to confirm that they have received and read the initial instructions email.

### Guidance to Associate Chairs

ACs should actively monitor the quality, timeliness, and consistency of reviews for their assigned papers. Reviewers should be told explicitly that ACs may ask them to revise or expand reviews.

- **Before reviewing:** Check submissions for possible desk rejection (scope, formatting, anonymity), missed or suspicious conflicts, sufficient expertise and diversity of reviewer perspectives, and acceptance of external review invitations. Report possible desk rejects to the RC chairs rather than deciding unilaterally. In 2026, papers with fixable formatting problems were given 24--48 hours to send a corrected PDF, which the AC uploaded; anonymity violations led to desk rejection.
- **During reviewing:** Read reviews **as they arrive**, not only at the deadline; ask for revisions when reviews are superficial, unclear, excessively harsh, or not technically grounded. Monitor reviewer progress and follow up before deadlines.
- **During author response:** Be available for author concerns about inappropriate reviews or important misunderstandings. Acknowledge concerns, evaluate them, and escalate sensitive cases to the RC chairs.
- **During discussion:** Prompt substantive discussion on every paper, follow up with nonresponsive reviewers, help resolve disagreement fairly, and oversee the discussion lead's meta-review. Read or at least skim author responses, especially for indications of problematic reviews. Only finalize a decision after checking the meta-review.

In 2026, ACs were given HotCRP chair permissions (subject to conflicts), and each AC was marked as the administrator of the papers in their pile, allowing them to manage those papers. Configure permissions carefully and make escalation paths explicit.

## Timing and Scheduling

### Avoiding Date Conflicts

- Check competing conferences: primarily **POPL, PLDI, and ICFP**, but also SE events like **ICSE, FSE, ASE, and ISSTA**. You cannot avoid all clashes, but avoid egregious ones (e.g., OOPSLA papers due during the week of POPL). In many cases, other conferences only settle their dates after yours are published.
- **Keep the OOPSLA R1 notification deadline well clear of the PLDI submission deadline.** A tight gap puts authors of OOPSLA R1 rejections under pressure to rework for PLDI in a few days, and overlaps the OOPSLA R1 discussion/decision crunch with PLDI submission for the many RC members who also submit to PLDI. Aim for at least a 2--3 week buffer.
- Be aware of major holidays: Christmas, New Year, Thanksgiving in the US (nearly a week lost). Europeans have also complained about review duties during August, the traditional vacation month, but it is hard to have two rounds and skip August entirely.

### Review Period Duration

- R2 generally receives more papers than R1, but the ratio varies. Size the RC and choose review-period lengths based on expected **papers per reviewer**, rather than a fixed R2/R1 ratio.
- Aim for review periods that allow approximately one paper per reviewer per week. Since R2 typically receives substantially more submissions than R1, its review period should be correspondingly longer. As a rough guideline, allow at least 6 weeks for R1 and 10 weeks for R2, adjusting for the expected reviewer workload. For comparison, 2026 had only about 4.5 weeks for R1 and 6.5 weeks for R2 (with about 10 papers per reviewer in R2), well above the one-paper-per-week principle. At the R2 deadline, many reviews were still missing, including a few papers with zero reviews and quite a few with only one. The submission deadlines and the publisher's deadlines leave little room, so plan the whole year's calendar with this in mind.
- Give authors **at least 4 full days for the response period**, not 3. A 3-day window is painful for authors with large time-zone differences, and the response phase otherwise consumes their entire week. The 2026 CfP uses 4 days (Tue--Fri for both R1 and R2); a Tue--Sat window is also reasonable as it gives authors the option to use weekend time without forcing it.
- There is one hard deadline above all: **the publisher's deadline**. Understand it and work everything else backward from there.

### Practical Scheduling Tips

- **Public-facing deadlines (submission, author response) should fall on Tue, Wed, or Thu.** Avoid Friday --- it is a weekend day or holiday in parts of the Middle East and some Asian countries, and it pushes the next step into the weekend for everyone. Avoid Monday --- it forces authors and reviewers to work through the previous weekend. Mid-week deadlines also respect that different countries observe different weekend days.
- For **internal, reviewer-facing** deadlines, **Friday AoE** is still a useful choice: it gives chairs the weekend to chase late reviewers before the next public-facing step starts on Monday or Tuesday.
- Give yourself **slack days**. People will always be late. For instance, make an internal review deadline on a Friday, but assign the next step to Tuesday rather than Monday.
- Set a **halfway checkpoint**: expect each reviewer to have completed approximately half of their assigned reviews, and aim for at least **one submitted review per paper**. Ask ACs to inspect both reviewer-level and paper-level progress, intervene early on papers with no reviews, and read incoming reviews for quality. In R1 2026, the chairs sent reminders at the halfway point and 10 and 3 days before the final review deadline; in R2, HotCRP reminders were sent about 14, 7, and 2 days before the deadline, in addition to reminders from the chairs. Do not wait until the deadline to chase missing reviews: in R2 2026, the slack between the review deadline (Friday) and the author response (Tuesday) was entirely consumed by chasing missing reviews, and a few papers still had a review missing when reviews were released to authors.

During the discussion period, actively monitor papers with little reviewer engagement or unresolved disagreements. Send targeted reminders to nonresponsive reviewers, and reserve Zoom meetings as an escalation mechanism when asynchronous discussion does not converge.

### Suggested Discussion Period Timeline (Minimum)

Based on 2025 experience, the following is a **contingency-oriented minimum schedule**, allowing time for Zoom meetings if asynchronous discussion fails. In 2026, all decisions were reached without such meetings; plan for Zoom escalation without assuming meetings will be necessary:

- **Week 1 Mon--Wed AoE** --- Author Response. ACs assign discussion leads concurrently.
- **Week 1 Thu--Fri AoE** --- Deadline for reviewers to start discussing (each reviewer weighs in once).
- **Weekend 1 Sat--Sun** --- ACs nudge reviewers who have not responded.
- **Week 2 Mon--Fri AoE** --- Deadline for asynchronous decisions (submission decision or assignment to Zoom RC Meeting).
- **Weekend 2 Sat** --- Chairs assign non-converged papers to Zoom RC Meetings.
- **Week 3 Tue** --- Zoom RC Meetings.
- **Week 3 Wed** --- Deadline for meta-reviews.
- **Week 3 Thu** --- Notification.

Plan a gap between the asynchronous decision deadline and the Zoom meetings so chairs can assign non-converged papers and reviewers can prepare. Not doing this in 2025 was a regret.

In 2026, the possibility of Zoom meetings was announced as a fallback for papers whose online discussion did not converge, which helped motivate timely participation; in the end, no meetings were needed. The discussion period was 10 days in R1 and 2 weeks in R2 (online discussion only), followed by notification a few days later.

***Discussion leads:***
Assign one reviewer as discussion lead for each paper, under the supervision of the AC. The discussion lead is responsible for preparing a meta-review that summarizes the consensus, explains the recommendation, and addresses important issues arising during discussion and author response. In 2026, discussion leads drafted meta-reviews as HotCRP comments with visibility **"Authors (eventually) and reviewers"**; ACs copied the drafts into the actual meta-reviews after verifying that they accurately summarized the evidence, responses, and discussion. ACs assigned themselves as meta-reviewers in HotCRP as needed and recorded the decision **only after the meta-review was complete**. ACs should at least skim all author responses and examine those that identify serious misunderstandings or questionable reviewer conduct.

### The 2026 Timeline in Practice

The 2026 chairs maintained a detailed timeline for each round (who does what, and when) on the SPLASH Google Drive. Start from the previous year's timelines; they are the most reusable planning material. The main phases in 2026 were:

| Phase | R1 2026 | R2 2026 |
|---|---|---|
| Submission | Fri 10 Oct | Tue 17 Mar |
| Bidding | 11--14 Oct | 18--20 Mar |
| Data sent to TPMS / assignment back | 15 Oct / 19 Oct | 21 Mar / 24 Mar |
| Expertise check | 20--21 Oct (2 days, too short) | 25--28 Mar (4 days) |
| Reviewing | 24 Oct -- 25 Nov (~4.5 weeks) | 31 Mar -- 15 May (~6.5 weeks) |
| Author response | Tue 2 -- Fri 5 Dec | Tue 19 -- Fri 22 May |
| Discussion | 6--15 Dec | 23 May -- 5 Jun |
| Notification | Wed 17 Dec | Wed 10 Jun |
| Revisions due | Tue 3 Feb | Tue 21 Jul |
| Reviewing of revisions | 4--13 Feb (10 days, too short) | 22 Jul -- 4 Aug (2 weeks) |
| Notification of revisions | Tue 17 Feb | Fri 7 Aug |
| Camera-ready | Fri 27 Feb | mid-Aug |

Note that the R1 2026 submission deadline fell on a Friday, contrary to the [advice above](#practical-scheduling-tips); R2 used a Tuesday.

Other recurring tasks in the 2026 timelines:

- **In January (before R2):** confirm the camera-ready date with the publisher (Conference Publishing) and the assignment turnaround with the TPMS admin.
- **Before each submission deadline:** email ACs and RC; check that every RC member has updated TPMS and HotCRP topic interests, and send individual reminders (check again a week later).
- **Right after submission:** check for submissions that are still marked as drafts, identify revisions from earlier rounds, assign ACs in HotCRP, and collect and vet Reserve Reviewers.
- **Status messages to the SC** after submission (numbers, resubmissions, topics) and after notification.
- **After notification:** remind authors of accepted and Minor Revision papers about artifact evaluation.
- **After the revision decisions:** prepare the PACMPL editorial for the issue.

### TPMS Timing

Account for TPMS in the bidding schedule (make this visible in the RC-only calendar):

1. **Before submissions:** ask reviewers and ACs to update TPMS publication profiles; check missing accounts/publications.
2. **After submissions:** prepare the submission data for TPMS and open HotCRP bidding, leaving approximately **3--4 days** for reviewers to enter preferences and expertise ratings. Explain the use of two-part bids (e.g., `12X`, `-7Y`) where applicable.
3. **After bidding closes:** remove unresponsive RC members, check HotCRP's conflict overview (`/conflictassign`), and provide TPMS with the papers (excluding resubmissions, which go to their previous reviewers), the HotCRP preferences, the conflicts, a list of desk-rejected and withdrawn papers, and the reviewers with the **maximum number of papers for each person**. Remember ACs, Reserve Reviewers, reduced loads, and members who are only available for one round. In R2, also consider the number of R1 reviews per person for fairness. In **2026, TPMS made the initial assignments** using these preferences together with its expertise matching; the turnaround was about 3--4 days. Confirm the turnaround with TPMS in advance.
4. **Before reviewing opens:** import the tentative assignments into HotCRP and **verify that they respect the conflicts**: in R2 2026, the assignments returned by TPMS assigned several papers to conflicted reviewers. Allow roughly **3--4 days** for reviewer expertise checks, AC checks, and manual corrections (2 days in R1 2026 was too short). Tell reviewers not to start until assignments are final.

Note: you can re-allocate Major Revision papers to past reviewers concurrently with the bidding process.

## Bidding and Paper Assignment

### Using TPMS

[TPMS](https://torontopapermatching.org/webapp/profileBrowser/about_us/) is very important. Get all RC members to upload or update their PDFs inside TPMS as soon as they accept their invites, so everything is ready when the submission deadline comes. Use the TPMS report to see who is missing papers or accounts.

- **For workflows that import TPMS match scores into HotCRP** (as described below for 2025 R2), previous chairs recommended multiplying TPMS rankings by 100 to obtain scores between 0 and 100, reserving values above 100 for reviewer-entered preferences, and using negative scores to signal papers to avoid. **Do not assume this score encoding applies to the 2026 workflow**, in which HotCRP bids were passed to TPMS for assignment. Confirm the current TPMS/HotCRP interface and bidding scale before reusing these instructions.
- In 2026, HotCRP reviewers were asked for two-part bids: a preference from -20 to +20 and expertise X/Y/Z, with at least 30 positive bids encouraged. Positive and negative bids both help matching; remind reviewers that declining to bid does not reduce their review load.
- Ask ACs to get TPMS accounts too; you can use TPMS to help assign their ~50 papers.
- TPMS is a paid service (about 1,500 CAD in 2026). Agree with the General Chair early that it is in the budget.

### Lessons from previous years

The 2024 chairs found TPMS indispensable. In 2025, the experience was more mixed:

- **R1:** Automatic assignment using TPMS alone led to many unhappy reviewers. Some felt it was just word-matching. A manual round was needed to fix assignments.
- **R2:** A better approach was used. TPMS scores were used to **populate initial bid values in HotCRP**. Reviewers were then asked to do manual bidding on top of these. If someone did not bid at all, there was still a reasonable approximation of their preferences rather than no information. This improved assignments for everyone. No complaints were received.

In 2026, RC members were asked to update their TPMS publication profiles and enter topic interests and bidding preferences in HotCRP. The HotCRP preferences were then provided to TPMS, which combined them with its expertise matching to compute the initial paper assignments. Reviewers subsequently checked their tentative assignments, and the chairs made manual adjustments based on their feedback. This approach worked well overall.

### Reserve Reviewers

In 2025, the Reserve Reviewer policy was initiated (see the [SIGPLAN blog post](https://blog.sigplan.org/2025/09/09/the-reserve-reviewer-policy/)). This was a life-saver and has been continued in the [2026 CfP](https://2026.splashcon.org/track/oopsla-2026#reserve-reviewer-policy).
Future chairs should continue to refine this approach. **Vet every Reserve Reviewer candidate before making assignments, even if the candidate formally qualifies under the Reserve Reviewer policy.** Formal eligibility does not guarantee the expertise needed to evaluate OOPSLA submissions. Examine each candidate's publication record and relevant reviewing experience, particularly at OOPSLA and closely related conferences, and retain only those with sufficient relevant expertise. In 2026, approximately half of the formally eligible Reserve Reviewer candidates were screened out because they lacked sufficient experience with OOPSLA and related conferences. Plan for this substantial reduction when estimating the available Reserve Reviewer pool; do not assume that every eligible candidate can be assigned a paper. Remember that the best way to maintain OOPSLA's high standards is to select the right reviewers!

In 2026, Reserve Reviewers received individual review invitations through HotCRP and were asked to **accept them explicitly**. ACs and chairs monitored outstanding invitations and followed up promptly. Reminders referred to the policy's possible **desk rejection of the Reserve Reviewer's own submission(s)** if they failed to accept and complete assigned reviews; apply any consequences only according to the published policy and after checking the facts and any extenuating circumstances. Remind Reserve Reviewers that delegation without approval is not permitted. Coordinate HotCRP automated notifications with assignment finalization: in 2026, some premature notifications caused confusion. Reserve Reviewers were already needed in R1 2026 when submissions exceeded expectations.

Practical notes from 2026:

- Use the HotCRP submission form to ask for the Reserve Reviewer's DBLP and/or Google Scholar entry (to support vetting), and remind them to register conflicts and topic interests in HotCRP.
- Reserve Reviewers were assigned **at most 2 papers** each.
- HotCRP has no real support for Reserve Reviewers. The 2026 chairs tagged them (`#ReserveReviewer`) and wrote scripts for extracting them and managing the assignments. Expect to do a fair amount of scripting.
- Requests for exemptions after submission (e.g., due to a heavy workload) were declined: by submitting, authors agree to the policy.

Reserve reviewers must complete the same [Reviewer Policies and Attestations](#reviewer-policies-and-attestations) as full RC members, at registration time.

### Expertise and Review Allocation

- Ask reviewers for an expertise check and to prioritise papers where they have strong expertise.
- Ask reviewers to be generous in marking themselves as **X** (expert). Many experts use Y unless they have accepted papers in the exact same area, which is too high a bar.
- Expert reviewers requested by authors often turned out to be not useful or even wrong. Consider dropping this.
- Treat **resubmitted papers** carefully. They can get lost in the mass of other papers. Preserve continuity with previous reviewers where possible, while ensuring adequate expertise and not reopening settled issues without good reason.

***Resubmissions from previous years:***
At the submission deadline, identify papers returning after Major or Minor Revision from the previous year. In 2026, the chairs supplied each responsible AC with a personalized document linking the earlier submission, reviews, decision, and discussion context. Ask the AC to invite the original reviewers as external reviewers in HotCRP. Prioritize retaining reviewers who were central to the earlier decision; a peripheral reviewer who declines may not need replacement. Two well-informed returning reviewers can sometimes suffice, if consistent with the year's review requirements and the paper still has appropriate expertise coverage. Begin invitations promptly.

***Tentative assignments and expertise checks:***
After automated assignment, release tentative assignments and give reviewers a short period (e.g., 3--4 days) to report papers for which they cannot provide a reasonably expert review (at least expertise level Y). Explicitly instruct reviewers not to begin reviewing until assignments are finalized. Use a structured form to collect reassignment requests and reserve time for manual adjustments.

## Decisions and Major Revisions

As of the [2026 CfP](https://2026.splashcon.org/track/oopsla-2026#review-process), there are four possible outcomes:

- **Accept:** Paper appears in PACMPL(OOPSLA).
- **Reject:** A rejected R1 submission is not allowed to be resubmitted in R2. A paper that is rejected in R2 is allowed to resubmit in R1 the following year. Check R2 submissions against R1 rejections early (titles, authors, abstracts): in 2026, such a resubmission was only caught by a reviewer after the reviews had been written.
- **Minor Revision:** Specific concerns reviewers want addressed; revisions expected within the revision phase. (Starting in 2026, "Conditional Accept" has been merged into Minor Revision.)
- **Major Revision:** Significant concerns requiring substantial rework; under the policy adopted for R2 2026, such papers had to wait until OOPSLA 2027 R1 rather than use the immediate revision phase.

From the authors' perspective, an advantage of submitting a revision is that the same reviewers will be asked to review the revision (to the extent possible).

The main reason for not allowing Major Revisions to submit in the revision phase is to reduce the risk that the reviewers treat Major and Minor revisions the same.
(This rule started in R2 of 2026 after observing a strikingly high acceptance rate of major revisions in the R1 revision phase: of the 28 Major Revision papers revised in February 2026, 19 were accepted, 5 became Minor Revision, 3 were rejected, and 1 was postponed. For comparison, all 38 revised Minor Revision papers were accepted.)
Whether Major Revisions should be allowed in the immediate revision phase has been discussed before, and earlier chairs argued for allowing it (the Major/Minor distinction being one of depth rather than time); future chairs may want to revisit this trade-off.

Make the mechanics of submitting a revision explicit to authors and ACs (which HotCRP option to use, which round, how to mark it as a revision of an earlier submission), especially for revisions that move from one round to the next.

Initial submissions have a **23-page limit** (excluding references and supplementary material); revisions may be up to **25 pages**. Authors must include a **Data-Availability Statement** before references (does not count toward page limits). Reviewing is **double-blind**.

***Decision recommendations:***
Encourage reviewers to make clear recommendations rather than using Minor or Major Revision as an expression of uncertainty. In particular, aim to have at least one reviewer who actively champions each accepted paper. Minor Revision should be used when specific, feasible concerns can be addressed within the revision period. Major Revision should indicate more substantial concerns that require further work, but where the paper has a realistic path to acceptance. Neither category should be used merely to postpone a difficult decision. See the [2026 CfP](https://2026.splashcon.org/track/oopsla-2026#review-process) for the definitions of Minor and Major Revision used in 2026.

***Revision reviews:***
Require reviewers to explain how revisions address the main concerns from the previous round, what remains unresolved, and why the revised paper should be accepted, rejected, or revised again. Even positive revision assessments should contain a brief substantive justification, rather than simply stating that the revision looks good.

***Revision phase mechanics:***
In 2026, reviewers posted their assessments of revisions as HotCRP comments rather than new reviews. A meta-review was not needed when a Minor Revision was simply accepted; author-visible comments were needed when the paper was not accepted or remained in revision. The revision phase is not intended for back-and-forth with the authors: reviewers communicate via the AC, and authors cannot submit another revision within the same round. For fairness to other authors, requests from R2 Major Revision papers to use the current round's revision phase were declined. When the revision deadline passes, email the reviewers and ACs explicitly with instructions and the decision deadline, even if the dates were announced earlier; some reviewers missed the R1 revision phase in 2026. Use HotCRP tags (e.g., `#r1-minor-revision`, `#r1-major-revision`, `#r1-revised`) to track revision outcomes for notification and statistics.

### Conflicts of Interest

The CfP requires authors to declare COI with: past advisors/advisees and mentored students, current institution colleagues (including recent moves), recent collaborators (typically past two years), and anyone with close personal relationships. Over-declaring to avoid review constitutes ethical misconduct! Make sure your HotCRP COI settings reflect these policies. Ask ACs to flag both **missing conflicts** and potentially **spurious conflicts** declared by authors, especially if they distort assignments. Have the RC chairs investigate such cases before taking action; a suspicious declaration is not itself proof of misconduct.

Papers for which one RC co-chair is conflicted are handled by the other co-chair. In 2026, RC co-chairs could submit revisions of earlier papers (but not new papers), handled by the other co-chair. This was considered reasonable since there are two co-chairs and all reviewing is double-anonymous.

### Appeals and Disputes

- **Appeals of decisions:** expect some authors to dispute rejections or meta-reviews. Look into genuine procedural errors, but be reluctant to overturn a decision after notification.
- **Authorship, plagiarism, and IP disputes**, and reports of errors in published papers, are not for the RC chairs to adjudicate. Consult the SC, and refer the people involved to [ACM's publications policy violation process](https://www.acm.org/publications/policies/publications-violation); SIGPLAN CARES may also be able to help.

### Artifact Evaluation

Artifact evaluation is not mandatory, but papers must explain the absence of artifacts if claims suggest they should exist. Only Accept and Minor Revision papers can submit artifacts. Artifact rejection does not affect paper acceptance.

### Open Access

Starting January 1, 2026, ACM has transitioned to 100% Open Access. Authors from ACM Open member institutions face no charges; others pay subsidized APCs ($250--$350 with ACM/SIG membership; $125--$175 from lower-middle-income countries). Be prepared for author questions about this.

## Logistics

### Communication

- Create a **custom email** for the chairs (e.g., oopsla26-chairs@googlegroups.com as used in 2026). Advertise it prominently in the CFP. When people email your personal addresses, ask them to use the chair email instead. This helps you stay organized and separate OOPSLA work from other work, especially during high-load periods like exams. Tell authors to allow 1--2 working days for a response.
- Set up **separate RC and AC mailing lists** early, in addition to the joint chairs address. Use the RC list for schedule and policy reminders, and the AC list for paper-management coordination; keep sensitive paper-specific discussions in appropriately access-controlled channels.
- Keep a **dated log of all emails sent to the RC, ACs, and authors** (e.g., HotCRP mail templates plus send dates).

### HotCRP

- We recommend having **"HotCRP chairs"** --- students who can help configure and run HotCRP across conferences. HotCRP is a complex system with little to no support, even in emergencies.
- As a starting point, ask the previous year's chairs to **export their HotCRP config** (Settings &gt; Advanced in HotCRP) so you can avoid their mistakes.
- For previous-year revisions, use the [resubmission procedure](#expertise-and-review-allocation) above. Verify in advance that old reviewers can be contacted and invited as external reviewers.
- Before bidding, ask RC members to verify **conflicts, email addresses, topic interests, and PC-member access** in HotCRP; inconsistent email accounts can hide the topic-interest controls. Verify TPMS profiles separately.
- Familiarize ACs with **tags**, including private per-user tags such as `~needs-nudge`, and with searches for `#R2` and `#resubmission`. In 2026, a structured form was useful for collecting reviewers' tentative-assignment concerns.
- The 2026 co-chairs found [HotCRP's API](https://hotcrp.com/devel/api/) (read-only) useful, also in combination with AI tools, for example for scripting routine monitoring and management tasks. This must of course be done in a way that protects confidentiality: **do not transmit confidential submissions, reviews, reviewer identities, or paper-specific discussions to external AI services**, and follow the current ACM and SIGPLAN policies.

### Talk Scheduling

- Past surveys on talk length (10, 15, 20, 25, 30 minutes) have produced mixed results. In 2021 (COVID), 15 minutes was most popular; in 2022 (in-person), people loved 30-minute slots.
- With ~150 accepted papers and 3 days, the options are roughly: 15-minute slots with 10-minute talks and 2 parallel sessions, or 3 parallel sessions with 20-minute slots and 15-minute talks.
- In 2026, there were about 180 papers to schedule (110 accepted plus 68 Minor Revisions as of late June), and the number of parallel tracks had to be discussed with the General Chair before all revision decisions were known. Fewer tracks with shorter talks is a reasonable option.
- FSE uses 9-minute talks; ICSE can be 5--7 minutes; NeurIPS uses posters. Going into workshop days is unpopular.
- Decide early, together with the General Chair, on the policies for attendance, remote talks, and recording. In 2026, authors were not required to register or present in person, there were no remote talks, and talks were not recorded (to save costs). Authors who could not attend (e.g., due to visa problems) were pointed to the SIGPLAN tracks at other SIGPLAN conferences, and to the possibility of making videos available via the researchr.org conference website.
- Keynotes in 2026 were 60-minute slots including questions. Consider a mix of senior and mid-career speakers, and invite them early (the 2026 invitations went out in the winter before the conference).
- **Run a post-conference survey every year.**
- Survey results from previous years can be found on the SPLASH Google Drive.

## Program Preparation, Conference, and Follow-up

The work does **not** end with reviewing or at the camera-ready deadline:

- **Before the conference:** Coordinate PACMPL issue preparation, including an editorial for **each** issue (one per round), create the program (including TOPLAS and SIGPLAN-track talks and keynotes), work with invited speakers, recruit session chairs and give them instructions, and prepare the award session presentation, the Town Hall, and a report for the SC meeting. Organize **Distinguished Paper Award nominations**: in 2026 the RC was invited to nominate accepted papers through a form. Arrange the selection process and publicity early.
- **Distinguished Reviewer Awards** were introduced in 2026 to recognize especially thoughtful, thorough, and constructive reviewing. ACs (not RC members) were asked to nominate reviewers from their piles with a short justification, and the chairs made the final selection. Prepare diplomas for both kinds of awards, and arrange for diplomas to be sent to winners who are not present.
- **Your own registration and travel:** agree with the General Chair early on whether the conference covers the RC chairs' registration, travel, and lodging. In 2026, this was only settled shortly before the conference.
- If SPLASH has a SIGPLAN track or similar, its talk proposals should not be reviewed by the OOPSLA RC chairs or RC, who have enough to do.
- **During the conference:** Make sure session chairs are present and run the chairs' presentation.
- **After the conference:** Conduct and summarize the participant survey, record lessons learned, and update these notes and the official SPLASH Google Drive materials.

## Enjoy!

Despite all the above, it is a ton of fun. You get the best bird's-eye view of what is happening in the area for that year, both inputs (paper titles, abstracts, and you might eyeball some papers) and outputs (reviewer opinions). You get to build a great pulse of the community.

Be proactive. There is a constant stream of work. Read reviews to the extent possible --- you may discover sloppy ACs in the process. By staying on top of things, you avoid crises. Because there are hard deadlines, crises can really blow up on you. See what papers are under-reviewed and which reviewers are under-reviewing. Send nudges and reminders.

Remember that OOPSLA is a journal. You are not a "PC Chair" --- you are helping to edit a journal issue. That means you have all the freedoms available to journal editors. Take advantage of it!

Relax. It will all work out in the end. Have fun.
