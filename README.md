# ubuntu-in-termux

## What's This?

นี่คือสคริปต์ที่ใช้ติดตั้ง Ubuntu ในแอปพลิเคชัน termux โดยไม่ต้องใช้อุปกรณ์ที่รูท

## Updates

**ubuntu 22.04**

### ขั้นตอนการติดตั้ง

1. Update termux: `apt-get update && apt-get upgrade -y`
2. Install wget: `apt-get install wget -y`
3. Install proot: `apt-get install proot -y`
4. Install git: `apt-get install git -y`
5. Go to HOME folder: `cd ~`
6. Download script: `git clone https://github.com/saengx/ubuntu-in-termux.git`
7. Go to script folder: `cd ubuntu-in-termux`
8. Give execution permission: `chmod +x ubuntu.sh`
9. Run the script: `./ubuntu.sh -y`
10. Now just start ubuntu: `./startubuntu.sh`
