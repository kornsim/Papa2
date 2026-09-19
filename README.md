# Papa2 v2.3 — External JSON Question Bank

`index.html` โหลดข้อสอบจาก `questions/*.json` ผ่าน `fetch()` และตรวจสอบก่อนใช้

Validator ตรวจ:
- JSON object
- questions array
- id มีและห้ามซ้ำ
- question ไม่ว่าง
- options 4 ตัว
- option ไม่ว่าง
- answer integer 0–3
- คำถามซ้ำ = warning
- ตัวเลือกซ้ำ = warning

ถ้ามี error จะไม่โหลดคลังนั้นเข้าเกม
