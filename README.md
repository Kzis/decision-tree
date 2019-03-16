# Decision-tree project
Our machine learning project


โค๊ดสำหรับทำงานร่วมกัน

สำหรับครั้งแรก ใช้ ```git clone https://github.com/Kzis/decision-tree.git```  
1. ```git pull``` ใช้ดึงโค๊ดบน github ลงมาที่เครื่องเรา เป็นการอัพเดตข้อมูลล่าสุด  
2. เขียนโค๊ด  
3. ```git status``` เพื่อดูไฟล์ที่มีการเปลี่ยนแปลง  
4. ```git add "ชื่อไฟล์.สกุล"``` เตรียมเพิ่มไฟล์ขึ้นไป กรณี จะเอาทั้งหมด ```git add -A```  
5. ```git commit -m "ใส่คอมเมนต์สั้นๆว่าแก้อะไรไป"```(ใส่ทุกครั้ง)  
6. ```git push``` ส่งขึ้นไป  

กรณี push ไม่ขึ้น อาจเกิดจาก มีคนอื่น push ขึ้น github แล้วเราไม่รู้  
1. กรณีเพิ่มไฟล์ที่ไม่เกี่ยวกับคนอื่น (เช่น ไฟล์ใหม่) ใช้ ```git pull``` ก่อน แล้วจึง ```git push```  
2. กรณีมีการแก้ไขไฟเดียวกัน มี 2 ทางเลือก  
2.1 Merge (ยังทำไม่เป็น)  
2.2 ลบของเราทิ้ง เอาของเพื่อน ใช้ ```git stash``` จากนั้น ```git pull```  

## Python package dependencies  
ติดตั้ง package เพิ่มเติม  
```conda install -c conda-forge pydotplus```  

ติดตั้ง graphviz  
1. ติดตั้งโปรแกรมจากลิงค์นี้ https://graphviz.gitlab.io/_pages/Download/Download_windows.html  
2. ติดตั้ง graphviz ใน python ใช้คำสั่ัง ```conda install -c anaconda graphviz```  
3. เพิ่ม C:\Program Files (x86)\Graphviz2.38\bin ใน User path  
4. เพิ่ม  C:\Program Files (x86)\Graphviz2.38\bin\dot.exe ใน System Path  
