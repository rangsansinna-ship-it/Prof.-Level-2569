# เว็บไซต์ ชก.151 — คู่มือการใช้งาน

## ไฟล์ที่มี
- `index.html` — ไฟล์เว็บไซต์หลัก
- `logo.png` — โลโก้ ชก. 151
- `banner.png` — Banner ที่ออกแบบใน Canva (**ต้องเพิ่มเอง**)

---

## 🎨 ขั้นตอนเพิ่ม Banner จาก Canva

### 1. ออกแบบใน Canva
- เข้า https://www.canva.com → สร้าง Design ใหม่
- **ขนาด Custom:** `1920 × 500 px`
- ออกแบบให้สวยตามที่ต้องการ

### 2. Export
- กดปุ่ม **Share** → **Download**
- เลือก **File type: PNG**
- บันทึกชื่อไฟล์ว่า **`banner.png`**

### 3. นำมาวาง
- วางไฟล์ `banner.png` ในโฟลเดอร์**เดียวกัน**กับ `index.html`
- เปิดเว็บใหม่ — Banner จะปรากฏอัตโนมัติ

> **หากยังไม่มี banner.png** เว็บจะแสดง Placeholder บอกวิธีการ ไม่พังครับ

---

## 🌐 นำเว็บขึ้น GitHub Pages (ทำครั้งเดียว)

### 1. สมัคร GitHub Account
- ไปที่ https://github.com → Sign up

### 2. สร้าง Repository ใหม่
- กด **New** → ตั้งชื่อ เช่น `training-2569`
- เลือก **Public** ✅ → ติ๊ก Add README → **Create**

### 3. Upload ไฟล์
- กด **Add file** → **Upload files**
- ลากไฟล์ทั้งหมดมาวาง (`index.html`, `logo.png`, `banner.png`)
- กด **Commit changes**

### 4. เปิด GitHub Pages
- **Settings** → ด้านซ้าย **Pages**
- **Source:** Deploy from a branch
- **Branch:** main / (root) → **Save**

### 5. รอ 1-2 นาที
- กลับมาที่หน้า Pages → จะเห็นลิงก์
- `https://username.github.io/training-2569`
- คัดลอกลิงก์ส่งให้ผู้เข้าอบรม

---

## ✏️ การแก้ไขทีหลัง

### เปลี่ยน Banner
- ลบ `banner.png` เดิม → Upload ไฟล์ใหม่ชื่อ `banner.png`
- รอ 1 นาที เว็บอัปเดตอัตโนมัติ

### เปลี่ยนลิงก์ Google Drive
- เข้า Repository → กดไฟล์ `index.html` → กดดินสอ (Edit)
- ค้นหา URL ที่ต้องการเปลี่ยน → แก้ไข → Commit

---

## 🧪 ทดสอบในเครื่องก่อน

ดับเบิลคลิก `index.html` ได้เลย — เปิดในเบราว์เซอร์เพื่อดูหน้าตา
