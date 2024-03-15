# การติดตั้ง PHP และ Laravel บน Windows

## การติดตั้ง PHP

1. ดาวน์โหลด PHP จาก [เว็บไซต์อย่างเป็นทางการ](https://windows.php.net/download/)
2. เลือกเวอร์ชัน PHP ที่ต้องการ
![PHP Installation](./image/1-DowloadfileZip.png)
3. แตกไฟล์ zip และย้ายโฟลเดอร์ PHP ไปยัง `C:\php`
![PHP เข้าไปที่โฟเดอร์ที่เก็บ PHP ที่ Dowlad มา](./image/2-OpenFloder.png)
![PHP แตกไฟล์](./image/3-Extrack.png)
![PHP Rename](./image/4-Rename.png)
![PHP ย้ายไปที่ C:/](./image/5-move.png)
4. เพิ่ม `C:\php` ไปยัง PATH ของระบบ
![PHP เข้าไปที่ Enviroment](./image/6-environment.png)
![PHP set path](./image/7-setpart.png)
5. ทดสอบการติดตั้งด้วยคำสั่ง `php -v` ใน Command Prompt
![PHP ตรวจสอบ Version](./image/8-php-v.png)

## การติดตั้ง Laravel

1. ติดตั้ง Composer จาก [เว็บไซต์อย่างเป็นทางการ](https://getcomposer.org/download/)
![Composer Installation](./image/1-composer.png)
![Composer Installation](./image/2-selectmode.png)
![Composer Installation](./image/3-step1.png)
![Composer Installation](./image/3-step2.png)
![Composer Installation](./image/3-step3.png)
2. ทดสอบการติดตั้ง Composer ด้วยคำสั่ง `composer -v` ใน Command Prompt
![Composer Installation](./image/4-composer-v.png)

3. ติดตั้ง Laravel ผ่าน Composer ด้วยคำสั่ง `composer global require laravel/installer`
4. เพิ่ม `C:\Users\[username]\AppData\Roaming\Composer\vendor\bin` ไปยัง PATH ของระบบ
5. ทดสอบการติดตั้ง Laravel ด้วยคำสั่ง `laravel -v` ใน Command Prompt

