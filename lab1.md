# การทดลองที่1
## วัตถุประสงค์
1.เพื่อศึกษาเกี่ยวกับการทำงานและการเชื่อมต่อเบื้องต้นของ microcontroller

2.เพื่อศึกษาเกี่ยวกับการ run microcontroller
### อุปกรณ์ที่ใช้
1.คอมพิวเตอร์

2.microcontroller ESP01

3.อุปกรณ์ต่อ USB-Serial
#### ศึกษาข้อมูลเบื้องต้น
run example 1 https://youtu.be/NLIUsWLEpmg

code https://github.com/choompol-boonmee/lab63b/blob/master/examples/01_Serial-Monitor/src/main.cpp
##### วิธีทำการทดลอง
1.เชื่อมต่อ microcontroller เข้ากับคอมพิวเตอร์ด้วยการต่อ USBไปยังSerial

2.เปิด cmd ซึ่งจากตัวอย่างอยู้ในโฟล์เดอร์ pattani ใช้คำสั่ง cd

3.ใช้คำสั่ง cd_Serial-Monitor ตามด้วย vi srv/main.cpp เพื่อการดูและศึกษาโค้ดตัวอย่างโปรแกรมที่ใช้ในการทดสอบ microcontroller

4.ใช้คำสั่ง vi platformio.ini เพื่อให้ทราบข้อมูลเกี่ยวกับ microcontroller

5.ใช้คำสั่ง pio run -t upload เพื่อทำการรัน microcontroller

6.กดที่ปุ่มของ microcontroller เพื่อให้โปรแกรมรับคำสั่งใหม่เข้าไป

7.หากขึ้น success ให้ใช้สั่ง pio device monitor

8.รอดูผลการทดลอง
##### การบันทึกผลการทดลอง
##### อภิปรายผลการทดลอง
##### คำถามหลังการทดลอง
