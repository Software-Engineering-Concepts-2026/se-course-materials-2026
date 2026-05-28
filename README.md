# รายวิชา วิศวกรรมซอฟต์แวร์ (Software Engineering)

**ผู้สอน:** อาจารย์ธรรมรัตน์ ธรรมา  
**ระดับหลักสูตร:** ปริญญาตรี ชั้นปีที่ 3 (สาขาวิทยาการคอมพิวเตอร์)  
**รูปแบบการเรียน:** บรรยาย 2 ชั่วโมง + ปฏิบัติการแล็บ 2 ชั่วโมง ต่อสัปดาห์ (รวม 15 สัปดาห์)  
**จำนวนผู้เรียน:** ~90 คน (แบ่งกลุ่มปฏิบัติการได้ประมาณ 18 ทีม ทีมละ ~5 คน)  
**ช่องทางบริหารจัดการโครงงานสเกลใหญ่:** [GitHub Organization ของรายวิชา]

---

## 🎯 เป้าหมายรายวิชา (Course Goal)
มุ่งเน้นให้นักศึกษาชั้นปีที่ 3 มีความรู้ความเข้าใจในหลักการและระเบียบวิธีทางวิศวกรรมซอฟต์แวร์ที่สอดคล้องกับมาตรฐานสากล โดยสามารถประยุกต์ใช้ความรู้ผ่านกระบวนการพัฒนาซอฟต์แวร์จริงในรูปแบบโปรเจกต์ทีม (Project-based/Team-based Learning) ตั้งแต่การวิเคราะห์ความต้องการ การออกแบบระบบ การสร้างซอฟต์แวร์ร่วมกัน การทดสอบ และการควบคุมคุณภาพ นอกจากนี้ รายวิชายังมุ่งเน้นการสร้างภูมิคุ้มกันและทักษะที่แท้จริงให้กับผู้เรียนเพื่อ **“ลดภาวะการพัฒนาทักษะเชิงลึกไม่ทันยุค AI” หรือ “mitigate skill atrophy in the AI era”** ในยุคปัญญาประดิษฐ์ ผ่านกลยุทธ์การประเมินผลเชิงรุกและการติดตามร่องรอยการทำงานในระบบ GitHub Organization เพื่อให้นิสิตสามารถปรับเปลี่ยนกระบวนทัศน์จากผู้เขียนโค้ดทั่วไป (Coder) สู่การเป็นวิศวกรซอฟต์แวร์มืออาชีพ (Engineer) ที่สามารถบูรณาการทักษะทางเทคนิคและการทำงานร่วมกันเป็นทีมได้อย่างมีวิศวกรรมและมีจริยธรรมในวิชาชีพ

---

## 📅 แผนการสอนและกิจกรรมรายสัปดาห์ (15-Week Course Syllabus)

