# ubuntu-in-termux

## What's This?

นี่คือสคริปต์ที่ใช้ติดตั้ง Ubuntu ในแอปพลิเคชัน termux โดยไม่ต้องใช้อุปกรณ์ที่รูท

## Updates

**ubuntu 22.04**

### ขั้นตอนการติดตั้ง

1. termux-setup-storage ตอบยอมรับเข้าถึงที่เก็บข้อมูล
2. pkg update -y ใส่ N ในทุกการเรียกถาม ถ้ามี
3. pkg install wget proot git -y
4. 
5. Go to HOME folder: `cd ~`
6. Download script: `git clone https://github.com/saengx/ubuntu-in-termux.git`
7. Go to script folder: `cd ubuntu-in-termux`
8. Give execution permission: `chmod +x ubuntu.sh`
9. Run the script: `./ubuntu.sh -y`
10. Now just start ubuntu: `./startubuntu.sh`
