## ขาดไม่ได้เดี๋ยวจารย์บ่น

```html
<!DOCTYPE html>
```
`ประกาศไฟล์ว่าเป็นภาษาHTML`
- ตัวนี้จะอยู่ข้างบนสุดของไฟล์โค้ด `index.html`
- ใช้สำหรับประกาศว่าไฟล์นี้เป็นภาษา HTML (HyperText Markup Language)

## โครงสร้างพื้นฐานของไฟล์ HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>อะไรวะเนี่ย</title>
</head>
<body>

</body>
</html>
```

- `<html lang="en">` : กำหนดภาษาของเนื้อหาในเอกสาร
- `<head>` : ส่วนหัวของเอกสารที่ใช้สำหรับการรวมข้อมูล meta, title, links, scripts
- `<meta charset="UTF-8">` : กำหนดชุดตัวอักษรเป็น UTF-8
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">` : ทำให้หน้าเว็บรองรับการแสดงผลบนอุปกรณ์ที่มีขนาดหน้าจอต่างกัน
- `<title>` : ชื่อของเอกสารที่จะแสดงในแท็บของเบราว์เซอร์
- `<body>` : ส่วนเนื้อหาหลักของเอกสาร

## ตัวอย่างการเขียนโค้ด HTML เบื้องต้น

### การสร้างส่วนหัว (Header)

```html
<header>
    <h1>ผมเรียนHTMLแล้วปวดขี้</h1>
</header>
```

- `<header>` : ใช้สำหรับกำหนดส่วนหัวของเอกสาร
- `<h1>` : หัวข้อหลักของเอกสาร

### การสร้างย่อหน้า (Paragraph)

```html
<p>เราจะทำตามสัญญา</p>
```

- `<p>` : แท็กสำหรับสร้างย่อหน้า

### การสร้างลิงก์ (Link)

```html
<a href="https://www.example.com">คลิกที่นี่เพื่อไปยัง หมาบิน.com</a>
```

- `<a>` : แท็กสำหรับสร้างลิงก์
- `href` : กำหนด URL ของหน้าเว็บที่ต้องการลิงก์ไป

### การสร้างรูปภาพ (Image)

```html
<img src="path/to/image.jpg" alt="คำอธิบายรูปภาพ">
```

- `<img>` : แท็กสำหรับแสดงรูปภาพ
- `src` : ที่อยู่ของไฟล์รูปภาพ
- `alt` : ข้อความสำรองที่จะแสดงเมื่อไม่สามารถแสดงรูปภาพได้

ถ้าเพื่อนรู้สึกว่า HTML ยากแล้ว สบายใจได้เลย ยังมีภาษา CSS, JavaScript, SQL และอีกเยอะเลย ที่โดนแน่ๆ
![image](https://github.com/MITUMAxDev/share/assets/144593781/181de9d5-e5ae-4ffa-a9c2-0aec60e3ff7d)