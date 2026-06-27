# 🎬 Online Movie Ticket Booking System
ระบบจองตั๋วภาพยนตร์ออนไลน์ที่ช่วยให้ผู้ใช้งานสามารถเช็ครอบฉาย เลือกที่นั่ง และทำรายการจองตั๋วได้อย่างสะดวก รวดเร็ว และรองรับการแสดงผลทุกอุปกรณ์

---

## ✨ ฟีเจอร์เด่นของระบบ (Key Features)
* **Browsing Movies:** ค้นหาและดูรายละเอียดภาพยนตร์ ซีเนม่า และโปรโมชันต่าง ๆ
* **Seat Selection:** ระบบเลือกที่นั่งจำลองแบบ Interactive เลือกที่นั่งที่ต้องการได้แบบเรียลไทม์
* **Authentication & Membership:** ระบบสมัครสมาชิก เข้าสู่ระบบ (Modal) และหน้าโปรไฟล์จัดการข้อมูลส่วนตัว
* **Checkout & Confirmation:** หน้าสรุปยอดชำระเงิน ตรวจสอบความถูกต้อง และออกตั๋วยืนยันการจอง
* **Responsive Design:** แสดงผลได้อย่างสวยงาม สมบูรณ์แบบทั้งบนคอมพิวเตอร์ แท็บเล็ต และสมาร์ทโฟน

---

## 🛠️ เทคโนโลยีที่เลือกใช้ (Tech Stack)

### Frontend & UI
* **HTML5 & CSS3:** โครงสร้างเว็บและหน้าต่าง ๆ (เช่น `booking-confirmation.html`, `seat-selection.html`)
* **JavaScript (ES6):** จัดการ Logic การทำงานของเว็บ, ข้อมูลภาพยนตร์ (`movies-data.js`), และระบบล็อกอิน (`auth.js`)

### Backend & Database (Firebase Integration)
* **Node.js & Express:** ระบบจำลอง Server หลังบ้านผ่านไฟล์ `server.js` เพื่อจัดการ API
* **Firebase Authentication:** ระบบจัดการและยืนยันตัวตนผู้ใช้งาน (Sign-in / Sign-up) ปลอดภัยและได้มาตรฐาน
* **Firebase Firestore / Realtime Database:** ใช้สำหรับจัดเก็บและจัดการข้อมูลของระบบแบบเรียลไทม์ ได้แก่:
  * ข้อมูลผู้ใช้งานและสมาชิก (User Profiles & Membership)
  * สถานะการจองตั๋วและประวัติการทำรายการ (Booking Transactions & History)
  * ข้อมูลผังที่นั่งในแต่ละรอบฉาย (Seat Availability Status)

---

## 🚀 เริ่มต้นใช้งานโปรเจกต์ (Getting Started)

1. ติดตั้ง Dependencies ที่จำเป็น:
   ```bash
   npm install
2. ตั้งค่า Firebase Configuration:
   * นำค่า Config ที่ได้จาก Firebase Console ไปใส่ในไฟล์ตั้งค่าของโปรเจกต์ (เช่น auth.js หรือไฟล์ Environment) ก่อนเริ่มใช้งาน
3. รัน Server หลังบ้าน:
   ```bash
   npm start
