# PDF Report Templates

Use this reference whenever the user asks for a downloadable PDF report, final report, interview report, candidate evaluation report, hiring memo, resume analysis report, or mock interview feedback report.

## Report selection rule

Choose one of the following three report frameworks based on the user's need. Do not invent a completely different report structure unless the user explicitly requests a custom format.

1. **Candidate interview preparation report**: use when the user is a candidate preparing for an interview, asks for resume-based preparation, wants predicted questions, or wants a prep plan.
2. **Interviewer candidate evaluation report**: use when the user is an interviewer, hiring manager, recruiter, or company evaluator assessing a candidate or designing an interview loop.
3. **Mock interview feedback report**: use after a mock interview or when the user asks for feedback on answers, performance, communication, or readiness.

If the user asks for multiple outputs, create separate sections or separate PDF files using the relevant frameworks. If the role is unclear, ask the role question before producing the report.

## General report rules

- Use the user's language by default; support Chinese, English, or bilingual output.
- Keep the report professional, evidence-based, and interview-ready.
- Separate facts from inference. Do not present inferred ability as confirmed evidence.
- Include a clear note when information is missing, extracted incompletely, or needs verification.
- Use tables for scorecards, question plans, risk summaries, resume extraction, and terminology lists.
- Include concise executive summaries so the report is useful to hiring managers or candidates.
- When generating the PDF, verify that headings, tables, Chinese characters, English terms, and page breaks render correctly.
- For text-heavy reports, prefer creating a structured document or Markdown first, then converting to PDF.
- Do not fabricate resume facts, metrics, publications, certifications, stability results, or candidate ownership.


## Required enhanced modules

When relevant to the user's request, integrate these modules into the selected report framework instead of adding an unrelated generic section:

- **Seniority calibration / 职级校准**: state the expected level and evaluate whether the evidence matches that level. Use `role-levels.md`.
- **Role profile matching / 岗位画像匹配**: map the candidate or preparation plan to the closest role profile(s). Use `role-profiles.md`.
- **Resume claim verification / 简历主张真实性验证**: identify high-impact claims and label them as explicit fact, reasonable inference, to verify, or unsupported. Use `resume-claim-verification.md`.
- **Follow-up question trees / 追问树**: for critical topics, provide layered probes rather than a flat list. Use `follow-up-question-trees.md`.
- **Calibrated scoring / 校准评分**: when a score is requested, use 1-5 anchors and state confidence level. Use `score-calibration.md`.
- **Bilingual terminology and answer patterns / 中英术语与回答模板**: include only when useful for candidate preparation, English interviews, or bilingual reports. Use `bilingual-terms-and-answer-patterns.md`.
- **Report quality checklist / 报告质量检查**: before final output, apply `report-quality-checklist.md`.

## Recommended one-page summary

For formal PDF reports, place a one-page summary near the beginning when the report is longer than 5 pages.

For interviewer evaluation reports, include:

| Field | Content |
|---|---|
| Target role / 目标岗位 | Role and seniority |
| Recommendation / 推荐结论 | Strong recommend / recommend / lean recommend / hold / lean no / no |
| Confidence / 置信度 | High / medium / low |
| Biggest strengths / 最大亮点 | 2-3 evidence-based bullets |
| Biggest risks / 最大风险 | 2-3 unresolved or role-critical risks |
| Must-verify questions / 必须验证的问题 | 3-5 decisive follow-up questions |
| Suggested next step / 下一步建议 | Next interview, technical assignment, reference check, or stop |

For candidate preparation reports, include:

| Field | Content |
|---|---|
| Target role / 目标岗位 | Role and seniority |
| Readiness / 准备度 | Ready / almost ready / targeted preparation needed / substantial preparation needed |
| Strongest selling points / 最强卖点 | 2-3 credible strengths |
| Highest-risk questions / 最高风险问题 | 3-5 likely difficult questions |
| Must-prepare evidence / 必须准备的证据 | Device area, statistics, stability protocol, personal contribution, figures, papers, etc. |
| 72-hour action plan / 72 小时行动计划 | Highest-priority review and practice tasks |

## Required evidence separation

Every PDF report must clearly distinguish these three categories:

1. **User-provided facts / 用户提供的事实**
   - Resume, CV, job description, project notes, interview notes, or user statements explicitly provided.
2. **AI analysis / AI 分析判断**
   - Role fit, capability assessment, risk judgment, recommended preparation priorities, or hiring recommendation based on the provided facts.
