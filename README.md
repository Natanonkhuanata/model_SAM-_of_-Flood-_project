********************   การอ่านค่าความสูงของระดับในเเม่น้ำ เพื่อช่วยเเจ้งเตือนให้กับชาวบ้านที่ได้รับผลกระทบจากอุทกภัย ***************************

โดยเป็นการทำเวอร์ชันก์เเรกเพื่อช่วยเเก้ปัญหาเบื้องต้น เเละมีเวอร์ชันก์ที่จะพัฒนาต่อคือการพยากรณ์การเกิดอุทกภัยล่วงหน้า  โดยใช้ Deep learning ในการทำ

โดยมีขั้นตอนดังนี้

1. มีการรับ input เป็น image จากกล้องเข้ามาทุกๆ 5 นาที
2. เข้าในส่วนของ model SAM ที่ทำการโค้ดไว้เพื่อให้ตีกรอบเเละอ่านค่าระดับ
3. ส่งค่าของระดับน้ำวันที่เข้าๆปเก็บข้อมูลภายใน excel
4. ส่งข้อมูลเข้า chat Line ที่มีชาวบ้านทุกคนอยู่ ข้อมูลที่ส่งจะมี 1.ระดับน้ำ 2.ระดับความเสี่ยง 3.รูปภาพ 4.ควรป้องกันอย่างไร
