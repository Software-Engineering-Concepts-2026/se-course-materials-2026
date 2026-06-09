# ประมวลรายวิชา (Course Syllabus)
## **Course Syllabus: แนวคิดวิศวกรรมซอฟต์แวร์ (Software Engineering Concepts)**

### **คำอธิบายรายวิชา (Course Description)**

รายวิชานี้จะนำพานิสิต/นักศึกษาเข้าสู่โลกของวิศวกรรมซอฟต์แวร์สมัยใหม่ โดยเปลี่ยนกระบวนทัศน์จากการพัฒนาซอฟต์แวร์ตามคำสั่ง (Project-based) ไปสู่การสร้างผลิตภัณฑ์ (Product-based) ที่ขับเคลื่อนด้วยแนวคิด Agile และ DevOps นิสิตจะได้เรียนรู้ตลอดวงจรชีวิตการพัฒนาซอฟต์แวร์ (SDLC) ตั้งแต่การทำความเข้าใจผู้ใช้ผ่าน Personas และ User Stories, การออกแบบสถาปัตยกรรมที่ยืดหยุ่น (Cloud-Native & Microservices), การสร้างโค้ดคุณภาพสูงตามปรัชญา Pragmatic Programmer, ไปจนถึงการสร้างกระบวนการทดสอบและส่งมอบอัตโนมัติ (CI/CD) โดยตลอดทั้งรายวิชาจะมีการประยุกต์ใช้เครื่องมือ Generative AI (เช่น GitHub Copilot, ChatGPT) ในฐานะผู้ช่วยเพื่อเร่งกระบวนการเรียนรู้และพัฒนา

### **วัตถุประสงค์การเรียนรู้ (Learning Objectives)**

เมื่อสิ้นสุดการเรียนการสอน นิสิตจะสามารถ:
1.  ประยุกต์ใช้ปรัชญาและหลักการออกแบบซอฟต์แวร์ที่สำคัญได้ (ETC, DRY, Orthogonality)
2.  ออกแบบและจัดทำเอกสารสถาปัตยกรรมซอฟต์แวร์โดยใช้แนวปฏิบัติสมัยใหม่ (C4 Model, ADRs)
3.  พัฒนาซอฟต์แวร์โดยใช้วินัย Test-Driven Development (TDD) และสร้างชุดทดสอบอัตโนมัติที่ครอบคลุม
4.  สร้างและบริหารจัดการท่อส่ง CI/CD อัตโนมัติด้วย GitHub Actions เพื่อทำการทดสอบและส่งมอบ Docker Image
5.  ประยุกต์ใช้หลักการความปลอดภัยพื้นฐานในการพัฒนาแอปพลิเคชัน (Input Validation, Secret Management)
6.  วิเคราะห์, ระบุ, และลงมือปรับปรุงโครงสร้างโค้ด (Refactoring) เพื่อชำระหนี้ทางเทคนิค (Technical Debt)
7.  สื่อสารแนวคิดทางเทคนิคและนำเสนอผลงานโครงการได้อย่างมืออาชีพ
8.  ใช้เครื่องมือ Generative AI (GitHub Copilot, ChatGPT) เพื่อช่วยในกระบวนการพัฒนาซอฟต์แวร์ได้อย่างมีประสิทธิภาพและมีวิจารณญาณ

### **เอกสารอ้างอิงเพื่อการศึกษาค้นคว้าหลัก (Core References)**

*   **[ESP]** Sommerville, I. (2019). *Engineering Software Products: An Introduction to Modern Software Engineering*. Pearson.
*   **[PP]** Hunt, A., & Thomas, D. (2019). *The Pragmatic Programmer: Your Journey to Mastery* (2nd ed.). Addison-Wesley Professional.
*   **[SCG]** Herszfang, H. P., & Henstock, P. V. (2025). *Supercharged Coding with GenAI*. Packt Publishing.

---

แน่นอนครับ ผมได้รวบรวมและสังเคราะห์การปรับปรุงทั้งหมดที่เราได้ทำร่วมกัน และจัดทำเป็น **"แผนการสอนฉบับสมบูรณ์ (Final Course Syllabus)"** ที่มีความสอดคล้อง, ลึกซึ้ง, และทันสมัย พร้อมสำหรับการนำไปใช้งานจริงในภาคการศึกษา

