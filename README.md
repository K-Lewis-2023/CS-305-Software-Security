# CS-305-Software-Security
Portfolio Submission
Kelly Lewis


•	Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

The client, Artemis Financial, is a financial consulting company that designs personalized financial plans for their patrons in the form of savings, retirement, investments and insurance accounts. The client requested that we analyze their RESTful web API for potential issues and protection against outside threats.

•	What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

I believe that identifying the areas of concern and implementing the static dependency check/ identifying the vulnerabilities. Secure coding is important to prevent many forms of attacks against our systems, we must work to prevent common intrusion types such as bypassing data input validation, access control, error handling, authentication/ password management, etc. Software security allows a company to be more capable in their daily tasks while reducing or removing security concerns.

•	What about the process of working through the vulnerability assessment did you find challenging or helpful?

On the helpful side, I found the implementation and assessment of the maven dependency to be extremely helpful in identifying the risks and allowing me the ability to address them. 

On the challenging side, some of the vulnerabilities did not have clear recommendations, thus deciding on the next logical step did prove challenging in some cases.

•	How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

I approached the need by first manually reviewing the code to identify any vulnerabilities caused by the initial code base. Then I analyzed the APIs utilizing the dependency check. I would use the same strategies, however my communication of my strategies would need to be polished more. Additionally, I would want to integrate new tools as well as ensuring that I was meeting industry standards.

•	How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

I started with a manual review of the code base, following data flows and checking for logic errors. Next, I implemented the OWASP Maven dependency check and ran it as a static checking tool to analyze the integrated APIs. Any time that the code base was refactored in anyway, I would again perform a manual review and dependency check, to ensure that no new vulnerabilities were introduced. 

•	What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

The two new tools that I have been given this term that I am proud to add to my coding arsenal, OWASP Maven dependency check (and the use of similar tools) and the various other resources that can guide through securing software.

•	Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

I would want to showcase my implementation, review, and response to the dependency check.

//END
