# 66160020-hw2-bootstrab
## git command
### เตรียม Project

1. git clone https://github.com/kewalin020/66160020-hw2-bootstrab
2. สร้างโฟลเดอร์เปล่า css,images
3. git checkout -b development
4.  สร้างไฟล์เปล่า home.html about.html contact.html , css/styles-home.css ,css/styles-about.css ,css/styles-contact.css 
5. git add .
6. git commit -m "init project”

### Home

1. git checkout -b feature/home
2. git add home.html
3. git commit -m "add navbar”
4. git add home.html
5. git commit -m "add Hero Section “
6. git add home.html
7. git commit -m "add Footer”
8. git add home.html
9. git commit -m "เพิ่มลิ้งค์ Font Awesome สำหรับใช้งานไอคอน" 
10. git add home.html
11. git commit -m "เพิ่มลิ้ง styles-home.css”

### About

1. git checkout -b feature/ about
2. git add about.html
3. git commit -m "เพิ่ม navbar และ footer “
4. git add about.html
5. git commit -m "add Grid Section”
6. git add about.html
7. git commit -m "แก้ไขชื่อ Title”

### Contact

1. git checkout -b feature/ contact
2. git add contact.html
3. git commit -m " add Navbar/Footer”
4. git add contact.html
5. git commit -m "add content Contact”
6. git add contact.html
7. git commit -m "Add Contact Form Modal”
8. git add contact.html
9. git commit -m "แก้ไข Title”

### CSS

1. git checkout -b feature/css
2. git add css/styles-home.css
3. git commit -m "แก้ไขและตกแต่งส่วน Navbar”
4. git add css/styles-home.css
5. git commit -m "ลดขนาดของ Hero Section”
6. git add css/styles-home.css
7. git commit -m "ตกแต่งเพิ่มเติมในส่วน Footer”
8. git add css/styles-about.css
9. git commit -m "เพิ่มการตกแต่งเพิ่มเติมในส่วน Navbar และ Footer”
10. git add css/styles-about.css
11. git commit -m "แก้ไขและตกแต่งในส่วนของ card และเพิ่ม box-shadow”
12. git add css/styles-contact.css
13. git commit -m "เพิ่มการตกแต่งเพิ่มเติมในส่วน Naะ Footer หน้า Contact”
14. git add css/styles-contact.css
15. git commit -m "ตกแต่งในส่วน content”

### เพิ่มไฟล์งาน

1. git checkout development
2. git add screenshot.pdf
3. git commit -m "เพิ่ม ไฟล์ screenshot"
4. git add README.md
5. git commit -m "git command"

### Merge และ Push
1. git checkout development
2. git merge feature/home
3. git merge feature/about
4. git merge feature/contact
5. git merge feature/css
6. git push origin development