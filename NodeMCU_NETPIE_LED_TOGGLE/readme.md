
แสดงการประยุกต์ NETPIE Freeboard ในการควบคุมอุปกรณ์ โดยในเบื้องต้นนี้ เราจะควบคุมไฟ LED บนบอร์ด NodeMCU ซึ่งใช้หลักการทางานบนพื้นฐานของการ Subscribe ข้อความจาก Topic หรือหัวข้อที่ระบุ และการกาหนดตรรกะของการควบคุมทั้งในส่วนของ Datasource และส่วนของ Widget ที่ใช้ควบคุม โดยมีขั้นตอนดังต่อไปนี้
### 1.ในหน้า NETPIE Freeboard 
คลิกเพิ่ม Datasource ที่สร้างขึ้นก่อนหน้านี้เพื่อแก้ไข ตั้งชื่อ Datasource ใส่ค่า KEY และ SECRET และในช่อง SUBSCRIBED TOPICS ให้ใส่ /pieled/state หรือ Topic ที่ท่านระบุไว้สาหรับการ publish ในไฟล์ pieled2.ino ดังแสดงในภาพด้านล่าง และกด Save

รูปแสดงหน้าต่างตั้งค่า Datasource ใน NETPIE Freeboard สาหรับควบคุม LED

![alt text](https://netpie.gitbooks.io/5-freeboard/content/assets/la1.jpg)
