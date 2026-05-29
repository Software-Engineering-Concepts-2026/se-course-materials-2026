# รายวิชา: Software Engineering Concepts

## คำอธิบายรายวิชา
รายวิชานี้ออกแบบสำหรับนักศึกษาวิทยาการคอมพิวเตอร์ชั้นปีที่ 3 โดยมุ่งพัฒนาความสามารถในการสร้างซอฟต์แวร์อย่างเป็นระบบตั้งแต่การเก็บความต้องการ การออกแบบ การพัฒนา การทดสอบ การประกันคุณภาพ ความปลอดภัย การบำรุงรักษา และการส่งมอบระบบ โดยใช้โครงงานทีมเป็นแกนกลางของการเรียนรู้ตลอดภาคการศึกษา [file:9][file:12] แนวทางของรายวิชานี้สอดคล้องกับลำดับหัวข้อหลักของวิศวกรรมซอฟต์แวร์ ได้แก่ SDLC, requirements, modeling, architecture, construction, testing, quality assurance, maintenance, project management และ teamwork ตามเอกสารประกอบรายวิชาที่แนบมา [file:5][file:9][file:12]

รายวิชายังบูรณาการการใช้ Generative AI หรือ LLMs เข้าไปในทุกช่วงของวงจรการพัฒนาซอฟต์แวร์ โดยยึดหลักว่า AI เป็นเครื่องมือช่วยเพิ่มผลิตภาพ ไม่ใช่ผู้แทนที่การตัดสินใจเชิงวิศวกรรมของมนุษย์ [file:5][file:12] นักศึกษาจะได้ฝึกเปลี่ยนจากการใช้ AI เพื่อ “ช่วยเขียนโค้ด” แบบไม่มีทิศทาง ไปสู่การใช้ AI ภายใต้ข้อกำหนด กระบวนการ และหลักฐานตรวจสอบได้ หรือที่สรุปเป็นแนวคิด Vibe Engineering [file:12][file:17]

## เป้าหมายรายวิชา
เมื่อสิ้นสุดรายวิชา นักศึกษาควรสามารถวิเคราะห์ปัญหาและพัฒนาซอฟต์แวร์ด้วยกระบวนการทางวิศวกรรมที่เป็นระบบ พร้อมทั้งใช้ LLMs อย่างรับผิดชอบในการสนับสนุนงานด้าน requirements, design, implementation, testing, review และ deployment โดยยังคงให้มนุษย์เป็นผู้ตรวจสอบและรับผิดชอบผลลัพธ์สุดท้าย [file:9][file:12][file:17]

## Learning Outcomes (CLOs)

| CLO | คำอธิบายผลลัพธ์การเรียนรู้ |
|---|---|
| CLO1 | อธิบายหลักการสำคัญของ SDLC, software process models, agile practices, และบทบาทของ artefacts ในวิศวกรรมซอฟต์แวร์ได้ [file:5][file:9] |
| CLO2 | เก็บ ร่าง และตรวจสอบ software requirements ได้ ทั้งในรูป SRS, user stories, use cases และ acceptance criteria [file:1][file:9] |
| CLO3 | ออกแบบระบบในระดับ architecture และ detailed design โดยอธิบาย trade-offs และเหตุผลเชิงวิศวกรรมได้ [file:9][file:12] |
| CLO4 | พัฒนาซอฟต์แวร์แบบทำงานเป็นทีมโดยใช้ coding standards, version control, code review และ collaborative workflow ได้ [file:5][file:12] |
| CLO5 | สร้างและประยุกต์ใช้ unit tests, integration tests, static analysis และ quality gates เพื่อยกระดับคุณภาพซอฟต์แวร์ได้ [file:5][file:9][file:12] |
| CLO6 | ประยุกต์ใช้แนวคิด secure coding, security requirements, maintenance, refactoring และ CI/CD เบื้องต้นกับโครงงานจริงได้ [file:9][file:12] |
| CLO7 | ใช้ Prompt Engineering และ LLMs อย่างมีจริยธรรม โปร่งใส และตรวจสอบได้ภายใต้ AI policy ของรายวิชาและของทีม [file:5][file:12][file:17] |

## โครงสร้างการเรียนรู้รายสัปดาห์

