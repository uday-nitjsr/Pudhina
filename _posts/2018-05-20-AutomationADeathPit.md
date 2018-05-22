---
layout: page
title:  "Automation a death pit"
subtitle: "Are you doing it the right way"
date:   2018-05-20 21:21:21 +0530
categories: ["Testing"]
---

I was recently watching this video by Allen Holub which was titled as "The death of Agile". As a software professional who started his career during the times when everyone is working in Agile methodology, or atleast aware of it. The idea of saying it is dead was appalling. At first I convinced myself that it is probably a provocative video where he is ranting why it is bad. To my surprise I was hooked after a few minutes of listening. According to Holub, most of the team dont understand the concept of agile, and only pretend to be following this methodology. He gave a indepth analysis why a big corporate is stringent towards changes hence can never call themselves agile.

[![Death of Agile](https://img.youtube.com/vi/vSnCeJEka_s/0.jpg)](https://www.youtube.com/watch?v=vSnCeJEka_s "Death of agile")

After listening to this video, it got me thinking that it is also true for Automation testing as well. Automation should be powerful tool which ideally should be leveraged to find bug at a very early stage and making product more robust. Instead, it is used as for verifying that application is not broken when new improvement or changes has been introduced in current feature. In my previous company the definition of automation testing is to do repetitive testing against different set of data. Automation was never seen as something which can be a part of functional testing during development.

Even though we have the concept of TDD. I have hardly seen it in use. The only implementation is during writing unit test cases. Sadly, most of the development team do no write test cases as it is time consuming, requires maintainence, and has lot of setup. As a result company has to hire QA professionals whose role is to make sure that application is bug free. We have created a whole industry which relies on developer's failure to write test cases. A reason oftenly given to counter this is that, since testing is time taking and needs extra effort, we might be comprimising with sprint velocity in a competetive enviroment. In a cut throat environment where everyone wanted to be the first to push functionalities so that they can be at the top of the rung, it is higly likely that anyone would be ready to make that trade off. This argument is well justified but it has been used since very long to avoid writing unit test cases at all. This has led to creation of an ecosystem where hardly developer's write unit test cases. And even if they it is the bare minimum coverage. 
