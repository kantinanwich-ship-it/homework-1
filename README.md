# Galaxy Portfolio

เว็บพอร์ตโฟลิโอ 3 หน้า ธีมม่วงอวกาศสไตล์ soft UI / neumorphism
สร้างด้วย HTML, CSS และ JavaScript ล้วน (ไม่ต้องติดตั้งหรือ build)

## หน้าเว็บ

| ไฟล์ | หน้า |
| --- | --- |
| `index.html` | Landing page |
| `about.html` | About me |
| `mywork.html` | My work |

## โครงสร้างโปรเจกต์

ทุกไฟล์อยู่ในระดับเดียวกัน (ไม่มีโฟลเดอร์ย่อย) เพื่อให้อัปขึ้น GitHub ได้ง่าย

```
index.html  about.html  mywork.html
style.css   main.js
profile.jpg astronaut.svg planet.svg rider.svg rocket.svg
```

## ดูตัวอย่างในเครื่อง

เปิดไฟล์ `index.html` ด้วยเบราว์เซอร์ได้เลย หรือรันเซิร์ฟเวอร์ชั่วคราว:

```bash
python3 -m http.server 8000
# แล้วเปิด http://localhost:8000
```

## นำขึ้น GitHub Pages

1. สร้าง repository ใหม่บน GitHub แล้วอัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ (ให้ `index.html` อยู่ที่ราก repo)
2. ไปที่ **Settings → Pages**
3. ที่ **Build and deployment** เลือก **Deploy from a branch**
4. เลือก branch `main` และโฟลเดอร์ `/ (root)` แล้วกด **Save**
5. รอสักครู่ เว็บจะออนไลน์ที่ `https://<username>.github.io/<repo-name>/`

ถ้าตั้งชื่อ repo เป็น `<username>.github.io` เว็บจะอยู่ที่ `https://<username>.github.io/`

## สิ่งที่ควรแก้เป็นของตัวเอง

- ค้นหาและแทนที่ `YOUR NAME`, `you@example.com`, `@your.handle` ในไฟล์ HTML
- แก้ชื่อและรายละเอียดโปรเจกต์ใน `mywork.html` (แอตทริบิวต์ `data-title`, `data-desc`, `data-tags`, `data-link`)
- เปลี่ยนรูปโปรไฟล์ที่ `profile.jpg`
- แทนที่ภาพ CSS ในแกลเลอรี (`<div class="art ...">`) ด้วย `<img>` ของผลงานจริง