นี่คือแผนการสอนฉบับสมบูรณ์สำหรับรายวิชา **Modern Software Engineering** ครับ

---

**การประเมินผล (Assessment Scheme):**
*   **25%** - งานปฏิบัติการรายสัปดาห์ (Weekly Labs)
*   **25%** - สอบกลางภาค: Project Milestone 1 (ส่งมอบสิ้นสัปดาห์ที่ 7)
*   **35%** - โครงงานปลายภาค และการนำเสนอ (Final Project & Demo)
*   **15%** - การมีส่วนร่วมและผลงานรายบุคคล (Individual Contribution & Reflection)

---

### **โครงสร้างการเรียนการสอนรายสัปดาห์**

#### **Module 1: Foundations & The Agile Mindset**

**[สัปดาห์ที่ 1: Introduction to Modern Software Engineering & The Pragmatic Mindset](./Week1/README.md)**
*   **Lecture:** ทำความเข้าใจความแตกต่างระหว่าง Project-based vs. Product-based, รู้จัก Modern Software Execution Models (SaaS), และปลูกฝังปรัชญา Pragmatic Programmer (Take Responsibility, Software Entropy).
*   **Lab:** ก่อตั้งทีม, เลือก Theme ของโปรเจกต์, สร้าง Project Charter, ตั้งค่า GitHub Repository ใน Organization, และส่งมอบงานชิ้นแรกผ่านกระบวนการ Git Workflow และ Pull Request ที่ถูกต้อง

**สัปดาห์ที่ 2: Agile Methodologies: Scrum & Extreme Programming (XP)**
*   **Lecture:** เจาะลึกปรัชญาและคุณค่าของ Agile Manifesto, ทำความเข้าใจกรอบการทำงาน Scrum (3 Pillars, Roles, Events, Artifacts), และเรียนรู้แนวปฏิบัติทางวิศวกรรมจาก Extreme Programming (XP) ที่เป็นเครื่องยนต์ขับเคลื่อนคุณภาพ
*   **Lab:** จำลอง "Sprint Zero" โดยใช้ GitHub Projects สร้าง Product Backlog จาก User Stories, ฝึกฝนการประเมินขนาดงานด้วย Planning Poker, และวางแผนสำหรับ Sprint 1

**สัปดาห์ที่ 3: Modern Requirements: Personas, Scenarios, and User Stories**
*   **Lecture:** เรียนรู้เทคนิคการ "ค้นพบ" ความต้องการแทนการ "รวบรวม" ผ่านการสร้าง Personas เพื่อสร้าง Empathy, การเล่าเรื่องผ่าน Scenarios เพื่อสำรวจบริบท, และการสกัดงานด้วย User Stories ที่มีคุณภาพตามเกณฑ์ INVEST
*   **Lab:** Workshop การสร้าง Personas และ Scenarios สำหรับโปรเจกต์ของทีมโดยใช้ GenAI เป็นผู้ช่วย, จากนั้นสกัด User Stories ที่ได้ไปปรับปรุง Product Backlog และจัดเก็บเอกสารทั้งหมดลง Git

