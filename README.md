# Chipotle-Visualization
**สมาชิกกลุ่ม**
- 6720422012 ปาลิตา วรานุสาสน์
- 6720422029 นัทธมน ปิยพรธนา

**คำถาม**
1. Top 15 Most Ordered Item
- เมื่อเรียงลำดับรายการที่ขายดีที่สุดจากจำนวนที่ขายได้ พบว่า Chicken Bowl, Chicken Burrito, Chips and Guacamole, Steak Burrito และ Canned Soft Drink คือรายการที่ขายดีที่สุดตามลำดับ

2. item ที่ขายดีที่สุด 5อันดับแรก มีrange ราคาอยู่เท่าไหร่บ้าง
- จาก Distribution of Item Prices for Top 5 Most Ordered Items เราจะพบว่า ราตาของ Chicken Bowl, Chicken Burrito, Chips and Guacamole, Steak Burrito และ Canned Soft Drink มีการกระจายของราคาที่ต่างกัน โดย Chips and Guacamole และ Canned Soft Drink หรือ น้ำอัดลมกระป๋อง จะมีราคาที่ค่อนข้างเท่าๆกัน ซึ่งแตกต่างกับอีก3รายการที่มีrange ราคาตั้งแต่ 8-11 USD เนื่องจากราคาเมนูอาหารจะขึ้นอยู่กับ Cost of living ในแต่ละพื้นที่
- Source : https://nycdatascience.com/blog/student-works/analyzing-chipotle-pricing-food-shortages
  
3. Salsa Type of Best selling Menu
- จากที่เราได้รู้ว่าเมนูที่ขายดี 5 อันดับแรกคือเมนูอะไรแล้ว ขาดไม่ได้เลยที่จะวิเคราะห์ว่า Salsa ซอสหรือเครื่องจิ้มสไตล์เม็กซิกันที่เป็นองค์ประกอบหลักของเมนูขายดีของ Chipotle นั้น ส่วนใหญ่แล้วลูกค้าจะเลือก Salsa ประเภทไหน เมื่อเรียงจากเมนูที่ขายดีที่สุด ที่มี Salsa เป็นองค์ประกอบ จาก Bar Chart of Salsa Type for Top 5 Most Ordered by Percentage จะพบว่า Fresh Tomato Salsa, Roasted Chilli Corn Salsa, Tomatillio Red Chilli Salsa และ Tomatillio Green Chilli Salsa คือ Salsa ที่ถุกเลือกมากที่สุดตามลำดับ
- นอกจากนี้ ใน Sunburst of Salsa Type for Top 5 Most Ordered ยังสามารถบอกได้อีกว่า ในแต่ละประเภทของ Salsa ที่ลูกค้าเลือกนั้น ลูกค้าส่วนใหญ่เลือกความเผ็ดระดับไหนอีกด้วย เช่น สำรับเมนู Chicken Bowl ลูกค้ามักเลือก Fresh Tomato Salsa เป็นอันดับที่ 1 ซึ่งระดับความเผ็ดประกอบไปด้วย Mild และไม่ได้ระบุเป็นส่วนมาก อันดับที่ 2 ลูกค้าเลือก Roasted Chilli Corn Salsa ซึ่งระดับความเผ็ดประกอบไปด้วย Mild และไม่ได้ระบุเป็นส่วนมาก จึงสรุปได้ว่าแต่ละ Salasa แต่ละประเภทจะมีความเผ็ดแค่ระดับเดียวดังนี้ fresh tomato salsa มีความเผ็ดระดับ mild, roasted chili-corn salsa มีความเผ็ดระดับ medium, tomatillo-green chili salsa มีความเผ็ดระดับ medium, และ tomatillo-red chili salsa มีความเผ็ดระดับ hot
- Source : https://www.franchisechatter.com/2015/12/05/turning-up-the-heat-the-chipotle-mexican-grill-menu

4. สัดส่วนจำนวนquantity ที่ซื้อในแต่ละorder
- จากกราฟพบว่า คำสั่งซื้อส่วนใหญ่จำนวน 57.6% เป็นการสั่งซื้อสินค้า 2 ชิ้น รองลงมาคือการสั่งซื้อ 3 ชิ้น คิดเป็น 25.2% และการสั่งซื้อ 4 ชิ้น คิดเป็น 9.9%
5. ช่วงราคาที่ลูกค้ามักใช้จ่ายต่อออเดอร์ (Spending per order) อยู่ในช่วงใดมากที่สุด?
= จากกราฟพบว่า ช่วงราคาที่ลูกค้าสั่งซื้อในแต่ละออเดอร์ส่วนใหญ่อยู่ในช่วง $10–15 โดยมีจำนวนออเดอร์รวมทั้งสิ้น 852 ออเดอร์ ซึ่งถือเป็นช่วงราคาที่มีการสั่งซื้อมากที่สุด


