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
