# U-WORK 999 · CFO Dashboard 2568 — Publish Pack

ครบชุดสำหรับการเผยแพร่ในทุกรูปแบบ — เลือกใช้ตามวัตถุประสงค์

---

## 📁 โครงสร้างของ Pack

```
UWORK_CFO_Publish_Pack/
├── 01_html/                          ← Interactive web dashboard
│   ├── index.html                    (พร้อม deploy ทันที)
│   └── CFO_Dashboard_UWORK999_v3.html (สำเนาชื่อยาว)
├── 02_pdf/                           ← Portable static report
│   └── UWORK_CFO_Report_2568.pdf     (19 หน้า A3 landscape)
└── 03_screenshots/                   ← Images for slides/social
    ├── 01_hero_cover.png             (1600×900 · cover)
    ├── 02_dashboard_overview.png     (charts overview)
    ├── 03_top_emitters.png           (top emitters list)
    ├── 04_equivalence.png            (54,032 = อะไรบ้าง)
    ├── 05_netzero_roadmap.png        (2568→2593 timeline)
    ├── 06_macc_curve.png             (10 มาตรการลด)
    ├── 07_cost_of_carbon.png         (฿5.4M-฿367M)
    ├── 08_live_pulse.png             (real-time counter)
    ├── 09_critical_findings.png      (6 issues)
    ├── 10_action_plan.png            (6 actions)
    └── 11_square_social.png          (1080×1080 for Line/IG)
```

---

## 🎯 ใช้แต่ละแบบเมื่อไหร่

### 📺 HTML Dashboard (`01_html/`)
**ใช้เมื่อ:** ต้องการประสบการณ์เต็มที่ — ผู้อ่านคลิกเล่น tabs, hover charts, ลาก slider, เห็นตัวเลขเดินสด

**เผยแพร่ทาง:**
- 🌐 **Public URL** — Netlify Drop (ลากไฟล์วาง 30 วินาที), GitHub Pages, Cloudflare Pages
- 🔒 **Internal portal** — โฮสต์บนเซิร์ฟเวอร์ภายในของบริษัทหลัง login
- 📤 **ส่งโดยตรง** — แนบไฟล์ใน Email/Drive ผู้รับเปิดในเบราว์เซอร์

**Best for:** ผู้บริหาร, ทีม TGO, ลูกค้าที่ต้องการเห็น drill-down

---

### 📄 PDF Report (`02_pdf/`)
**ใช้เมื่อ:** ต้องการเอกสารที่เปิดได้ทุกที่ ส่งทางไหนก็ได้ พิมพ์ออกมาได้

**เผยแพร่ทาง:**
- 📧 แนบ email (1.7 MB ไม่ใหญ่เกิน)
- 📁 อัปโหลด Google Drive / SharePoint / DocuSign
- 🖨️ พิมพ์เป็นเล่ม A3 (สามารถใช้ A4 ได้แต่ตัวอักษรจะเล็ก)
- 📲 ส่งใน Line/WhatsApp/Slack ได้

**Best for:** การส่งเป็นเอกสารราชการ · แนบรายงาน TGO, archive

---

### 🖼️ PNG Screenshots (`03_screenshots/`)
**ใช้เมื่อ:** ต้องการนำภาพไปวางใน slide / social media / โพสต์

**เผยแพร่ทาง:**
- 🎤 **PowerPoint / Keynote** — ลากภาพวางได้เลย ขนาด 1600×900 = 16:9 พอดี slide
- 📱 **Line / Facebook** — ภาพ landscape สำหรับ post, ภาพ 11 สำหรับ IG/Line square
- 📰 **บทความ / blog** — ใส่ภาพประกอบเรื่อง
- 📊 **Internal report** — แทรกใน Word document

**Best for:** Marketing, presentation, SocMed

---

## 🚀 Quick Start: เผยแพร่ใน 3 นาที

### วิธีที่เร็วที่สุด — Netlify Drop

```
1. เปิด https://app.netlify.com/drop
2. ลากไฟล์ 01_html/index.html ไปวาง
3. คัดลอก URL ที่ได้ → ส่งให้ทีม
```

ใช้ได้ทันที, HTTPS อัตโนมัติ, ฟรี

### วิธีที่ดูเป็นมืออาชีพ — GitHub Pages

```
1. สร้าง repo ใหม่ที่ github.com/new (public)
2. อัปโหลด 01_html/index.html
3. Settings → Pages → Source: main / root → Save
4. รอ 2 นาที → ได้ URL: https://[user].github.io/[repo]/
```

URL ถาวร, ดูน่าเชื่อถือ

---

## 📊 ข้อมูลสำหรับการสื่อสาร (Talking Points)

หากต้องเขียน caption / email subject / slide title ใช้ตัวเลขเหล่านี้:

**Headline numbers:**
- รวมทั้งบริษัท: **53,955 tCO₂eq**
- 19 สถานที่ · 84 รายการ · 425,645 ตร.ม.
- Carbon Intensity: 0.127 tCO₂eq/ตร.ม.

**Key insights:**
- Scope 3 = 92% (ภาพปกติของอุตสาหกรรมก่อสร้าง)
- ปูนผงก่อทั่วไปคิดเป็น 68% รายการเดียว
- ไซต์งาน 15 แห่ง = 98% ของยอดรวม
- Embodied carbon = 92% · Operational = 8%

**Call to action:**
- 6 ประเด็นทวนสอบ (2 HIGH · 2 MEDIUM · 2 LOW)
- Action plan 3 ระยะ → Net Zero 2593
- หากแก้ EF ปูน ลดได้ −34,000 ตัน (-63%)

---

## ✅ Pre-publish Checklist

- [ ] เปิดไฟล์ `01_html/index.html` ในเบราว์เซอร์ทดสอบครบทุก tab
- [ ] เปิดไฟล์ PDF ดูทุกหน้า (19 หน้า) ตรวจตัวเลข
- [ ] ตรวจสอบ screenshots 11 ภาพ ดูความคมชัด
- [ ] ตัดสินใจว่าใครจะเข้าถึงได้ (public / private / password)
- [ ] เลือกแพลตฟอร์ม deploy
- [ ] แชร์ URL/ไฟล์ตามช่องทางที่เหมาะกับผู้รับ

---

## 💡 ตัวอย่างการใช้

**For ผู้บริหาร U-WORK 999:**
- ส่ง URL HTML dashboard ทาง Email
- แนบ PDF เป็น attachment สำหรับ archive
- ใช้ screenshots ใน slide ประชุมบอร์ด

**For ทีมภายใน:**
- โฮสต์ HTML บน internal server / Slack
- Screenshots ใน case study deck
- PDF ใน folder client deliverables

**For TGO submission:**
- PDF เป็น primary document
- HTML link เป็น supplementary

**For marketing / public communication:**
- 11_square_social.png ใน Line OA / IG
- 04_equivalence.png ใน blog (ตัวเลขจับต้องได้)
- 08_live_pulse.png ใน LinkedIn (เรื่องเล่าน่าสนใจ)

---

จัดทำโดย **U-WORK 999 · CFO Reporting**
ปีฐาน 2568 · ทวนสอบตาม TGO CFO Guidelines V.6 · ISO 14064-1:2018