| Week | Lecture Focus (หัวข้อบรรยาย 2 ชม.) | Lab Focus (กิจกรรมแล็บ 2 ชม.) | Deliverables / Notes | Assessment / Weight (การประเมิน / สัดส่วนคะแนน) |
| :---: | :--- | :--- | :--- | :--- |
| **1** | **บทนำสู่วิศวกรรมซอฟต์แวร์และวงจรการพัฒนาซอฟต์แวร์**<br>• นิยามวิศวกรรมซอฟต์แวร์ ความแตกต่างจากวิทยาการคอมพิวเตอร์และงาน Coding ทั่วไป<br>• รู้จักแนวคิดกระบวนการ SDLC (Waterfall, Iterative, Agile/Scrum เบื้องต้น)<br>• การทำงานร่วมกันเป็นทีมและบทบาทหน้าที่ในโปรเจกต์ (Teamwork Concepts) | **Team Formation & Tool Setup**<br>• จัดกลุ่มนักศึกษา (ประมาณ 5 คน/กลุ่ม)<br>• แนะนำการใช้งาน GitHub Organization ร่วมกันในระดับทีม<br>• ระดมสมองคิดหัวข้อโปรเจกต์ (Project Idea Generation) | • สรุปรายชื่อสมาชิกทีม หน้าที่ และขอบเขตหัวข้อโปรเจกต์ขั้นต้น (ส่งผ่าน GitHub Issues) | • ไม่มีคะแนนโดยตรง<br>• ใช้เป็น baseline สำหรับการจัดทีมและเริ่มต้นโครงงาน |
| **2** | **การประเมินเชิงวินิจฉัยรายบุคคลครั้งที่ 1 และการเก็บความต้องการซอฟต์แวร์**<br>• 🧪 **[สอบจับผิด 1 ชม.]** วิเคราะห์ข้อบกพร่องในเอกสารความต้องการที่สร้างโดย AI เพื่อวัดความเข้าใจพื้นฐานรายบุคคล<br>• [บรรยาย 1 ชม.] Software Requirements & Elicitation (Functional / Non-functional Requirements) | **Requirements Elicitation Workshop**<br>• ฝึกทำ User Interview จำลองสถานการณ์เป็น Client และ Developer เพื่อเก็บความต้องการระบบจริงของโปรเจกต์กลุ่ม<br>• การประยุกต์ใช้ LLMs ในฐานะเครื่องมือช่วยขัดเกลาและจัดประเภทความต้องการภายใต้การตรวจสอบของผู้เรียน | • คะแนนเดี่ยวจาก Quiz จับผิดเอกสารความต้องการระบบ<br>• บันทึกสรุปความต้องการของโปรเจกต์กลุ่ม (Draft Functional Requirements) ลงใน Repository | • **Quiz / Diagnostic 1 = 10%** |
| **3** | **Software Requirements Specification (SRS)**<br>• โครงสร้างเอกสาร SRS ตามมาตรฐาน ISO/IEC/IEEE 29148:2018<br>• เทคนิคการเขียนความต้องการที่สามารถตรวจสอบได้ (Verifiable Requirements) และพฤติกรรมระบบ | **SRS Drafting & GitHub Management**<br>• สมาชิกในกลุ่มช่วยกันร่างเอกสาร SRS เวอร์ชันแรก<br>• เรียนรู้การแปลง Requirements ไปเป็น Task หรือ Ticket บนระบบ GitHub Projects (Kanban Board) | • เอกสาร SRS ร่างแรก (Markdown บน GitHub)<br>• บอร์ดงานบน GitHub Projects ที่แตกย่อยเป็น Task พร้อมกำหนดผู้รับผิดชอบชัดเจน | • **Project Artefact: SRS = 5%** |
| **4** | **System Modeling & UML (Behavioral Aspect)**<br>• แนวคิดระเบียบวิธีการออกแบบ (Design Methodologies)<br>• การจำลองระบบด้วย Use Case Diagram และ Description<br>• การสื่อสารสถาปัตยกรรมระบบขั้นพื้นฐาน | **Use Case Modeling & Peer Review**<br>• กลุ่มร่วมกันสร้าง Use Case Diagram สำหรับโปรเจกต์ของตนเอง<br>• แลกเปลี่ยนกันรีวิว Use Case ระหว่างกลุ่ม เพื่อค้นหาจุดบกพร่องและขอบเขตระบบที่ยังไม่ชัดเจน | • Use Case Diagram และ Use Case Description ของแต่ละฟังก์ชันหลักในรูปแบบไฟล์รูปภาพ/Markdown บน Git | • **Project Artefact: Use Case Model = 5%** |
| **5** | **Structural Modeling & Basic Design Principles**<br>• การออกแบบระดับโครงสร้างด้วย Class Diagram (Attributes, Methods, Relationships)<br>• หลักการออกแบบเบื้องต้นเบื้องหลังความคุ้มค่า (High Cohesion, Low Coupling และ Separation of Concerns)<br>• แนวคิดเบื้องต้นของ SOLID principles และ code contracts เพื่อสนับสนุนการออกแบบที่บำรุงรักษาได้และทดสอบได้ง่าย | **Class Diagram & Database Schema Mapping**<br>• เขียน Class Diagram ของระบบให้สอดคล้องกับฐานข้อมูลที่เคยเรียนมา<br>• ปรับปรุง Class Diagram ให้รองรับ Business Logic ของโปรเจกต์ | • Class Diagram ร่างแรก<br>• เริ่มเน้นย้ำเกณฑ์ Process Tracking (ความถี่ในการอัปเดตไฟล์บน Git) | • **Project Artefact: Class Diagram / Design Rationale = 5%** |
| **6** | **Software Architecture & Secure Coding Foundations**<br>• ภาพรวมสถาปัตยกรรมซอฟต์แวร์ (Architectural Design: MVC, Layered, Client-Server)<br>• พื้นฐานความปลอดภัย (Basic Security Requirements): การตระหนักรู้ภัยคุกคาม เช่น Injection, Broken Authentication และแนวคิดการเข้ารหัสข้อมูลสำคัญ | **Architectural & Security Mapping**<br>• นิสิตร่วมกันกำหนด Architecture Pattern และเทคโนโลยีที่จะเลือกใช้ในโปรเจกต์<br>• วิเคราะห์หาจุดเสี่ยงด้านความปลอดภัยของโปรเจกต์กลุ่ม และออกแบบระบบป้องกันขั้นต้น (เช่น การแฮชรหัสผ่าน) | • แผนภาพสถาปัตยกรรมซอฟต์แวร์ระบบ (Architecture Diagram)<br>• รายการความปลอดภัยทางเทคนิคที่ต้องระวัง | • **Project Artefact: Architecture & Security = 5%** |
| **7** | **Collaborative Construction & Version Control Workflow**<br>• มาตรฐานการเขียนโค้ด (Coding Standards) และระเบียบวิธีสร้างซอฟต์แวร์ร่วมกัน<br>• การทำงานแบบ Collaborative Git ขั้นสูง (Git Branching Strategies: GitHub Flow/Gitflow, Pull Requests, Merge Conflict Resolution) | **Git Collaborative Lab**<br>• กิจกรรมจำลองการเกิด Merge Conflict เพื่อฝึกให้นิสิตรู้วิธีแก้ไขร่วมกัน<br>• เริ่มต้นตั้งโครงสร้างโปรเจกต์ทีม (Project Initialization) และสร้าง Git Branch สำหรับฟีเจอร์แรก | • โครงร่างซอฟต์แวร์ (Project Skeleton Code) ที่ Push ขึ้น GitHub Main Branch<br>• การแยก Branch ทำงานรายบุคคลอย่างมีระบบ | • **Milestone Review 1 / Progress Check = 5%** |
| **8** | 🛑 **Midterm Assessment Period**<br>*(ไม่มีการบรรยาย)* | 🛑 **Midterm Assessment Period**<br>*(ไม่มีกิจกรรมแล็บ)* | • สัปดาห์เคลียร์งานและเตรียมสอบ<br>• ไม่มีการสั่งงานใหม่และไม่มีการนัดหมายส่งงานใด ๆ ในสัปดาห์นี้ | • **Midterm Exam = 15%** |
| **9** | **การประเมินเชิงวินิจฉัยรายบุคคลครั้งที่ 2 และพื้นฐานการทดสอบซอฟต์แวร์**<br>• 🧪 **[สอบจับผิด 1 ชม.]** วิเคราะห์ bug เชิงตรรกะ ตัวแปรสลับ หรือช่องโหว่ความปลอดภัยในโค้ดที่สร้างโดย AI<br>• [บรรยาย 1 ชม.] Software Testing Levels & Test Design Techniques | **Test Case & Test Script Planning**<br>• นิสิตฝึกออกแบบแนวทางการทดสอบระบบของโปรเจกต์กลุ่ม<br>• เขียนเอกสาร Test Case Specification ระบุ Input, Expected Output และประเภทของการทดสอบ | • คะแนนเดี่ยวจาก Quiz จับผิด bug ในซอฟต์แวร์ที่มาจาก AI<br>• เอกสารรายการ Test Cases สำหรับโปรเจกต์กลุ่ม | • **Quiz / Diagnostic 2 = 10%** |
| **10** | **Unit Testing & Test Automation Basics**<br>• แนวคิดการทดสอบระดับย่อย (Unit Testing) และประโยชน์ของการเขียนเทสตั้งแต่เนิ่น ๆ<br>• แนะนำการใช้งาน Testing Framework ในภาษาที่กลุ่มเลือกใช้ (เช่น JUnit, PyTest)<br>• แนวคิดเบื้องต้นของ Test-Driven Development (TDD) และวงจร Red-Green-Refactor | **Writing Unit Tests for the Project**<br>• นิสิตแต่ละคนเขียน Unit Test ให้กับโมดูลโค้ดที่ตนเองได้รับผิดชอบในโปรเจกต์กลุ่มจริง<br>• ทดลองใช้แนวทาง test-first กับฟังก์ชันย่อยอย่างน้อยหนึ่งส่วนเพื่อสะท้อนผลต่อการออกแบบโค้ด | • ชุดคำสั่งสำหรับทดสอบ (Unit Test Scripts) ที่ผสานรวมอยู่ในระบบ GitHub Repository ของทีม<br>• บันทึกสั้นเกี่ยวกับผลการใช้แนวคิด TDD | • **Testing & Quality Evidence: Unit Test = 5%** |
| **11** | **Quality Control & Peer Code Review**<br>• เทคนิคการควบคุมคุณภาพซอฟต์แวร์ (Quality Control/Quality Assurance)<br>• วัฒนธรรมและขั้นตอนการทำ Code Review อย่างสร้างสรรค์<br>• การอ่านและทำความเข้าใจโค้ดของผู้อื่น | **GitHub Pull Request & Review Lab**<br>• นิสิตเปิดฟีเจอร์ของตนเองผ่าน Pull Request (PR) บน GitHub<br>• ให้สมาชิกในทีมคนอื่นเข้ามาทำ Code Review และกด Approve ก่อนที่จะ Merge โค้ดเข้าสู่ Main Branch | • ร่องรอยการทำ Code Review และการสนทนาถกเถียงบนระบบ GitHub Pull Request | • **Team Contribution / Process Tracking 1 = 5%** |
| **12** | **Static Analysis & Modern QA (DevOps Overview)**<br>• แนะนำเครื่องมือการวิเคราะห์โค้ดแบบสถิต (Static Analysis Tools เช่น SonarQube, Linters)<br>• ภาพรวมและแนวคิด DevOps และ Continuous Integration (CI) | **Setting Up Linter & CI Pipeline**<br>• นักศึกษาเปิดใช้งาน Linter ตรวจรูปแบบโค้ดอัตโนมัติ<br>• เขียนไฟล์คอนฟิก GitHub Actions (CI pipeline) เพื่อให้ระบบรัน Unit Test อัตโนมัติทุกครั้งที่มีการเปิด PR หรือ Push โค้ด | • ไฟล์คอนฟิก CI<br>• ป้ายสถานะผ่านการทดสอบ (CI Build Passing Badge) บนไฟล์ README ของโครงการ | • **Testing & Quality Evidence: CI / Static Analysis = 10%** |
| **13** | **Software Maintenance, Technical Debt & Refactoring**<br>• วงจรการบำรุงรักษาและการเปลี่ยนผ่านของซอฟต์แวร์ (Maintenance & Evolution)<br>• ความหมายและผลกระทบของ "Technical Debt" (หนี้ทางเทคนิค)<br>• หลักการปรับปรุงโครงสร้างโค้ดโดยไม่เปลี่ยนผลลัพธ์ภายนอก (Refactoring Basics) | **Code Smells Hunting & Refactoring**<br>• ร่วมกันตรวจหาร่องรอยโค้ดที่ไม่มีประสิทธิภาพ (Code Smells) ในซอฟต์แวร์ของโปรเจกต์กลุ่ม<br>• ทำการ Refactoring โค้ดชิ้นนั้นให้สะอาด อ่านง่าย และยืดหยุ่นขึ้น โดยมี Unit Test คอยคุมไม่ให้ระบบพัง | • โค้ดโปรเจกต์กลุ่มที่ผ่านการ Refactor และไม่มีข้อผิดพลาดจากการตรวจสอบของ Static Analysis | • ไม่มีคะแนนแยกเฉพาะ<br>• ใช้ประกอบการประเมิน milestone และคุณภาพงานปลายภาค |
| **14** | **Final Integration & Project Wrap-up**<br>• การรวมระบบในขั้นตอนสุดท้าย (Final System Integration)<br>• เทคนิคการจัดทำรายงานสรุปโครงการและการเตรียมตัวนำเสนอผลงาน (Project Demo Prep) | **Bug Fixing & Deployment Check**<br>• ทดสอบระบบร่วมกันทั้งระบบเพื่อหาข้อผิดพลาดช่วงสุดท้าย (System & Integration Testing)<br>• เตรียมพร้อมระบบให้ทำงานบนสภาพแวดล้อมจำลองที่พร้อมทดสอบ (Staging/Production Environment) | • ซอฟต์แวร์เวอร์ชันสมบูรณ์ (Production-ready Version) ที่ล็อกเวอร์ชันผ่าน Git Tag บน GitHub | • **Milestone Review 2 / Final Integration = 5%** |
| **15** | **Project Demo, Retrospective & Evaluation**<br>• สรุปบทเรียนและการเรียนรู้ตลอดภาคการศึกษา<br>• การปิดโครงการและการทำ Retrospective เพื่อปรับปรุงกระบวนการพัฒนาตนเอง | **Project Marketplace & AI Exam Defense**<br>• นำเสนอโปรเจกต์กลุ่ม (Group Demo) และส่งรายงานฉบับสมบูรณ์<br>• ทำกิจกรรม Agile Retrospective ภายในกลุ่ม<br>• ดำเนินการสอบปากเปล่ารายบุคคลเพื่อยืนยันความเข้าใจและการมีส่วนร่วมในงาน | • เอกสารรายงานสรุปบทเรียน (Retrospective Report)<br>• คะแนนการประเมินเพื่อนร่วมกลุ่ม (Peer Evaluation) | • **Final Demo / Oral Defense = 10%**<br>• **Team Contribution / Peer Evaluation 2 = 5%** |

