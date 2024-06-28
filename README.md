# CS305-SoftwareSecurity

Summary
Client Overview and Software Requirements
Client: Artemis Financial
Artemis Financial handles sensitive financial data for clients, including savings, retirement, investments, and insurance information. The company required enhancements to its web application's security to protect this data from unauthorized access and comply with industry regulations. Specifically, they needed secure communication channels and robust data integrity verification.

Issue Addressed:
The company wanted to address potential vulnerabilities in their data transmission and storage processes to ensure the integrity and confidentiality of sensitive client information.

Security Vulnerabilities Identification and Importance of Secure Coding
What was done well:
In identifying security vulnerabilities, we conducted a comprehensive review of the application, focusing on encryption methods, certificate generation, and secure communication protocols. We used the OWASP Dependency Check tool and manual code reviews to ensure no new vulnerabilities were introduced.

Importance of Secure Coding:
Coding securely is vital to protect sensitive data from breaches and cyber-attacks. Secure software enhances a company’s reputation, builds client trust, and ensures compliance with legal and regulatory standards. By securing software, a company can prevent data breaches, reduce the risk of costly incidents, and maintain a strong market position.

Challenges and Learnings from the Vulnerability Assessment
Challenges and Helpful Aspects:
The most challenging part of the vulnerability assessment was ensuring that the implementation of new security measures did not introduce new vulnerabilities. The detailed static and dynamic testing processes were particularly helpful in identifying and mitigating potential security issues.

Increasing Layers of Security and Future Vulnerability Assessments
Increasing Security Layers:
To increase security, we implemented SHA-256 for data integrity verification and configured HTTPS for secure communications using a self-signed certificate. In the future, tools like OWASP Dependency Check and manual code reviews will be used to continuously assess vulnerabilities and decide on appropriate mitigation techniques.

Ensuring Functional and Secure Code
Ensuring Functionality and Security:
After refactoring the code to include new security measures, we performed extensive testing using the OWASP Dependency Check tool and manual reviews. This ensured that the application remained functional and that no new vulnerabilities were introduced during the refactoring process.

Useful Resources, Tools, and Practices
Resources and Tools Used:

SHA-256 Encryption: For data integrity verification.
Java Keytool: For generating self-signed certificates.
Spring Boot: For configuring HTTPS.
OWASP Dependency Check: For identifying vulnerabilities in project dependencies.
Manual Code Reviews: For identifying syntactical, logical, and security vulnerabilities.
These tools and practices will be valuable in future assignments for maintaining high standards of security in software development.

Demonstrating Skills and Knowledge to Future Employers
Showcase to Employers:
From this assignment, I would highlight the implementation of SHA-256 encryption for data integrity, the configuration of HTTPS for secure communication, and the comprehensive testing and review processes used to ensure the application’s security. These elements demonstrate my ability to enhance software security and ensure robust protection of sensitive data.
