# 🌐 The Living Existence Network (LEN)
*"โครงสร้างดิจิทัลที่มีชีวิต — ปรับตัว วิวัฒน์ และปกป้องการดำรงอยู่ของผู้ใช้โดยอัตโนมัติ"*

---

## 📖 ภาพรวม (Overview)
**The Living Existence Network (LEN)** คือสถาปัตยกรรมเครือข่ายแบบกระจายศูนย์รุ่นใหม่ที่ก้าวข้ามโมเดล TCP/IP แบบดั้งเดิม
แทนที่จะเป็นเพียงระบบส่ง packet LEN ถูกออกแบบให้เป็นโครงสร้างที่ **"มีชีวิต"** — สามารถปรับ topology ตัวเองได้อัตโนมัติ ฟื้นฟูเมื่อเกิดความผิดพลาด และปกป้องความเป็นส่วนตัวในระดับสถาปัตยกรรม ไม่ใช่แค่ระดับ application

## ✨ คุณสมบัติหลัก (Key Features)
* 🧬 **Self-Evolving Topology:** Evolution Engine วิเคราะห์สถานะเครือข่ายและปรับ topology อัตโนมัติ — ตัดเส้นทางที่ช้า เพิ่มเส้นทางใหม่เมื่อ traffic หนาแน่น โดยไม่ต้องหยุดระบบ
* 🛡️ **Zero-Downtime Self-Healing:** เมื่อ Node ล้มเหลว ระบบตรวจจับและหาเส้นทางสำรองในระดับมิลลิวินาที Node สามารถฟื้นฟูตัวเองผ่าน lifecycle: `ACTIVE → DEGRADED → FAILED → HEALING → ACTIVE`
* 🔒 **Structural Privacy:** ข้อมูลผูกกับตัวตนโดยโครงสร้าง (Identity-Bound Encryption) ไม่สามารถเข้าถึงได้หากไม่ใช่เจ้าของ ไม่ต้องพึ่ง policy ระดับ application
* ✋ **Consent-Before-Transmit:** ไม่มี ExistencePacket ใดถูกส่งได้โดยไม่ได้รับการยินยอมจากผู้รับก่อน บังคับใช้ผ่าน ConsentManager ในระดับ protocol
* 🌌 **Multi-Reality Integration:** รองรับการเชื่อมต่อข้าม Physical, Virtual และ Simulation layers พร้อมกัน

## 🏗️ สถาปัตยกรรม 5 ชั้น (5-Layer Architecture)
```text
[5] Reality Integration Layer      ← เชื่อมโลกจริง โลกเสมือน และระบบจำลอง
[4] Human Awareness Layer          ← ป้องกัน Cognitive Overload, บังคับ Consent
[3] Existence Communication Layer  ← ExistencePacket + ETP Protocol
[2] Evolution Engine               ← ปรับ topology อัตโนมัติ
[1] Infrastructure Layer           ← Node runtime, Routing, Self-Healing

โครงสร้าง Repository (Project Structure)
├── README.md
├── demo.html
├── docs/
│   ├── Architecture_Spec.md
│   ├── Implementation_Plan.md
│   ├── Formalization.md
│   ├── Book_Theoretical.md
│   ├── DAFT-Extended-Edition.md
│   ├── special-edition.md
│   └── Edition-Comparison.md
├── planning/
│   ├── Sprint_Plan.md
│   └── Role_and_Responsibility.md
└── src/
    ├── Coding.md
    └── test_results.md

Sprint ProgressSprintเป้าหมายสถานะ
Sprint AlphaNode Runtime, Basic Routing, Unit Tests🟢 เสร็จสิ้น
Sprint 3Bug Fixes, Domain Mapping, CI/CD Pipeline🟢 เสร็จสิ้น
Sprint 4Maturity Metrics, Ethics/Governance, MVP🟢 เสร็จสิ้น

ทีมพัฒนา (Development Team)
ทีมพัฒนา
ชื่อ				รหัสนักศึกษา				บทบาท
ธนธัช วรรณไทย 	673380403-2 		Architect
จีรภัทร แก้วดี 	673380577-9		Tester/QA
อนัตตา โยคาพจร 	673380429-4		Engineer
ธีธัช ลิมประยูรวงศ์ 	673380408-2		Specialist
ยุทธนา เหล่าวิสัย 	673380422-8		DevOps
