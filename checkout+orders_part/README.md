##   Group Project: Regalix Ecommerce Website

### ลิงก์เข้าหน้าเว็บ
[Checkout] | [Orders]

### command line ติดตั้งโมดูลที่ต้องใช้
```shell
  npm i express path moment router multer mongoose ejs nodemon cheerio
```
### ทำอะไรไปบ้าง?

- [x] เชื่อมกับตะกร้าสินค้า
- [x] ปรับปรุงแบบฟอร์มหน้า checkout เดือนเมื่อผู้ใช้ไม่ได้กรอกบางช่องหรือกรอกผิดรูปแบบ
- ![img_3.png](img_3.png)
- [x] รองรับการอัพโหลดสลิปโอนเงินเข้า NodeJs Server จะอยู่ใน *checkout+orders_part/public/images/transactions*
- ![img_1.png](img_1.png)
- [x] เชื่อมกับ mongoDB ผ่าน URI
- ![img.png](img.png)
  + ไม่ต้อง import database 
  + เปิดโปรแกรม MongoDB Compass แล้วเชื่อมต่อโดยใช้ URI: mongodb://localhost:27017 จะสามารถเชื่อมต่อกับ DB ได้เลย
- [x] เชื่อมหน้า Checkout กับ Orders แล้ว
- [x] หน้า Orders แสดงผลข้อมูลโดยเรียงล่าสุดไว้บนสุด
- ![img_2.png](img_2.png)