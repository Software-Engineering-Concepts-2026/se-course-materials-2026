# ประมวลรายวิชา (Course Syllabus)

## รายวิชา: Software Engineering Concepts (แนวคิดวิศวกรรมซอฟต์แวร์)

**จำนวนสัปดาห์:** 15 สัปดาห์

**รูปแบบการเรียนการสอน:** บรรยายร่วมกับการปฏิบัติการ (Lecture & Hands-on Lab)

**การวัดผล:** โครงงานและการประเมินผลอย่างต่อเนื่อง 100% (ไม่มีการสอบทฤษฎีในห้องสอบ)

---

### 1. คำอธิบายรายวิชา (Course Description)

ศึกษาแนวคิด ปรัชญา และหลักการของวิศวกรรมซอฟต์แวร์สมัยใหม่ เปรียบเทียบการพัฒนารูปแบบโครงการ (Project-based) กับรูปแบบผลิตภัณฑ์ (Product-based) ปลูกฝังทัศนติแบบ "Pragmatic Programmer" การบริหารจัดการโครงการด้วยแนวคิด Agile (Scrum & Extreme Programming) การวิเคราะห์ความต้องการและการจำลองสถานการณ์ผู้ใช้ (Personas, User Stories) การสร้างต้นแบบอย่างรวดเร็วโดยใช้ AI ช่วยเหลือ (AI-Assisted Prototyping)

ศึกษาหลักการออกแบบสถาปัตยกรรมซอฟต์แวร์ (Software Architecture) และสถาปัตยกรรมสมัยใหม่บนคลาวด์ (Cloud-Native & Microservices) การสร้างสรรค์โค้ดที่สะอาด (Clean Code) การประกันคุณภาพและการทดสอบอัตโนมัติ (TDD, Unit Testing) วัฒนธรรมและกระบวนการ DevOps (CI/CD Pipeline, Infrastructure as Code) วิศวกรรมซอฟต์แวร์ที่ปลอดภัยและความเป็นส่วนตัวของข้อมูล (Secure by Design & Data Privacy) เทคนิคการปรับปรุงโครงสร้างโค้ด (Refactoring) เพื่อลดหนี้ทางเทคนิค ตลอดจนจรรยาบรรณวิชาชีพและแนวโน้มในอนาคตของวิศวกรรมซอฟต์แวร์

---

### 2. วัตถุประสงค์การเรียนรู้ (Learning Objectives)

เมื่อนิสิตศึกษาเนื้อหาและปฏิบัติงานในรายวิชานี้ครบ 15 สัปดาห์แล้ว จะมีความสามารถตามองค์ประกอบ 3 ด้าน ดังนี้:

#### 2.1 ด้านความรู้และทักษะทางปัญญา (Cognitive & Intellectual Skills)

* **LO1:** สามารถ**อธิบายและเปรียบเทียบ**ความแตกต่างระหว่างการพัฒนารูปแบบโครงการ (Project-based) และการพัฒนาผลิตภัณฑ์ซอฟต์แวร์ (Product-based) ในบริบทของอุตสาหกรรมยุคปัจจุบันได้ถูกต้อง
* **LO2:** สามารถ**วิเคราะห์และตัดสินใจ (Trade-off Analysis)** ในการเลือกรูปแบบสถาปัตยกรรมซอฟต์แวร์ (เช่น Monolith vs Microservices) และเทคโนโลยีสแตก (Tech Stack) ให้เหมาะสมกับข้อกำหนดของระบบทั้งในแง่ฟังก์ชันและคุณลักษณะที่ไม่ใช่ฟังก์ชัน (Non-functional attributes)
* **LO3:** สามารถ**ออกแบบระบบการทดสอบและกระบวนการส่งมอบซอฟต์แวร์** โดยประยุกต์ใช้หลักการของ Test-Driven Development (TDD) และ DevOps (CI/CD) ได้อย่างเป็นระบบ

#### 2.2 ด้านทักษะการปฏิบัติและทักษะวิชาชีพ (Practical & Professional Skills)

