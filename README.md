# โปรเจกต์ Test Scenario ระบบจองร้านบุฟเฟต์

## ลิ้งก์ระบบ
- ลิ้งก์ฟอร์มจอง:https://docs.google.com/forms/d/e/1FAIpQLScOMKD4hGaGbMQx-RVEgctrYXhI-oNXkRKVB526sQ0danZriQ/viewform
- ลิ้งก์ Google Sheet:https://docs.google.com/spreadsheets/d/1_mBcTzKI01DOPOWb2snd_hGGgM3fMLmlKOGPRC0Py2Y/edit?usp=sharing
- ลิ้ง Google Drive(หลักฐาน) https://drive.google.com/drive/folders/1feAHSbxyReL8elEvVauQEUBI7BPV5FjE?usp=sharing
  
## รายละเอียดโปรเจกต์
โปรเจกต์นี้จัดทำขึ้นเพื่อออกแบบและทดสอบระบบจองร้านบุฟเฟต์ โดยใช้ Google Form + Google Sheet
และจัดทำชุด Test Scenario 

## วัตถุประสงค์
- ศึกษาและฝึกเขียน Test Scenario
- สร้างระบบจำลองที่สามารถทดสอบได้จริง
- จัดทำเอกสารสำหรับ Portfolio

## เครื่องมือที่ใช้
- Google Form (หน้าจอง)
- Google Sheet (ฐานข้อมูล)
- GitHub (จัดเก็บผลงาน)

## ลิงก์ระบบ
- ลิงก์ฟอร์มจอง:https://docs.google.com/forms/d/e/1FAIpQLScOMKD4hGaGbMQx-RVEgctrYXhI-oNXkRKVB526sQ0danZriQ/viewform

## รายการ Test Scenario
| Scenario ID | Title | priority | Expected Result (ผลที่คาดหวัง) |
|-------------|------------------------------------------|----------|--------------------------------------------------------------------------------------------|
| TS-001 | จองบุฟเฟต์สำเร็จด้วยข้อมูลครบถ้วน | High | แสดงหน้า "ส่งคำตอบแล้ว" และข้อมูลปรากฏใน Google Sheet "Your response has been recorded." |
| TS-002 | พยายามส่งฟอร์มโดยไม่กรอกชื่อลูกค้า | High | ระบบไม่ให้ส่ง และแจ้งให้กรอกชื่อลูกค้า "This is a required question" |
| TS-003 | พยายามส่งฟอร์มโดยไม่กรอกเบอร์โทร | High | ระบบไม่ให้ส่ง และแจ้งให้กรอกเบอร์โทร "This is a required question" |
| TS-004 | จองรอบกลางวันสำเร็จ | High | ส่งสำเร็จ และใน Sheet แสดงรอบกลางวัน "Your response has been recorded." |
| TS-005 | จองรอบเย็นสำเร็จ | High | ส่งสำเร็จ และใน Sheet แสดงรอบเย็น "Your response has been recorded." |
| TS-006 | จองจำนวน 1 คน | Medium | ส่งสำเร็จ และบันทึกจำนวน 1 คน "Your response has been recorded." |
| TS-007 | จองจำนวน 6 คนขึ้นไป | Medium | ส่งสำเร็จ และบันทึกจำนวน 6 คนขึ้นไป "Your response has been recorded." |
| TS-008 | เลือกสาขาสยาม | Medium | ส่งสำเร็จ และใน Sheet แสดงสาขาสยาม "Your response has been recorded." |
| TS-009 | เลือกสาขาบางนา | Medium | ส่งสำเร็จ และใน Sheet แสดงสาขาบางนา "Your response has been recorded." |
| TS-010 | ตรวจสอบว่าข้อมูลถูกบันทึกลง Google Sheet | High | ข้อมูลที่กรอกในฟอร์มปรากฏครบถ้วนใน Sheet |
																					
## ผู้จัดทำ																					
นางสาว พัทธนันท์ สุขมูล
