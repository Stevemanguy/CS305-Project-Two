# CS305-Project-Two

1. Briefly summarize your client, Artemis Financial, and its software requirements.
Artemis Financial is a fictional company that needed help securing its financial web application. The company wanted to identify and fix security vulnerabilities in its software.

2. What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?
I used tools like dependency-check to find known vulnerabilities. Coding securely protects user data, builds trust, and prevents cyberattacks that can harm the company.

3. Which part of the vulnerability assessment was challenging or helpful to you?
Setting up the dependency-check plugin and understanding all the reported CVEs was challenging but helped me learn how to identify real risks.

4. How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
I added HTTPS, created a keystore, and used SHA-256 hashing. In the future, I would continue using tools like OWASP Dependency-Check and stay updated on best practices.

5. How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
I tested the application endpoints, verified the checksum output, and reran the dependency-check report to confirm no new issues were added.

6. What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
I used Java’s MessageDigest class, Spring Boot, HTTPS configuration, and OWASP tools. These are useful for secure development and testing.

7. Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
I would show the vulnerability report, the secure code with HTTPS and hashing, and the final working application as proof of secure software development skills.