* **LO4:** สามารถ**ประยุกต์ใช้กระบวนการทำงานแบบ Agile (Scrum & XP)** เพื่อบริหารจัดการงานและสปรินต์ (Sprint) ร่วมกับทีมผ่านเครื่องมือสมัยใหม่ (เช่น GitHub Projects) ได้อย่างมีประสิทธิภาพ
* **LO5:** สามารถ**แปลงความต้องการของผู้ใช้ (Requirements)** จากรูปแบบ Personas และ Scenarios ให้กลายเป็น User Stories และเกณฑ์การยอมรับ (Acceptance Criteria) ที่สามารถนำไปพัฒนาต่อได้จริง
* **LO6:** สามารถ**สร้าง ปรับปรุง (Refactor) และปกป้องซอฟต์แวร์** โดยใช้แนวคิด Clean Code หลักการ DRY/ETC การเขียน Dockerfile และการประยุกต์ใช้มาตรการความปลอดภัยขั้นพื้นฐาน (Secure by Design)
* **LO7:** สามารถ**เลือกและใช้เครื่องมือ Generative AI (เช่น GitHub Copilot, ChatGPT)** ในฐานะผู้ช่วยเพื่อเพิ่มประสิทธิภาพในการทำต้นแบบ (Prototyping) การเขียนโค้ด และการสร้างชุดทดสอบอัตโนมัติได้อย่างชาญฉลาด

#### 2.3 ด้านทักษะทางสังคม จริยธรรม และการสื่อสาร (Soft Skills, Ethics & Communication)

* **LO8:** สามารถ**สื่อสาร นำเสนอ และสาธิตซอฟต์แวร์ (Software Demo)** ที่ทำงานได้จริงให้แก่ผู้มีส่วนได้ส่วนเสีย พร้อมทั้งอธิบายเหตุผลเบื้องหลังการตัดสินใจเชิงวิศวกรรมได้อย่างชัดเจนและเป็นมืออาชีพ
* **LO9:** มีความรับผิดชอบในการ**ทำงานร่วมกันเป็นทีมผ่านระบบควบคุมเวอร์ชัน (Git/GitHub)** มีวินัยในการส่งมอบงานอย่างสม่ำเสมอ และสามารถตรวจสอบย้อนกลับกระบวนการทำงานของตนเองได้ (Git Contribution)
* **LO10:** มีความตระหนักรู้ในเรื่อง**จรรยาบรรณวิชาชีพ (Professional Ethics)** และตระหนักถึงความรับผิดชอบในประเด็นความปลอดภัยและความเป็นส่วนตัวของข้อมูลผู้ใช้ (Data Privacy / PDPA)

---

### 3. ปรัชญาและแนวทางการวัดผล (Grading & Assessment Philosophy)

รายวิชานี้เน้นปรัชญา **"Pragmatic" (การลงมือทำ การแก้ปัญหาจริง และเรียนรู้จากประสบการณ์)** การประเมินผลจะพิจารณาจากผลงานที่จับต้องได้ (Tangible Artifacts) และกระบวนการทำงานที่มีคุณภาพ (Quality Process) ผ่านระบบ GitHub เป็นหลัก โดยเก็บคะแนนสะสมอย่างต่อเนื่องตลอดทั้งภาคการศึกษา (Continuous Assessment 100%) เพื่อส่งเสริมการเรียนรู้เชิงลึกและลดความกดดันจากการสอบท่องจำ **(ไม่มีการสอบทฤษฎีในห้องสอบ)**

#### สัดส่วนการประเมินผล (Grading Scheme)

| องค์ประกอบการประเมิน (Assessment Component) | สัดส่วนคะแนน | วัตถุประสงค์ที่สอดคล้อง |
| --- | --- | --- |
| **A. งานปฏิบัติการรายสัปดาห์ (Weekly Labs)** | **25%** | LO4, LO5, LO6, LO7, LO9 |
| **B. สอบกลางภาค: Project Milestone 1** | **25%** | LO1, LO2, LO5, LO6, LO9 |
| **C. โครงงานปลายภาค และการนำเสนอ (Final Project & Demo)** | **35%** | LO2, LO3, LO6, LO8, LO9 |
| **D. การมีส่วนร่วมและผลงานรายบุคคล (Individual Contribution)** | **15%** | LO9, LO10 |
| **รวม** | **100%** |  |

---

### 4. รายละเอียดเกณฑ์การประเมินผล (Rubrics)

