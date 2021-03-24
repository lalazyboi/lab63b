# การทดลองที่ ๖ เรื่อง การเขียนโปรแกรมสร้างไวไฟแอคเซสพอยต์ (Wifi AP)

## วัตถุประสงค์
1. เพื่อให้นักศึกษามีความรู้เกี่ยวกับการเขียนโปรแกรมลงไมโครคอนโทรเลอร์
2. เพื่อศึกษาการเขียนโปรแกรมสร้างไวไฟแอคเซสพอยต์ (Wifi AP)

## อุปกรณ์ที่ใช้
1. ไมโครคอนโทรลเลอร์ (ESP-01)
2. อุปกรณ์ในการเขียนโปรแกรม เช่น PC,Laptop
3. USB to serial port

## ศึกษาข้อมูลเบื้องต้น
* [วิธีการทดลอง](https://www.youtube.com/watch?v=T26DVHePlTs&ab_channel=TANI-IOT)
* [Source code](https://github.com/choompol-boonmee/lab63b/tree/master/examples)
* [platformIO](https://platformio.org/)

## วิธีทำการทดลอง
1. เสียบไมโครคอนโทรเลอร์บน USB to serial
![2021-03-25 (26)](https://user-images.githubusercontent.com/78695932/112371791-9a712980-8d11-11eb-9fa8-77d05051fe57.png)

2. พิมพ์คำสั่ง `pwd` แล้วเข้าที่ไปโฟลเดอร์ 6 โดยพิมพ์ `cd 06_Wifi-AP-Web-Server`
![2021-03-25 (27)](https://user-images.githubusercontent.com/78695932/112371801-9e04b080-8d11-11eb-839a-753c6a340c1a.png)

3. พิมพ์ `vi src/main.cpp` เพื่อดูชื่อไวไฟและรหัสโดยสามารถเปลี่ยนชื่อและรหัสได้
![2021-03-25 (29)](https://user-images.githubusercontent.com/78695932/112371963-c7254100-8d11-11eb-8352-48f40f44873c.png)

4. upload โปรแกรมโดยพิมพ์ `pio run -t upload`
![2021-03-25 (30)](https://user-images.githubusercontent.com/78695932/112371984-cdb3b880-8d11-11eb-9df1-1b5eae8a5ca7.png)

5. กดปุ่ม upload และปุ่ม reset ที่ไมโครคอนโทรเลอร์ 
![2021-03-25 (31)](https://user-images.githubusercontent.com/78695932/112371995-d0aea900-8d11-11eb-9ef7-62bbdce3b1b8.png)

6. พิมพ์ `pio device monitor` เพื่อรันโปรแกรม
![2021-03-25 (32)](https://user-images.githubusercontent.com/78695932/112372006-d3a99980-8d11-11eb-98ac-b365dec64da9.png)

7. ค้นหาชื่อไวไฟที่เราตั้งไว้จากมือถือหรือคอมพิวเตอร์
![2021-03-25 (33)](https://user-images.githubusercontent.com/78695932/112372013-d60bf380-8d11-11eb-928d-0c3a3291c1a1.png)

## การบันทึกผลการทดลอง
    ให้สังเกตผลการทดลองแล้วเขียนอธิบาย เช่น พบไวไฟชื่อเหมือนกับที่เราตั้งไว้ในตอนเขียนโปรแกรม

## อภิปรายผลการทดลอง
    ในการทดลองนี้เราสามารถนำไปประยุกต์ใช้หรือคิดต่อยอดอะไรได้อีกบ้าง เช่น เราสามารถสร้างไวไฟเองได้โดยการเขียนโปรแกรมลงไมโครคอนโทรเลอร์
## คำถามหลังการทดลอง
    อุปกรณ์กระจายสัญญาณมีอะไรบ้าง
     * Access Point (AP)
     * Router
     * Exterder
    


