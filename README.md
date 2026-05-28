# รายวิชา วิศวกรรมซอฟต์แวร์ (Software Engineering)

**ผู้สอน:** อาจารย์ธรรมรัตน์ ธรรมา  
**ระดับหลักสูตร:** ปริญญาตรี ชั้นปีที่ 3 (สาขาวิทยาการคอมพิวเตอร์)  
**รูปแบบการเรียน:** บรรยาย 2 ชั่วโมง + ปฏิบัติการแล็บ 2 ชั่วโมง ต่อสัปดาห์ (รวม 15 สัปดาห์)  
**จำนวนผู้เรียน:** ~90 คน (แบ่งกลุ่มปฏิบัติการได้ประมาณ 18 ทีม ทีมละ ~5 คน)  
**ช่องทางบริหารจัดการโครงงานสเกลใหญ่:** [GitHub Organization ของรายวิชา]

---

## 🎯 เป้าหมายรายวิชา (Course Goal)
มุ่งเน้นให้นักศึกษาชั้นปีที่ 3 มีความรู้ความเข้าใจในหลักการและระเบียบวิธีทางวิศวกรรมซอฟต์แวร์ที่สอดคล้องกับมาตรฐานสากล โดยสามารถประยุกต์ใช้ความรู้ผ่านกระบวนการพัฒนาซอฟต์แวร์จริงในรูปแบบโปรเจกต์ทีม (Project-based/Team-based Learning) ตั้งแต่การวิเคราะห์ความต้องการ การออกแบบระบบ การสร้างซอฟต์แวร์ร่วมกัน การทดสอบ และการควบคุมคุณภาพ นอกจากนี้ รายวิชายังมุ่งเน้นการสร้างภูมิคุ้มกันและทักษะที่แท้จริงให้กับผู้เรียนเพื่อต่อสู้กับภาวะ **Never-skilling** ในยุคปัญญาประดิษฐ์ ผ่านกลยุทธ์การประเมินผลเชิงรุกและการติดตามร่องรอยการทำงานในระบบ GitHub Organization เพื่อให้นักศึกษาสามารถปรับเปลี่ยนกระบวนทัศน์จากผู้เขียนโค้ดทั่วไป (Coder) สู่การเป็นวิศวกรซอฟต์แวร์มืออาชีพ (Engineer) ที่สามารถบูรณาการทักษะทางเทคนิคและการทำงานร่วมกันเป็นทีมได้อย่างมีวิศวกรรมและมีจริยธรรมในวิชาชีพ

---

## 📅 แผนการสอนและกิจกรรมรายสัปดาห์ (15-Week Course Syllabus)

