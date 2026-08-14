# gittest2.2

#ขั้นตอนการปฏิบัติงาน:

1. สร้าง Repository ใหม่บน GitHub ของตนเองชื่อ git-test-2-รหัสประจำตัวนร(รหัสเต็ม) (แคปหน้าจอตั้งชื่อไฟล์เป็น step1.png เก็บไว้ที่ Floder SS ที่ desktop)
2. ทำการ Clone Git URL มาไว้ที่เครื่องคอมพิวเตอร์ของคุณ และเข้าไปยังโฟลเดอร์ของโปรเจกต์นั้นใน Terminal (แคปหน้าจอ step2.png)
3. ทำการตั้งค่าชื่อและอีเมล กำหนดให้ user.name เป็น "ชื่อจริง นามสกุล" และ user.email เป็น "อีเมลของวิทยาลัย" (แคปหน้าจอ step3.png)
4. สร้างไฟล์ Version.txt พิมพ์ข้อความบรรทัดแรกว่า "Version 1.0"
5. ทำการ Add และ Commit ด้วยข้อความ "Add index.txt for V.1" (แคปหน้าจอ step4.png)
6. สร้าง Branch ใหม่ชื่อ BUG1 และสลับไปทำงานที่ Branch นี้ (แคปหน้าจอ step5.png)
7. เปิดไฟล์ index.txt ขึ้นมา แก้ไขบรรทัดที่ 1 จาก "Version 1.0" เป็น "Version 2.0 (Hotfix)" จากนั้นทำการ Add และ Commit ด้วยข้อความ "Update version to 2.0" (แคปหน้าจอ step6.png)
8. สลับกลับมาที่ Branch หลัก (main หรือ master) (แคปหน้าจอ step7.png)
9. เปิดไฟล์ index.txt ขึ้นมาอีกครั้ง แล้วแก้บรรทัดที่ 1 จาก "Version 1.0" เป็น "Version 1.5 (Main)" จากนั้นทำการ Add และ Commit ด้วยข้อความ "Update version to 1.5 by team" (แคปหน้าจอ step8.png)
10. สร้าง Branch ใหม่ชื่อ BUG2 และสลับไปทำงานที่ Branch นี้ (แคปหน้าจอ step9.png)
11. เปิดไฟล์ Version.txt ขึ้นมา และเพิ่มข้อความบรรทัดใหม่ (บรรทัดที่ 2) ว่า "edit by [ชื่อจริงของนักเรียน]" จากนั้นทำการ Add และ Commit ด้วยข้อความ "Add edit by [ชื่อนร.]" (แคปหน้าจอ step10.png)
12. เปลี่ยนชื่อ Branch จาก Bug2 ให้เป็นชื่อ fix (แคปหน้าจอ step11.png)
13. ทำการ ลบ Branch hotfix1 ทิ้ง (แคปหน้าจอตอนลบสำเร็จเป็น step12.png)
14. สลับกลับมาที่ Branch หลัก (main หรือ master) จากนั้นให้พิมพ์คำสั่งนี้เพื่อดึงประวัติการทำงาน: "git log --all --oneline --graph > my-history.txt" (แคปหน้าจอ step13.png)
15. ให้ ย้ายโฟลเดอร์ ss จากหน้า Desktop เข้ามาใส่ไว้ในโฟลเดอร์โปรเจกต์ Git ของ จากนั้นทำการ Add และ Commit ด้วยข้อความ "Add history log and screenshots"
16. ทำการ Push โค้ด ทั้ง Branch หลัก และ Branch fix ขึ้น GitHub ของตนเอง 
