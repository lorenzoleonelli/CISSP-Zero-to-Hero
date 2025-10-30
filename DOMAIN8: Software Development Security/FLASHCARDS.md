## Flashcards ##

1. What is the Software Development Life Cycle (SDLC)?

<details> <summary>Show answer</summary> The SDLC is a structured process used by organizations to design, develop, test, and deploy high-quality software. </details>

2. What is the core philosophy of DevSecOps?

<details> <summary>Show answer</summary> DevSecOps integrates security practices, tools, and responsibilities into every phase of the DevOps pipeline, from planning to deployment. </details>

3. What is Threat Modeling?

<details> <summary>Show answer</summary> A structured process used to identify potential security threats and vulnerabilities in an application's design phase, and then define countermeasures. </details>

4. What does the STRIDE model, used in threat modeling, stand for?

<details> <summary>Show answer</summary> Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, and Elevation of Privilege. </details>

5. What is Input Validation?

<details> <summary>Show answer</summary> The security practice of properly testing and sanitizing all user-supplied data before it is processed by an application to prevent injection attacks. </details>

6. What is the purpose of Output Encoding?

<details> <summary>Show answer</summary> To convert special characters into a safe format before rendering them in a user's browser, primarily to prevent Cross-Site Scripting (XSS) attacks. </details>

7. What is a SQL Injection attack?

<details> <summary>Show answer</summary> An attack technique where malicious SQL code is inserted into input fields, allowing an attacker to manipulate or access the backend database. </details>

8. What is a Buffer Overflow vulnerability?

<details> <summary>Show answer</summary> A condition where a program writes data beyond the boundaries of its allocated memory buffer, potentially overwriting adjacent memory and causing crashes or code execution. </details>

9. What is a Time-of-Check to Time-of-Use (TOCTOU) attack?

<details> <summary>Show answer</summary> A race condition vulnerability where an attacker manipulates the state of a resource (like a file) between the time the system checks it and the time it uses it. </details>

10. What is Static Application Security Testing (SAST)?

<details> <summary>Show answer</summary> A "white-box" testing methodology that analyzes an application's source code, byte code, or binary code without executing it to find security vulnerabilities. </details>

11. What is Dynamic Application Security Testing (DAST)?

<details> <summary>Show answer</summary> A "black-box" testing methodology that tests a running application from the outside, probing its inputs and outputs to find vulnerabilities just as an attacker would. </details>

12. What is Fuzz Testing (Fuzzing)?

<details> <summary>Show answer</summary> A testing technique that involves providing invalid, unexpected, or random data (known as "fuzz") to an application's inputs to discover errors and security flaws. </details>

13. What is the main difference between White Box and Black Box testing?

<details> <summary>Show answer</summary> White Box testing involves full knowledge of the application's internal code and structure, while Black Box testing involves no internal knowledge, only testing from a user's perspective. </details>

14. What is the purpose of Change Management in software development?

<details> <summary>Show answer</summary> To provide a structured process for managing all changes to software, ensuring they are documented, tested, and authorized to prevent unintended outages or security issues. </details>

15. What is Version Control?

<details> <summary>Show answer</summary> A system that tracks and manages changes to source code over time, allowing developers to collaborate, revert to previous versions, and manage different branches. </details>

16. What is Software Escrow?

<details> <summary>Show answer</summary> A legal agreement where a third party holds the source code of a critical application, which is released to the customer if the vendor goes bankrupt or fails to provide support. </details>

17. What is the risk of using Open Source Software (OSS)?

<details> <summary>Show answer</summary> The primary risk is inheriting any unpatched vulnerabilities within the open-source components, which requires diligent tracking and vulnerability management. </details>

18. What is Software Composition Analysis (SCA)?

<details> <summary>Show answer</summary> An automated process that scans an application to identify all open-source components, their license types, and any known security vulnerabilities. </details>

19. What is the primary security concern with Application Programming Interfaces (APIs)?

<details> <summary>Show answer</summary> Improper authorization and authentication, which can lead to attackers accessing or manipulating data they shouldn't be able to. </details>

20. What is a Maintenance Hook or Backdoor?

<details> <summary>Show answer</summary> An unauthorized or undocumented entry point left in a program by a developer, which can be exploited by an attacker for unauthorized access. </details>

21. What is Acceptance Testing?

<details> <summary>Show answer</summary> The final phase of testing where the software is validated against the business requirements to determine if it meets the criteria for delivery. </details>

22. What is the Principle of Least Privilege in secure coding?

<details> <summary>Show answer</summary> It dictates that a process or application should run with only the minimum access rights and permissions necessary to perform its specific task. </details>

23. What is the difference between Fail-Secure and Fail-Open?

<details> <summary>Show answer</summary> A "Fail-Secure" system denies access or service upon failure (e.g., a firewall blocking all traffic). A "Fail-Open" system permits access upon failure (e.g., a door unlocking during a fire). </details>

24. What is secure Error Handling?

<details> <summary>Show answer</summary> The practice of catching errors and logging detailed information internally, while only showing generic, non-informative error messages to the end-user to avoid leaking system data. </details>

25. What is the risk of hardcoding credentials?

