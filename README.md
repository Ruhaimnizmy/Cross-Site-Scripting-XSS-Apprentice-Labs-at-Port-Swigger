# Cross-Site Scripting (XSS) Attacks - Practical Report

This repository contains a practical report on **Cross-Site Scripting (XSS)** attacks, completed as part of the *Web Security (IE2062)* module at SLIIT. The report demonstrates different XSS attack techniques and exploitation methods on vulnerable websites.

## 📌 Topics Covered
- **Introduction to XSS:**
  - Understanding XSS attacks and how they work.
  - Injecting malicious JavaScript into trusted websites.
  
- **Types of XSS Attacks:**
  - **Stored XSS:** Persistent attacks where scripts are stored on the server.
  - **Reflected XSS:** Non-persistent attacks where scripts are reflected via web requests.
  - **DOM-Based XSS:** Client-side attacks manipulating the DOM.

- **Practical Labs:**
  - Reflected XSS into HTML context.
  - Stored XSS into HTML context.
  - DOM-Based XSS using `document.write()` and `innerHTML`.
  - DOM-Based XSS with jQuery functions.
  - Reflected XSS breaking out of JavaScript strings.

- **Exploitation Techniques:**
  - Using `<script>` tags and event handlers like `onload`, `onerror`, `onclick`.
  - Breaking out of attributes and injecting JavaScript payloads.
  - Using Burp Suite for intercepting and modifying requests.

- **Preventive Measures:**
  - Proper sanitization and filtering of user inputs.
  - Implementing Content Security Policies (CSP).
  - Avoiding the use of `innerHTML` and `document.write()` for rendering user inputs.

## 📖 Usage
Clone the repository and refer to the labs section for step-by-step instructions on performing various XSS attacks.  

## 📌 Author
**Mohammed Ruhaim** - IT23256446 - SLIIT

