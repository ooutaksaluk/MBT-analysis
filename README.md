# MBT-analysis
march9

โปรเจกต์นี้ใช้ YOLO ในการตรวจจับ Sight และ Mantlet บนภาพ และเชื่อมต่อกับ Anvil เพื่อใช้งานผ่านเว็บ
วิธีใช้
เปิดใช้งาน google colab (MBT-analysis) และรันโค้ด
คุณสามารถเปลี่ยนเป็น google drive ของตัวเองได้และเพิ่มข้อมูลได้ 
เมื่อเริ่มรันโค้ดในส่วนของ Anvil แล้ว ให้เข้าไปที่ https://jgqcerxrr5dwb5qh.anvil.app/DU7EUTV7IDSXTY4KIDWIVWCS เพื่อใช้งาน Anvil
/content/dataset_yolo/
│── images/
│   ├── train/ (ภาพสำหรับ Train)
│   ├── val/ (ภาพสำหรับ Validation)
│── labels/
│   ├── train/ (ไฟล์ Label `.txt` สำหรับ Train)
│   ├── val/ (ไฟล์ Label `.txt` สำหรับ Validation)
│── dataset.yaml  (ไฟล์ config ของ YOLO)


วิดิโอ https://youtu.be/ekPpHOCnt7A