3. **Items to verify / 需要进一步确认的问题**
   - Missing or ambiguous information that should be confirmed in interview, follow-up, reference check, or technical assignment.

A compact evidence-status table is recommended near the beginning of each report.

---

# Framework 1: Candidate Interview Preparation Report

Use this framework when the user is preparing as a candidate.

Suggested filename: `perovskite_interview_prep_report.pdf`

## Title

**Perovskite PV Interview Preparation Report**  
**钙钛矿光伏面试准备报告**

## 1. Executive Summary / 摘要

Include:
- Target role / 目标岗位
- Candidate background overview / 候选人背景概览
- Interview preparation focus / 面试准备重点
- Main strengths / 主要优势
- Main risks or weak spots / 主要风险或短板
- Highest-priority preparation actions / 最优先准备动作

## 2. Candidate Profile / 候选人画像

Include when available:
- Education background / 教育背景
- Research or work direction / 研究或工作方向
- Project experience / 项目经历
- Publications, patents, awards / 论文、专利、奖项
- Equipment, process, and characterization skills / 设备、工艺、表征技能
- Match to target role / 与目标岗位的匹配度

If based on an uploaded resume, state which details came directly from the resume and which are inferred.

## 3. Seniority and Role Profile Match / 职级与岗位画像匹配

Include:
- Expected seniority level / 目标职级
- Matching role profile / 匹配岗位画像
- Must-have capabilities for that level / 该职级必备能力
- Evidence already visible in resume / 简历中已体现的证据
- Gaps to prepare for / 需要补足的缺口

## 4. Target Role Analysis / 目标岗位分析

Include:
- Core capability requirements / 岗位核心能力要求
- Must-have technical skills / 必备技术能力
- Nice-to-have skills / 加分能力
- Likely interview focus areas / 可能被重点考察的方向
- Seniority expectations / 对应职级要求

Adapt this section to the role: perovskite single-junction, perovskite/silicon tandem, all-perovskite tandem, stability, encapsulation, process scale-up, equipment, materials, or technical lead.

## 5. Resume-Based Interview Question Forecast / 基于简历的面试问题预测

Use a table with columns such as:

| Resume evidence / 简历依据 | Likely question / 可能问题 | Follow-up probes / 追问 | What to prepare / 准备要点 |
|---|---|---|---|

Cover:
- Questions for each project experience / 针对每段项目经历的问题
- Questions for publications or patents / 针对论文或专利的问题
- Experimental detail questions / 针对实验细节的问题
- Personal contribution questions / 针对个人贡献的问题
- Stability, scale-up, encapsulation, tandem, or manufacturing questions when relevant / 针对稳定性、放大、封装、叠层、量产等方向的问题

## 6. Technical Deep-Dive Topics / 技术深挖主题

Select relevant topics rather than listing everything mechanically:
- Perovskite device structure / 钙钛矿器件结构
- p-i-n and n-i-p architectures
- Interface engineering / 界面工程
- Defect passivation / 缺陷钝化
- Thin-film crystallization / 薄膜结晶
- Characterization and data interpretation / 表征与数据分析
- Stability and reliability / 稳定性与可靠性
- Encapsulation and modules / 封装与组件
- Perovskite/silicon tandem / 钙钛矿/晶硅叠层
- All-perovskite tandem / 全钙钛矿叠层
- Scale-up and manufacturing / 量产与放大

For each selected topic, include likely questions, expected depth, and common traps.

## 7. Suggested Answer Frameworks / 答题框架

Include:
- Project experience answer framework / 项目经历回答框架
- Technical question answer framework / 技术问题回答框架
- Failure case answer framework / 失败案例回答框架
- Personal contribution statement / 个人贡献说明框架
- English answer guidance if relevant / 英文回答建议

Recommended answer structure:

**Problem → Method → Evidence → Result → Mechanism → Personal Contribution → Limitation / Next Step**

Also support STAR + Evidence + Mechanism:
- Situation/Task
- Action
- Result
- Evidence
- Mechanism
- Personal ownership

## 8. Weakness and Risk Areas / 薄弱点与风险点

Include:
- Capabilities not sufficiently shown in the resume / 简历中未充分体现的能力
- Topics likely to be asked but underprepared / 可能被追问但准备不足的内容
- Phrases that may be challenged / 容易被质疑的表述
- Missing data to prepare / 需要补充准备的数据
- Suggested knowledge review areas / 建议补充复习的知识点