* **A. งานปฏิบัติการรายสัปดาห์ (Weekly Labs) - 25%:** ตรวจสอบจากการส่งงาน (Commit) บน GitHub Repository ของแต่ละทีม เน้นการให้คะแนนแบบ *Completion and Effort* (ทำครบถ้วนตามโจทย์และแสดงให้เห็นถึงความพยายาม) เพื่อกระตุ้นให้นิสิตกล้าทดลองและเรียนรู้จากข้อผิดพลาด
* **B. สอบกลางภาค: Project Milestone 1 - 25%:** ประเมินความสมบูรณ์ของคลังโค้ด ณ สิ้นสุดสัปดาห์ที่ 7 แบ่งเป็น Project Management & Process (5%), Requirements & Design Artifacts (5%), Code Quality (10%), และ Repository & Docker Documentation (5%)
* **C. โครงงานปลายภาคและการนำเสนอ (Final Project & Demo) - 35%:** ประเมิน ณ สัปดาห์ที่ 14 จากความสามารถในการทำงานของซอฟต์แวร์จริง (10%), ความยอดเยี่ยมทางเทคนิคและสถาปัตยกรรม (10%), ความสมบูรณ์ของ DevOps Pipeline (5%), ทักษะการนำเสนอและสาธิต Demo (5%), และเอกสารคู่มือพัฒนา (5%)
* **D. การมีส่วนร่วมและผลงานรายบุคคล (Individual Contribution) - 15%:** วิเคราะห์ผลงานรายบุคคลผ่าน Git History Analysis ดูความถี่และความสม่ำเสมอในการส่งมอบงาน (10%) และการส่งงานเขียนถอดบทเรียนและความเข้าใจท้ายเทอม Final Reflection (5%)

---

### 5. แผนการเรียนรายสัปดาห์และเอกสารอ่านประกอบ (15-Week Course Outline)

#### [ ครึ่งแรกของภาคการศึกษา: Foundation, Agility & Architecture ]

* **สัปดาห์ที่ 1: Introduction to Modern Software Engineering & The Pragmatic Mindset**
* **เนื้อหา:** ปูพื้นฐานวิศวกรรมซอฟต์แวร์ยุคปัจจุบัน; เปรียบเทียบ Project-based vs Product-based; ปลูกฝังทัศนคติ "Pragmatic Programmer" ความรับผิดชอบ และการเรียนรู้ตลอดชีวิต
* **งานปฏิบัติการ (Lab 1 - 1%):** *First Pragmatic Commit* — ส่งไฟล์ `<your-name>.md` ที่เขียนสะท้อนความคิดลงบน GitHub
* **เอกสารอ่านประกอบ:** [ESP] Chapter 1-2, [PP] Chapter 1


* **สัปดาห์ที่ 2: Agile Methodologies: Scrum & Extreme Programming (XP)**
* **เนื้อหา:** เจาะลึกหลักการ Agile Manifesto; กระบวนการทำงานของ Scrum (Roles, Events, Artifacts); แนวปฏิบัติทางเทคนิคจาก Extreme Programming (XP) เพื่อสร้างซอฟต์แวร์ที่คล่องตัว
* **งานปฏิบัติการ (Lab 2 - 2%):** *Sprint Zero Setup* — ตั้งค่า GitHub Projects Board และร่วมกันสร้าง Product Backlog ของทีม
* **เอกสารอ่านประกอบ:** [ESP] Chapter 3


* **สัปดาห์ที่ 3: Modern Requirements: Personas, Scenarios, and User Stories**
* **เนื้อหา:** เทคนิคการเก็บและวิเคราะห์ความต้องการยุคใหม่; เปลี่ยนเอกสารซับซ้อนให้เป็นความเข้าใจผู้ใช้ผ่าน Personas; จำลองสถานการณ์ด้วย Scenarios และแจกแจงงานด้วย User Stories
* **งานปฏิบัติการ (Lab 3 - 2%):** *Requirements Documentation* — ส่งมอบเอกสาร Personas และ Scenarios ไว้อย่างเป็นระบบในโฟลเดอร์ `docs/`
* **เอกสารอ่านประกอบ:** [ESP] Chapter 4-5


* **สัปดาห์ที่ 4: Prototyping and Introduction to AI-Assisted Development**
* **เนื้อหา:** แนวทางการสร้างต้นแบบ (Prototype) เพื่อทดสอบไอเดียอย่างรวดเร็ว; การใช้เครื่องมือ Generative AI (GitHub Copilot, ChatGPT) ในฐานะผู้ช่วยรังสรรค์โค้ดและต้นแบบ
* **งานปฏิบัติการ (Lab 4 - 2%):** *Rapid Prototyping* — ส่งมอบไฟล์ Prototype (HTML/CSS/JS) ที่สามารถทำงานและโต้ตอบเบื้องต้นได้
* **เอกสารอ่านประกอบ:** [ESP] Chapter 6, [SCG] Chapter 1-3


