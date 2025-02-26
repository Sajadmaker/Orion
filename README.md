<h1 align="center">
  <a href="">
    Orion
  </a>
  <br>
</h1>
<p align="center">
   A Python-based toolkit for Information Gathering and <br>Reconnaissance
</p>

---

## About The Project

Orion is your all-in-one, Python-powered toolkit designed to simplify and enhance the process of information gathering and reconnaissance. With its intuitive interface and a robust suite of modules, Orion equips you with the tools to explore networks, web applications, and security configurations with ease and precision.

Whether you're conducting research, performing authorized security assessments, or simply curious about network infrastructures, Orion delivers a wealth of information—all in one place.

---

## ⚠️ WARNING: LEGAL DISCLAIMER

This tool is intended **strictly for educational and ethical purposes**. The author bears no responsibility for any illegal or unauthorized use of this tool. Users must ensure they have explicit permission to scan or assess any target systems.

---

## ⚙️ Installation

Getting started with Orion is quick and straightforward. Follow these steps to set it up:

```bash
git clone https://github.com/sajadmaker/orion.git
cd orion
pip install -r requirements.txt
```

Once installed, launch Orion using:

```bash
python orion.py
```

---

## 📖 Usage

Orion is packed with a comprehensive set of tools, organized into three main categories:

### Network & Infrastructure Tools

These tools are designed to help you uncover critical details about networks, servers, IP addresses, DNS records, and more:

1. **Associated Hosts**: Identify domains linked to the target.
2. **DNS Over HTTPS**: Securely resolve DNS queries using encrypted channels.
3. **DNS Records**: Retrieve DNS records, including A, AAAA, MX, and more.
4. **DNSSEC Check**: Verify the proper configuration of DNSSEC.
5. **Domain Info**: Gather domain details such as registrar information and expiration dates.
6. **Domain Reputation Check**: Assess the trustworthiness of a domain using multiple reputation sources.
7. **IP Info**: Obtain geographic and ownership details for a given IP address.
8. **Open Ports Scan**: Scan the target for open ports and running services.
9. **Server Info**: Extract key server details using advanced techniques.
10. **Server Location**: Determine the physical location of the server.
11. **SSL Chain Analysis**: Analyze the SSL certificate chain for trust and validity.
12. **SSL Expiry Alert**: Monitor SSL certificates for upcoming expirations.
13. **TLS Cipher Suites**: List the TLS cipher suites supported by the server.
14. **TLS Handshake Simulation**: Simulate a TLS handshake to identify potential security issues.
15. **Traceroute**: Trace the network path to the target.
16. **TXT Records**: Fetch TXT records, often used for verification and configuration.
17. **WHOIS Lookup**: Perform WHOIS queries to retrieve domain ownership details.
18. **Zone Transfer**: Attempt DNS zone transfers to gather additional information.
19. **HTTP/2 and HTTP/3 Support Checker**: Verify if the server supports HTTP/2 and HTTP/3 protocols.

### Web Application Analysis Tools

These modules focus on understanding the structure, performance, and security of web applications:

20. **Archive History**: Explore the target's historical data using internet archives.
21. **Broken Links Detection**: Identify broken links that may impact user experience or security.
22. **Carbon Footprint**: Evaluate the environmental impact of a website.
23. **CMS Detection**: Detect the content management system (CMS) in use, such as WordPress or Joomla.
24. **Cookies Analyzer**: Analyze cookies for secure attributes and potential privacy concerns.
25. **Content Discovery**: Uncover hidden directories, files, and endpoints.
26. **Crawler**: Crawl the site to map its structure and gather data.
27. **Robots.txt Analyzer**: Analyze the `robots.txt` file for hidden or restricted resources.
28. **Directory Finder**: Search for directories that may not be publicly indexed.
29. **Email Harvesting**: Extract email addresses associated with the target domain.
30. **Performance Monitoring**: Monitor the website's response time and load performance.
31. **Quality Metrics**: Assess the quality of the site's content and user experience.
32. **Redirect Chain**: Analyze redirect chains for potential security risks.
33. **Sitemap Parsing**: Extract URLs from the site's sitemap.
34. **Social Media Presence Scan**: Identify and analyze social media profiles linked to the target.
35. **Technology Stack Detection**: Detect the technologies and frameworks powering the site.
36. **Third-Party Integrations**: Identify third-party services integrated into the site.

### Security & Threat Intelligence Tools

These modules are designed to assess the target's security posture and gather threat intelligence:

37. **Censys Reconnaissance**: Leverage Censys for detailed insights into the target's assets.
38. **Certificate Authority Recon**: Examine the certificate authority details.
39. **Data Leak Detection**: Check for potential data leaks and sensitive information exposure.
40. **Exposed Environment Files Checker**: Identify publicly accessible `.env` files.
41. **Firewall Detection**: Detect the presence of firewalls or web application firewalls (WAFs).
42. **Global Ranking**: Check the site's global ranking to gauge its popularity.
43. **HTTP Headers**: Analyze HTTP response headers for security configurations.
44. **HTTP Security Features**: Verify the presence of secure HTTP headers like HSTS and CSP.
45. **Malware & Phishing Check**: Scan the site for signs of malware or phishing activity.
46. **Pastebin Monitoring**: Search paste sites for leaks related to the target.
47. **Privacy & GDPR Compliance**: Assess the site's compliance with GDPR and other privacy regulations.
48. **Security.txt Check**: Locate and analyze the `security.txt` file for vulnerability disclosure policies.
49. **Shodan Reconnaissance**: Use Shodan to discover open ports, services, and vulnerabilities.
50. **SSL Labs Report**: Generate a detailed SSL/TLS assessment via SSL Labs.
51. **SSL Pinning Check**: Verify if SSL pinning is implemented on the site.
52. **Subdomain Enumeration**: Discover subdomains associated with the target domain.
53. **Subdomain Takeover**: Test for subdomain takeover vulnerabilities.
54. **VirusTotal Scan**: Check the target's reputation using VirusTotal.

---

## 🛠 Configuration

Some modules require API keys to function. Ensure you add the necessary API keys to the `config/settings.py` file before running Orion to unlock its full potential.

---

## 🔄 Changelog

### 1.1 Release Notes
- Added **Emails Harvesting** module.
- Added **HTTP/2 and HTTP/3 Support Checker** module.
- Added **Check for Publicly Exposed Environment Files** module.
- Fixed **Txt Files Export** functionality.
- Updated **Traceroute** module.
- Improved **Report Generation** module.
- Added `.gitignore` file for better project management.

---

## ⭐️ Show Your Support

If you find Orion useful, please consider giving it a star on GitHub! Your support helps us improve and grow the project.

---

**Coded by:** [sajadmaker](https://github.com/sajadmaker)
```