<details> <summary>Show answer</summary> Storing usernames, passwords, or API keys directly in the source code makes them easily discoverable by anyone with access to the code, leading to system compromise. </details>

26. What is the Agile development methodology?

<details> <summary>Show answer</summary> An iterative approach to software development that emphasizes flexibility, customer collaboration, and rapid delivery of functional software in small increments. </details>

27. What is the Waterfall model?

<details> <summary>Show answer</summary> A traditional, sequential SDLC model where each phase (e.g., Requirements, Design, Implementation, Testing) must be fully completed before the next one begins. </details>

28. What is a Cross-Site Scripting (XSS) attack?

<details> <summary>Show answer</summary> A vulnerability where an attacker injects malicious scripts (usually JavaScript) into a trusted website, which then execute in a victim's browser. </details>

29. What is a Cross-Site Request Forgery (CSRF) attack?

<details> <summary>Show answer</summary> An attack that tricks a user's authenticated browser into sending an unintended command to a web application (e.g., changing a password, making a purchase). </details>

30. What is the primary defense against CSRF attacks?

<details> <summary>Show answer</summary> Using unique, unpredictable anti-CSRF tokens for each session or state-changing request, which the server validates before executing the action. </details>

31. What is Code Signing?

<details> <summary>Show answer</summary> The process of using a digital signature to confirm the identity of the software publisher and guarantee that the code has not been tampered with since it was signed. </details>

32. What is Software Assurance (SA)?

<details> <summary>Show answer</summary> The level of confidence that software functions as intended and is free of vulnerabilities, whether intentionally or unintentionally introduced. </details>

33. What is a "secure baseline"?

<details> <summary>Show answer</summary> A standardized, hardened configuration for an operating system or application that is applied to all new deployments to ensure a consistent and secure starting point. </details>

34. What is Infrastructure as Code (IaC)?

<details> <summary>Show answer</summary> The process of managing and provisioning infrastructure (networks, VMs, load balancers) through machine-readable definition files (code), rather than manual configuration. </details>

35. What is the security benefit of Infrastructure as Code (IaC)?

<details> <summary>Show answer</summary> It allows security configurations to be defined, version-controlled, and automatically audited, ensuring consistent and repeatable application of security policies. </details>

36. What is a Container (in software)?

<details> <summary>Show answer</summary> A lightweight, standalone, executable package of software that includes everything needed to run it: code, runtime, system tools, and libraries (e.g., Docker). </details>

37. What is a key security challenge with Containers?

<details> <summary>Show answer</summary> Using base images that contain unpatched vulnerabilities, or misconfiguring container runtime permissions, which could allow an attacker to "escape" the container. </details>

38. What is Code Obfuscation?

<details> <summary>Show answer</summary> The process of making source code or machine code difficult for humans to read or reverse-engineer, often used to protect intellectual property. </details>

39. What is Normalization (in database security)?

<details> <summary>Show answer</summary> The process of organizing data in a database to reduce redundancy and improve data integrity, which can also help prevent certain types of data modification anomalies. </details>

40. What is Regression Testing?

<details> <summary>Show answer</summary> Testing conducted after a change or fix to ensure that the new functionality has not introduced new defects or broken existing functionality. </details>

41. What is a Security Requirements Traceability Matrix (SRTM)?

<details> <summary>Show answer</summary> A document that maps security requirements to the corresponding design, code, and test cases to ensure all security needs are explicitly met and verified. </details>

42. What is Software Supply Chain Security?

<details> <summary>Show answer</summary> The process of managing and securing the entire "chain" of components, libraries, and tools used to build and deliver software, from development to the end-user. </details>

43. What is a Peer Review in secure development?

<details> <summary>Show answer</summary> A structured process where a developer's code is manually examined by other developers to identify defects, security flaws, and deviations from coding standards. </details>

44. What is the main goal of Configuration Management?

<details> <summary>Show answer</summary> To establish and maintain consistency of a product's performance, functional, and physical attributes with its requirements, design, and operational information. </details>

45. What is Runtime Application Self-Protection (RASP)?

<details> <summary>Show answer</summary> A security technology that is integrated into a running application to detect and block attacks in real-time by monitoring its own behavior and data flows. </details>

46. What is Code Attestation?

<details> <summary>Show answer</summary> A process that verifies the integrity and source of code. A system can check the "fingerprint" (hash) of its code to ensure it hasn't been tampered with. </details>

47. What is a "dead code" vulnerability?

<details> <summary>Show answer</summary> Code that is never executed in an application. It serves no purpose but increases the attack surface and can contain vulnerabilities that are missed by testers. </details>

48. What is the purpose of Secure Session Management?

<details> <summary>Show answer</summary> To securely handle the life cycle of a user's session, including generating strong session tokens, protecting them in transit (e.g., HTTPS), and invalidating them upon logout. </details>

49. What is the difference between Authentication and Authorization?

<details> <summary>Show answer</summary> Authentication is the process of proving who you are (e.g., logging in). Authorization is the process of determining what you are allowed to do (e.g., viewing a file). </details>

50. What is the "build" phase in the SDLC?

<details> <summary>Show answer</summary> The phase where the human-readable source code is compiled into an executable binary or deployable package. Security scans (like SAST) are often integrated here. </details>