| Week | Lecture focus (2 ชม.) | Lab focus (2 ชม.) | Deliverables / Notes |
|---|---|---|---|
| 1 | ภาพรวมวิศวกรรมซอฟต์แวร์ยุค AI, ความต่างระหว่าง programming กับ software engineering, SDLC, บทบาททีม, แนวคิด Vibe Engineering [file:5][file:9][file:12] | ตั้งทีม, เลือกโจทย์, ระบุผู้ใช้และปัญหา, ร่าง project vision ด้วยการช่วยของ LLM แล้วตรวจความสมเหตุสมผล [file:5][file:12] | Project brief, team charter, initial AI usage agreement |
| 2 | Prompt Engineering fundamentals: Five S’s, single-prompt, multi-prompt, prompt chaining, role prompting, context engineering, executable specifications [file:5][file:17] | ฝึกออกแบบ prompt สำหรับ requirement drafting, story decomposition, และ ambiguity checking [file:1][file:17] | Prompt library v1, prompt style guide |
| 3 | AI policy สำหรับรายวิชา: สิ่งที่อนุญาต/ไม่อนุญาต, human-in-the-loop, disclosure, privacy, IP, academic integrity, quality gate ก่อนส่งงาน [file:5][file:12][file:17] | สร้าง Team AI Policy และ template บันทึก prompt/response/review ของทีม [file:12][file:17] | Team AI policy, AI usage log template |
| 4 | Requirements engineering: elicitation, stakeholder analysis, FR/NFR, SRS structure, requirement quality, validation และ verification [file:1][file:9] | ทำ elicitation, แตกความต้องการทีละฟีเจอร์ด้วย LLM, เขียน SRS ร่างแรกและตรวจ ambiguity [file:1] | SRS draft v1, stakeholder summary, FR/NFR list |
| 5 | Requirements representation และ modeling: use case, user stories, context model, traceability, acceptance criteria [file:1][file:9] | สร้าง context diagram, use case diagram, use case specification, user stories และ acceptance criteria [file:1][file:9] | Use case package, backlog v1, traceability matrix v1 |
| 6 | Architecture and design: architectural drivers, patterns, 3-tier/MVC, API-first, class design, high cohesion/low coupling, trade-off analysis [file:9][file:12] | ให้ LLM เสนอ architecture alternatives แล้วให้ทีมวิเคราะห์และเลือก พร้อมร่าง class/component/API design [file:9][file:12] | ADR, architecture diagram, class diagram, API draft |
| 7 | Construction and collaboration: coding standards, repo structure, Git workflow, issue management, AI pair programming with guardrails [file:5][file:12] | ตั้ง repository, branch strategy, issue/PR template, coding conventions, เริ่ม implementation increment แรก [file:5] | Repo setup, coding standard, first working increment |
| 8 | AI risks in construction: automation bias, trust debt, hallucination in code, responsible SE, secure coding mindset; Midterm checkpoint [file:5][file:12][file:17] | Midterm review ของ requirement, design, repo และ AI-generated code โดยผู้เรียนต้องอธิบายเหตุผลของโค้ดได้ [file:12] | Midterm demo, revised SRS/design plan, AI audit note |
| 9 | Testing fundamentals: test levels, unit testing, test design techniques, edge cases, assertions, testability [file:5][file:9] | เขียน unit tests ให้กับโมดูลจริงของทีม และใช้ LLM ช่วยสร้าง test ideas ก่อนคัดกรองด้วยมนุษย์ [file:5][file:12] | Unit tests v1, test case table, coverage baseline |
| 10 | TDD, integration testing, regression testing และ “70% problem” ของ AI ในงานวิศวกรรมซอฟต์แวร์ [file:12][file:9] | ฝึก TDD กับฟีเจอร์ย่อย, เชื่อมหลายโมดูล, รัน integration tests และบันทึก defect [file:5][file:12] | TDD exercise, integration tests, defect log |
| 11 | QA/QC: code review, inspections, static analysis, linting, metrics, review checklist และ quality gates [file:1][file:5][file:9] | ตั้งค่า linter/formatter/static analysis, ทำ peer review ผ่าน PR, ใช้ checklist ตรวจ style/correctness/security [file:5][file:12] | Review checklist, PR evidence, static analysis report |
| 12 | Security for SE: security requirements, misuse cases, input validation, authentication/authorization basics, privacy awareness [file:9][file:12] | ระบุ security risks ของระบบ, เพิ่ม validation/error handling และ misuse cases [file:9][file:12] | Security note, misuse cases, secure coding fixes |
| 13 | Maintenance and evolution: refactoring, technical debt, maintainability, documentation for evolution, few-shot prompting เพื่อคุม style ของทีม [file:9][file:12] | Refactor โค้ดจริงของทีม, เปรียบเทียบก่อน-หลัง, ให้ AI ช่วย refactor ตาม style guide แล้ว review [file:5][file:12] | Refactoring report, technical debt register, updated codebase |
| 14 | Project management + DevOps: estimation, planning, Kanban/Scrum review, CI/CD, build automation, release readiness, deployment assistant [file:5][file:9][file:12] | ตั้ง CI ให้ run lint + tests + build ทุก PR, เตรียม deployment/readme และ demo environment [file:5][file:12] | CI pipeline, release checklist, deployment guide |
| 15 | Final demo, oral defense, retrospective, peer evaluation, บทเรียนจากการใช้ AI ใน SDLC [file:9][file:12][file:17] | สาธิตระบบ, อธิบาย requirements-design-code-test-quality-security-AI policy, retrospective และ peer evaluation [file:12] | Final demo, final report, repository submission, retrospective |

