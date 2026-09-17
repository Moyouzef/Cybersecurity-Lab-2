# Cybersecurity-Lab-2
WeeK 2 project
# Week 2 — Web Reconnaissance & Information Gathering

I have successfully completed my **Week 2 cybersecurity internship project**, where I focused on **web reconnaissance, information gathering, and identifying website security technologies**.

This week's practical session gave me a much better understanding of how penetration testers begin assessing a target before moving into more advanced testing. I learned that before attempting to identify vulnerabilities, it is important to first understand the target, collect publicly available information, identify technologies, and determine what security mechanisms may be protecting the website.

## What I Learned

During Week 2, I worked with three important reconnaissance tools:

* **WHOIS**
* **WhatWeb**
* **WAFW00F**

Each tool provided different information about a target and helped me understand how reconnaissance contributes to the penetration-testing process.

---

## 1. WHOIS — Domain Information Gathering

I started by learning how to use **WHOIS** to gather information about a domain.

WHOIS can provide information associated with a domain registration, depending on what information is publicly available. During the exercise, I learned how to investigate a domain and identify information such as:

* Domain registration information
* Registrar information
* Domain creation and expiration information
* Name servers
* Domain status
* Relevant registration details

This exercise helped me understand that a penetration tester should first build a picture of the target's external infrastructure before moving further.

I also learned that WHOIS information can sometimes be limited because of **privacy protection, redaction, or changes in registration policies**. Therefore, a tester should not assume that every domain will expose the same information.

### command


whois networkwalks.com


The output can then be reviewed and documented as part of the reconnaissance report.

---

## 2. WhatWeb — Identifying Website Technologies

The next tool I worked with was **WhatWeb**.

WhatWeb helped me understand how a website can be fingerprinted to identify technologies that may be running behind it.

During the practical exercise, I used WhatWeb to investigate information such as:

* Web server technologies
* Web frameworks
* Content management systems
* JavaScript libraries
* Web technologies
* HTTP-related information
* Other identifiable components

### command

whatweb networkwalks.com


This was particularly useful because I learned that understanding the technologies used by a website can help a penetration tester determine which areas may require further investigation.

For example, identifying a particular web server or framework does not automatically mean that it is vulnerable. Instead, it gives the tester useful information that can guide the next stages of authorized security testing.

---

## 3. WAFW00F — Identifying Web Application Firewalls

The third tool I learned was **WAFW00F**.

This was one of the most interesting parts of the session because I learned how to investigate whether a website may be protected by a **Web Application Firewall (WAF)**.

A WAF is a security mechanism designed to monitor and filter HTTP/HTTPS traffic to help protect web applications from malicious requests and common web attacks.

I used WAFW00F to investigate whether a target appeared to be behind a WAF.

### command


wafw00f networkwalks.com


The tool can provide an indication of whether a WAF is detected and, in some cases, identify the technology or provider.

This taught me an important lesson: **the visible website is not necessarily the complete picture of the infrastructure behind it**.

A website may have additional security layers such as:

* Web Application Firewalls
* Reverse proxies
* CDN services
* Traffic filtering
* Rate limiting
* Other security controls

Understanding these layers is important during the reconnaissance stage of a penetration test.

---

# My Practical Workflow

During this week's project, I followed a basic reconnaissance workflow.

### Step 1 — Identify the Domain

I started with the target domain and established the basic information needed for the assessment.

### Step 2 — Perform WHOIS Reconnaissance

I used WHOIS to gather publicly available domain and registration information.


whois networkwalks.com


I reviewed the results and recorded useful information for my report.

### Step 3 — Fingerprint the Website

Next, I used WhatWeb to identify technologies associated with the website.

whatweb Networkwalks.com


I examined the output and documented the technologies identified by the tool.

### Step 4 — Check for WAF Protection

I then used WAFW00F to investigate whether the website appeared to be protected by a Web Application Firewall.


wafw00f Networkwalks.com

I recorded the results and considered how the presence or absence of a WAF could affect the next stages of an authorized security assessment.

### Step 5 — Collect and Document Results

Finally, I organized the information collected from the different tools and prepared it for reporting.

This part of the exercise helped me understand that **information collection and documentation are important parts of penetration testing**, rather than simply running tools and looking at their output.

---

# What This Session Taught Me

One of the biggest lessons from Week 2 was that **reconnaissance is an important foundation of penetration testing**.

Before testing for vulnerabilities, a security professional needs to understand the target.

WHOIS helped me understand **domain-related information**.

WhatWeb helped me understand **the technologies used by a website**.

WAFW00F helped me investigate **whether security infrastructure such as a Web Application Firewall may be protecting the application**.

Together, these tools showed me how different pieces of information can be collected and combined to create a better understanding of a target.

I also learned that reconnaissance results should not automatically be treated as vulnerabilities. For example, identifying a particular technology does not mean that the technology is vulnerable. It simply provides information that can help guide further authorized testing.

---

# My Experience

This session gave me a great practical experience because I was not only learning commands but also beginning to understand the **thought process behind penetration testing**.

I learned that penetration testing is not simply about running tools. It involves:

**Reconnaissance → Information Gathering → Analysis → Documentation → Further Testing**

The more information a tester can responsibly and legally gather about an authorized target, the better they can understand the environment and plan the next stage of an assessment.

This Week 2 project also helped me become more comfortable working in my Kali Linux environment and interpreting command-line results.

---

# Key Takeaways

By completing Week 2, I gained practical experience in:

* Performing basic domain reconnaissance
* Using WHOIS for domain information gathering
* Using WhatWeb for web technology fingerprinting
* Using WAFW00F to investigate WAF protection
* Understanding the importance of reconnaissance
* Collecting and organizing technical information
* Documenting reconnaissance results
* Understanding how reconnaissance supports penetration testing
* Recognizing the importance of conducting security testing only against authorized targets

## Conclusion

Completing Week 2 has given me a stronger foundation in **web reconnaissance and information gathering**.

I now have a better understanding of how penetration testers begin an assessment by learning about the target before moving toward vulnerability identification and exploitation.

Each session is giving me more practical experience, and I am looking forward to continuing this journey, learning more advanced penetration-testing techniques, and developing my cybersecurity skills throughout the internship.

**Week 2 completed — more to learn, more to practice, and more experience to gain.**

**Appreciation**

I would like to express my sincere appreciation to NETWORKWALKS for providing me with this valuable practical learning opportunity and for giving me access to hands-on cybersecurity exercises.

I would also like to thank my tutor, Waqas Karim (CCIE), for his guidance, support, and practical explanations throughout the sessions. His guidance has helped me better understand the concepts and apply them in a practical environment.

I am grateful for the opportunity to learn, practice, and continuously improve my cybersecurity skills. I look forward to the upcoming sessions and gaining more hands-on experience throughout this internship.
