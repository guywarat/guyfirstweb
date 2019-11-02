# My First App
## Git Commands
- เริ่มต้นใช้งาน git
```bash
git init
```
- เชื่อมต่อโปรเจคใน Local เข้ากับ git server กำหนดเฉพาะครั้งแรก
```bash
git remote add "https://github.com/git_name/guyfirstweb.git"
```
- เลือกไฟล์ให้อยู่ในสถานะ Staging area
```bash
git add file_name or git add .
```
- เพิ่มคำอธิบาย
```bash
git commit -m "คำอธิบาย"
```
- อัพไฟล์ที่ถูก commit ขึ้น git server
```bash
git push -u origin master (เฉพาะครั้งแรก)
git push 
```
