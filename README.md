# Papa2 ป.3 — JSON แยกตามรายวิชา

โครงสร้างนี้จัดทำจากไฟล์ต้นฉบับ พว. ป.3 ชุดที่ 1 จำนวน 2,850 ข้อ

## โครงสร้าง

questions/
└── p3/
    ├── p3_thai.json
    ├── p3_math.json
    ├── p3_science.json
    ├── p3_social.json
    ├── p3_history.json
    ├── p3_english.json
    ├── p3_work.json
    ├── p3_art.json
    └── p3_health.json

p3_all_2850.json
└── สำรองรวมข้อสอบทั้งหมด

## การใช้งานใน Papa2

เมื่อเด็กเลือกวิชา ให้โหลดเฉพาะ JSON ของวิชานั้น
เช่น คณิตศาสตร์ → questions/p3/p3_math.json

จากนั้นกรองด้วย:
- unit_id
- topic_id
- skill_ids

แล้วสุ่มข้อสอบตามจำนวนที่กำหนด เช่น 20 ข้อ

หมายเหตุ:
- ข้อมูลที่ไม่มีในไฟล์ต้นฉบับจะไม่ถูกแต่งเติม
- topic_id, learning_objective และ difficulty อาจว่าง
