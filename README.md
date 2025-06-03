# RaspberryPiWebServer
Web Application Dev/Pen Testing
Anish/Tanner
Overview
We are setting up a self-hosted web server on a Raspberry Pi
•	Practice web application development
•	Search for and exploit vulnerabilities
•	learn web application security (securing website)

System Architecture
Hardware
-	Raspberry Pi
-	MicroSD
-	Optional SSD could help with performance?
OS
-	Raspberry Pi OS
-	Maybe have ssh enabled for access?
Software Stack
-	Webserver: Nginx or Apache
-	Backend: Node.js or Python (Flask/Fast API)
-	Database: MySQL
-	Frontend: HTML/CSS/JS or React

General Idea
-	Setup webserver and configure website from ground up (Understand)
-	Manual and Automated(tool) testing of web application to look for vulnerabilities/misconfigurations (Exploit)
-	Secure web application, harden web server, patch vulns (Fix)
-	Detailed report documenting the journey (Report)
UEFR
Understand, Exploit, Fix, Report

Security
Attack Path Vectors
-	Command Injection
-	Insecure File Uploads
-	IDOR (Insecure Direct Object Reference)
-	XXS (Cross-site scripting)
-	Broken Access (Authentication and login vulns)
-	Path Traversal
-	Security Misconfigurations
-	SSL attacks
