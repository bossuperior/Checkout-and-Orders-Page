##   Group Project: Regalix Ecommerce Website

### command line ติดตั้งโมดูลที่ต้องใช้
```shell
  npm i express path moment router multer mongoose ejs nodemon cheerio
```
### ทำอะไรไปบ้าง?

- [x] เชื่อมกับตะกร้าสินค้า
- [x] ปรับปรุงแบบฟอร์มหน้า checkout เดือนเมื่อผู้ใช้ไม่ได้กรอกบางช่องหรือกรอกผิดรูปแบบ
  ![image](https://github.com/user-attachments/assets/7d8a5645-b0ef-4dcd-b23d-58758eeeea9a)
- [x] รองรับการอัพโหลดสลิปโอนเงินเข้า NodeJs Server จะอยู่ใน *checkout+orders_part/public/images/transactions*
  ![image](https://github.com/user-attachments/assets/131af937-4893-4cb3-b1fb-53dfa84313e8)
- [x] เชื่อมกับ mongoDB ผ่าน URI
  
  + ไม่ต้อง import database 
  + เปิดโปรแกรม MongoDB Compass แล้วเชื่อมต่อโดยใช้ URI: mongodb://localhost:27017 จะสามารถเชื่อมต่อกับ DB ได้เลย
- [x] เชื่อมหน้า Checkout กับ Orders แล้ว
- [x] หน้า Orders แสดงผลข้อมูลโดยเรียงล่าสุดไว้บนสุด
- ![img_2.png](img_2.png)
