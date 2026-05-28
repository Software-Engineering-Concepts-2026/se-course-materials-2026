# รายวิชา วิศวกรรมซอฟต์แวร์ (Software Engineering)

**ระดับหลักสูตร:** ปริญญาตรี ปีที่ 3 (สาขาวิทยาการคอมพิวเตอร์)  
**รูปแบบการเรียน:** บรรยาย 2 ชั่วโมง + ปฏิบัติการแล็บ 2 ชั่วโมง ต่อสัปดาห์ (รวม 15 สัปดาห์)  
**ผู้สอน:** อาจารย์ประจำรายวิชา อ.กิ๊ก (ไม่มีผู้ช่วยสอน - TA)  
**ช่องทางส่งงานหลัก:** [GitHub Organization ของรายวิชา]

---

## 🎯 เป้าหมายรายวิชา (Course Objective)
รายวิชานี้มุ่งเน้นให้นักศึกษาเข้าใจและประยุกต์ใช้หลักการ ระเบียบวิธี และเครื่องมือทางวิศวกรรมซอฟต์แวร์ตลอดวัฏจักรการพัฒนาซอฟต์แวร์ (SDLC) ผ่านการลงมือปฏิบัติจริงในรูปแบบโปรเจกต์ทีม (Project-Based Learning) โดยสามารถวิเคราะห์ความต้องการ ออกแบบสถาปัตยกรรม เขียนโค้ดตามมาตรฐาน ทดสอบระบบ ควบคุมคุณภาพ และบริหารจัดการโครงการด้วยแนวคิด Agile/Scrum ร่วมกับเครื่องมือ DevOps สมัยใหม่ ควบคู่ไปกับการสร้างวินัยในการทำงานร่วมกันผ่านระบบ Git และการพัฒนาทักษะการตรวจสอบความถูกต้องเชิงตรรกะในยุค Generative AI เพื่อป้องกันภาวะพึ่งพา AI จนขาดทักษะพื้นฐาน (Never-skilling)

---

## 📅 แผนการสอนและกิจกรรมรายสัปดาห์ (15-Week Syllabus)

