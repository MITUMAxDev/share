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

### การประกาศแท็กต่างๆ (Tags)

```html
<tag> contents </tag>
```

- `<tag>` : ทำหน้าที่เป็นตัวเปิดแท็กนั้นๆ (คล้ายการประกาศตัวแปร)
- `</tag>` : ทำหน้าที่เป็นตัวปิดแท็ก โดยใช้ `/` เป็น เครื่องหมายปิด
- `content` : ก็ คอนเทนต์อะว่าข้างในแท็กจะเป็นอะไร

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

### ผลลัพธ์:

![image](https://cdn.discordapp.com/attachments/1244310987109302444/1246459479957045299/lv_0_20240601202609.gif?ex=665c775a&is=665b25da&hm=29006ed7a350c41e7d37ca6aadd14f718204d6508bfa8d52c4960dada344090b&)

### การสร้างรูปภาพ (Image)

```html
<img src="path/to/image.jpg" alt="คำอธิบายรูปภาพ">
```

- `<img>` : แท็กสำหรับแสดงรูปภาพ
- `src` : ที่อยู่ของไฟล์รูปภาพ
- `alt` : ข้อความสำรองที่จะแสดงเมื่อไม่สามารถแสดงรูปภาพได้
- `เตือนคำ` : ไฟล์รูปภาพ ควรอยู่ในโฟลเดอร์เดียวกันกับ index.html เพื่อความง่ายในการเรียกใช้ (จะอยู่ลึกแค่ไหนก็ได้แต่ index.html ควรเรียกหาได้)

### ผลลัพธ์:

![image](https://media.discordapp.net/attachments/1244310987109302444/1246614051497185461/Screenshot_2024-06-02-06-58-56-01_f9a7afa717ced9e1fc9be9833291031a.jpg?ex=665d074e&is=665bb5ce&hm=b20a199590fca94dda2b9354be0b3f60cebeadb2f6b894474cd4ba72e285eaef&)

### การเขียนคำอธิบาย (Comments)
```html
<!-- นี่คือคำอธิบายนะจ๊ะ -->
```
- `<!-- ??? -->` : ประกาศว่า Content ข้างใน จะไม่นับรวมเป็นโค้ด/แท็ก
-  เอาไว้อธิบายโค้ดตัวเอง เวลากลับมาแก้/ส่งต่อให้คนอื่นทำ จะได้เข้าใจ did you get it!?

## HTML Formatting Elements

- `<b>` - Bold text
- `<strong>` - Important text
- `<i>` - Italic text
- `<em>` - Emphasized text
- `<mark>` - Marked text
- `<small>` - Smaller text
- `<del>` - Deleted text
- `<ins>` - Inserted text
- `<sub>` - Subscript text
- `<sup>` - Superscript text

### เว็บตัวอย่างที่เขียนในClass
```html
<!DOCTYPE html>
<html>
  <head>
    <!-- หัวข้อของเว็บเพจที่จะแสดงในแถบด้านบนของเบราว์เซอร์ -->
    <title>หัวข้อ Website (แสดงในแถบข้างบน)</title>
  </head>
  <body style="background-color: white">
    <!-- เนื้อหาหลักของเว็บเพจ -->
    
    <!-- ข้อความหัวข้อใหญ่ -->
    <h1>text ไซส์ H1</h1>
    
    <!-- แสดงภาพจากไฟล์ที่กำหนด ถ้าไฟล์ไม่เจอจะแสดงข้อความ Error -->
    <img src="ชื่อไฟล์ภาพ.???" alt="Error">
    
    <!-- ข้อความคอนเทนต์บรรทัดเดียว -->
    <p>คอนเทนต์(บรรทัดเดียว)</p>
    
    <!-- ข้อความหลายบรรทัดที่เว้นบรรทัดได้แบบโหดๆ -->
    <pre>
      คอนเทนต์แบบ
      หลายบรรทัด
      เว้นบรรทัดได้
    </pre>
  </body>
</html>
```
### ผลลัพธ์
![image](https://media.discordapp.net/attachments/1244310987109302444/1246443310890094653/Screenshot_2024-06-01-19-40-03-98_f9a7afa717ced9e1fc9be9833291031a.jpg?ex=665c684b&is=665b16cb&hm=642faafde466f3e523a43af9c750b50390e85c28374bd45367927554838d239e&)

## Note หลังเรียน


ถ้าเพื่อนรู้สึกว่า HTML ยากแล้ว สบายใจได้เลย ยังมีภาษา CSS, JavaScript, SQL และอีกเยอะเลย ที่โดนแน่ๆ
![image](https://github.com/MITUMAxDev/share/assets/144593781/181de9d5-e5ae-4ffa-a9c2-0aec60e3ff7d)


# CSS [พื้นฐาน]

