# baitong-birthday

โครงสร้างพร้อมใช้งานทันทีสำหรับเว็บวันเกิด

## โฟลเดอร์

- `index.html`
- `assets/images/`
- `assets/audio/`

## ไฟล์ที่ควรวาง

ใส่ไฟล์ตามชื่อนี้ เพื่อให้เว็บโหลดได้ทันทีโดยไม่ต้องแก้โค้ด:

- `assets/audio/birthday.mp3` (หรือ `song.mp3` / `music.mp3` / `track.mp3` ตามที่โค้ดลองหา)
- `assets/images/hero.png` — รูปปก hero
- `assets/images/photo-1.png`
- `assets/images/photo-2.png`

ถ้าใช้ไฟล์ `.jpg` แทนได้ โค้ดจะลอง `.png` ก่อน แล้วค่อย fallback เป็น `.jpg` อัตโนมัติ

## วิธีใช้งาน

1. วางรูปและเพลงตามชื่อไฟล์ด้านบน
2. เปิด `index.html` ได้เลย
3. ถ้าจะลงกิต ให้ commit โฟลเดอร์ `baitong-birthday/` ทั้งก้อน
