# final_part__1
1.	ตอบ 	ไม่เห็นด้วยเพราะการทำagile ไม่ใช่การทำแฮกเกอร์ แต่เป็นการพัฒนาซอฟต์แวร์อีกรูปแบบหนึ่งเช่นเดียวกับ waterfallแต่ทั้ง2มีความต่างกันซึ่งการทำ agile ดีกว่าตรงที่นักพํฒนาและลูกค้าได้พูดคุยกันได้ทำงานร่วมกันไปเน้นความต้องการของลูกค้าเป็นหลักไม่เน้นแผ่นเอกสารสามารถปรับเปลี่ยนตามความต้องการของลูกค้าได้เลยซึ่งทางด้านwaterfallนั้นจะเน้นอะไรที่เป็นกระบวนการแบบแผนซะมากกว่านักพัฒนามีโอกาสได้พูดคุยกับลูกค้าน้อยและการใช้waterfallก็ไม่สามารถดูงานได้จนกว่าจะเสร็จซึ่งนี่เป็นข้อเสียถ้างานออกมาไม่ตรงกับความต้องการลูกค้าจะปรัปเปลี่ยนแก้ไขยากเสียค่าใช้จ่ายแพงจึงทำให้ไม่มีใครนิยมใช้waterfallกันแล้ว

2.	ตอบ	ไม่เห็นด้วยเพราะไม่ว่าจะ git/GitHub หรือ cvs/svnในเรื่องการทำversion control ทั้ง git/GitHub และ cvs/svn ต่างก็ทำได้แต่มีวิธีการต่างกันเล็กน้อยซึ่งส่วนตัวคิดว่าไม่ว่าจะใช้git/GitHub หรือ cvs/svnก็ได้แต่ต้องดูงานที่ทำว่าควรจะเลือกใช้อันไหนเอาที่เหมาะกับงานดีกว่า

3.	ตอบ	1. git checkout --orphan feature1
        2. git add .
        3. git commit feature1.
        4. git push origin feature1

4.	ตอบ	เมื่อเราทำการmergeซึ่งการเกิดconflictมันมีโอกาสเกิดมากอยู่แล้วแต่ก็อาจไม่เสมอไปแล้วถ้ามันเกิดconflictขึ้นมันก็มีวิธีแก้ไขอยู่แล้วส่วนตัวคิดว่าคำพูดของรุ่นพี่ส่วนนี้ไม่ดีเอาสียเลยเป็นการพูดที่บันทอนจิตใจการทำงานของเด็กรุ่นใหม่การทำงานมันมีโอกาสเกิดปัญหาอยู่แล้วแต่อยู่ที่เราจะแก้ไขได้หรือไม่

5.	ตอบ	

6.	 ตอบ	นั่นคือความชอบส่วนตัวก็เรื่องของคุณแต่ในส่วนของการทำ web application ไม่ใช่การทำตามกันเพราะแฟชั่นแต่หากเป็นการใช้เทคโนยีใหม่ๆที่มันมีความสะดวกรวดเร็วมากขึ้นมาใช้เพื่อที่จะใช้พัฒนาหรือสร้างสิ่งที่ทำให้มนุษย์ใช่งานได้ง่ายขึ้นสะดวกและรวดเร็วขึ้นกว่าการมานั่งเอาซอฟต์แวร์ลงแผ่น

7.	ตอบ	 1. เริ่มจาก Client ส่ง Requestไปที่ Web App 
         2.ถูกส่งต่อให้ Controller  ทำการตรวจสอบข้อมูลที่มาให้ (Request Method, Request Parameters) 
         3. แล้ว Controller จะเรียก Method ให้ทำงานเพื่อจัดการ Request นั้น 
         4. Model จะทำการคำนวณและอาจติดต่อกับ Database เพื่อจัดการกับ Request  
         นั้น แล้วส่งผลลัพธ์กลับไปที่ Controller 
         5. เมื่อ Controller ได้ผลลัพธ์จาก Model แล้วก็ใช้ผลลัพธ์นั้นส่งต่อให้ View ทำงาน 
         6. View จะสร้าง Page สำหรับแสดงผลลัพธ์นั้น แล้วส่ง page กลับไปที่ Controller  
         7. Controller ส่ง Page นั้น (เป็น Response) กลับไปยัง Client

8.	ตอบ	 jQuery = JavaScript Library ซึ่งถูกออกแบบมาเพื่อให้การเขียน JavaScript นั้นมีความสะดวกและง่ายขึ้นมันก็คือจาวาสคริปต์ ที่เขาเขียนไว้เป็นฟังก์ชั่นสำเร็จรูปมีความสะดวกในการใช้ ส่วน Rails = Ruby Gem หรือ Library ที่ใช้ในการเขียนเว็บ ผ่าน Command Line Interface (CLI) ซึ่งถูกสร้างโดย David Heinemeier Hansson มีความสะดวกสบายพอกันในการใช้งาน

9.	ตอบ	Heroku บริการกลุ่มเมฆแบบ PaaS ที่เดิมทีออกแบบมาเพื่อ Ruby เพียงอย่างเดียว (แล้วขยายมายัง Python, Java, Node.js ในภายหลัง)สามารถสร้าง buildpack สำหรับภาษาอื่นๆได้ซึ่งมีบทบาทที่สำคัญในการสร้าง web application จะช่วยลดเวลาในการพัฒนาแอปโดยตั้งเป้าหมายไปที่การพัฒนาแอปเลย ไม่ต้องตั้งค่าเครื่องเซิร์ฟเวอร์เองให้เปลืองเวลา ช่วยให้เราสร้าง web applicationได้สะดวกมากยิ่งขึ้น

10.	ตอบ	เพราะเพื่อให้นิสิตนักศึกษาได้เรียนรู้เกี่ยวกับ Software Development Process กระบวนการพัฒนาซอฟต์แวร์ เพื่อนำไปปรับใช้กับการทำงานให้เป็นระบบและเรียนรู้เครื่องมือเทคนิกวิธีการต่างๆที่จะช่วยให้การทำงานมีประสิทธิภาพมากยิ่งขึ้น 