| Week | Lecture Focus (หัวข้อบรรยาย 2 ชม.) | Lab Focus (กิจกรรมแล็บ 2 ชม.) | Deliverables / Notes |
| :---: | :--- | :--- | :--- |
| **1** | **Introduction to Software Engineering & SDLC**<br>• นิยามวิศวกรรมซอฟต์แวร์ ความแตกต่างจากวิทยาการคอมพิวเตอร์และงาน Coding ทั่วไป<br>• รู้จักแนวคิดกระบวนการ SDLC (Waterfall, Iterative, Agile/Scrum เบื้องต้น)<br>• การทำงานร่วมกันเป็นทีมและบทบาทหน้าที่ในโปรเจกต์ (Teamwork Concepts) | **Team Formation & Tool Setup**<br>• จัดกลุ่มนักศึกษา (ประมาณ 5 คน/กลุ่ม ได้ ~18 ทีม)<br>• แนะนำการใช้งาน GitHub Organization ร่วมกันในระดับทีม<br>• ระดมสมองคิดหัวข้อโปรเจกต์ (Project Idea Generation) | • สรุปรายชื่อสมาชิกทีม หน้าที่ และขอบเขตหัวข้อโปรเจกต์ขั้นต้น (ส่งผ่าน GitHub Issues) |
| **2** | **Strategic Learning: Adversarial Assessment #1**<br>• 🧪 **[สอบจับผิด 1 ชม.]** กิจกรรม "สอบจับผิด" ดัดหลัง AI โดยให้ตรวจเอกสารความต้องการระบบที่เจนด้วย AI ซึ่งมีข้อผิดพลาดเนียนๆ 3-4 จุด เพื่อทดสอบ Schema ความเข้าใจพื้นฐานรายบุคคล<br>• [บรรยาย 1 ชม.] Software Requirements & Elicitation (Functional / Non-functional Requirements) | **Requirements Elicitation Workshop**<br>• ฝึกทำ User Interview จำลองสถานการณ์เป็น Client และ Developer เพื่อเก็บความต้องการระบบจริงของโปรเจกต์กลุ่ม<br>• การประยุกต์ใช้ LLMs ในฐานะเครื่องมือช่วยขัดเกลาและจัดประเภทความต้องการ (แต่อยู่ภายใต้การตรวจสอบของผู้เรียน) | • **คะแนนเดี่ยว (1):** Quiz จับผิดเอกสารความต้องการระบบ<br>• บันทึกสรุปความต้องการของโปรเจกต์กลุ่ม (Draft Functional Requirements) ลงใน Repository |
| **3** | **Software Requirements Specification (SRS)**<br>• โครงสร้างเอกสาร SRS ตามมาตรฐาน IEEE 830<br>• เทคนิคการเขียนความต้องการที่สามารถตรวจสอบได้ (Verifiable Requirements) และพฤติกรรมระบบ | **SRS Drafting & GitHub Management**<br>• สมาชิกในกลุ่มช่วยกันร่างเอกสาร SRS เวอร์ชันแรก<br>• เรียนรู้การแปลง Requirements ไปเป็น Task หรือ Ticket บนระบบ GitHub Projects (Kanban Board) | • **Deliverable:** เอกสาร SRS ร่างแรก (Markdown บน GitHub)<br>• บอร์ดงานบน GitHub Projects ที่แตกย่อยเป็น Task พร้อมกำหนดผู้รับผิดชอบชัดเจน |
| **4** | **System Modeling & UML (Behavioral Aspect)**<br>• แนวคิดระเบียบวิธีการออกแบบ (Design Methodologies)<br>• การจำลองระบบด้วย Use Case Diagram และ Description<br>• การสื่อสารสถาปัตยกรรมระบบขั้นพื้นฐาน | **Use Case Modeling & Peer Review**<br>• 各กลุ่มร่วมกันสร้าง Use Case Diagram สำหรับโปรเจกต์ของตนเอง<br>• แลกเปลี่ยนกันรีวิว Use Case ระหว่างกลุ่ม เพื่อค้นหาจุดบกพร่องและขอบเขตระบบที่ยังไม่ชัดเจน | • **Deliverable:** Use Case Diagram และ Use Case Description ของแต่ละฟังก์ชันหลักในรูปแบบไฟล์รูปภาพ/Markdown บน Git |
| **5** | **Structural Modeling & Basic Design Principles**<br>• การออกแบบระดับโครงสร้างด้วย Class Diagram (Attributes, Methods, Relationships)<br>• หลักการออกแบบเบื้องต้นเบื้องหลังความคุ้มค่า (High Cohesion, Low Coupling และ Separation of Concerns) | **Class Diagram & Database Schema Mapping**<br>• เขียน Class Diagram ของระบบให้สอดคล้องกับฐานข้อมูลที่เคยเรียนมา<br>• ปรับปรุง Class Diagram ให้รองรับ Business Logic ของโปรเจกต์ | • **Deliverable:** Class Diagram ร่างแรก<br>• **Note:** เริ่มเน้นย้ำเกณฑ์ Process Tracking (ความถี่ในการอัปเดตไฟล์บน Git) |
| **6** | **Software Architecture & Secure Coding Foundations**<br>• ภาพรวมสถาปัตยกรรมซอฟต์แวร์ (Architectural Design: MVC, Layered, Client-Server)<br>• พื้นฐานความปลอดภัย (Basic Security Requirements): การตระหนักรู้ภัยคุกคาม เช่น Injection, Broken Authentication และแนวคิดการเข้ารหัสข้อมูลสำคัญ | **Architectural & Security Mapping**<br>• นิสิตร่วมกันกำหนด Architecture Pattern และเทคโนโลยีที่จะเลือกใช้ในโปรเจกต์<br>• วิเคราะห์หาจุดเสี่ยงด้านความปลอดภัยของโปรเจกต์กลุ่ม และออกแบบระบบป้องกันขั้นต้น (เช่น การแฮชรหัสผ่าน) | • **Deliverable:** แผนภาพสถาปัตยกรรมซอฟต์แวร์ระบบ (Architecture Diagram) และรายการความปลอดภัยทางเทคนิคที่ต้องระวัง |
| **7** | **Collaborative Construction & Version Control Workflow**<br>• มาตรฐานการเขียนโค้ด (Coding Standards) และระเบียบวิธีสร้างซอฟต์แวร์ร่วมกัน<br>• การทำงานแบบ Collaborative Git ขั้นสูง (Git Branching Strategies: GitHub Flow/Gitflow, Pull Requests, Merge Conflict Resolution) | **Git Collaborative Lab**<br>• กิจกรรมจำลองการเกิด Merge Conflict เพื่อฝึกให้นิสิตรู้วิธีแก้ไขร่วมกัน<br>• เริ่มต้นตั้งโครงสร้างโปรเจกต์ทีม (Project Initialization) และสร้าง Git Branch สำหรับฟีเจอร์แรก | • **Deliverable:** โครงร่างซอฟต์แวร์ (Project Skeleton Code) ที่ Push ขึ้น GitHub Main Branch และการแยก Branch ทำงานรายบุคคลอย่างมีระบบ |
| **8** | 🛑 **Midterm Assessment Period**<br>*(ไม่มีการบรรยาย)* | 🛑 **Midterm Assessment Period**<br>*(ไม่มีกิจกรรมแล็บ)* | **[สัปดาห์เคลียร์งานและเตรียมสอบ]**<br>• นิสิตเคลียร์และทบทวนเนื้อหาเพื่อเตรียมตัวสอบกลางภาค/สอบไล่ในรายวิชาอื่น ๆ ได้อย่างเต็มที่<br>• **ไม่มีการสั่งงานใหม่และไม่มีการนัดหมายส่งงานใดๆ ในสัปดาห์นี้** |
| **9** | **Strategic Learning: Adversarial Assessment #2**<br>• 🧪 **[สอบจับผิด 1 ชม.]** กิจกรรม "สอบจับผิดโค้ดที่เจนด้วย AI" โดยอาจารย์ซ่อน Bug เชิงตรรกะ ตัวแปรสลับ หรือช่องโหว่ความปลอดภัยเนียนๆ 3-4 จุด ให้นิสิตหาและอธิบายวิธีแก้<br>• [บรรยาย 1 ชม.] Software Testing Levels & Test Design Techniques | **Test Case & Test Script Planning**<br>• นิสิตฝึกออกแบบแนวทางการทดสอบระบบของโปรเจกต์กลุ่ม<br>• เขียนเอกสาร Test Case Specification ระบุ Input, Expected Output และประเภทของการทดสอบ | • **คะแนนเดี่ยว (2):** Quiz จับผิด Bug ในซอฟต์แวร์ที่มาจาก AI<br>• เอกสารรายการ Test Cases สำหรับโปรเจกต์กลุ่ม |
| **10** | **Unit Testing & Test Automation Basics**<br>• แนวคิดการทดสอบระดับย่อย (Unit Testing) และประโยชน์ของการเขียนเทสตั้งแต่เนิ่นๆ<br>• แนะนำการใช้งาน Testing Framework ในภาษาที่กลุ่มเลือกใช้ (เช่น JUnit, PyTest) | **Writing Unit Tests for the Project**<br>• นิสิตแต่ละคนเขียน Unit Test ให้กับโมดูลโค้ดที่ตนเองได้รับผิดชอบในโปรเจกต์กลุ่มจริง (ห้ามเขียนเทสเฉพาะเคสที่ผ่านง่ายๆ เท่านั้น) | • **Deliverable:** ชุดคำสั่งสำหรับทดสอบ (Unit Test Scripts) ที่ผสานรวมอยู่ในระบบ GitHub Repository ของทีม |
| **11** | **Quality Control & Peer Code Review**<br>• เทคนิคการควบคุมคุณภาพซอฟต์แวร์ (Quality Control/Quality Assurance)<br>• วัฒนธรรมและขั้นตอนการทำ Code Review อย่างสร้างสรรค์<br>• การอ่านและทำความเข้าใจโค้ดของผู้อื่น | **GitHub Pull Request & Review Lab**<br>• นิสิตเปิดฟีเจอร์ของตนเองผ่าน Pull Request (PR) บน GitHub<br>• บังคับให้สมาชิกในทีมคนอื่นเข้ามาทำ Code Review และกด Approve ก่อนที่จะ Merge โค้ดเข้าสู่ Main Branch | • **Deliverable:** ร่องรอยการทำ Code Review และการสนทนาถกเถียงบนระบบ GitHub Pull Request (ใช้ประเมิน Process Tracking) |
| **12** | **Static Analysis & Modern QA (DevOps Overview)**<br>• แนะนำเครื่องมือการวิเคราะห์โค้ดแบบสถิต (Static Analysis Tools เช่น SonarQube, Linters)<br>• ภาพรวมและแนวคิด DevOps และ Continuous Integration (CI) | **Setting Up Linter & CI Pipeline**<br>• นักศึกษาเปิดใช้งาน Linter ตรวจรูปแบบโค้ดอัตโนมัติ<br>• เขียนไฟล์คอนฟิก GitHub Actions (CI pipeline) เพื่อให้ระบบรัน Unit Test อัตโนมัติทุกครั้งที่มีการเปิด PR หรือ Push โค้ด | • **Deliverable:** ไฟล์คอนฟิก CI และป้ายสถานะผ่านการทดสอบ (CI Build Passing Badge) บนไฟล์ README ของโครงการ |
| **13** | **Software Maintenance, Technical Debt & Refactoring**<br>• วงจรการบำรุงรักษาและการเปลี่ยนผ่านของซอฟต์แวร์ (Maintenance & Evolution)<br>• ความหมายและผลกระทบของ "Technical Debt" (หนี้ทางเทคนิค)<br>• หลักการปรับปรุงโครงสร้างโค้ดโดยไม่เปลี่ยนผลลัพธ์ภายนอก (Refactoring Basics) | **Code Smells Hunting & Refactoring**<br>• ร่วมกันตรวจหาร่องรอยโค้ดที่ไม่มีประสิทธิภาพ (Code Smells) ในซอฟต์แวร์ของโปรเจกต์กลุ่ม<br>• ทำการ Refactoring โค้ดชิ้นนั้นให้สะอาด อ่านง่าย และยืดหยุ่นขึ้น โดยมี Unit Test คอยคุมไม่ให้ระบบพัง | • **Deliverable:** โค้ดโปรเจกต์กลุ่มที่ผ่านการ Refactor และไม่มีข้อผิดพลาดจากการตรวจสอบของ Static Analysis |
| **14** | **Final Integration & Project Wrap-up**<br>• การรวมระบบในขั้นตอนสุดท้าย (Final System Integration)<br>• เทคนิคการจัดทำรายงานสรุปโครงการและการเตรียมตัวนำเสนอผลงาน (Project Demo Prep) | **Bug Fixing & Deployment Check**<br>• ทดสอบระบบร่วมกันทั้งระบบเพื่อหาข้อผิดพลาดช่วงสุดท้าย (System & Integration Testing)<br>• เตรียมพร้อมระบบให้ทำงานบนสภาพแวดล้อมจำลองที่พร้อมทดสอบ (Staging/Production Environment) | • **Deliverable:** ซอฟต์แวร์เวอร์ชันสมบูรณ์ (Production-ready Version) ที่ล็อกเวอร์ชันผ่าน Git Tag บน GitHub |
| **15** | **Project Demo, Retrospective & Evaluation**<br>• สรุปบทเรียนและการเรียนรู้ตลอดภาคการศึกษา<br>• การปิดโครงการและการทำ Retrospective เพื่อปรับปรุงกระบวนการพัฒนาตนเอง | **Project Marketplace & AI Exam Defense**<br>• นำเสนอโปรเจกต์กลุ่ม (Group Demo) และส่งรายงานฉบับสมบูรณ์<br>• ทำกิจกรรม Agile Retrospective ภายในกลุ่ม<br>• 🤖 **[AI-Driven Oral Exam & Defense]** ทดสอบปากเปล่ารายบุคคลผ่าน AI Bot ตามรายละเอียดในเกณฑ์ประเมินผล | • **Deliverable:** เอกสารรายงานสรุปบทเรียน (Retrospective Report) และคะแนนการประเมินเพื่อนร่วมกลุ่ม (Peer Evaluation) |