Encourage honest framing. Do not help the candidate fabricate experience.

## 9. Practice Questions / 练习问题

Include:
- Basic questions / 基础问题
- Intermediate questions / 中级问题
- Advanced questions / 高级问题
- Scenario or experimental design questions / 情景题或实验设计题
- English mock interview questions when relevant / 英文模拟面试问题

Rank questions by probability or importance when possible.

## 10. Preparation Checklist / 面试前准备清单

Include:
- Must-review technical points / 必须复习的技术点
- Data and numbers to prepare / 必须准备的数据
- Figures, papers, or project examples to prepare / 建议准备的图表、论文或案例
- Personal contribution boundaries / 必须讲清楚的个人贡献
- Questions to ask the interviewer / 可以反问面试官的问题
- Final 24-hour checklist if useful / 面试前 24 小时清单

## 12. Appendix / 附录

Optional appendices:
- Chinese-English terminology table / 中英术语表
- Technical keyword table / 技术关键词表
- Recommended follow-up question list / 推荐追问清单
- Resume extraction table / 简历信息提取表
- Full practice question bank / 完整练习题库

---

# Framework 2: Interviewer Candidate Evaluation Report

Use this framework when the user is evaluating or interviewing a candidate.

Suggested filename: `perovskite_candidate_evaluation_report.pdf`

## Title

**Perovskite PV Candidate Evaluation Report**  
**钙钛矿光伏候选人评估报告**

## 1. Executive Summary / 摘要

Include:
- Overall candidate judgment / 候选人整体判断
- Target role / 目标岗位
- Recommendation conclusion / 推荐结论
- Main strengths / 主要优势
- Main risks / 主要风险
- Whether to proceed to next round / 是否建议进入下一轮
- Confidence level / 判断置信度

Use one of these recommendation labels unless the user provides another scale:
- Strong recommend / 强烈推荐
- Recommend / 推荐
- Lean recommend / 谨慎推荐
- Hold / 暂缓判断
- Lean no / 倾向不推荐
- No / 不推荐

## 2. One-Page Hiring Summary / 一页版录用摘要

For formal hiring reports, include a compact decision page:

| Field / 字段 | Content / 内容 |
|---|---|
| Target role and level / 目标岗位与职级 | |
| Recommendation / 推荐结论 | |
| Confidence / 置信度 | |
| Top strengths / 主要优势 | |
| Top risks / 主要风险 | |
| Must-verify questions / 必须验证问题 | |
| Suggested next step / 下一步建议 | |

## 3. Candidate Background Summary / 候选人背景摘要

Include:
- Education and work experience / 教育与工作经历
- Core project experience / 核心项目经历
- Technical direction / 技术方向
- Publications, patents, outcomes / 论文、专利、成果
- Key skill tags / 关键技能标签
- Evidence source / 信息来源

Do not overstate unverified claims. Mark claimed achievements as claims unless validated.

## 4. Role Fit Assessment / 岗位匹配度评估

Include:
- Fit to target role / 与目标岗位的匹配程度
- Capabilities already shown / 已体现能力
- Capabilities not sufficiently shown / 未充分体现能力
- Capabilities that must be verified in interview / 需要面试验证的能力
- Likely level or seniority fit / 可能匹配职级

Use a table where useful:

| Requirement / 要求 | Evidence / 证据 | Gap / 缺口 | Verification question / 验证问题 |
|---|---|---|---|

## 5. Technical Competency Evaluation / 技术能力评估

Evaluate only categories relevant to the role:
- Device physics understanding / 器件物理理解
- Thin-film fabrication and process capability / 薄膜制备与工艺能力
- Interface engineering and defect control / 界面工程与缺陷控制
- Characterization and data analysis / 表征与数据分析能力
- Stability and reliability awareness / 稳定性与可靠性意识
- Tandem cell understanding / 叠层电池理解
- Scale-up and manufacturing judgment / 放大与量产意识
- Encapsulation and module experience / 封装与组件经验
- Equipment/process integration / 设备与工艺集成
- Technical leadership / 技术领导力

For each category, include evidence, concern, and interview validation plan.

## 6. Resume-Based Probing Questions / 基于简历的追问问题

Use a table with:

