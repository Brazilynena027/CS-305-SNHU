# CS-305-SNHU



•	Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

Artemis Financial is a financial consulting company that creates financial plans for individuals which include savings plans, retirement investments and insurance.  Artemis Financial objective is to modernize its operations through the implementation of the most current and effective software security. Specifically, Artemis Financial wants to add a file verification to its web application to make sure that there is secure communication. That verification step will be a checksum. To do this, I need to use their existing software application and add the secure communications and meet all the company’s software requirements. The requirements that need to be met are:

1.	Secure Communication – using the checksum and encryption will protect the data during transfer.
2.	Hashing – using the hashing algorithm will validate the data increasing its reliability. 
3.	Vulnerability analysis – by conducting this analysis, it helps to identify areas of code to fix that can be exploited.
4.	Compliance- Helps Artemis financial stay within compliance according to federal and state regulations.
   
•	What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

I feel that my strongest area when dealing with the client’s software security vulnerabilities was to identify false positives. Through investigation of each vulnerability, I was able to identify the vulnerabilities that needed to be suppress due to no official fix or patch for that vulnerability. It is important to code security because it can prevent vulnerabilities in the software that attackers could exploit. By ensuring proper coding it create a more robust and secure application that clients can trust.  The value that it brings is it protects the company’s assets and gives the customer peace of mind and confidence in Artemis Financial.

•	Which part of the vulnerability assessment was challenging or helpful to you?

At first, I did find the vulnerability assessment confusing, however with some research and reading I began to understand. In the beginning I was only concentrating on the first vulnerability and not taking into consideration the rest. Which I quicky found out was incorrect once I started to go through looking for the false positives and suppressing them. 

•	How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

I increased my layers of security by using encryption, checksum verification and vulnerability analysis to protect the system and its data from vicious attacks ensuring if one layer fail the other will still offer protection. In the future to assess vulnerabilities and decide what mitigation techniques to use would be based on continuous scans and monitoring of the system to detect new vulnerabilities.  For example, web application scanners which target web applications to find vulnerabilities such as SQL injection and cross site scripting. Also, network scanners which will discover vulnerabilities in network protocols, ports and services. Tools to assess the risks which will prioritize them according to the severity and impact. Depending on what vulnerabilities are found will determine if a patch or limiting the access just to name a few will need to be implemented.

•	How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

To make sure the code and software were functional and secure I used vulnerability analysis and created a vulnerability report before and after each code change to see if any new vulnerabilities revealed themselves.  I used testing Dynamic testing to evaluate the software’s behavior. 

•	What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

The resources, tools or coding practices I used that might be useful in future assignments or tasks would be to rely on any documentation, online books and blogs. Tools such as IDES and debugging tools. Coding practices such as performing code reviews, continuous testing and continuous refactoring the code.  By implementing these resources, tools and practices can enhance the productivity and quality of the program and help the development process. 

•	Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I would consider showing employers my GitHub repositories that include my codes and projects from my coursework at SNHU and add any snippets of future projects. 