---

## 📊 วิธีการประเมินผล (Assessment Ratios)

การประเมินผลแบ่งออกเป็น 3 ส่วนหลัก เน้นร่องรอยการทำงานและการพิสูจน์ความเข้าใจจริงเพื่อสกัดกั้นภาวะ Never-skilling:

### 1. กระบวนการทำงานและการเก็บร่องรอย (Process Tracking) [35%]
ประเมินบนระบบ GitHub Organization อิงจากร่องรอยเชิงวิศวกรรมจริง:
* **Git Commit History (15%):** ตรวจสอบประวัติและการกระจายตัวของ Commit เป็นรายบุคคล *(หากชี้ว่าคนใดโผล่มางอกโค้ด 500 บรรทัดในคืนเดียวก่อนส่งโดยไม่มีประวัติการทำทีละส่วนย่อยย่อมได้ 0 คะแนนในส่วนนั้น)*
* **GitHub Project Board & Pull Requests Activity (20%):** วัดจากการจัดการตั๋วงานบน Kanban และร่องรอยการพิมพ์คอมเมนต์ถกเถียง คัดค้าน หรือรีวิวโค้ดให้เพื่อนบน Pull Request เพื่อพิสูจน์พฤติกรรมการคิดจริง (Agentic Workflow)

### 2. การทดสอบและยืนยันความเข้าใจรายบุคคล (Individual Core Assessment) [35%]
* **In-Class Adversarial Quizzes (15%):** คะแนนจากการสอบ "จับผิด" ในสัปดาห์ที่ 2 และ 9 คัดกรองผ่านระบบปรนัย/เติมคำสั้นใน LMS เพื่อเช็กว่าผู้เรียนมี Schema พื้นฐานพอที่จะตรวจสอบความถูกต้องของระบบได้จริง
* **AI-Driven Oral Exam & Defense (20%):** ในสัปดาห์สุดท้าย นิสิตต้องนำโค้ดส่วนที่ตนรับผิดชอบไปทดสอบปากเปล่ากับบอทแชทที่กำหนด (เช่น Custom GPT หรือ Claude Projects) ตัวบอทจะใช้ Socratic Method ยิงคำถามจี้ถามทีละคนเพื่อวัดความเข้าใจจริง
  > ⚠️ **นโยบายสุ่มตรวจ:** อาจารย์จะเข้าไปตรวจสอบปากเปล่าด้วยตนเอง (Manual Viva) เฉพาะกลุ่มหรือรายบุคคลที่ AI ติดธงแดง (**Red Flag**) ว่ามีแนวโน้มก๊อปปี้งานมาหรือตอบคำถามไม่ได้เท่านั้น เพื่อบริหารจัดการเวลาอย่างมีประสิทธิภาพสูงสุด