* **สัปดาห์ที่ 5: Fundamentals of Software Architecture**
* **เนื้อหา:** ความสำคัญของสถาปัตยกรรมซอฟต์แวร์ต่อคุณภาพระยะยาว; การวิเคราะห์ Trade-offs; คุณลักษณะที่ไม่ใช่ฟังก์ชัน (Non-functional attributes); หลักการแบ่งส่วนระบบ (System Decomposition)
* **งานปฏิบัติการ (Lab 5 - 2%):** *Architectural Artifacts* — ออกแบบและส่งมอบ C4 Diagrams และไฟล์เอกสาร `tech_stack.md`
* **เอกสารอ่านประกอบ:** [ESP] Chapter 7, [PP] Chapter 5


* **สัปดาห์ที่ 6: Architectural Patterns: Cloud-Native and Microservices**
* **เนื้อหา:** รูปแบบสถาปัตยกรรมสมัยใหม่บนคลาวด์; แนวคิด Virtualization และ Containers; หลักการออกแบบ Microservices Architecture เพื่อระบบที่ยืดหยุ่นและขยายตัวได้ง่าย
* **งานปฏิบัติการ (Lab 6 - 3%):** *First Container* — เขียนและส่งมอบ Dockerfile สำหรับ Microservice แรก พร้อมทดลอง Push Image ขึ้น Docker Hub
* **เอกสารอ่านประกอบ:** [ESP] Chapter 8-9


