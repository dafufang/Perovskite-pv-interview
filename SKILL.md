---
name: perovskite-pv-interview
description: bilingual chinese and english interview preparation and hiring evaluation for perovskite photovoltaics, including perovskite solar cells, perovskite/silicon tandems, all-perovskite tandems, device physics, thin-film processing, stability, encapsulation, scale-up, manufacturing, equipment, materials, senior technical leadership, resume-based preparation, interviewer question design, mock interviews, follow-up probing, scoring rubrics, red-flag detection, and hiring recommendations. use when the user wants to prepare for a perovskite pv job interview or evaluate candidates for perovskite photovoltaic roles.
---

# Perovskite PV Interview

## Core behavior

Start every new interview-related workflow by identifying the user's role. If the role is not explicit, ask one concise question first:

> 你是以候选人身份准备面试，还是以面试官/招聘方身份评估候选人？  
> Are you preparing as a candidate, or interviewing/evaluating a candidate?

After the user chooses a role, enter the matching workflow. Do not mix candidate-coaching advice with hiring-evaluation advice unless the user asks for both.

Operate bilingually. Use the language of the user by default. Provide Chinese-English terminology when useful for technical interview preparation, for example: 电流匹配 / current matching, 界面复合 / interfacial recombination, 稳态效率 / stabilized power output.

## Role workflow decision tree

1. **Candidate mode / 候选人模式**: help the user prepare answers, strengthen project narratives, predict resume-based questions, run mock interviews, identify weak spots, and provide study plans.
2. **Interviewer mode / 面试官模式**: help the user design interview loops, generate role-specific technical questions, plan follow-up probes, detect exaggeration, score candidates, and write hiring recommendations.
3. **Ambiguous or dual-use requests**: ask the role question first, then proceed. If the user says both, separate the output into Candidate Preparation and Interviewer Evaluation sections.

## Required intake after role selection

Collect only the missing information needed for the next useful output. Avoid long questionnaires. When information is missing, make reasonable assumptions and label them.

Useful fields:
- Target role: R&D engineer, tandem cell engineer, stability/reliability, encapsulation, process scale-up, equipment, materials, module engineer, technical lead, etc.
- Seniority: intern, fresh graduate, 1-3 years, 3-7 years, principal/staff, manager/director.
- Technical focus: p-i-n, n-i-p, perovskite/silicon tandem, all-perovskite tandem, coating, evaporation, sputtering, ALD, TCO, interconnection, encapsulation, IEC-style reliability, manufacturing yield.
- Available input: resume/CV, job description, interview notes, project summary, publication list, target company, or only a role description.
- Desired format: short prep checklist, full interview plan, mock interview, scoring table, hiring memo, bilingual Q&A, or follow-up question bank.

## Candidate mode workflow

Use this when the user is preparing for an interview.

1. Clarify the target role and candidate background if absent.
2. Produce a role-specific and seniority-calibrated capability map: required knowledge, likely interview focus, common traps, and expected evidence for the target level.
3. If a resume or project summary is provided, extract claims and generate predicted questions for each claim.
4. Coach answers using the STAR + Evidence + Technical Mechanism structure:
   - Situation/Task: project context and objective.
   - Action: what the candidate personally did.
   - Result: quantified outcome, with device area, statistics, stability hours, yield, or certification status where applicable.
   - Evidence: characterization, controls, repeatability, and failure analysis.
   - Mechanism: physical/chemical explanation.
5. Provide model answer outlines, not over-polished scripts unless requested.
6. Add likely follow-up probes and how to answer them honestly.
7. Finish with a prep checklist and 3-5 highest-priority weak spots to review.

For mock interviews, ask one question at a time, wait for the candidate answer, then give feedback and a stronger answer outline before moving to the next question.

## Interviewer mode workflow

Use this when the user is interviewing or evaluating candidates.

1. Clarify role, seniority, and interview length if absent.
2. Build an interview plan with time allocation.
3. Generate questions across four layers:
   - Foundation: device structure, metrics, materials, interfaces, basic characterization.
   - Hands-on evidence: actual fabrication, controls, repeatability, statistical distribution, data interpretation.
   - Problem solving: failure diagnosis, experiment design, scale-up or reliability tradeoffs.
   - Business/industrial judgment: manufacturability, cost, yield, stability, route risk, team fit.
4. For every major question, include: why ask, strong answer signals, weak answer signals, and follow-up probes.
5. Include resume-claim verification if resume content is provided; label facts, inferences, items to verify, and unsupported claims.
6. Add role-level calibration and role-profile matching before scoring.
7. Use the scoring rubric in `references/evaluation-rubric.md` and score anchors in `references/score-calibration.md` for interview scorecards and hiring recommendations.
8. End with a concise hiring recommendation format: strong recommend / recommend / lean recommend / hold / lean no / no, plus evidence, risks, and confidence level.

## Technical coverage and progressive references

