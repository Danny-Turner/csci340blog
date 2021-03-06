---
layout: post
author: Dan Turner
---
As part of  this course (CSCI 340), my project team partnered with a local non-profit organization called [City of Hope](https://www.coho58.org/) (CoHO). I already knew a little about CoHO because they worked with my church ([First Presbyterian](https://www.fpcconway.org/)) to make a community garden. After our first client meeting at CoHO, I learned that they help meet the needs of under resourced communities in Central Arkansas. They have worked with six different locations to provide services including: Community Gardens for food, CoHO Academy for after school education and activities for youth, and Hope Home to provide temporary housing and employment for men while they transition to independent living. Rather than trying to make large scale systemic changes, they focus on specific communities where they can have a more significant impact.

Most of their work is done by volunteers. Our project was to develop a database/website to allow volunteers to track their time (clock in/out) and to allow CoHO staff to run reports on volunteer activities. These reports will assist them in applying for grants. During our client meetings, we learned more about the type of information that is important for them to track. In particular, they need to know if their volunteers are on workers comp, or doing community service. In addition, in order to apply for grants, they need to track demographic information like  race, disabilities, education level, gender, etc

I enjoyed the opportunity to work on a project that will actually be used by a local non-profit. Knowing that our project will actually be used added a sense of responsibility to the work. I believe that we have done a very good job of creating a system to track the activities of their volunteers, but I have some concerns about the project that I would change if I have the opportunity to work with other projects like this in the future.

In particular, we did not implement our reporting functionality until late in the project and I am not certain  that the reports we have implemented will fully address our clients needs. I would like to have had an opportunity to get feedback from CoHO staff after we had a working version of the project. This would have allowed us to address inevitable issues that will be discovered when  people use the program.

Even if our project is bug free and meet the clients needs, it seems that the maintenance of the programs may be an issue.
- How long will Hendrix host the website for CoHO?
- Will Hendrix provide tech/server support when needed?
- If at some point in time in the future Hendrix stops hosting the site, will there be an opportunity for them to transfer the data history to CoHO staff?

In addition, near the end of our project, our team realized that we made some design decisions that might be problematic for CoHO.
- We decided to implement login and authorization using the Identity package for ASP.NET. However this will need a security certificate to work correctly once the project goes live. I believe CoHO can obtain a certificate free of charge, but I am not certain what it will take to maintain this on the server.
- Additionally, when our team implemented the reporting capabilities we used a package called Syncfusion. Syncfusion allows the website to create Excel spreadsheets and Word documents; however, while preparing for our final presentation we realized it requires a license to use in production. Fortunately, after a little research, we determined that a small nonprofit (such as CoHO) can apply for a free license, but this is another hoop our client will need to jump through in order to make full use of the solution we designed.

Overall, I feel that working on this project was a very valuable experience. The various members of our team developed several useful programming skills, and worked together with the staff at CoHO to develop a very nice project.
