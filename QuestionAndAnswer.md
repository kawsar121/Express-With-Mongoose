# 🚀 Question And Answer (Node.js + Express + MongoDB)

**1. Je kono akta jinish er upor base kore data find kora**
Ans : db.test.find({gender: "male"}); but ekhane akta bishoy hochhe jodi 100 ta datar modde gender thake tahle 100 ta datar shob info show korbe Ex: name, email ect

**2. But ami chai just Gender wala data show hobe but onno kichu jate show na kore?**
Ans : db.test.find({gender: "male"}, {gender:1}); Ekhane 1 mane true tai shudu gender e show hobe

**3. Search MongoDB Oparetors**
Ans : MongoDB Oparetors > Queary and projection Oparetors > Comparisom Query Oparetors