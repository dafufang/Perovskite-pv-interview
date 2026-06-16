# Resume and project analysis

When the user provides a resume, CV, publication list, or project summary, extract claims and convert them into interview probes.

## Candidate mode

For each project, produce:
- What the interviewer will likely notice.
- Likely technical questions.
- Likely ownership questions.
- How to answer with STAR + Evidence + Mechanism.
- Weak points to prepare honestly.

Coach the candidate to state:
- Device architecture and area.
- Baseline and improved performance with which metric changed.
- Number of devices/batches and distribution, if available.
- Stability conditions and duration, if claimed.
- Characterization evidence and controls.
- Personal contribution versus team contribution.

## Interviewer mode

For each resume claim, produce:
- Claim to verify.
- Why it matters.
- Primary question.
- Follow-up probes.
- Strong evidence.
- Red-flag answer.

## Common claim probes

Claim: "improved PCE to X%"
- Ask: What area? certified or internal? scan direction/rate? stabilized output? EQE integrated current? distribution across devices?

Claim: "developed passivation/additive strategy"
- Ask: What mechanism? What control molecule/material? What characterization proves defect reduction or interface change? Any stability side effect?

Claim: "worked on tandem cells"
- Ask: 2T or 4T? current-limiting subcell? recombination/contact layer? TCO damage mitigation? EQE current balance?

Claim: "scaled process to large area"
- Ask: area, uniformity, yield, coating method, drying/annealing window, inline QC, batch variation, failure Pareto.

Claim: "led a team/project"
- Ask: team size, decision rights, roadmap, go/no-go criteria, budget/equipment constraints, failed route and lessons.

## Uploaded resume/CV attachment workflow

Use this workflow whenever the resume arrives as an uploaded file rather than pasted text.

1. Read the attachment and extract only visible/resolved content. Preserve uncertainty if text extraction is partial.
2. Normalize the resume into a structured profile:
   - Basic profile: degree, years, employers/labs, role titles, publications/patents if listed.
   - Domain map: perovskite single-junction, perovskite/silicon tandem, all-perovskite tandem, module, stability, encapsulation, manufacturing, equipment, materials, simulation, or characterization.
   - Evidence table: claim, metric/result, device area or scale, method, characterization evidence, stability/reliability evidence, personal ownership, missing proof.
3. Identify the candidate's likely level: junior, independent contributor, senior engineer/scientist, staff/principal, manager/technical lead. Mark this as an inference if not explicit.
4. Generate the next artifact requested by the user:
   - Candidate preparation: predicted questions, answer skeletons, missing-data checklist, and mock interview sequence.
   - Interviewer evaluation: interview plan, claim-verification probes, role-fit concerns, scorecard, and hiring recommendation template.
5. When both role and target job are missing, ask the role question first and assume a general perovskite PV technical role only for the initial digest.

## Resume digest template

Use this concise template before deeper analysis:

| Section | Findings | Evidence from resume | Gaps / questions |
|---|---|---|---|
| Candidate snapshot |  |  |  |
| Core technical domains |  |  |  |
| Major projects |  |  |  |
| Claimed outcomes |  |  |  |
| Methods and tools |  |  |  |
| Publications / patents |  |  |  |
| Scale-up / reliability exposure |  |  |  |
| Ownership signals |  |  |  |

## Candidate preparation output from resume

After the digest, produce:
- Top 8-12 likely questions ranked by probability.
- For each major project, a 60-90 second answer outline using STAR + Evidence + Mechanism.
- A missing-information checklist the candidate should prepare before interview.
- 3-5 technical weak spots to review based on resume gaps.
- Optional English interview version if the user asks for English or bilingual preparation.

## Interviewer evaluation output from resume

After the digest, produce:
- Resume-claim verification map: claim, primary question, follow-up probes, strong answer, red flag.
- 30/45/60 minute interview plan depending on requested interview length.
- Role-fit analysis against the target job.
- Scorecard focus areas with weights adjusted to role and seniority.
- Final debrief template: hire recommendation, evidence, risks, and next-round questions.

## Attachment-specific caution

For resumes, avoid over-weighting polished wording. Prioritize evidence of direct ownership, quantitative results, controls, repeatability, and ability to explain mechanism. For publication-heavy candidates, distinguish first-author contribution, corresponding/team contribution, and hands-on process ownership. For industry candidates, distinguish line responsibility from participation in cross-functional projects.
