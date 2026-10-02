วิธีupload เบื้องต้น โหลดGit มาด้วยในCMD
วิธีupload
git init
git add .
git branch -M main
git remote add origin https://github.com/GSSun0000/CCTVProject.git
git push -u origin main

# 📹 CCTVProject

ระบบบันทึกและจัดการกล้องวงจรปิด (CCTV Monitoring & Management System)

---

## 📌 ภาพรวมโครงการ (Overview)
**CCTVProject** คือระบบที่พัฒนาขึ้นเพื่อจัดการ สตรีม และบันทึกสัญญาณภาพจากกล้องวงจรปิด (IP Camera / RTSP) แบบรวมศูนย์ ช่วยให้ผู้ดูแลระบบสามารถตรวจสอบภาพสดและดูบันทึกย้อนหลังได้อย่างสะดวก ปลอดภัย และมีประสิทธิภาพ

---

## ✨ ฟีเจอร์หลัก (Features)
- 🔴 **Live Streaming:** รองรับการดึงสัญญาณภาพสดผ่านโปรโตคอล RTSP / HTTP
- 💾 **Video Recording:** ระบบบันทึกวิดีโออัตโนมัติ พร้อมตั้งเวลาหรือบันทึกตามเหตุการณ์
- 🚨 **Motion & Event Detection:** ตรวจจับความเคลื่อนไหวและแจ้งเตือนเมื่อพบสิ่งผิดปกติ
- 📊 **Dashboard:** หน้าจอแสดงผลสถานะกล้องและข้อมูลเหตุการณ์

---

## 🛠 เทคโนโลยีที่ใช้ (Tech Stack)
- **Language:** Python / JavaScript / C++ *(แก้ไขตามที่ใช้งานจริง)*
- **Computer Vision & Video:** OpenCV, FFmpeg
- **Frameworks:** *(เช่น FastAPI, Flask, React, Node.js)*
- **Database:** *(เช่น SQLite, PostgreSQL, MongoDB)*

---

## 🚀 วิธีการติดตั้งและใช้งาน (Getting Started)

### 1. โคลนคลังโค้ด (Clone Repository)
\`\`\`bash
git clone https://github.com/GSSun0000/CCTVProject.git
cd CCTVProject
\`\`\`

### 2. ติดตั้ง Dependencies
\`\`\`bash
pip install -r requirements.txt
# หรือ npm install (กรณีใช้ Node.js)
\`\`\`

### 3. ตั้งค่าระบบ (Configuration)
สร้างและแก้ไขไฟล์ตั้งค่า (เช่น `.env` หรือ `config.json`):
\`\`\`text
RTSP_URL=rtsp://username:password@ip_address:554/stream
PORT=8000
\`\`\`

### 4. เริ่มต้นระบบ (Run Project)
\`\`\`bash
python main.py
\`\`\`

---

## 📤 วิธีอัปโหลดโค้ดขึ้น GitHub (สำหรับทีมพัฒนา)

\`\`\`bash
# 1. เตรียมไฟล์ทั้งหมด
git add .

# 2. บันทึก Commit
git commit -m "Update project files"

# 3. ส่งโค้ดขึ้น GitHub
git push origin main
\`\`\`

---

## 👥 สมาชิกผู้พัฒนา (Contributors)
- GSSun0000 และทีมงาน

## 📄 ลิขสิทธิ์ (License)
โปรเจกต์นี้เปิดให้ใช้งานและพัฒนาต่อเพื่อการศึกษา/ใช้งานส่วนบุคคล
