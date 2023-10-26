- การ Clone Repository ลงใน GitHub Desktop
- 1. File > Clone repository
![image](https://github.com/ShaLeeZ2002/CE341_ID1398/assets/149044605/10c01abb-e112-437c-8f7f-27717b9f305e)
  2. เลือก Repository ที่ต้องการ clone
- ![image](https://github.com/ShaLeeZ2002/CE341_ID1398/assets/149044605/7df1dab8-1002-4f6b-af52-ad8a655f1495)
- เมื่อมีการเปลี่ยนแปลงใดๆจาก file ภายในเครื่อง ก็สามารถ commit และ push ไปยัง GitHub Website ได้
![image](https://github.com/ShaLeeZ2002/CE341_ID1398/assets/149044605/8a354196-0f8e-4806-9167-ba3281b84ff9)
![image](https://github.com/ShaLeeZ2002/CE341_ID1398/assets/149044605/b7e0c2b9-8a37-4185-845e-069bbd6de48f)
![image](https://github.com/ShaLeeZ2002/CE341_ID1398/assets/149044605/5090d972-2a28-4c4e-8871-0aec325702f8)
- __________________
- การ clone repository ไปยัง Unbuntu และ Apache webhost
- 1. ทำการ login และ update apt ด้วยคำสั่ง sudo apt update -y
  2. install apache2 และ git ด้วยคำสั่ง sudo apt install apache2 , sudo apt install git
![image](https://github.com/ShaLeeZ2002/CE341_ID1398/assets/149044605/174e63b0-f8c4-403c-8809-3e3690ea44d0)
![image](https://github.com/ShaLeeZ2002/CE341_ID1398/assets/149044605/9f806e0a-0075-49ca-bd59-48874fb74321)
  3. พิมพ์คำสั่ง ip a เพื่อเช็ค ip ของตัวเอง แล้วนำไอพีไปเปิดใน browser จะปรากฎหน้าเว็บของ apache
![image](https://github.com/ShaLeeZ2002/CE341_ID1398/assets/149044605/6503b9b5-64f9-445e-a613-9ed86479eb1f)
![image](https://github.com/ShaLeeZ2002/CE341_ID1398/assets/149044605/d9e3dfd2-9a7d-4852-9f03-d2b911eb6801)
  4. กลับมาที่ terminal แล้วพิมพ์ git clone "[ลิงก์Repository]" เพื่อ clone repository จาก GitHub web
  5. เมื่อเรียบร้อยแล้วเช็ค directory และ ไฟล์ต่างๆ ด้วยคำสั่ง ls และ cat
  - ![image](https://github.com/ShaLeeZ2002/CE341_ID1398/assets/149044605/b3f6ff3a-e07f-4444-8514-a52bf6b6585b)
![image](https://github.com/ShaLeeZ2002/CE341_ID1398/assets/149044605/441e6996-b2b4-438c-b8c0-d5f179bc44c9)
  6. เมื่อมั่นใจว่าถูกต้อง ทำการ copy file "index.html" ไปวางทับไฟล์ชื่อเดียวกันที่directoryปลายทางของ webhost apache ด้วยคำสั่ง
     - sudo cp index.html /var/www/html/
     - ![image](https://github.com/ShaLeeZ2002/CE341_ID1398/assets/149044605/d0442a4b-8687-4e9c-9da3-10bbcbca63e0)
  7. จากนั้นกลับมาที่ browser ที่ใส่ ip ของตัวเอง และรีเซ็ตหน้า จะปรากฎหน้าเว็บที่เขียน HTML ไว้จาก Repository
     - ![image](https://github.com/ShaLeeZ2002/CE341_ID1398/assets/149044605/76bc04b4-67c8-47c5-a2c6-d572e23656c6)