| Resume claim / 简历表述 | Why it matters / 为什么重要 | Primary question / 主问题 | Follow-up probes / 追问 | Strong answer signal / 强回答信号 | Red flag / 红旗 |
|---|---|---|---|---|---|

Cover:
- Project authenticity verification / 项目真实性验证问题
- Personal contribution verification / 个人贡献验证问题
- Data reliability verification / 数据可靠性验证问题
- Technical route selection / 技术路线选择问题
- Failure diagnosis and troubleshooting / 失败案例与问题诊断问题

## 7. Resume Claim Verification / 简历主张真实性验证

Use this section when a resume, CV, project list, publication list, or interview note contains concrete claims. Include:

| Claim / 简历主张 | Evidence status / 证据状态 | Verification question / 验证问题 | Strong evidence / 强证据 | Red flag / 红旗 |
|---|---|---|---|---|

Evidence status must use: explicit fact, reasonable inference, to verify, or unsupported.

## 8. Suggested Interview Plan / 建议面试流程

Provide a 30-, 45-, or 60-minute plan depending on the user's request. If no length is specified, provide a 45-minute default.

Example structure:
- 5 min: background and project overview / 背景与项目概述
- 10-15 min: resume-based technical deep dive / 基于简历的技术深挖
- 10-15 min: problem-solving or experiment design / 问题诊断或实验设计
- 5-10 min: scale-up, reliability, and industrial judgment / 放大、可靠性与产业化判断
- 5 min: candidate questions and close / 候选人提问与收尾

For each stage, include objective, sample questions, and evaluation focus.

## 9. Scoring Rubric / 评分表

Use a 1-5 scale unless the user requests another scale.

Recommended dimensions:
- Foundation theory / 基础理论
- Experimental ability / 实验能力
- Problem diagnosis / 问题诊断
- Process scale-up / 工艺放大
- Stability awareness / 稳定性意识
- Industrial judgment / 产业化判断
- Communication and attribution / 沟通与归因
- Role-specific capability / 岗位特定能力
- Overall score / 综合评分

Recommended columns:

| Dimension / 维度 | Score / 分数 | Evidence / 证据 | Concern / 风险 | Follow-up needed / 后续验证 |
|---|---:|---|---|---|

## 10. Red Flags / 红旗信号

Include only relevant red flags and mark them as probes unless confirmed:
- Talks only about champion efficiency and not statistical distribution / 只讲 champion efficiency，不讲统计数据
- Does not distinguish small-area cells from large-area modules / 不区分小面积器件与大面积组件
- Does not distinguish J-V scan efficiency from stabilized output / 不区分 J-V 扫描效率与稳态输出
- Vague stability test conditions / 稳定性测试条件含糊
- Unclear personal vs team contribution / 个人贡献与团队贡献不清
- Vague tandem experience / 叠层经验表述不具体
- Cannot discuss EQE current integration or current matching / 讲不清 EQE 积分电流或电流匹配
- Lacks failure analysis / 缺少失败实验复盘能力

## 11. Hiring Recommendation / 录用建议

Include:
- Decision / 结论
- Suggested role direction / 推荐岗位方向
- Suggested level / 建议职级
- Onboarding risks / 入职后可能需要补强的能力
- Next-round interview suggestions / 下一轮面试建议
- Optional technical assignment / 可选技术作业
- Final rationale / 最终理由

The recommendation must be evidence-based and tied back to resume/interview facts.

## 11. Appendix / 附录

Optional appendices:
- Full interview question list / 面试问题清单
- Detailed scoring criteria / 评分细则
- Technical terminology table / 技术术语表
- Resume extraction table / 简历信息提取表
- Interview notes / 面试记录
- Follow-up question bank / 追问题库

---

# Framework 3: Mock Interview Feedback Report

Use this framework after a mock interview or when evaluating the user's interview answers.

Suggested filename: `perovskite_mock_interview_feedback.pdf`

## Title

**Perovskite PV Mock Interview Feedback Report**  
**钙钛矿光伏模拟面试反馈报告**

## 1. Executive Summary / 摘要

Include:
- Mock interview role / 模拟面试岗位
- Overall performance / 总体表现
- Recommended improvement direction / 推荐提升方向
- Main strengths / 主要优势
- Main weaknesses / 主要短板
- Readiness rating / 准备度评级

Use a clear readiness rating:
- Ready / 已准备好
- Almost ready / 基本准备好
- Needs targeted preparation / 需要针对性准备
- Needs substantial preparation / 需要系统准备