## แผนที่ CLO กับกิจกรรมรายวิชา

| CLO | สัปดาห์ที่เกี่ยวข้อง | หลักฐานการประเมิน |
|---|---|---|
| CLO1 | 1, 3, 14 | Quiz, discussion, process artifacts |
| CLO2 | 4, 5 | SRS, use cases, user stories, traceability |
| CLO3 | 6, 8 | ADR, architecture diagram, class diagram, oral review |
| CLO4 | 7, 8, 11 | Git workflow evidence, PRs, code review records |
| CLO5 | 9, 10, 11 | Unit tests, integration tests, coverage, QA reports |
| CLO6 | 12, 13, 14 | Security notes, refactoring report, CI/CD pipeline |
| CLO7 | 2, 3, 8, 15 | Prompt library, AI usage logs, policy compliance, oral defense |

## AI Policy สำหรับรายวิชา

### หลักการสำคัญ
การใช้ Generative AI ในรายวิชานี้ได้รับอนุญาตอย่างเป็นทางการ แต่ต้องอยู่ภายใต้หลักความโปร่งใส ความรับผิดชอบ และการตรวจสอบโดยมนุษย์เสมอ [file:5][file:12] ผู้เรียนอาจใช้ AI เพื่อช่วยระดมความคิด สรุปข้อมูล ร่างเอกสาร เสนอแนวทางออกแบบ สร้าง test ideas ช่วย refactor และช่วยตรวจรูปแบบภาษาได้ แต่ไม่อาจยกความรับผิดชอบในการตัดสินใจทางวิศวกรรมให้ AI ได้ [file:12][file:17]

### สิ่งที่อนุญาต
- ใช้ LLM เพื่อช่วย brainstorm โจทย์ ปัญหา ผู้ใช้ และขอบเขตระบบ [file:5][file:12]
- ใช้ช่วยร่าง SRS, user stories, acceptance criteria, diagrams description และ architecture alternatives โดยต้องมีการตรวจแก้โดยทีม [file:1][file:9][file:12]
- ใช้ช่วยสร้าง code skeleton, test cases, refactoring suggestions, deployment steps และ documentation drafts ได้ [file:5][file:12]
- ใช้ช่วยตรวจความกำกวมของ requirement หรือช่วยสร้าง checklist สำหรับ review ได้ [file:1][file:17]

### สิ่งที่ไม่อนุญาต
- ส่งงานที่คัดลอกผลลัพธ์จาก AI โดยไม่มี human review หรือไม่เข้าใจสิ่งที่ส่ง [file:5][file:12]
- อ้างว่าเป็นผลงานที่สร้างเองทั้งหมดโดยไม่เปิดเผยว่า AI มีส่วนช่วย [file:12][file:17]
- ป้อนข้อมูลลับ ข้อมูลส่วนบุคคล ข้อมูลที่มีข้อจำกัดด้านลิขสิทธิ์ หรือ credentials ลงในเครื่องมือ AI ที่ไม่ได้รับอนุญาต [file:5][file:12]
- ใช้ AI เพื่อสร้างข้อมูลปลอม หลักฐานปลอม การทดสอบปลอม หรืออธิบายผลการทดลองที่ไม่ได้ทำจริง [file:12]

