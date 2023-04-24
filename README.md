# CS-305

    Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
    Artemis Finacial is a consulting firm that creates individualized financial plans for their clients. They wanted us to secure their RESTful API web application.
    
    What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
    When vulnerabilities were found, I think I did a good job detailing what they were and the steps necessary to mitigate them. Some vulnerabilities in libraries and frameworks have no known solution, even when everything is up to date; coding securely means you are using industry best practices to protect your program and databases, despite software shortcomings. The company Artemis Financial benefits from robust software security because of the trust it instills in their clientele.
    What part of the vulnerability assessment was challenging or helpful to you?
    I found understanding the vulnerabilities in the dependency check report to be a steep learning curve, especially because I was not familiar with most of the software it was refering to. But the owasp dependency check report is well constructed and easy to follow, which was a great help.
    How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
    After the vulnerabilities were assessed, I was able to increase security by securing API interactions, Error Handling, Code Quality, and Encapsulation. In the future I would like to explore DAST.
    How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
    The owasp dependency check was repeated as necessary until no new or unaddressed vulerabilities were in the report.
    What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
    https://cheatsheetseries.owasp.org/index.html was a giant help in understanding software security conceptually and then implementing industry best practices. It is a permanent fixture in my toolbar quick-links now!
    Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
    I had to do a lot of troubleshooting and configuration to get the embedded tomcat webserver in spring to redirect from HTTP to HTTPS. I think I would walk someone through that process and discuss what I learned and overcame with that difficulty.