### 3. ชิ้นงานและเอกสารซอฟต์แวร์สุดท้าย (Final Product Artifacts) [30%]
* **SRS, UML Diagrams & Retrospective Documents (10%):** คะแนนความสมบูรณ์ ความสอดคล้องเชิงโครงสร้าง และความถูกต้องทางวิศวกรรมของเอกสารกลุ่ม
* **Software Functionality & Quality (20%):** วัดจากฟังก์ชันการใช้งาน ความปลอดภัยพื้นฐานที่กำหนดไว้ และการส่งผ่านซอฟต์แวร์สำเร็จรูปที่ผ่านการทดสอบอัตโนมัติบนระบบ CI Pipeline (GitHub Actions)

---

## 📚 คลังข้อมูลและหนังสืออ้างอิงหลักประจำรายวิชา (Course References & Syllabus Core Data)

รายวิชานี้ผ่านการออกแบบโดยบูรณาการองค์ความรู้และทักษะจากทรัพยากรวิศวกรรมซอฟต์แวร์สากลชั้นนำ ดังรายชื่อ VERBATIM ต่อไปนี้:

### ตำราหลักและแนวคิดวิศวกรรมซอฟต์แวร์สมัยใหม่ (Core Textbooks)
* `Fundamentals of Software Engineering_ From Coder to Engineer -- Nathaniel Schutta & Dan Vega -- 2026 -- 03fa27e9885e055ca5bfdc2238f01ca7 -- Anna’s Archive_3.pdf`
* `(Global_Edition)_Ian_Sommerville_-_Software_Engineering_10th_Edition-Pearson_(2016)_3.pdf`
* `Engineering_Software_Products__An_Introduction_to_Modern_--_Ian_Sommerville_--_1_2019_--_Pearson_--_9780135210642_--_b87629f789800b0b6dc89f1b4e51b5ba_--_Annas_Archive_3.pdf`
* `Copy of Ian Sommerville - Engineering Software Products_ An Introduction to Modern Software Engineering (2020, Pearson) - libgen.li_3.pdf`
* `A Concise Introduction to Software Engineering - With Open -- Pankaj Jalote -- Undergraduate Topics in Computer Science, 2, 2025 -- SPRINGER -- 9783031743177 -- 9d87a967fb2baa82c1c70756f4b88bef -- Anna’s Archiv_3.pdf`
* `Modern Software Engineering_ Doing What Really Works to -- David  Farley; Trisha Gee -- 1, 2022 -- Pearson Education, Limited; Addison-Wesley -- isbn13 9780137314782 -- Anna’_3.pdf`
* `Modern Software Engineering_ Doing What Works to Build -- David Farley -- 2021 -- Addison-Wesley Professional -- ee860ccb1adf33439d7a4e52b2a54910 -- Anna’s Archive_3.pdf`
* `New Challenges in Software Engineering_ Volume 1 -- Jezreel Mejía · Mirna Muñoz · Alvaro Rocha · Francisco -- 1, 2025 -- Springer -- e6f584cdf0dc96349b55650ee43f24ad -- Anna’s Archive_3.pdf`
* `Responsible Software Engineering (for True Epub) -- Daniel J_ Barrett -- 2025 -- O'Reilly Media, Inc_ -- 9914e4eb6f2414347f3de156ac9fabf0 -- Anna’s Archive_3.pdf`

