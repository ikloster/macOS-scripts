# macOS-scripts
scripts ต่าง ๆ ที่ใช้ใน macOS

ip-up
-----
ip-up แบบ selectively route network traffic through VPN
วิธีการนำไปใช้
1. เก็บไว้ใน /etc/ppp/ip-up
2. must have 0755 permissions
3. must be owned by root
4. ปรับแก้ค่า GATEWAY และคำสั่ง route ตามการใช้งาน
