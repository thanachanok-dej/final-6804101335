# Software Testing Final Exam - Playwright TypeScript

โครงการทดสอบระบบอัตโนมัติ (Automated Testing) สำหรับเว็บไซต์ [SauceDemo](https://www.saucedemo.com/) โดยใช้เครื่องมือ Playwright Test ร่วมกับภาษา TypeScript ครอบคลุมการทดสอบ 3 ระดับ ได้แก่ Unit/UI Component Testing, Integration Testing (Top-Down และ Bottom-Up) และ System Testing (End-to-End)

## รายชื่อสมาชิก / ผู้จัดทำ
- **รหัสนักศึกษา:** [6804101335]
- **ชื่อ - นามสกุล:** [thanachanok dejbandit]
- **สาขาวิชา:** วิทยาการคอมพิวเตอร์ ชั้นปีที่ 2 มหาวิทยาลัยแม่โจ้

---

## โครงสร้างโปรเจกต์ (Project Structure)
```text
final-exam/
├── README.md
├── package.json
├── package-lock.json
├── playwright.config.ts
├── tests/
│   ├── unit/
│   │   ├── UT-01.spec.ts
│   │   └── UT-02.spec.ts
│   ├── integration/
│   │   ├── IT-01.spec.ts
│   │   └── IT-02.spec.ts
│   └── system/
│       ├── ST-01.spec.ts
│       └── ST-02.spec.ts
├── playwright-report/
│   ├── index.html
│   └── data/
└── reports/
    ├── results.json
    └── test-summary.md