### การจัดการทีมและกระบวนการทำงานร่วมกัน (Agile & Team Leadership)
* `Agile Retrospectives_ Making Good Teams Great -- Esther Derby, Diana Larsen, Ken Schwaber -- July 26, 2006 -- Pragmatic Bookshelf -- isbn13 9780977616640 -- 402d3b067314377da567f88e4d162b0e -- Anna’s Archive_3.pdf`
* `From Culture to Code_Leading Software Engineering Teams -- Sosa J_ -- 2025 -- 2f316deefdbc6ae93bd3e0936e46475f -- Anna’s Archive_3.pdf`
* `Learning Git_ A Hands-On and Visual Guide to the Basics of -- Anna Skoulikari -- 1, 2023 -- O'Reilly Media -- 9781098133917 -- 8ec4aacd108f1f44e94dec36576c0d16 -- Anna’s Archive_3.pdf`

### สถาปัตยกรรมและการจัดการคุณภาพโค้ด (Architecture & Clean Code)
* `Fundamentals of Software Architecture_ A Modern Engineering -- Mark Richards, Neal Ford -- 2, 2025 mar 25 -- O'Reilly Media, Incorporated -- isbn13 9781098175511 -- ac481e941fa04cff91ea6b8f9adcc01a -- Anna’s Ar_3.pdf`
* `Software Architecture_ The Hard Parts_ Modern Trade-Off -- Neal Ford & Mark Richards & Pramod Sadalage & Zhamak -- 1, PS, 2021 -- O'Reilly Media, -- isbn13 9781492086895 -- 6abdba667e209c75f49d97e44bc16b5c -- A_3.pdf`
* `Good Code, Bad Code _ Think Like a Software Engineer -- Tom Long, (Software engineer) -- 1st edition, Erscheinungsort nicht ermittelbar, 2021 -- isbn13 9781617298936 -- 86efc5fa6411ffe18da6cc3799fe530e -- Anna’_3.pdf`
* `Grokking Simplicity _ Taming Complex Software with -- Eric Normand, (Desarrollador de software) -- Simon & Schuster, New York, 2021 -- Simon and -- isbn13 9781617296208 -- c8db3770d6b36a49587c827cec7964ed -- An_3.pdf`
* `Hands-On Software Engineering with Python, 2nd Edition -- Brian Allbee -- 2, 2025 -- Packt Publishing -- c7c95a93c0de906ee4f6a65fd0cb45f3 -- Anna’s Archive_3.pdf`
* `Soft Computing_ Engineering Applications (Edge AI in Future -- Pradip Debnath & Binod Chandra Tripathy -- 1, PT, 2025 -- CRC Press -- isbn13 9781032738529 -- cdb628b0d2b32ae91da974c3e45ab704 -- Anna’s Archive_3.pdf`

### แหล่งเรียนรู้ บล็อกวิศวกรรม และกรณีศึกษาจากอุตสาหกรรม (Tech Blogs & Platforms)
* `The latest from GitHub's engineering team - The GitHub Blog_3`
* `ByteByteGo | Top 9 Engineering Blogs_3`
* `Docker Blog | Docker_3`
* `Blog Overview | bol - Techlab_3`
* `Blog CodeIT Blog — Software Development Insights & Tech Trends_3`
* `Custom Software Development Blog | SCAND_3`
* `DEV Community_3`
* `freeCodeCamp Programming Tutorials: Python, JavaScript, Git & More_3`
* `Software News - Software Development News, Internet, World Wide Web_3`
* `The Daily WTF: Curious Perversions in Information Technology_3`
* `How to grow your ecommerce business internationally (with examples)_3`
* `Attention Required! | Cloudflare_3`

