# 🛡️ Workshop: Web Application Pen Testing (PortSwigger Labs)

**Date:** September 2025  
**Organizer:** Reversec (sponsored session)  
**Duration:** 10:00am – 2:30pm  
**Focus Area:** Web Application Penetration Testing  

---

## 📖 Overview
This workshop provided a hands-on introduction to **web application penetration testing** using PortSwigger’s Web Security Academy.  
We explored common vulnerabilities in web applications, focusing on **access control flaws, business logic vulnerabilities, and brute-force attacks**, all demonstrated using **Burp Suite**.  

---

## 🧩 Key Learnings
- **HTTP Basics**  
  - Difference between `GET` and `POST` requests.  
  - How cookies maintain sessions and authentication state.  

- **Access Control Flaws**  
  - Horizontal privilege escalation (accessing another user’s account).  
  - Vertical privilege escalation (gaining admin functionality).  
  - Insecure Direct Object References (IDOR).  

- **Brute Force Attacks**  
  - Automating login attempts with Burp Suite Intruder.  
  - Using wordlists to discover valid usernames and passwords.  

- **Business Logic Vulnerabilities**  
  - Exploiting shopping cart logic flaws (negative quantities).  
  - Manipulating price parameters to reduce product costs.  
  - Skipping validation steps by altering request sequences.  
  - Demonstrating how weak 2FA flows can be bypassed.  

---

## 🛠️ Hands-On Activities
We used **Burp Suite** to intercept and manipulate live web traffic in PortSwigger labs.  

Key activities included:  
- Intercepting and analyzing HTTP requests and responses.  
- Modifying request parameters to exploit **IDORs and privilege escalation flaws**.  
- Performing brute-force attacks on login forms.  
- Manipulating shopping cart values (negative quantities & price parameters).  
- Bypassing validation flows and weak 2FA sequences.  

---

## 📸 Hands-On Screenshots (to be added)
Screenshots from the live Burp Suite labs will be added here to document the exploitation process.  

---

## 🚀 Skills Gained
- Web traffic analysis with Burp Suite  
- Identifying and exploiting access control flaws  
- Detecting and abusing insecure business logic  
- Brute-force attack methodology  
- Understanding session handling with cookies  

---

## 📚 Resources
- [PortSwigger Web Security Academy](https://portswigger.net/web-security)  
- [Burp Suite Documentation](https://portswigger.net/burp/documentation)  

---

## 💡 Personal Reflection
This workshop gave me practical, step-by-step exposure to **realistic web application attacks**.  
I now have a clearer understanding of how simple oversights—like unvalidated input or misplaced trust in client-side parameters—can lead to serious security risks.  

Moving forward, I plan to:  
- Practice more labs on **PortSwigger Academy**.  
- Apply these techniques in **CTFs and personal projects**.  
- Deepen my knowledge of web security testing beyond introductory exploitation.  
