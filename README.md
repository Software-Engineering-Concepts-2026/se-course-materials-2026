# 💻 วิชา 225311 Software Engineering Concepts (ปีการศึกษาต้น 2569)

ยินดีต้อนรับอาจารย์ ผู้ช่วยสอน (TAs) และนิสิตชั้นปีที่ 3 สาขาวิทยาการคอมพิวเตอร์ทุกคนเข้าสู่พื้นที่ปฏิบัติการและคลังซอฟต์แวร์กลางประจำรายวิชาครับ 

องค์กรนี้ถูกตั้งขึ้นเพื่อเป็นพื้นที่เรียนรู้และจำลอง "สภาพแวดล้อมการทำงานจริงในอุตสาหกรรมซอฟต์แวร์" (Industry-strength Environment) ผ่านโครงงานแบบกลุ่มตลอดภาคการศึกษา

---

## 🎯 กฎเหล็กและข้อตกลงการใช้งาน (Ground Rules)

เพื่อสร้างวัฒนธรรมการพัฒนาซอฟต์แวร์ที่ดีและเป็นมืออาชีพ นิสิตทุกคนต้องปฏิบัติตามกฎวิศวกรรมซอฟต์แวร์ดังต่อไปนี้:

1. **[No Broken Windows] รักษามาตรฐานโค้ด:** ห้ามเขียนโค้ดแบบลักไก่ สมาชิกทุกคนต้องปฏิบัติตาม Coding Standards และ Linters ที่กำหนดร่วมกันในทีม
2. **[Branch Governance] ห้าม Push เข้า Main โดยตรง:** ทุกฟีเจอร์ต้องแยกสายออกไปทำใน Feature Branch (เช่น `feature/login`) และผสานกลับผ่านระบบ **Pull Request (PR)** เท่านั้น
3. **[Automated Testing] ท่อสีเขียวเท่านั้น:** ตั้งแต่สัปดาห์ที่ 11 ระบบ Continuous Integration (CI) ผ่าน GitHub Actions จะเปิดทำงาน ปุ่ม Merge จะถูกล็อกหากท่อทดสอบเป็นสีแดง (รัน Unit Tests หรือ Static Analysis ไม่ผ่าน)
4. **[Auditability & Tracking]:** ประวัติคลัง (Commit History), บอร์ดบริหารงาน (**GitHub Projects**), และระบบรีวิวโค้ด จะถูกใช้ตรวจสอบ Contribution Insights เพื่อคิดคะแนนรายบุคคลจริง (ป้องกันปัญหา Free Rider)

---

## 📂 โครงสร้าง Repository ภายในองค์กร

- **`course-materials`**: คลังเก็บเอกสาร Template, ไฟล์ตั้งค่า .gitignore มาตรฐาน, สไลด์บรรยาย และคำชี้แจงโจทย์แล็บรายสัปดาห์ (สิทธิ์: Read-only สำหรับนิสิต)
- **`lab-[assignment-name]-[username]`**: คลังส่วนตัวสำหรับส่งใบงานและแล็บเดี่ยวรายสัปดาห์ที่จ่ายงานผ่านระบบ
- **`project-[team-name]`**: คลังส่วนกลางของแต่ละกลุ่มสำหรับลุยโปรเจกต์เทอม (สิทธิ์: Write สำหรับสมาชิกทีม และ Read-only สำหรับกลุ่มอื่นในช่วงทำ Peer Review)

---

## 📊 สัดส่วนคะแนนพาร์ทปฏิบัติการ (รวม 60%)

| ส่วนการประเมิน | สัดส่วน | รายละเอียดเครื่องมือที่ใช้ตรวจสอบ |
| :--- | :---: | :--- |
| **Lab Deliverables** | 20% | ความถูกต้องของ Artifacts (SRS, UML Diagrams, Test Cases) ในแต่ละสัปดาห์ |
| **Project Management** | 10% | ความเคลื่อนไหวบน GitHub Project Board, ความถี่ของการ commit และระบบ PR Workflow |
| **Software Quality** | 20% | โครงสร้างสถาปัตยกรรม, ระดับความครอบคลุมของ Unit Testing และผลลัพธ์จากท่อ CI |
| **Demo & Presentation** | 5% | ความสมบูรณ์ของฟีเจอร์ในระบบ Production วันนำเสนอเวอร์ชันสุดท้าย |
| **Peer Evaluation** | 5% | คะแนนประเมินพฤติกรรมการทำงานเป็นทีมจากเพื่อนในกลุ่มเดียวกัน |

---

## 🛠️ รายชื่อผู้ดูแลและช่องทางการติดต่อ

- **อาจารย์ผู้รับผิดชอบรายวิชา:** อ.ธรรมรัตน์ [thammarat.th@up.ac.th]
- **ทีมผู้ช่วยสอน (TAs):** หาคนอยู่ครับ [ระบุชื่ออีเมล / ช่องทาง Slack หรือ Discord ถ้ามี]

*“True ownership of code is not defined by authorship. It is the possession of a robust and accurate mental model of a system's behavior, its dependencies, and its failure modes.”*
