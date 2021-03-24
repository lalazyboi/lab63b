# การทดลองที่ ๑

## วัตถุประสงค์
1. เพื่อศึกษาการใช้ตัวไมโครคอนโทรเลอร์
2. เพื่อฝึกเขียนโปรแกรมลงบนไมโครคอนโทรเลอร์

## อุปกรณ์ที่ใช้
1. ไมโครคอนโทรลเลอร์(ESP-01)
2. อุปกรณ์ในการเขียนโปรแกรม เช่น PC,Laptop
3. USB to serial port

## ศึกษาข้อมูลเบื้องต้น
* วิธีการทดลอง https://github.com/choompol-boonmee/lab63b
* Source code https://github.com/choompol-boonmee/lab63b/tree/master/examples
* platformIO https://platformio.org/

## วิธีทำการทดลอง
1. เสียบ USB to serial เข้าที่คอมพิวเตอร์ จากนั้นเสียบไมโครคอนโทรเลอร์ลง USB
2. เขียนโปรแกรมโดยพิมพ์คำสั่ง cd pattani แล้วพิมพ์ ls
3. ให้เข้าไปที่โฟลเดอร์ที่ 1 โดยพิมพ์ cd 01_Serial-Monitor ตามด้วย vi src/main.cpp
4. Upload โปรแกรมจากคำสั่ง pio run -t upload
5. กดปุ่มสีดำที่ไมโครคอนโทรเลอร์เพื่อทำการ Download โปรแกรมแล้วกดปุ่ม Reset
6. พิมพ์ pio device monitor เพื่อรันโปรแกรม

## การบันทึกผลการทดลอง


## อภิปรายผลการทดลอง


## คำถามหลังการทดลอง