### ข้อกำหนดการเปิดเผยการใช้ AI
ทุกทีมต้องแนบ “AI Usage Disclosure” กับงานสำคัญ โดยอย่างน้อยต้องระบุ 4 รายการต่อไปนี้ [file:12][file:17]
- ใช้เครื่องมือใด
- ใช้ช่วยงานส่วนใด
- ใช้ prompt ลักษณะใดหรือ workflow แบบใด
- ทีมตรวจสอบ แก้ไข หรือยืนยันความถูกต้องอย่างไร

### Human Review Requirement
งานทุกชิ้นที่มี AI ช่วยต้องผ่านการตรวจจากมนุษย์ก่อนส่งเสมอ [file:12] สำหรับโค้ด ผู้เรียนต้องสามารถอธิบายตรรกะ โครงสร้างข้อมูล จุดเสี่ยง และเหตุผลในการเลือกแนวทางได้อย่างชัดเจน [file:5][file:12] สำหรับเอกสาร requirements และ design ผู้เรียนต้องสามารถอธิบายที่มาของแต่ละข้อกำหนด ความเชื่อมโยงกับ stakeholder และวิธีตรวจสอบได้ [file:1][file:9]

## Prompt Engineering Guide แบบพร้อมใช้สอน

### หลัก Five S’s
การออกแบบ prompt ของรายวิชานี้ใช้หลัก Five S’s ได้แก่ Structured, Surrounding context, Single task, Specific และ Short เพื่อให้ผลลัพธ์มีความชัดเจนและลดความกำกวมในการสื่อสารกับ LLM [file:17]

### รูปแบบ prompt แนะนำ
1. **Requirement drafting prompt**: ระบุบริบทโครงการ ผู้ใช้หลัก เป้าหมาย และให้ AI สร้าง requirement ทีละ feature แทนการสั่งทั้งระบบในครั้งเดียว [file:1][file:17]
2. **Validation prompt**: ให้ AI ตรวจ requirement ตามเกณฑ์ เช่น ambiguity, completeness, consistency, verifiability และ traceability [file:1]
3. **Architecture prompt**: ให้ AI เสนอทางเลือก 2-3 แบบพร้อม trade-offs และข้อจำกัด แทนการขอคำตอบเดียว [file:9][file:12]
4. **Testing prompt**: ระบุบทบาทเป็น test engineer, ป้อนฟังก์ชันหรือคลาสพร้อมข้อกำหนด แล้วให้ AI สร้าง unit tests ที่ครอบคลุม normal, boundary และ edge cases [file:5][file:12]
5. **Refactoring prompt**: ให้ AI อธิบายปัญหาเดิม หลัก style guide ของทีม และโครงสร้างที่ต้องการก่อนเสนอ refactor [file:5][file:12]

### ตัวอย่าง prompt แม่แบบ
```text
Role: You are a software requirements assistant.
Context: Our team is building a web-based appointment system for a university clinic.
Task: Draft only the functional requirements for the appointment booking feature.
Constraints: Use clear “The system shall …” statements, avoid design decisions, and list ambiguities separately.
Output format: 1) Functional requirements 2) Ambiguities/questions 3) Suggested acceptance criteria.
```
ตัวอย่างนี้สอดคล้องกับหลักการเขียน requirement ที่ควรมีความชัดเจน สม่ำเสมอ และตรวจสอบได้ โดยแยก requirement ออกจาก design และระบุ ambiguity ให้ตรวจทานต่อได้ [file:1]

## รูปแบบงานและ artefacts หลักของรายวิชา

| หมวดงาน | Artefacts หลัก |
|---|---|
| Requirements | Problem statement, stakeholder summary, SRS, FR/NFR list, use cases, user stories, traceability matrix |
| Design | Architecture diagram, ADR, class diagram, API design, data model |
| Construction | Repository, coding standard, issue board, pull requests, implementation increments |
| Testing & QA | Unit tests, integration tests, coverage report, review checklist, static analysis report |
| Security & Maintenance | Security note, misuse cases, refactoring report, technical debt register |
| Delivery | CI/CD pipeline, release checklist, deployment guide, final demo, retrospective |
| Responsible AI | Prompt library, AI policy, AI usage disclosure, AI audit note |

