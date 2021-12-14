# Software-Security

**Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?**
  * Artemis Financial was a financial consulting company that delivered financial saving plans for savings, retirement, investments and insurance. Artemis Financial desire to modernize its operations and had the software to their public web interface. They wanted to address the steps to protect their client data and financial information, the steps to add file verification to their web app, and wanted data verification in the form of a checksum when data is transferred. 

**What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?**
  * I think I did a solid job in identifying Artemis Financials’ software security vulnerabilities. The source code that Artemis Financial provided had many security vulnerabilities so the main suggestion I can make is upgrading from Spring Framework version 2.2.4 to a more modern version. I now understand how to assess vulnerabilities, which is critical when designing secure code. It's much cheaper to incorporate secure practices early into a project than it is to come back to it. Customers expect their data to be kept secure so it cannot be viewed or stolen by anyone, so it's important to code securely and to run many tests to limit vulnerabilities.

**What about the process of working through the vulnerability assessment did you find challenging or helpful?**
  * The vulnerability assessment document provided is a good guide, but is also vague. Each of the separate vulnerable areas have a large amount of additional vulnerabilities to consider. I found the guide to potential vulnerabilities helpful, but wished the research was more guided as there is a lot of information on the web, and when learning it's hard to know what is factual or false information. 

**How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?**
  * For file verification, I used a hash key to ensure that the downloaded file matches Artemis Financials’ key. I also used the SHA-256 and RSA encryption algorithms to be able to encrypt data while in transfer and rest. Once a secure connection is established between client and server, the encrypted data can easily be decrypted. In the future, I would continue to follow industry best practices and use OWASP and NIST to stay on top of security vulnerabilities. 

**How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?**
  * I ran the code using a black-box testing approach to see what would be produced. When constructing the code, I incorporated tags and used Java pre-built classes and the SHA-256 encryption algorithm to ensure it is secure. First the data is encrypted, then cast into bytes, and then converted to Hex, finally producing the checksum value. After refactoring code, I ran a custom Maven build to install a dependency report, which I studied to ensure there weren't any added vulnerabilities. 

**What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?**
  * I learned some about the Spring Framework and Tomcat server. I also learned a lot about web security and data encryption, although I still have a lot to learn. I learned how to suppress vulnerabilities in a dependency report and also how to use OWASP to identify vulnerabilities. I would find each of these resources, tools, or coding practices helpful in the future as I will continue to develop code with security in mind. 

**Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?**
  * See the attached reports.
