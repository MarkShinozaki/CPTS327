# Homeworks 


### [Summary of Homework 1](https://github.com/MarkShinozaki/CPTS327-CyberSecurity-CryptoGraphy/tree/Homeworks/HW01)

#### Summary of the Assignment:

The assignment is to perform threat modeling for a system where a 'Host Web Client' interacts with:

1. A **'Remote Web Server'** via an HTTP request/response cycle.

2. An external **'User'** via a generic command/service cycle.

3. A **'File System'** using a read/write cycle.

The task requires creating a data flow diagram (DFD) and identifying threats using the STRIDE approach (Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, and Elevation of Privilege). While proposing mitigations for the identified threats is optional, the main objective is to perform threat modeling from the perspective of a system administrator for the company controlling the 'Host Web Client'. The threat model should focus on a company perspective rather than an end-user perspective.



--- 

### [Summary of Homework 2](https://github.com/MarkShinozaki/CPTS327-CyberSecurity-CryptoGraphy/tree/Homeworks/HW02)

#### Summary of the Assignment:

The assignment involves completing a tutorial on password security, available at the provided GitHub link. Students are expected to perform the tasks and activities described in the tutorial, which include various password cracking techniques, analyzing hashing algorithms, and understanding different modes of password attacks



#### Topics Learned:

##### 1. Password Cracking Techniques:

- Cracking passwords using default MD5 hashing.
- Cracking passwords using wordlists.
- Cracking passwords by specifying rules.

##### 2. Analysis of Cryptographic Hashing Algorithms:

- Understanding why certain algorithms like SHA-1 should not be used due to vulnerabilities like collision attacks.
- Recognizing the importance of using strong hashing algorithms like bcrypt for password security.

##### 3. Effectiveness of Different Password Cracking Modes:
- Comparing default cracking mode and wordlist mode to understand their effectiveness depending on the password's structure and complexity.

##### 4. Brute-Force Attacks:
- Theoretical understanding that brute-force attacks can crack any password given enough time and resources, while practical limitations make such attacks infeasible for complex passwords.


--- 

### [Summary of Homework 3](https://github.com/MarkShinozaki/CPTS327-CyberSecurity-CryptoGraphy/tree/Homeworks/HW03)

#### Summary of the Assignment:

The assignment is designed to help students understand and evaluate access control systems in commonly found operating systems. 

#### The key tasks include:

1. **Identifying the Main Computing Environment**: Students will identify their primary operating system, such as Windows, MacOS, or Linux.

2. **Discovering Access Control Systems**: Students will explore and document all forms of access control systems present in their main computing environment, supported by screenshots.

3. **Categorizing Access Control Systems**: The discovered access control systems must be categorized into models like Discretionary Access Control (DAC), Mandatory Access Control (MAC), Role-Based Access Control (RBAC), or other relevant access control models.

4. **Evaluating from a Malicious Perspective**: Students will evaluate these access control systems from the perspective of a malicious agent, identifying any potential weaknesses or vulnerabilities.

#### Topics Learned:

##### 1. Understanding Access Control Models:

- **Discretionary Access Control (DAC)**: Control based on the discretion of the user or administrator, such as NTFS permissions and share permissions in Windows.
  
- **Mandatory Access Control (MAC)**: More rigid access control often used in high-security environments.
  
- **Role-Based Access Control (RBAC)**: Access based on roles assigned to users, as seen in systems like Windows Firewall.

##### 2. Access Control Evaluation:

- Analyzing access control systems to understand their effectiveness and potential vulnerabilities from a security perspective.

##### 3. Practical Application:

- Documenting access control settings with screenshots and analyzing these settings to understand how access is managed within a specific operating system.




---

### [Summary of Homework 4](https://github.com/MarkShinozaki/CPTS327-CyberSecurity-CryptoGraphy/tree/Homeworks/HW04)

#### Summary of the Assignment:

This assignment involves working through a tutorial on static testing and static analysis, focusing on identifying code issues without executing the program. Students are expected to perform various activities outlined in the tutorial, such as analyzing code for potential defects, understanding memory leaks, and using code review checklists.

#### Topics Learned:

##### 1. Memory Leaks:

- Understanding how memory leaks occur, particularly in complex structures like the "UberNode" class, where destructors do not properly release allocated memory.

##### 2. Static Testing vs. Static Analysis:

- **Static Analysis**: Automated examination of code to identify issues without running the program. It focuses on structure, syntax, and potential errors like memory leaks.

- **Static Testing**: A broader approach that includes both static analysis and code reviews, focusing on identifying defects through human inspection and documentation.

##### 3. Halting Problem:

- The concept from Alan Turing that proves no algorithm can determine whether all possible programs will terminate or run forever. This highlights the challenge of proving the correctness of non-trivial programs.

##### 4. Technical Review and Code Inspection:

- Utilizing checklists for systematic code reviews to ensure quality, identify defects, and maintain coding standards.

This assignment reinforces the importance of rigorous code analysis without execution, highlighting the role of both automated tools and human inspections in ensuring software quality. The exercise also provides practical insights into how theoretical concepts like the halting problem influence real-world programming practices.

---

### [Summary of Homework 5](https://github.com/MarkShinozaki/CPTS327-CyberSecurity-CryptoGraphy/tree/Homeworks/HW05)

#### Summary of the Assignment:

This assignment focuses on understanding and mitigating web security vulnerabilities, specifically Cross-Site Scripting (XSS) and Cross-Site Request Forgery (CSRF). The students are required to perform activities and challenges related to these vulnerabilities using a tutorial and a vulnerable web application called bWAPP.

#### Topics Learned:

##### 1. Cross-Site Scripting (XSS) Vulnerabilities:

- Understanding how XSS attacks exploit unsanitized user input to execute malicious scripts within a user’s browser.

- Recognizing the importance of input validation, output encoding, and implementing Content Security Policies (CSP) to prevent XSS.


##### 2. Cross-Site Request Forgery (CSRF) Attacks:

- Exploring how CSRF attacks trick users into executing unwanted actions on a web application in which they are authenticated.

- Implementing defenses against CSRF, such as synchronizing tokens, double-submitting cookies, and using same-site cookies.

##### 3. Mitigation Techniques:

- Applying techniques like one-time token implementations to prevent the reuse of session tokens by attackers, thereby safeguarding against CSRF attacks.

##### 4. Practical Security Challenges:

- Engaging in hands-on activities to modify and exploit web vulnerabilities and then developing strategies to secure web applications against such attacks.

This assignment provides practical exposure to identifying and mitigating web security vulnerabilities, reinforcing the importance of secure coding practices and the use of security mechanisms like token synchronization and input validation.










