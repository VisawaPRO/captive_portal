# Example นี้มีชื่อว่า captive_portal
โดยการทำงานของ Example นี้คือทำให้ esp32 เป็น Captive Portal และเป็น Access Point โดยจะหน้าเข้าสู่ระบบกับอุปกรณ์ที่มาเชื่อมต่อ
#
ขั้นตอนแรกเลือก Example
# ![image](https://github.com/user-attachments/assets/ef9952f9-8264-4747-895a-5cd63fbbac8f)
รันและbuildโปรแกรม
# ![image](https://github.com/user-attachments/assets/2260f1f4-2003-482b-ba91-cbebd0f545f1)
เลือกเชื่อมกับ esp32_ssid
# ![image](https://github.com/user-attachments/assets/ee3d8e56-4e77-43b9-b09f-b5e86b00c07a)
จะขึ้นหน้า root.html เมื่อนำอุปกรณ์เชื่อมต่อเข้าไปที่เครือข่าย
# ![image](https://github.com/user-attachments/assets/3173804d-da18-4407-9252-1c406a346405)
# แก้ไขเพิ่มเติม
สามารถแก้ไขชื่อและรหัส Access Point โดยการกด menuconfig
# ![image](https://github.com/user-attachments/assets/85a7dce2-9d21-48d5-9068-396cffa7cb2b)
หา Example Configuration และเปลี่ยนตามต้องการแล้วกด save
# ![image](https://github.com/user-attachments/assets/e95b1b0e-55d7-4f5a-8084-1ddf0bbbb719)
และสามารถแก้ไขหน้า root.html ได้
# ![image](https://github.com/user-attachments/assets/ebf52964-7ce3-45b4-a39c-cd560b47be75)
รันและbuildโปรแกรม แล้วเชื่อมต่อจะได้หน้า root.html ที่แก้ใหม่
# ![image](https://github.com/user-attachments/assets/7f5f1f58-1812-4395-a006-39a7ff10fb03)