## 2. Interview Context / 面试背景

Include:
- Target role / 目标岗位
- Interview language / 面试语言
- Difficulty level / 面试难度
- Technical focus / 重点技术方向
- Types of questions covered / 本次模拟覆盖的问题类型
- Number of questions or session length / 问题数量或时长

## 3. Question-by-Question Feedback / 逐题反馈

Use a table or repeated subsections:

| Question / 问题 | Answer summary / 回答摘要 | Strengths / 优点 | Gaps / 不足 | Improved answer outline / 优化回答框架 | Follow-up risk / 可能追问 |
|---|---|---|---|---|---|

For each question, include:
- Original question / 原问题
- Candidate answer summary / 候选人回答摘要
- Strengths / 回答优点
- Gaps / 回答不足
- Improved answer outline / 建议优化回答
- Potential follow-up probes / 可被继续追问的点

## 4. Technical Accuracy Review / 技术准确性检查

Assess:
- Concept accuracy / 概念是否准确
- Logic completeness / 逻辑是否完整
- Data clarity / 数据表达是否清楚
- Evidence quality / 证据是否充分
- Personal contribution clarity / 是否体现个人贡献
- Mechanism explanation / 是否能解释机制与证据
- Limits and uncertainty / 是否能诚实说明限制

Mark unknowns if the answer did not provide enough information.

## 5. Communication Assessment / 表达能力评估

Assess:
- Structure clarity / 结构清晰度
- English expression if applicable / 英文表达能力，如适用
- Technical narrative depth / 技术叙述深度
- Interviewer friendliness / 面试官友好度
- Conciseness / 简洁度
- Whether answers are too generic / 回答是否过于泛泛

## 6. Competency Scorecard / 能力评分卡

Use a 1-5 scale unless otherwise requested.

Recommended dimensions:
- Professional foundation / 专业基础
- Project storytelling / 项目表达
- Technical depth / 技术深度
- Problem diagnosis / 问题诊断
- Industrial understanding / 产业化理解
- Interview communication / 面试沟通
- Evidence and ownership / 证据与个人贡献
- Overall readiness / 综合准备度

Recommended columns:

| Dimension / 维度 | Score / 分数 | Evidence / 证据 | Improvement action / 提升动作 |
|---|---:|---|---|

## 7. Improved Answer Examples / 优化回答示例

Include when enough user answer content is available:
- Chinese improved version / 中文优化版
- English improved version when relevant / 英文优化版，如需要
- STAR or Problem-Method-Result-Contribution version / STAR 或“问题-方法-结果-贡献”框架版

Avoid inventing facts. Use placeholders such as `[insert device area]`, `[insert stability condition]`, or `[insert personal contribution]` where the candidate needs to supply real data.

## 8. Follow-Up Practice Plan / 后续练习计划

Include:
- Next 3 days review focus / 接下来 3 天复习重点
- Next 1 week practice focus / 接下来 1 周练习重点
- Data, figures, or examples to prepare / 需要补充准备的数据、图表或案例
- Recommended next mock interview questions / 推荐继续 mock 的问题
- Priority drills / 优先练习动作

## 9. Appendix / 附录

Optional appendices:
- Full mock interview question list / 本次模拟问题列表
- Technical terminology table / 术语表
- High-frequency follow-up probes / 高频追问问题
- Original user answers if the user wants them included / 原始回答记录
- Scoring details / 评分细则

---

# Filename selection

Use these default filenames unless the user specifies a filename:

- Candidate preparation: `perovskite_interview_prep_report.pdf`
- Interviewer evaluation: `perovskite_candidate_evaluation_report.pdf`
- Mock interview feedback: `perovskite_mock_interview_feedback.pdf`

# Quality checklist before delivery

Before delivering the PDF or report-ready Markdown, verify:

- The selected framework matches the user's role and request.
- The report includes an executive summary.
- User-provided facts, AI analysis, and items to verify are separated.
- The report avoids unsupported claims and does not fabricate resume facts.
- Tables are readable and not overly wide.
- Chinese and English text render correctly.
- The filename matches the report type.
- Seniority calibration and role-profile matching are included when role fit or hiring evaluation is requested.
- Resume claims are labeled as explicit facts, reasonable inferences, items to verify, or unsupported claims.
- 1-5 scores use calibrated anchors and include confidence level.
- Critical technical questions include follow-up trees when depth matters.