* **สัปดาห์ที่ 7: Pragmatic Programming: The Art of Clean Code Construction**
* **เนื้อหา:** การเขียนโค้ดที่สะอาดและมีคุณภาพสูงจากแก่นปรัชญา Pragmatic Programmer; เรียนรู้หลักการ DRY (Don't Repeat Yourself), Orthogonality, และแนวคิด "Easier to Change" (ETC)
* **งานปฏิบัติการ (Lab 7 - 2%):** *Refactoring Commit* — ปรับปรุงโค้ดให้สะอาดขึ้น พร้อมส่งมอบด้วย Commit Message ที่ถูกต้องตามมาตรฐาน
* **เอกสารอ่านประกอบ:** [PP] Chapter 2 & Chapter 4
* *หมายเหตุ: กำหนดส่งมอบ Project Milestone 1 (สอบกลางภาค) ณ สิ้นสุดสัปดาห์นี้*


* **สัปดาห์ที่ 8: Midterm Examination Period (No Classes)**
* **เนื้อหา:** *งดการเรียนการสอน* เพื่อให้นิสิตทุ่มเทกับการสอบกลางภาคในรายวิชาอื่นได้อย่างเต็มที่ (ไม่มีคะแนนในสัปดาห์นี้)



---

#### [ ครึ่งหลังของภาคการศึกษา: Quality, DevOps & Delivery ]

* **สัปดาห์ที่ 9: Quality Assurance & Automated Testing**
* **เนื้อหา:** การสร้างวัฒนธรรมคุณภาพในซอฟต์แวร์; เรียนรู้ Test-Driven Development (TDD) และ Unit Testing; ขยายผลสู่ Integration & System Testing; การใช้ AI เร่งกระบวนการสร้างและดูแล Test Suites
* **งานปฏิบัติการ (Lab 9 - 3%):** *Unit Test Implementation* — ส่งมอบไฟล์ Unit Test (`test_*.py` หรือตามภาษาที่ใช้) และตั้งค่าระบบ CI Workflow พื้นฐาน
* **เอกสารอ่านประกอบ:** [ESP] Chapter 11, [PP] Chapter 7, [SCG] Chapter 6


* **สัปดาห์ที่ 10: The DevOps Pipeline: From CI to CD and Infrastructure as Code**
* **เนื้อหา:** หลักการ DevOps เพื่อการส่งมอบซอฟต์แวร์อัตโนมัติครบวงจร; การจัดการ Git Branching; การสร้าง Continuous Integration (CI) และ Continuous Delivery/Deployment (CD) Pipeline; แนะนำแนวคิด Infrastructure as Code (IaC)
* **งานปฏิบัติการ (Lab 10 - 3%):** *Full CI/CD Pipeline* — ส่งมอบไฟล์ Workflow การทำงานที่สมบูรณ์ (เช่น Build, Test และ Push Docker Image อัตโนมัติ)
* **เอกสารอ่านประกอบ:** [ESP] Chapter 10, [SCG] Chapter 8


* **สัปดาห์ที่ 11: Secure Software Engineering & Data Privacy**
* **เนื้อหา:** การสร้างซอฟต์แวร์ให้ปลอดภัยตั้งแต่เริ่มต้น (Secure by Design); การป้องกันช่องโหว่พื้นฐานที่นักพัฒนาต้องรู้; ความรับผิดชอบทางกฎหมายและจริยธรรมเกี่ยวกับความเป็นส่วนตัวของข้อมูล (Data Privacy / PDPA)
* **งานปฏิบัติการ (Lab 11 - 3%):** *Security Hardening* — ส่งมอบโค้ดที่มีระบบ Input Validation และการจัดการคีย์ความลับผ่านไฟล์ `.env` (Secrets Management)
* **เอกสารอ่านประกอบ:** [ESP] Chapter 12, [PP] Chapter 6


* **สัปดาห์ที่ 12: Advanced Refactoring & Code Maintenance**
* **เนื้อหา:** การจัดการหนี้ทางเทคนิค (Technical Debt); เทคนิคการปรับปรุงโครงสร้างโค้ดเดิมที่ซับซ้อนให้บำรุงรักษาง่ายในระยะยาว; การใช้ AI เป็นผู้ช่วยวิเคราะห์และเสนอแนะแนวทางแก้ไข Code Smells
* **งานปฏิบัติการ (Lab 12 - 2%):** *Advanced Refactoring* — ตรวจสอบ แก้ไข และปิดประเด็น (Issues) ของ Code Smells ที่ถูกเปิดไว้ในคลังโค้ด
* **เอกสารอ่านประกอบ:** [PP] Chapter 8, [SCG] Chapter 5


* **สัปดาห์ที่ 13: Project Workshop & Final Sprint Consultation**
* **เนื้อหา:** คาบปฏิบัติการและทำงานร่วมกันเต็มรูปแบบ (Workshop); นิสิตลงมือพัฒนาโปรเจกต์ใน Sprint สุดท้าย; รับคำปรึกษาเชิงลึกจากอาจารย์ผู้สอน (Final Consultation) เพื่อเตรียมความพร้อมขั้นสุดท้าย
* **งานปฏิบัติการ:** ไม่มีคะแนน Lab ย่อย (เน้นการโค้ชชิ่งกลุ่มเพื่อเตรียมความพร้อมสำหรับวัน Demo)
* **เอกสารอ่านประกอบ:** [PP] Chapter 9


* **สัปดาห์ที่ 14: Final Project Presentations & Demo Day**
* **เนื้อหา:** วันนำเสนอผลงานโครงงานปลายภาค (Demo Day); แต่ละกลุ่มนำเสนอผลิตภัณฑ์ซอฟต์แวร์ที่ทำงานได้จริง (Working Software) ต่อหน้าสาธารณะ อธิบายการตัดสินใจเชิงสถาปัตยกรรม และสาธิตกระบวนการทำงานแบบ Agile/DevOps ที่ใช้จริง
* **การประเมินผล:** ประเมินคะแนนโครงงานปลายภาคและการนำเสนอ (35%)


* **สัปดาห์ที่ 15: Professional Practice, Ethics, and The Future of Software Engineering**
* **เนื้อหา:** สรุปภาพรวมรายวิชา; อภิปรายเรื่องจรรยาบรรณวิชาชีพวิศวกรซอฟต์แวร์; การวางแผนเส้นทางอาชีพ (Career Path); ร่วมวิเคราะห์อนาคตของ Software Engineering และผลกระทบของ AI ต่อบทบาทนักพัฒนาในทศวรรษหน้า
* **งานส่งมอบ:** *Final Reflection* — ส่งเล่มหรือไฟล์สะท้อนความคิดรายบุคคล (คิดเป็นคะแนนส่วนบุคคล 5%)
* **เอกสารอ่านประกอบ:** [ESP] Chapter 13, [PP] Chapter 1 (Topic: Code Management & Responsibility)



---

### 6. เอกสารอ้างอิงเพื่อการศึกษาค้นคว้าหลัก (Core References)

* **[ESP]** Sommerville, I. (2019). *Engineering Software Products: An Introduction to Modern Software Engineering*. Pearson.
* **[PP]** Hunt, A., & Thomas, D. (2019). *The Pragmatic Programmer: Your Journey to Mastery* (2nd ed.). Addison-Wesley Professional.
* **[SCG]** Herszfang, H. P., & Henstock, P. V. (2025). *Supercharged Coding with GenAI*. Packt Publishing.