| สัปดาห์ที่ (Week) | หัวข้อบรรยาย (Lecture Focus - 2 ชม.) | กิจกรรมห้องปฏิบัติการ (Lab Focus - 2 ชม.) | สิ่งส่งมอบ / หมายเหตุ (Deliverables / Notes) |
| :---: | :--- | :--- | :--- |
| **1** | **Introduction to SE, SDLC & Process Models**<br>• ภาพรวมวิศวกรรมซอฟต์แวร์และวิวัฒนาการ<br>• Process Models: Waterfall vs. Agile<br>• บทบาทหน้าที่ในทีมและสัญญาร่วมของทีม (Working Agreement) | **GitHub Workflow & Team Setup**<br>• จัดกลุ่มโปรเจกต์ (ทีมละ 5-6 คน)<br>• ตอบรับคำเชิญเข้า GitHub Org<br>• ฝึกใช้ Git Command Line ขั้นพื้นฐาน (Clone, Commit, Push, Pull) | • จัดตั้งกลุ่มและเลือกหัวข้อโปรเจกต์ทีม<br>• สมาชิกทุกคนทำการ Commit ประวัติทีมเข้าคลังข้อมูลกลุ่มบน GitHub |
| **2** | **Software Requirements & Elicitation**<br>• การเก็บรวบรวมความต้องการ (Elicitation Techniques)<br>• Functional vs. Non-Functional Requirements<br>• โครงสร้างเอกสารข้อกำหนดความต้องการซอฟต์แวร์ (SRS) | 🧪 **[สอบจับผิด] In-Class Adversarial Quiz #1**<br>• กิจกรรมวิเคราะห์และจับผิดเอกสาร SRS ที่เจนโดย AI ซึ่งผู้สอนซ่อน Bug เชิงตรรกะและข้อขัดแย้งไว้ 3-4 จุด รายบุคคล | • **คะแนนรายบุคคล:** คะแนนสอบจับผิดครั้งที่ 1<br>• **งานกลุ่ม:** ร่างเอกสารความต้องการขั้นต้น (Initial User Stories) |
| **3** | **Agile Requirements & Project Management**<br>• การเขียน User Stories และการประมาณการงานแบบง่าย (Story Points)<br>• การจัดลำดับความสำคัญ (Product Backlog Refinement)<br>• แนะนำเครื่องมือ GitHub Projects (Kanban Board) | **Agile Board & Backlog Setup**<br>• ร่วมกันแตก User Stories ของโปรเจกต์ลงสู่ GitHub Projects Board ของกลุ่ม<br>• กำหนดสิทธิ์และมอบหมายงาน (Issue Assignment) | • **Deliverable:** GitHub Projects Board ที่เปิดใช้งานจริง มีตั๋วงาน (Issues) และการมอบหมายงานที่ชัดเจน |
| **4** | **System Modeling & Architectural Design**<br>• หลักการออกแบบระบบและการแบ่งส่วนย่อย (Modularity, Cohesion, Coupling)<br>• การออกแบบสถาปัตยกรรมซอฟต์แวร์ขั้นแนะนำ (Client-Server, MVC)<br>• Use Case Diagram และ Sequence Diagram | **System Modeling Workshop**<br>• สมาชิกทีมระดมสมองและออกแบบ Use Case และ Sequence Diagram สำหรับฟังก์ชันหลักของโปรเจกต์ทีมจริง | • **Deliverable:** แผนภาพ Use Case และ Sequence Diagram ร่างแรก อัปโหลดขึ้นคลังซอร์สโค้ดในรูปแบบไฟล์รูปภาพหรือ Markdown (Mermaid.js) |
| **5** | **Detailed Design & Object-Oriented Modeling**<br>• Class Diagram และความสัมพันธ์ระหว่างออบเจกต์<br>• หลักการออกแบบซอฟต์แวร์พื้นฐาน (เช่น SOLID Principles เบื้องต้น)<br>• สถาปัตยกรรมฐานข้อมูลและแนวทางการเชื่อมต่อ | **Class Diagram & DB Schema Mapping**<br>• ออกแบบ Class Diagram ของระบบเพื่อเตรียมพร้อมสำหรับการเริ่มเขียนโค้ด<br>• เชื่อมโยงสถาปัตยกรรมตัวเลือกกับฐานข้อมูล | • **Deliverable:** เอกสาร **SRS ฉบับสมบูรณ์** และ **Class Diagram** ที่ผ่านการอนุมัติร่วมกันภายในทีม ส่งเข้า GitHub |
| **6** | **Construction & Coding Standards**<br>• มาตรฐานการเขียนโค้ด (Coding Standards) และระเบียบวิธีที่ดี<br>• การทำงานร่วมกันผ่าน Git Branching Strategy (Feature Branching)<br>• การจัดการ Pull Requests และสิทธิ์ในคลังซอร์สโค้ด | **Collaborative Construction Kick-off**<br>• ตั้งค่าโครงสร้างโปรเจกต์เริ่มต้น (Project Boilerplate)<br>• เริ่มต้น Sprint 1: แยก Branch ทำงานตาม Issues บนบอร์ด | • **Deliverable:** โครงสร้างโปรเจกต์หลักบน GitHub และร่องรอยประวัติ Commit แรกของสมาชิกแต่ละคน (เริ่มกระบวนการ Process Tracking) |
| **7** | **Software Construction & Tech Debt**<br>• การอ่านซอร์สโค้ดและการสืบหารอยโรคในโค้ด (Code Smells)<br>• หนี้ทางเทคนิคระดับเบื้องต้น (Technical Debt Intro)<br>• แนวคิดการปรับปรุงโครงสร้างโค้ด (Refactoring Concept) | **Sprint 1 Execution & Peer Review**<br>• ลงมือเขียนโค้ดโปรเจกต์ทีมอย่างต่อเนื่อง<br>• ฝึกฝนการทำ Code Review กันเองภายในทีมผ่าน GitHub Pull Requests | • **Process Tracking:** สุ่มตรวจความถี่และรายละเอียดของ Commit History และกิจกรรมบนบอร์ด Kanban ของทีม |
| **8** | **Midterm Week**<br>*(ไม่มีการบรรยายและแล็บ)* | **Midterm Progress Sync**<br>• อาจารย์สุ่มตรวจความคืบหน้าของโค้ดใน GitHub Organization และสรุปฟีดแบ็กรายกลุ่ม | • **Deliverable:** ซอร์สโค้ดเวอร์ชันเสถียรเวอร์ชันแรก (Alpha Release) ที่รันได้จริงบางส่วนบน GitHub |
| **9** | **Software Testing Foundations**<br>• ระดับของการทดสอบ (Unit, Integration, System, UAT)<br>• เทคนิคการออกแบบกรณีทดสอบ (Test Case Design)<br>• ความสำคัญของการเขียนชุดทดสอบอัตโนมัติ (Automated Testing) | 🧪 **[สอบจับผิด] In-Class Adversarial Quiz #2**<br>• กิจกรรมค้นหา Bug และความบกพร่องเชิงตรรกะในชุดโค้ดสำเร็จรูป (ซ่อน Bug เนียนๆ 3-4 จุด) โดยวิเคราะห์รายบุคคลในห้องแล็บ | • **คะแนนรายบุคคล:** คะแนนสอบจับผิดครั้งที่ 2 (วัด Schema การทำความเข้าใจและตรวจสอบโค้ดที่เจนโดย AI) |
| **10** | **Unit Testing & Test-Driven Development (TDD)**<br>• หลักการเขียน Unit Test ที่ดีและครอบคลุม<br>• แนวคิด Test-Driven Development (TDD) เบื้องต้น<br>• เครื่องมือทดสอบ Unit Test ตามภาษาที่ทีมเลือกใช้ (เช่น JUnit, PyTest) | **Unit Test Implementation**<br>• ลงมือเขียน Unit Test และสร้าง Test Case ให้กับโค้ดโมดูลหลักในโปรเจกต์จริงของนักศึกษา | • **Deliverable:** Pull Request ที่ประกอบด้วยโค้ดระบบควบคู่ไปกับไฟล์ชุดคำสั่ง Unit Test ที่เขียนขึ้นจริง |
| **11** | **Quality Control & DevOps Overview**<br>• การควบคุมคุณภาพซอฟต์แวร์ด้วย Static Analysis<br>• แนวคิดพื้นฐานของ DevOps และวงจรการส่งมอบอัตโนมัติ<br>• Continuous Integration (CI) มีบทบาทอย่างไรในวิศวกรรมซอฟต์แวร์ | **GitHub Actions Setup (CI Pipeline)**<br>• ฝึกฝนการเขียนเวิร์กโฟลว์สำหรับ GitHub Actions<br>• เชื่อมต่อ CI Pipeline เพื่อสั่งรัน Unit Test และตรวจ Linting อัตโนมัติทุกครั้งที่มีการ Push โค้ด | • **Deliverable:** ไฟล์คอนฟิก CI (`.github/workflows/`) ที่รันผ่านสำเร็จและแสดงสถานะ Passing Status บน GitHub |
| **12** | **Software Security Basics**<br>• ความปลอดภัยในระดับรายวิชาพื้นฐาน SE (Secure Coding Concepts)<br>• ข้อกำหนดด้านความปลอดภัยพื้นฐาน (Basic Security Requirements)<br>• การจัดการช่องโหว่และการซ่อนความลับ (Secret Management) | **Security Scanning Integration**<br>• ตรวจสอบสิทธิ์และการซ่อน API Keys / Secrets ไม่ให้หลุดไปบนคลังสาธารณะ<br>• เพิ่มเครื่องมือสแกนโค้ดเบื้องต้นเข้า CI | • **Deliverable:** ซอร์สโค้ดที่มีการจัดเก็บ Secret อย่างปลอดภัย และปรับปรุงตามฟีดแบ็กด้านความปลอดภัยพื้นฐาน |
| **13** | **Maintenance, Evolution & Metrics**<br>• การบำรุงรักษาซอฟต์แวร์หลังการส่งมอบ (Software Maintenance)<br>• การประเมินคุณภาพโค้ดด้วยตัวชี้วัดพื้นฐาน (Basic Software Metrics)<br>• วิธีจัดการและลด Technical Debt ในชีวิตจริง | **Sprint 2 Execution & Code Hardening**<br>• เก็บตกฟังก์ชันการทำงานต่างๆ ของโปรเจกต์<br>• ตรวจทานความเรียบร้อยและแก้ Bug ที่หลงเหลือเพื่อเตรียมตัวสำหรับ Final Product Deployment | • **Process Tracking:** สุ่มตรวจร่องรอยการเดินทางของโค้ดและการแก้ไขงานผ่านประวัติ Pull Requests บนคลังซอร์สโค้ด |
| **14** | **Software Deployment & Team Retrospective**<br>• กลยุทธ์การปรับใช้ซอฟต์แวร์และการส่งมอบ (Deployment Strategies)<br>• ความสำคัญของการทำ Sprint Retrospective เพื่อพัฒนาทีม<br>• การประเมินผลการทำงานร่วมกันภายในวิศวกรรมทีม | **Final Release & Prep Presentation**<br>• ทีมร่วมกัน Deploy ซอฟต์แวร์ขึ้นระบบจำลองหรือคลาวด์<br>• ฝึกฝนการวิเคราะห์และสรุปบทเรียนการพัฒนาซอฟต์แวร์ในรูปแบบทีม | • **Deliverable:** ลิงก์ซอฟต์แวร์ที่ใช้งานได้จริง (Live Demo Link) บนหน้าหลักของ GitHub คลังซอร์สโค้ดกลุ่ม |
| **15** | **Project Demo & AI-Driven Oral Defense**<br>*(ไม่มีการบรรยาย)* | 🤖 **AI-Driven Oral Exam & Retrospective**<br>• นักศึกษาทุกคนเข้าทดสอบปากเปล่ารายบุคคลกับ AI Bot ที่ระบุไว้เพื่อพิสูจน์ความเข้าใจจริงในโค้ดและเอกสารที่ส่งมอบ | • **Deliverables:**<br>1. ผลคะแนนล็อกบทสนทนาจาก AI Bot และใบสรุปคะแนนประเมินเพื่อนร่วมทีม (Peer Evaluation)<br>2. ซอร์สโค้ดฉบับสมบูรณ์และเอกสารรายงานฉบับสุดท้าย (Final Project Report) บน GitHub |

