# CS-305-12205-M01-Software-Security-2025

My client, Artemis Financial, is a financial services firm that provides web-based solutions to its clientele. The company has requested a thorough review of its code for security purposes and enhancements to guarantee that its application complies with secure software development standards. They expressed particular concern regarding vulnerabilities that might compromise customer data and the overall reliability of the application. 

In the process of identifying and addressing the software security vulnerabilities of Artemis Financial, I successfully employed static code analysis, dependency checking, and secure coding practices. A notable achievement was my configuration of the OWASP Dependency-Check tool and the implementation of suppression rules to manage false positives. Secure coding is crucial as it safeguards sensitive information, mitigates the risk of exploitation, and fosters user trust. Robust software security not only enhances a company's reputation but also diminishes financial and legal risks. 

One difficulty I encountered while conducting the vulnerability assessment was distinguishing false positives in the dependency-check report and effectively suppressing them without overlooking genuine threats. Nevertheless, this procedure enhanced my ability to critically assess reported vulnerabilities. 

To enhance security measures, I have implemented SSL to guarantee encrypted communication and to verify data integrity through the use of checksums. Moving forward, I plan to utilize automated tools such as SonarQube or OWASP ZAP in conjunction with manual code reviews to evaluate vulnerabilities and establish mitigation strategies based on their severity and potential for exploitation. 

To guarantee that the code continued to function properly and securely following modifications, I performed tests and re-evaluated the OWASP report to identify any new issues. Additionally, I confirmed that SSL was appropriately configured by utilizing browser inspection tools and executing HTTPS connections. 

I utilized Maven for managing the project, employed OWASP Dependency-Check for scanning vulnerabilities, and adhered to secure coding practices including input validation and appropriate encryption. These tools and practices will prove beneficial in upcoming development projects and professional assignments. 

Through this assignment, I can present to prospective employers the finalized secure software report as proof of my capability to conduct a genuine vulnerability assessment and implement secure coding practices. This showcases both the technical and analytical skills essential for software development that is aware of cybersecurity. 
