# เตรียมความพร้อมเครื่อง Windows 10 สำหรับวิชา Web Programming

---

## โปรแกรมที่ต้องใช้
* NodeJS
* MySQL database
* VSCode
* VSCode Live Server
* Postman

---

### 1. ติดตั้ง Nodejs

Nodejs เป็น runtime ภาษา javascript ที่ช่วยให้เราสามารถรันโค๊ด javascript นอกเว็บเบราเซอร์ได้

1. เข้าไปที่เว็บไซต์ https://nodejs.org/en/ ดาวน์โหลดและติดตั้งเวอร์ชันล่าสุด (15.5.1 ขึ้นไป)  
Double Click เพื่อติดตั้งโปรแกรม `node-v15.5.1-x64.msi` และกด next ไปเรื่อยๆ (ใช้ค่า default ทั้งหมด)
<details>
<img src="imgs/nodejs/nodejs-download.png" width="400"/><br>
<img src="imgs/nodejs/nodejs-install-1.png" width="400" /><br> 
<img src="imgs/nodejs/nodejs-install-2.png" width="400"/><br>
<img src="imgs/nodejs/nodejs-install-3.png" width="400"/><br>
<img src="imgs/nodejs/nodejs-install-4.png" width="400"/><br>
<img src="imgs/nodejs/nodejs-install-5.png" width="400"/><br>
<img src="imgs/nodejs/nodejs-install-6.png" width="400"/><br>
<img src="imgs/nodejs/nodejs-install-7.png" width="400"/><br>
</details>
<br>

2. ตรวจสอบว่าติดตั้งสำเร็จโดย เปิดโปรแกรม `powershell.exe.` และพิมพ์คำสั่ง
```
PS \> node --version
v15.5.1
```
<details>
<img src="imgs/nodejs/nodejs-install-8.png" width="400"/><br>
<img src="imgs/nodejs/nodejs-install-9.png" width="400"/><br>
</details>

### 2. ติดตั้ง MySQL Database
1. Download ตัว installer จาก https://dev.mysql.com/downloads/installer/  
<img src="imgs/mysql/mysql-download-1.png" width="600"/><br>
<img src="imgs/mysql/mysql-download-2.png" width="600"/><br>

2. รันตัวติดตั้งโปรแกรม `mysql-installer-web-community-8.0.22.0.msi`  
<img src="imgs/mysql/install-1.png" width="600"/><br>

3. เลือก Custom  
<img src="imgs/mysql/install-2.png" width="600"/><br>

4. รายการที่เราต้องการจะ Install
    - ยกเลิกรายการด้านขวาทั้งหมด  
<img src="imgs/mysql/install-3.png" width="600"/><br>
    - เลือก **MySQL Server/MySQL Server 8.0/MySQL Server 8.0.22 - x64**  
<img src="imgs/mysql/install-4.png" width="600"/><br>
    - เลือก **Application/MySQL Workbench/MySQL Workbench 8.0.22 - x64**  
<img src="imgs/mysql/install-5.png" width="600"/><br>
    - กด Next  
<img src="imgs/mysql/install-6.png" width="600"/><br>

5. กด Execute รอจนโปรแกรมดาวน์โหลดเสร็จ จากนั้นกด Next  
<img src="imgs/mysql/install-7.png" width="600"/><br>
<img src="imgs/mysql/install-8.png" width="600"/><br>

6. กด Execute และรอให้โปรแกรมติดตั้งเสร็จ จากนั้นกด Next และ Finish
<img src="imgs/mysql/install-9.png" width="600"/><br>
<img src="imgs/mysql/install-10.png" width="600"/><br>
<img src="imgs/mysql/install-11.png" width="600"><br>

7. รันตัวติดตั้งโปรแกรม `mysql-installer-web-community-8.0.22.0.msi` อีกครั้ง  
และคลิก Reconfigure เพื่อทำการตั้งค่า MySQL Server  
<img src="imgs/mysql/install-12.png" width="600"><br>
<img src="imgs/mysql/install-13.png" width="600"><br>
<img src="imgs/mysql/install-14.png" width="600"><br>
<img src="imgs/mysql/install-15.png" width="600"><br>
<img src="imgs/mysql/install-16.png" width="600"><br>
<img src="imgs/mysql/install-17.png" width="600"><br>

8. เปิดโปรแกรม MySQL Workbench เพื่อตรวจสอบว่าติดตั้งสำเร็จแล้ว
<img src="imgs/mysql/install-18.png" width="600"><br>