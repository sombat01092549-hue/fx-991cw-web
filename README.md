# CASIO fx-991CW Simulator (Pure Offline PWA)

เว็บจำลองเครื่องคิดเลขวิทยาศาสตร์ **CASIO fx-991CW (ClassWiz)** สีชมพูพาสเทล (`fx-991CW-PK`) และสีดำ (`fx-991CW-BK`) ทำงานได้ **Offline 100%** ไม่พึ่งพา CDN ภายนอก

## ไฟล์ในโปรเจกต์
- `index.html` — ตัวเครื่องคิดเลข, หน้าจอ Natural Textbook Display, ระบบ 13 แอป, ตัวสร้าง QR Code ในตัว, คู่มือฝึกกด, ประวัติ และคีย์ลัด
- `manifest.json` — ข้อมูลติดตั้งเป็นแอปบนมือถือ/iPad (PWA)
- `sw.js` — Service Worker สำหรับเก็บแคชให้เปิดใช้งานออฟไลน์ได้ 100%
- `icon-192.png`, `icon-512.png` — ไอคอนแอปหน้าจอโฮม

## วิธีใช้งานบนเครื่องทันที
เปิดไฟล์ `index.html` ด้วยเบราว์เซอร์ (Chrome / Edge / Safari) ได้เลยทันที

## วิธีอัปโหลดเป็นเว็บส่วนตัวฟรี (สำหรับเปิดบนมือถือ / iPad)

### วิธีที่ 1: Netlify Drop (เร็วที่สุด ไม่ต้องพิมพ์คำสั่ง)
1. ไปที่ https://app.netlify.com/drop
2. ลากโฟลเดอร์ `fx-991cw-web` ทั้งโฟลเดอร์ไปวาง
3. จะได้ลิงก์ `https://....netlify.app` ทันที

### วิธีที่ 2: GitHub Pages (ใช้บัญชี `sombat01092549-hue`)
1. สร้าง Repository ใหม่บน GitHub ชื่อ `fx-991cw-web` (ตั้งเป็น Public)
2. อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ขึ้นไป
3. ไปที่ `Settings` → `Pages` → เลือก Branch `main` / `/ (root)` → กด Save
4. เปิดใช้งานได้ที่ `https://sombat01092549-hue.github.io/fx-991cw-web/`

## วิธีติดตั้งเป็นแอปบนมือถือ / iPad
- **iPhone / iPad (Safari):** กดปุ่ม **Share** (สี่เหลี่ยมมีลูกศรชี้ขึ้น) → เลือก **Add to Home Screen (เพิ่มไปยังหน้าจอโฮม)**
- **Android (Chrome):** กดจุดสามจุดมุมขวาบน → เลือก **Install app / Add to Home screen**