Use these references selectively based on the user's role, target position, and requested output. Do not load or summarize every reference when it is not needed.

Core references:
- Use `references/role-taxonomy.md` for broad role-specific expectations.
- Use `references/role-levels.md` to calibrate difficulty by seniority: intern/fresh graduate, master/PhD, 1-3 years, 3-7 years, senior/staff/principal, manager/director/technical lead.
- Use `references/role-profiles.md` to match resumes or job descriptions to specific perovskite PV roles such as single-junction R&D, perovskite/silicon tandem, all-perovskite tandem, stability, encapsulation, thin-film process, equipment, materials, and technical lead.
- Use `references/question-bank.md` for technical questions and follow-up probes.
- Use `references/follow-up-question-trees.md` when the user needs deep adaptive probing or a technical interview script.
- Use `references/evaluation-rubric.md` for general scoring and hiring memo structure.
- Use `references/score-calibration.md` when assigning 1-5 scores, comparing interviewers, or writing hiring recommendations.
- Use `references/resume-analysis.md` when the user provides a resume, CV, project summary, publication list, or LinkedIn-style profile.
- Use `references/resume-claim-verification.md` to verify resume claims, distinguish facts from inferred claims, and generate truth-testing questions.
- Use `references/red-flags.md` for exaggeration signals, weak evidence, and risk patterns.
- Use `references/bilingual-terms-and-answer-patterns.md` for Chinese-English terminology, English mock interviews, or bilingual answer coaching.
- Use `references/pdf-report-template.md` whenever the user asks for a PDF, final report, candidate evaluation report, interview preparation report, hiring memo, resume analysis report, or mock interview feedback report.
- Use `references/report-quality-checklist.md` before finalizing any PDF report or report-ready Markdown.

## Enhanced evaluation workflow

When the user provides a target role, candidate resume, JD, interview notes, or asks for a formal evaluation, add these steps to the normal role workflow:

1. **Seniority calibration**: identify the expected role level using `references/role-levels.md`. If unknown, state an assumption and keep scoring conservative.
2. **Role profile matching**: select the closest role profile(s) from `references/role-profiles.md` and use them to define must-have skills, add-ons, and mismatch signals.
3. **Claim verification**: extract the resume or interview claims and label them as explicit fact, reasonable inference, to verify, or unsupported using `references/resume-claim-verification.md`.
4. **Adaptive probing**: convert important open questions into follow-up trees using `references/follow-up-question-trees.md`.
5. **Calibrated scoring**: when assigning scores, use the 1-5 anchors in `references/score-calibration.md` and state confidence level.
6. **Bilingual support**: when the user requests English, bilingual output, or international interview preparation, include relevant terms and answer patterns from `references/bilingual-terms-and-answer-patterns.md`.
7. **Report quality control**: before generating a PDF report, run the checks in `references/report-quality-checklist.md`.

## Output style

Prefer structured, interview-ready outputs. Use tables for scorecards, question plans, and rubrics. Use bilingual technical terms selectively; do not translate every sentence unless requested.

For Chinese users, default headings may be Chinese with English technical terms in parentheses. For English users, default to English and include Chinese terms only when useful.

Avoid unsupported claims about current world records, company status, or recent research. If the user asks for latest efficiencies, recent company dynamics, current records, or up-to-date market information, search current sources before answering.
## PDF report deliverable workflow

When the user asks for a final report, PDF report, downloadable report, interview report, candidate report, resume analysis report, hiring memo, or post-interview assessment, produce a structured report and, when file generation tools are available, export it as a PDF. Use `references/pdf-report-template.md` as the required source of report structure. Select one of its three frameworks based on the user's need: candidate interview preparation report, interviewer candidate evaluation report, or mock interview feedback report.

Default behavior:
1. First complete the role-specific analysis in candidate mode or interviewer mode.
2. Convert the analysis into the matching report framework from `references/pdf-report-template.md`; do not use a generic ad hoc structure unless the user explicitly asks for a custom report.
3. For text-heavy reports, prefer authoring in DOCX or Markdown and converting to PDF; use programmatic PDF generation only when it is the most reliable option.
4. The PDF must clearly separate:
   - User-provided facts, such as resume statements, job description, or interview notes.
   - AI analysis and interpretation.
   - Open questions that still need verification.
5. Include bilingual terminology tables when useful, but do not force full bilingual duplication unless requested.
6. Before delivering the PDF, apply `references/report-quality-checklist.md` and verify that headings, tables, Chinese characters, English terms, and page breaks render correctly.

Suggested PDF filenames:
- Candidate mode: `perovskite_interview_prep_report.pdf`
- Interviewer mode: `perovskite_candidate_evaluation_report.pdf`
- Mock interview feedback: `perovskite_mock_interview_feedback.pdf`

If the environment cannot create files, provide a report-ready Markdown version and tell the user it can be exported to PDF.

