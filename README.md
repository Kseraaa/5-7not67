# ☁️ Cloud Computing Lab: Vercel Deployment

ยินดีต้อนรับสู่แล็บแรกของวิชา Cloud Computing! ในแล็บนี้คุณจะได้เรียนรู้การนำเว็บไซต์ขึ้นแพลตฟอร์ม Cloud (PaaS) ผ่านระบบ CI/CD Automation

---

## 🚀 ขั้นตอนการทำแล็บ

### 1. Clone โปรเจกต์ลงเครื่อง
เปิด Terminal แล้วรันคำสั่ง:
```bash
git clone https://github.com/Kseraaa/5-7not67.git
```

เปลี่ยนชื่อ-นามสกุลให้เป็นของตัวเอง
สร้าง repo ใหม่และ push code ของตัวเอง
```bash
git remote add origin <ใส่-URL-Repository-ตัวเอง>
git add .
git commit -m "feat: update my student profile"
git push -u origin main
```
### 2. Deploy ขึ้นบน Vercel (Cloud Deployment)
ล็อกอินเข้าสู่ระบบที่ Vercel.com ด้วยบัญชี GitHub

บนหน้า Dashboard ให้กดปุ่ม "Add New..." ➔ เลือก "Project"

ระบบจะแสดงรายการ Repository บน GitHub ของคุณ ให้กดปุ่ม "Import" โปรเจกต์ของตัวเอง

ปล่อยการตั้งค่า Build & Output Settings เป็นค่าเริ่มต้น แล้วกด "Deploy"

รอระบบ Build ประมาณ 10–20 วินาที เมื่อเสร็จเรียบร้อย ให้กดเข้าไปดูผลลัพธ์ผ่าน URL ที่ Vercel ออกให้อัตโนมัติ! ✨

### ส่งลิงก์ของตัวเองผ่าน classroom

