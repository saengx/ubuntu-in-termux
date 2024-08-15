# ubuntu-in-termux

## What's This?

นี่คือสคริปต์ที่ใช้ติดตั้ง Ubuntu ในแอปพลิเคชัน termux โดยไม่ต้องใช้อุปกรณ์ที่รูท

## Updates

**ubuntu 22.04**

### ขั้นตอนการติดตั้ง

1. termux-setup-storage ตอบยอมรับเข้าถึงที่เก็บข้อมูล
2. pkg update -y ใส่ N ในทุกการเรียกถาม ถ้ามี
3. pkg install wget proot git -y
4. git clone https://github.com/saengx/ubuntu-in-termux.git
5. cd ubuntu-in-termux
6. chmod +x ubuntu.sh
7. ./ubuntu.sh
8. การเปิดใช้คำสั่ง./startubuntu.sh

###การเปิดให้ubuntuทำงานุกครั้งที่เปิดtermux

1. pkg install nano -y
2. cd && cd /data/data/com.termux/files/usr/etc && nano profile
3. เมื่อเข้าหน้า nano ให้เลื่อนเคอร์เซอร์ลงล่างสุด เพิ่มบรรทัดสุดท้าย cd && cd ubuntu-in-termux && ./startubuntu.sh
4.ctrl x ตอบ y เพื่อ save
5. exit เพื่อปิด แล้วเปิดใหม่