## การประเมินผล

| องค์ประกอบการประเมิน | สัดส่วนคะแนน |
|---|---:|
| Project deliverables ตลอดภาคการศึกษา | 40 |
| Lab assignments / weekly artifacts | 20 |
| Midterm review / checkpoint | 15 |
| Final demo + oral defense | 15 |
| Quiz / short individual checks | 5 |
| Peer evaluation + retrospective | 5 |

แนวทางนี้ให้น้ำหนักกับ artefacts และหลักฐานเชิงกระบวนการมากกว่าการวัดผลปลายทางเพียงอย่างเดียว ซึ่งสอดคล้องกับธรรมชาติของวิชาวิศวกรรมซอฟต์แวร์และการเรียนรู้แบบ project-based learning [file:9][file:12] นอกจากนี้ การมี oral defense ยังช่วยตรวจสอบได้ว่าผู้เรียนเข้าใจสิ่งที่ AI ช่วยสร้างขึ้นจริง ไม่ได้เพียงคัดลอกผลลัพธ์มาใช้งาน [file:12][file:17]

## Rubric ประเมิน Responsible AI Usage

| ระดับ | คำอธิบาย |
|---|---|
| 4 ดีมาก | เปิดเผยการใช้ AI ครบถ้วน, prompt มีคุณภาพ, มีการตรวจสอบและแก้ไขโดยมนุษย์ชัดเจน, อธิบายเหตุผลและข้อจำกัดของผลลัพธ์ AI ได้ดี |
| 3 ดี | ใช้ AI อย่างเหมาะสมและเปิดเผยส่วนใหญ่ครบ, มี human review, อธิบายผลลัพธ์ได้ในระดับดี |
| 2 พอใช้ | ใช้ AI ได้แต่ยังขาดความสม่ำเสมอในการเปิดเผยหรือการตรวจทาน, อธิบายเหตุผลของ artefacts ได้เพียงบางส่วน |
| 1 ต้องปรับปรุง | ใช้ AI แบบพึ่งพามากเกินไป, เปิดเผยไม่ครบ, อธิบายงานตนเองไม่ได้, หลักฐานการตรวจสอบไม่เพียงพอ |
| 0 ไม่ผ่าน | ส่งงานจาก AI โดยแทบไม่มีการตรวจสอบหรือมีการปกปิดการใช้ AI |

## แนวทางการจัดการเรียนการสอน
- ใช้ lecture เพื่อวางกรอบแนวคิด หลักการ และมาตรฐานของ artefacts [file:5][file:9]
- ใช้ lab เพื่อให้นักศึกษาสร้าง artefacts ของโปรเจกต์ทีมจริงในสัปดาห์นั้นทันที [file:12]
- ใช้ weekly review สั้น ๆ เพื่อตรวจทั้งความคืบหน้าเชิงเทคนิคและการใช้ AI อย่างรับผิดชอบ [file:12][file:17]
- ใช้ repository, issue tracker และ pull requests เป็นหลักฐานกลางของพัฒนาการตลอดเทอม [file:5]

## ภาคผนวก: Template AI Usage Disclosure

```text
Project / Team:
Week / Deliverable:
AI Tool Used:
Purpose of Use:
Prompting Approach Used:
Output Generated by AI:
Human Review Performed By:
What Was Modified or Rejected:
Final Responsibility Taken By:
```

## ภาคผนวก: คำแนะนำสำหรับอาจารย์
เพื่อให้รายวิชานี้มีความชัดเจนในการประเมิน ควรกำหนดตั้งแต่ต้นว่า “การใช้ AI ไม่ใช่การทุจริต หากมีการเปิดเผยและตรวจสอบอย่างเหมาะสม” และ “การไม่เปิดเผยหรือไม่เข้าใจสิ่งที่ส่ง คือปัญหาทางวิชาการ” [file:12][file:17] วิธีนี้ช่วยสร้างวัฒนธรรมการใช้ AI แบบมืออาชีพ ซึ่งสอดคล้องกับแนวโน้มการทำงานจริงที่วิศวกรต้องใช้เครื่องมือช่วยงานภายใต้ข้อกำกับของมาตรฐาน คุณภาพ และความรับผิดชอบ [file:5][file:12]
