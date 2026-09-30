# CHAGWOW SHOP — PRO STATUS

เว็บแสดงสถานะโปร Android / iOS พร้อมปุ่มไปซื้อโปรที่ CHAGWOW SHOP

## ไฟล์
- `index.html` — โครงสร้างหน้าเว็บ
- `style.css` — ดีไซน์ทั้งหมด
- `script.js` — รายการโปรและสถานะ
- `logo.png` — โลโก้ CHAGWOW SHOP

## เปลี่ยนสถานะโปร
เปิด `script.js`

```js
["ชื่อโปร", "online"]   // 🟢 ใช้งานได้ปกติ
["ชื่อโปร", "offline"]  // 🔴 ปรับปรุง
```

## เปลี่ยน/เพิ่มโปร
แก้ในตัวแปร `data` เช่น

```js
Android: [
  ["ชื่อโปรใหม่", "online"],
  ["อีกโปร", "offline"]
]
```

## ลิงก์ซื้อโปร
ปุ่ม `ซื้อโปรที่ CHAGWOW SHOP` อยู่ใน `index.html` และชี้ไปที่:

https://chagwowshop.orynx.xyz/

## เอาขึ้น GitHub Pages

1. สร้าง GitHub Repository ใหม่ เช่น `chagwow-pro-status`
2. อัปโหลด `index.html`, `style.css`, `script.js`, `logo.png` ลงใน Repository
3. เข้า `Settings` → `Pages`
4. ใน `Build and deployment` เลือก `Deploy from a branch`
5. เลือก Branch `main` และ Folder `/ (root)`
6. กด `Save`
7. รอ GitHub ประมาณสักครู่ แล้วเข้า URL รูปแบบ:

`https://ชื่อผู้ใช้.github.io/ชื่อ-repository/`

ตัวอย่าง ถ้า Repository ชื่อ `chagwow-pro-status`:

`https://ชื่อผู้ใช้.github.io/chagwow-pro-status/`

> ถ้าใช้ GitHub Pages แบบ Project Site URL จะมีชื่อ repository ต่อท้ายโดเมน
