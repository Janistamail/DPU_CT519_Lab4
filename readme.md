## Janista Sihirunwong 645162010030

## LAB 4 วิธีการ run ที่ docker desktop

<p>1. clone project จาก repository DPU_CT519_Lab4 ลงมาที่เครื่อง </p>
<p>2. cd ไปที่ DPU_CT519_Lab4/ (ที่เก็บ docker-compose.yaml) และ run คำสั่ง docker compose up -d </p>
<p>ดูที่ container จะได้ตามภาพ</p>
<img width="400px" height="200px" src="https://github.com/Janistamail/DPU_CT519_Lab4/blob/master/img/container.png?raw=true">
<p>3. docker ps เพื่อเช็คว่ามี containers 3 อัน start อยู่ใน lab4 คือ ctn_adminer, ctn_maria-db, ctn_php </p>
<img width="600px" height="50px" src="https://github.com/Janistamail/DPU_CT519_Lab4/blob/master/img/dockerps.png?raw=true">
<p>4. เปิด browser 127.0.0.1:8080 ต้องได้รูปตามภาพ</p>
<img width="200px" height="300px" src="https://github.com/Janistamail/DPU_CT519_Lab4/blob/master/img/table.png?raw=true">
<p>5. เปิด browser 127.0.0.1:8081 กรอกข้อมูลตามภาพ และกรอก Password: dbpassw0rd</p>
<img width="700px" height="400px" src="https://github.com/Janistamail/DPU_CT519_Lab4/blob/master/img/loginAdminer.png?raw=true">
<p>6. login เข้ามาจะได้รูปตามภาพข้างล่าง</p>
<img width="300px" height="200px" src="https://github.com/Janistamail/DPU_CT519_Lab4/blob/master/img/adminer.png?raw=true">
