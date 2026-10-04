# DigiNex AI – Narrative Dashboard
วิชา **Business Idea Creation** | กลุ่มอุตสาหกรรมดิจิทัล

## รายชื่อกลุ่ม
| รหัสนักศึกษา | ชื่อ-สกุล |
|---|---|
| 67160376 | สิรภพ ณ ระนอง |
<!-- เพิ่มสมาชิกคนอื่นในตารางนี้ -->

## โครงสร้าง Repository
- `index.html` – Dashboard เชิงเล่าเรื่อง (เปิดในเบราว์เซอร์ได้เลย ไม่ต้องติดตั้ง)
- `data/` – ข้อมูลที่ใช้ (CSV)
  - `revenue_by_stream.csv` รายรับแยกตาม Revenue Streams (ล้านบาท/ไตรมาส)
  - `costs.csv` รายจ่ายแยกตาม Cost Structure (ล้านบาท/ไตรมาส)
  - `segments.csv` ลูกค้าและสัดส่วนรายได้ตาม Customer Segments
  - `channels.csv` Leads และการปิดการขายตาม Channels

## เรื่องที่ Dashboard เล่า
ตลาด/ลูกค้า → รายรับ → ต้นทุน → กำไร → ช่องทาง → ข้อเสนอแนะ
เชื่อมกับ Business Model Canvas, SWOT, 4M, 4P และ Branding ของ DigiNex AI

## หมายเหตุ
ข้อมูลเป็น **ข้อมูลจำลอง (Illustrative/Simulated)** ที่ออกแบบให้สอดคล้องกับ Business Model Canvas ของบริษัทสมมติ ไม่ใช่ตัวเลขจริง
ข้อมูลใน `index.html` ฝังไว้ตรงกับไฟล์ใน `data/`

## วิธีส่ง/เผยแพร่
`git init && git add . && git commit -m "DigiNex AI dashboard" ` แล้ว push ขึ้น GitHub (เปิด GitHub Pages ที่ branch main ได้)