---

## 📊 เกณฑ์การประเมินผล (Assessment Ratios)

เพื่อป้องกันภาวะ **Never-skilling** และให้ความสำคัญกับ **"กระบวนการเรียนรู้และวินัยในการทำวิศวกรรมซอฟต์แวร์"** มากกว่าเพียงแค่ผลลัพธ์สุดท้ายที่อาจพึ่งพา AI เจนมาโดยไม่เข้าใจ รายวิชานี้จึงใช้สัดส่วนคะแนนดังนี้:

### 1. กระบวนการทำงานและการเก็บร่องรอย (Process Tracking) [30%]
* **Git Commit Workflow (15%):** ตรวจสอบความถี่ ความละเอียด และความสอดคล้องของประวัติ Commit History รายบุคคล *(กรณีที่โค้ดงอกมา 500+ บรรทัดในคืนเดียวก่อนส่งโดยไม่มีประวัติการทำงานย่อย = 0 คะแนน)*
* **Code Review & Board Activity (15%):** ตรวจร่องรอยการสื่อสารและการรีวิวโค้ดร่วมกันผ่านระบบ GitHub Pull Request ตลอดจนความคืบหน้าในการขยับตั๋วงานบน GitHub Projects Board

### 2. การสอบวัดความเข้าใจรายบุคคล (Individual Assessments) [35%]
* **In-Class Adversarial Quizzes (15%):** คะแนนจากการทดสอบจับผิดโค้ดหรือเอกสารความต้องการซอฟต์แวร์ (SRS) ที่ซ่อนจุดพังเชิงตรรกะไว้ เพื่อวัด Schema พื้นฐานในหัวของนักศึกษา (สัปดาห์ที่ 2 และ 9)
* **AI-Driven Oral Exam & Defense (20%):** การสอบปากเปล่าสัปดาห์สุดท้ายรายบุคคลผ่าน AI Bot ที่ตั้งระบบไว้ เพื่อตอบคำถามเชิงจี้ถามและพิสูจน์ความเข้าใจจริงในโค้ดส่วนของตนเอง *(ผู้สอนจะเข้าแทรกแซงเพื่อทำการสอบปากเปล่าแบบดั้งเดิม (Manual Viva) เฉพาะนักศึกษาที่ AI ติดธงแดง [Red Flag] ว่าไม่เข้าใจงานหรือก๊อปปี้มาเท่านั้น)*