> หมายเหตุ: การประเมินผลรายสัปดาห์ในตารางนี้เป็นการแจกแจงความเชื่อมโยงระหว่างกิจกรรมการเรียนรู้ ชิ้นงาน และองค์ประกอบการให้คะแนนของรายวิชา ทั้งนี้ การประเมินบางส่วนอาจพิจารณาจากหลักฐานสะสมต่อเนื่องตลอดภาคการศึกษา เช่น process tracking, code review, commits, pull requests และการมีส่วนร่วมใน repository ของทีม [file:23][file:12][file:5]

---

## ข้อเสนอการกระจายน้ำหนักคะแนน

| องค์ประกอบการประเมิน | สัดส่วน | เหตุผล |
| --- | ---: | --- |
| แบบทดสอบรายบุคคล / Quiz / Diagnostic assessment | 20% | ใช้วัดความเข้าใจพื้นฐานของแต่ละคน และช่วยยืนยันว่าผู้เรียนเข้าใจ requirements, testing และแนวคิดสำคัญของวิศวกรรมซอฟต์แวร์จริง [file:23][file:9] |
| งานโครงงานรายสัปดาห์ / Project artefacts | 20% | ครอบคลุม SRS, use case, class diagram, architecture และ artefacts สำคัญของการออกแบบและการพัฒนา [file:23][file:9] |
| Unit test, CI, static analysis และ quality evidence | 15% | สะท้อนความสามารถด้าน testability, test automation, continuous integration และ quality control [file:12][file:5] |
| งานนำเสนอระหว่างทาง / Milestone review / Progress check | 10% | ใช้ติดตามความก้าวหน้าและลดความเสี่ยงของการสะสมงานช่วงปลายภาค [file:23][file:12] |
| สอบกลางภาค | 15% | ใช้วัดความเข้าใจเชิงทฤษฎีและการเชื่อมโยงเนื้อหาช่วงต้นถึงกลางภาค [file:23][file:9] |
| สอบปลายภาค / Final demo / Oral defense | 10% | ประเมินความเข้าใจภาพรวมของระบบ การตัดสินใจเชิงออกแบบ และความสามารถในการอธิบายผลงานของตน [file:23][file:12] |
| การมีส่วนร่วมในทีม / Peer evaluation / GitHub contribution | 10% | ใช้สะท้อนการทำงานร่วมกันจริงจาก issues, commits, pull requests, code review และ peer evaluation [file:23][file:12][file:5] |
| **รวม** | **100%** |  |

---

## สรุปการแมปคะแนนตามสัปดาห์

- Week 2: 10%
- Week 3: 5%
- Week 4: 5%
- Week 5: 5%
- Week 6: 5%
- Week 7: 5%
- Week 8: 15%
- Week 9: 10%
- Week 10: 5%
- Week 11: 5%
- Week 12: 10%
- Week 14: 5%
- Week 15: 15%
- Weeks 1 and 13: ไม่มีคะแนนโดยตรง แต่มีผลต่อคุณภาพงานและหลักฐานการมีส่วนร่วมตลอดภาคการศึกษา [file:23]
