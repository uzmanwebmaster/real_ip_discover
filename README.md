# VULNFIX — A Community-Powered Tool for Real IP Discovery Behind WAFs
 VULNFIX uncovers real IP addresses behind WAFs like Cloudflare, Akamai, Incapsula, and Sucuri. Using Shodan, Censys, and Zoomeye, it scans for leaks via DNS, SNI, and passive subdomain discovery. Free, community-driven, and ethical—try 3 daily scans or unlimited with registration.

<img width="1470" alt="SCR-20250412-tieq" src="https://github.com/user-attachments/assets/15006659-3fdb-427f-b09e-35ca1f5a1bda" />


Modern websites often rely on Web Application Firewalls (WAFs) such as Cloudflare, Akamai, Incapsula, or Sucuri to hide their origin infrastructure and reduce the attack surface. However, due to DNS misconfigurations, legacy data leaks, or improperly secured services, the real IP address of a server may still be exposed—leaving organizations unknowingly vulnerable.

VULNFIX is a community-driven open-source security tool designed to identify origin IP addresses hidden behind WAFs using a combination of passive analysis, fingerprinting, and infrastructure enumeration.


Key Features

🔍 Real IP Detection
Detects origin IPs behind WAF-protected domains using advanced fingerprinting and validation techniques.

📡 SNI-Based Enumeration<br>
Leverages Server Name Indication (SNI) data over TLS connections to uncover indirect exposure paths.

🧩 DNS Leak Analysis<br>
Analyzes DNS records for misconfigurations and inherited data that may leak sensitive server information.

🎯 CDN/IP Fingerprinting<br>
Identifies inconsistencies and origin patterns by comparing CDN IP blocks with resolved records.

🔗 Subdomain Enumeration<br>
Collects and analyzes passive subdomains to track alternate access points to the same infrastructure.
📝 DNS Record Inspection<br>
Retrieves and inspects A, MX, TXT, and CNAME records to find exposures or legacy mappings.
💾 Data Export<br>
Export findings in JSON or CSV for external audit, integration, or long-term documentation.


Technical Stack
Backend: Built with Go for high concurrency and performance<br>
Frontend: Developed in Vue.js for an intuitive and fast user experience<br>
Database: Uses PostgreSQL for scalable and consistent data storage<br>
Deployment: Fully Docker-compatible for effortless local or cloud deployment<br>

Use Ethically<br>
VULNFIX is intended strictly for ethical security research, defensive analysis, and educational purposes. Please ensure all usage complies with applicable laws and permission-based scanning practices.


🌐 Access the Platform
<div style="text-align:center; font-size:22px; margin-top:10px;"> <strong>Try it now →</strong> <a href="https://vulnfix.com" target="_blank" style="color:#1E90FF; text-decoration:none;"><strong>VULNFIX.COM</strong></a> </div>
