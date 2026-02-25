# 🚀 Question And Answer (Node.js + Express + MongoDB)

**1. Je kono akta jinish er upor base kore data find kora**
Ans : db.test.find({gender: "male"}); but ekhane akta bishoy hochhe jodi 100 ta datar modde gender thake tahle 100 ta datar shob info show korbe Ex: name, email ect

**2. But ami chai just Gender wala data show hobe but onno kichu jate show na kore?**
Ans : db.test.find({gender: "male"}, {gender:1}); Ekhane 1 mane true tai shudu gender e show hobe

**3. Search MongoDB Oparetors**
Ans : MongoDB Oparetors > Queary and projection Oparetors > Comparisom Query Oparetors

**4. Condittion Cheek jemon age : 12; jara ache shudu tader data Dao**
Ans : db.test.find({age: {$eq : 12}}); je data gular age 12 shudu shegula dekhabe

**5. Condittion Cheek jemon age : 12; jara ache shudu tader **bade** baki data Dao**
Ans : db.test.find({age: {$ne : 12}}); je data gular age 12 shegula sara bakigula dekhabe.

**Waht is gt** 
Ans : Same Bhabe aro che **gt** mane gater than 30:gt tahle 30er uporer gula show hobe.        


**Waht is gte** 
Ans : **gte** mane 30:gte tahle 30er shoman and er uporer gula nibe

**4. Akta range onujaye Condittion Cheek jemon age 18 thek 30**
Ans : db.test.find({age: {$gte: 18, $lte: 30}}, {age:1});

**$Set**
Ans : $set use korle data replece korbe new data boshbe 



