# CS305 Software Security


## Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
Throughout this course I played the role of developer for a third-party company specializing in software security. Artemis Financial approached the software security company to ensure their website met up-to-date standards of networking and software security. 

## What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
I consider myself particularly good at identifying security vulnerabilities through code review. I am far less experienced in the maven static testing procedure, which is what we used throughout this course.

## What about the process of working through the vulnerability assessment did you find challenging or helpful?
I found learning maven's dependency check testing very challenging--not particularly in set-up and execution--but rather in review. Once I figured out that assessing vulnerabilities through the dependency check report is simply just researching each potential vulnerability to uncover if it is genuine or just a false positive was very helpful in understanding the process.

## How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?
I approached the need for increased security by first reviewing code as I believe the first step in writing secure software is to ensure the code base meets industry standards for best practices. After the code review and refactoring (if necessary), I will then run the maven dependency check to ensure any libraries used in the code base do not have security vulnerabilities that can transfer into the final product I am working on. 

## How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?
To ensure I did not introduce any new vulnerabilities to the code base, I ran the maven dependency check report again to ensure no new vulnerabilities were found.

## What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?
The only new tool introduced to me through this course was the maven dependency check plugin. I can see myself using it in the future, but not as frequently as used in this course. 

## Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?
The project 2 submission would be the example I would submit. It shows my practical experience learned in this course through the code base, as well as showing my technical understanding and writing competency via the write-up