### 3. ผลผลิตเชิงวิศวกรรมซอฟต์แวร์ (Core Software Engineering Artifacts) [15%]
* **SRS Document & Agile Backlog (7.5%):** ความสมบูรณ์ ถูกต้อง และสามารถตรวจสอบวัดผลได้ของเอกสารความต้องการซอฟต์แวร์ ควบคู่กับการแตกประเด็นงานลงสู่ตั๋วบนระบบบอร์ด
* **System Architecture & Modeling (7.5%):** ความถูกต้องเชิงโครงสร้างและการเชื่อมโยงกันของสถาปัตยกรรม แผนภาพ UML (Use Case, Sequence, Class Diagram)

### 4. ซอฟต์แวร์สุดท้ายและการตรวจสอบอัตโนมัติ (Final Product & CI Verification) [20%]
* **Automated Verification via CI Pipeline (10%):** ซอฟต์แวร์ของกลุ่มสามารถทำงานได้จริงตามขอบเขตที่ตกลงกันไว้ และสามารถตรวจสอบผ่านระบบ Continuous Integration (GitHub Actions) โดยคำสั่งทดสอบ Unit Test ที่เขียนไว้จะต้องผ่านทั้งหมด (Passing Status)
* **Final Product Usability & Live Demo (10%):** ซอฟต์แวร์สามารถแสดงผลและใช้งานจริงได้อย่างมีสิทธิภาพตามเป้าหมายของโครงการ

---
*หมายเหตุ: สัดส่วนคะแนนและแผนการสอนนี้ได้รับการออกแบบมาเพื่อให้สอดคล้องกับการดูแลผู้เรียนสเกลใหญ่ (90 คน) โดยใช้ระบบอัตโนมัติและสถาปัตยกรรมการเรียนรู้ช่วยแบ่งเบาภาระงานของผู้สอนและส่งเสริมให้ผู้เรียนเกิดทักษะที่แท้จริง*