**สัปดาห์ที่ 4: Prototyping and Introduction to AI-Assisted Development**
*   **Lecture:** ทำความเข้าใจปรัชญาการสร้างต้นแบบเพื่อ "การเรียนรู้" (Prototype to Learn), เปรียบเทียบความแตกต่างระหว่าง Low-Fidelity และ High-Fidelity Prototypes, และวิเคราะห์ความแตกต่างเชิงกลยุทธ์ระหว่าง Prototypes (ใช้แล้วทิ้ง) และ Tracer Bullets (โครงสร้างเพื่อต่อยอด) พร้อมแนะนำเครื่องมือ GenAI และหลักการ Prompt Engineering (The Five S's)
*   **Lab:** ลงมือปฏิบัติการ AI-Powered Prototyping โดยการแปลง User Story ให้กลายเป็น Interactive Mockup ที่ทำงานได้จริง โดยใช้ GitHub Copilot สร้างโครงสร้าง HTML/CSS และใช้ ChatGPT สร้างโค้ด JavaScript สำหรับการโต้ตอบเบื้องต้น

#### **Module 2: Architecture & Clean Code Construction**

**สัปดาห์ที่ 5: Fundamentals of Software Architecture**
*   **Lecture:** เจาะลึกนิยามของสถาปัตยกรรมซอฟต์แวร์, การวิเคราะห์ Trade-offs, และผลกระทบต่อคุณภาพระบบ (-ilities) เรียนรู้แนวคิดพื้นฐานในการออกแบบ (Decomposition, Layered Architecture, Client-Server, MVC) และหลักการวัดคุณภาพ (Low Coupling, High Cohesion) พร้อมแนะนำการบันทึกการตัดสินใจด้วย ADRs
*   **Lab:** Workshop การร่างพิมพ์เขียวสถาปัตยกรรมด้วย C4 Model (Context & Container Diagrams) และฝึกฝนการตัดสินใจเลือก Tech Stack อย่างมีเหตุผลพร้อมบันทึกเป็น ADR-001

**สัปดาห์ที่ 6: Architectural Patterns: Cloud-Native and Microservices**
*   **Lecture:** ทำความเข้าใจกระบวนทัศน์ Cloud-Native ผ่าน 3 เสาหลัก (Scalability, Elasticity, Resilience) และเทคโนโลยีพื้นฐาน (VMs vs. Containers) จากนั้นเปรียบเทียบสถาปัตยกรรม Monolith กับ Microservices และเรียนรู้ส่วนประกอบสำคัญ (API Gateway, Service Discovery)
*   **Lab:** ลงมือปฏิบัติการ "Decomposing the Monolith" โดยการแยกฟังก์ชันหนึ่งออกมาสร้างเป็น Microservice ด้วย Python/Flask, เขียน Dockerfile ด้วยความช่วยเหลือจาก AI, และรันเป็น Container ที่ทำงานได้อย่างอิสระ

**สัปดาห์ที่ 7: Pragmatic Programming & Milestone 1 Finalization**
*   **Lecture:** สรุปและเจาะลึกหลักการเขียนโค้ดคุณภาพจาก "The Pragmatic Programmer" ได้แก่ DRY, Orthogonality, Decoupling, Design by Contract, และการเขียนโค้ดอย่างมีเจตนา (Programming Deliberately)
*   **Lab:** เป็นช่วงเวลาทำงานและให้คำปรึกษา (Work Session & Consultation) เพื่อให้ทุกทีมทำการ Peer Review และ Refactor โค้ดของตนเองตามหลักการที่เรียนมา และตรวจสอบความครบถ้วนของงานทั้งหมดเพื่อเตรียมส่งมอบ Project Milestone 1
*   **Submission:** **ส่งมอบ Project Milestone 1 ณ สิ้นสัปดาห์**

**สัปดาห์ที่ 8: Midterm Examination Period (No Classes)**
*   **กิจกรรม:** เว้นว่างจากการเรียนการสอน เพื่อให้นิสิต/นักศึกษามีเวลาสำหรับการสอบกลางภาคในรายวิชาอื่นๆ

#### **Module 3: Quality, Delivery, and Professional Practice**

**สัปดาห์ที่ 9: Quality Assurance & Automated Testing**
*   **Lecture:** สร้างความเข้าใจในวัฒนธรรมคุณภาพผ่าน Testing Pyramid, เจาะลึกกระบวนการ Test-Driven Development (TDD), และเรียนรู้เทคนิคการเขียน Unit Test ที่ดี (AAA Pattern, Mocking) พร้อมสำรวจการใช้ AI ช่วยสร้างชุดการทดสอบ
*   **Lab:** ลงมือปฏิบัติการ TDD เพื่อสร้างฟังก์ชันใหม่, เขียน Unit Tests สำหรับโค้ดเดิมโดยใช้ AI ช่วย, และสร้าง GitHub Actions Workflow แรกสำหรับ Continuous Integration (CI)

**สัปดาห์ที่ 10: The DevOps Pipeline: From CI to CD and Infrastructure as Code**
*   **Lecture:** ทำความเข้าใจวัฒนธรรม DevOps, เรียนรู้กระบวนการส่งมอบอัตโนมัติเต็มรูปแบบจาก Continuous Integration (CI) สู่ Continuous Delivery/Deployment (CD), และแนวคิด Infrastructure as Code (IaC)
*   **Lab:** ต่อยอด CI Workflow จากสัปดาห์ที่แล้วให้กลายเป็น CD Pipeline ที่สมบูรณ์ โดยเพิ่มขั้นตอนการ Build และ Push Docker Image ของ Microservice ขึ้นไปยัง Docker Hub โดยอัตโนมัติ

**สัปดาห์ที่ 11: Secure Software Engineering & Data Privacy**
*   **Lecture:** เรียนรู้หลักการพัฒนาซอฟต์แวร์ให้ปลอดภัย (Secure by Design), ทำความรู้จักช่องโหว่ที่พบบ่อย (SQL Injection, XSS), และตระหนักถึงความรับผิดชอบทางจริยธรรมและกฎหมายในการปกป้องข้อมูลส่วนบุคคลของผู้ใช้ (Data Privacy)
*   **Lab:** ลงมือ "เสริมความแข็งแกร่ง" ให้โปรเจกต์ โดยการเพิ่ม Input Validation ในฝั่งเซิร์ฟเวอร์ และย้ายข้อมูลลับ (Secrets) ทั้งหมดออกจากโค้ดไปจัดการผ่าน Environment Variables (`.env` file)

**สัปดาห์ที่ 12: Advanced Refactoring & Code Maintenance**
*   **Lecture:** เจาะลึกแนวคิด "หนี้ทางเทคนิค" (Technical Debt) และเรียนรู้เทคนิคการ "ชำระหนี้" ผ่านการ Refactoring เรียนรู้วิธีการระบุ "Code Smells" และใช้เทคนิคต่างๆ (เช่น Extract Method) เพื่อปรับปรุงโครงสร้างโค้ด
*   **Lab:** Workshop การทำ Code Smell Hunt ในโปรเจกต์ของตนเอง, เปิด Issue เพื่อติดตาม Technical Debt, และลงมือ Refactor โค้ดโดยใช้เครื่องมืออัตโนมัติใน IDE และความช่วยเหลือจาก GenAI

**สัปดาห์ที่ 13: Project Workshop & Final Sprint Consultation**
*   **Lecture:** สรุปภาพรวมและให้คำแนะนำสำหรับการนำเสนอโครงงานปลายภาค, การเล่าเรื่อง (Storytelling), และการสาธิตที่มีประสิทธิภาพ
*   **Lab:** เป็นคาบทำงานเต็มรูปแบบ (Work Session) สำหรับ Sprint สุดท้าย โดยมีอาจารย์คอยให้คำปรึกษาเชิงลึก (Deep-Dive Consultation) กับแต่ละทีมเพื่อเตรียมความพร้อมสำหรับ Demo Day

**สัปดาห์ที่ 14: Final Project Presentations & Demo Day**
*   **กิจกรรม:** แต่ละทีมนำเสนอและสาธิตการทำงานของโครงงานปลายภาคที่เสร็จสมบูรณ์ อธิบายการตัดสินใจเชิงสถาปัตยกรรม และแสดงให้เห็นถึงกระบวนการทำงานแบบมืออาชีพที่ได้เรียนรู้มาตลอดทั้งเทอม พร้อมช่วง Q&A และการให้ Feedback จากเพื่อนร่วมชั้น

**สัปดาห์ที่ 15: Professional Practice, Ethics, and The Future of Software Engineering**
*   **Lecture:** สรุปภาพรวมจรรยาบรรณวิชาชีพ, การวางแผนเส้นทางอาชีพ, และการเรียนรู้ตลอดชีวิต (Managing Your Knowledge Portfolio) พร้อมอภิปรายถึงอนาคตของวิศวกรรมซอฟต์แวร์และผลกระทบของ AI ต่อบทบาทของนักพัฒนา
*   **Lab:** กิจกรรม "Team Retrospective" เพื่อทบทวนการทำงานในโปรเจกต์ และปิดท้ายด้วยเซสชัน "Career Q&A" กับอาจารย์

---
