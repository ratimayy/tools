**Link ที่ทำกราฟ** https://github.com/ratimayy/tools/blob/main/HW_plotly_graph.ipynb


**Explain your data sources**

Dataset ที่เลือกมาจัดทำโดย GoodCarBadCar ที่เป็นเว็บให้ข้อมูลเกี่ยวกับการจัดอันดับรถที่ขายดีทั่วโลก โดยแบ่งย่อยไปถึงระดับทวีปและประเทศ โดยข้อมูลที่เลือกมาเป็นเป็นข้อมูลจาก https://www.goodcarbadcar.net/2024-us-auto-sales-figures-by-brand-brand-rankings/ ซึ่งเป็นบทความเรื่อง 2024 U.S. Automotive Sales by Brand – The Best-Selling Automotive Brands By Sales Volume ซึ่งข้อมูลในลิ้งมีหลายแบรนด์
แต่ข้อมูลที่เลือกมาทำกราฟเป็นแบรนด์ที่ขายได้จำนวนคันมากสุด 5 อันดับแรก (Ford, Toyota, Chevrolet, Honda, Nissan) ระหว่าง Quarters1 2022 ถึง Quarter4 2023

![newplot](https://github.com/ratimayy/tools/assets/135037700/0b55cbdb-acdf-414f-9f4c-8ab37917a2a0)

โดยจากกราฟ ที่ทำได้นั้นบอกได้ว่า จาก 5 แบรนด์ที่ขายดีในประเทศอเมริกา 3 แบรนด์เป็นของประเทศญี่ปุ่น(Toyota, Honda, Nissan) และ 2 แบรนด์เป็นของประเทศอเมริกา(Ford, Chevrolet) 
อีกที่จากจำนวนยอดขายรถรวมปี 2022 และ 2023 3 อันดับแบรนด์ที่ขายดีคือ Ford, Toyata, Chevrolet และ 2 อันดับท้ายคือ Honda และ Nissan ซึ่ง 2 อันดับท้าย จำนวนรถที่ขายได้น้อยกว่า 3 อันดับแรกมาก


**Explain why choose the chart with your data**

ต้องการศึกษาว่าแบรนด์รถยี่ห้ออะไรและจากประเทศไหน ขายดีในประเทศอเมริกา และยอดขายแต่ละไตรมาสเป็นเท่าไหร่
เหตุผลที่เลือก Bar charts with Long Format Data เพราะสามารถแสดงและเปรียบเทียบยอดขายของแต่ละไตรมาสระหว่างแบรนด์ โดยความสูงของแท่ง bar บอกว่า ปี 2022 และ 2023 ยอดรวมปริมาณรถยนต์ที่ขายได้ โดยแท่งสูงกว่าแปลว่าขายดีกว่า
