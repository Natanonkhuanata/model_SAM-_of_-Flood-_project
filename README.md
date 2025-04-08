## Segment Anything Model with object detection

![enter image description here](https://lh3.googleusercontent.com/5Vi-ILZY-xi9UBdX9vzTb6pUfddwvszhzWqIS5CODbm3ASOzB493PjRwVLt8RIQUT2E2IFRGMIV2LOA26HCSXPs9uGYAeS-I-Afek8TD0q8TAtvrHB7I5BsACkfmGPztvy6WmjN_uq-Vv48oR3Hjc3I)

 - การอ่านค่าความสูงของอุปกรณ์วัดระดับในเเม่น้ำ
   เพื่อช่วยเเจ้งเตือนให้กับชาวบ้านที่ได้รับผลกระทบจากอุทกภัย
   
 - โดยเป็นการทำเวอร์ชันก์เเรกเพื่อช่วยเเก้ปัญหาเบื้องต้น
 
 - **การพัฒนา  คือการพยากรณ์การเกิดอุทกภัยล่วงหน้า  โดยใช้ Deep learning**

## ขั้นตอน processing

 1. มีการรับ input เป็น image จากกล้องเข้ามาทุกๆ 5 นาที
 2. เข้าในส่วนของ model SAM ที่ทำการโค้ดไว้เพื่อให้ตีกรอบเเละอ่านค่าระดับ
 3. ส่งค่าของระดับน้ำวันที่เข้าๆปเก็บข้อมูลภายใน excel
 4. ส่งข้อมูลเข้า chat Line ที่มีชาวบ้านทุกคนอยู่
 5. ข้อมูลที่ส่งจะมี  ระดับน้ำ  ระดับความเสี่ยง  รูปภาพ  วิธีการรักษาความ

   
