# 🚀 RudraX Web Code Studio™ — Official Architecture & Documentation Guide

> **Enterprise Entity:** RudraX Technologies Studio™  
> **Product Prefix Standard:** RudraX [Web Code Studio]  
> **Official Executive Authority:** Rudra Parmar  
> **Foundation & Origin Record:** 07 March 2026 (Firebase Core Epoch Verification)  
> **Licensing Standard:** Strict Proprietary Ecosystem License  

---

## 📌 1. About the Application & Parent Brand

**RudraX Web Code Studio™** ek lightweight, browser-based native IDE (Integrated Development Environment) aur multi-file real-time rendering engine hai. Is application ko **RudraX Technologies Studio™** ke dwara design, develop aur deploy kiya gaya hai.

Yeh web studio developers aur creators ko browser ke andar hi multi-file web components (HTML, CSS, JS) create, structure, live preview aur secure cloud storage par manage karne ki seamless suvidha deta hai.

* **Genesis & Historical Record:** Is project ki official architecture foundation **07 March 2026** ko launch ki gayi thi. Founder ke verified credentials aur Firebase persistent state ke aadhar par is engine ki original identity time-stamped hai.

---

## 🔐 2. Authentication & Secure Recovery Flow

Application me traditional, vulnerable passwords ka use nahi hota. System direct OAuth aur unique recovery token methodology par kaam karta hai:

### Step 1: Zero-Password Sign-In
* User ko dashboard access karne ke liye **Google SSO** ya **GitHub SSO** me se kisi ek ka chunav karna hota hai.
* Kisi email confirmation link ya password memorize karne ki zaroorat nahi hoti.

### Step 2: Generation of 9-Digit Unique Code
* Jab koi naya user sign-up karta hai, engine unke profile ke liye ek unique 9-digit security code generate karta hai:
  * Google users ke liye prefix standard: `G********`
  * GitHub users ke liye prefix standard: `GH*******`
* Yeh code user ke Firebase profile me cryptographically bind ho jata hai.

### Step 3: Account Restoration Protocol
* **Permanent Identity Asset:** Yeh 9-digit security code ek offline backup key ke roop me kaam karta hai.
* Agar user apna session kho deta hai ya direct device restore chahta hai, toh login page par jakar **"Restore Account with Code"** option ka use karke apna User Identity/Email aur yeh 9-digit code enter karke session instantly retrieve kar sakta hai.
* **Instruction for Users:** Is 9-digit code ko kisi safe jagah save karein; bina authorized identity aur is code ke session recover nahi kiya ja sakega.

---

## 🛠️ 3. Actual Engine Working & How-To-Use Guide

Application ka working core client-side sandboxed iframe aur Firebase Realtime Database par directly depend karta hai:

### Step-by-Step Operational Workflow:

1. **Workspace / Project Creation:**
   * Dashboard par jaakar **"+ Create Project"** par click karein.
   * Project ka naam assign karein (Database structure me by default ek root `index.html` file inject ho jati hai).
   * Free limits ke mutabik max 10 active projects workspace me banaye ja sakte hain.

2. **File Hierarchy & Multi-File Linking:**
   * Apne project par click karein to open file workspace.
   * **"+ CREATE NEW FILE"** button ka use karke extensions select karein (`.html`, `.css`, `.js`).
   * Engine files ko uniquely key format (e.g., `style_css`, `main_js`) me parse karta hai.

3. **Multi-File Linked Engine (Real-Time Preview):**
   * Code Editor me code likhne ke baad **"▶ RUN & SAVE CODE"** button dabayein.
   * **Internal Build Process:** Engine runtime par project ki sari linked `.css` files ko automatically `<style>` tag me convert karke `index.html` ke `<head>` me inject karta hai, aur sari `.js` files ko `<script>` blocks me convert karke `</body>` ke pehle inject karta hai.
   * Is dynamic concatenation ke baad real-time output secure Sandboxed iframe me render hota hai.

---

## ⚠️️ 4. Workspace Inactivity & Storage Rules

Data efficiency aur database integrity banaye rakhne ke liye engine me automated cleanup rules implement kiye gaye hain:

* **30-Day Inactivity Rule:** Agar kisi standard workspace me 30 din tak koi edit ya open session activity detect nahi hoti, toh vah project database se automatically prune (delete) kar diya jata hai.
* **24-Hour Expiry Warning Tag:** Jab koi project 29 din inactive ho jata hai, engine dashboard card par red warning tag display karta hai: `⚠️ Inactive: Delete in 24h`. Project ko delete hone se bachane ke liye use bas ek baar open karke save karna hota hai.
* **Safe Permanent Delete Modal:** Agar user manually kisi project ko delete karta hai, toh mandatory checkbox confirmation ke bina deletion process trigger nahi hota. Ek baar delete hone ke baad data unrecoverable hota hai.

---

## 🛡️ 5. Administrative Rights & Security Governance

Platform ka central control **RudraX IP-Guard Architecture** aur Admin Dashboard ke dwara govern hota hai. Studio Administration ke paas platform stability ke liye nimnlikhit absolute rights hain:

* **Direct Security Blacklisting & Lockout:** Kisi bhi account, email, ya identity ko temporary ya permanent blacklist me add karne ka exclusive right admin ke paas hai. Blacklisted identity browser par instant permanent terminal screen trigger karti hai (jahan logout ya bypass options completely disable ho jate hain).
* **System-Wide Announcements & Notices:** Dynamic admin notices aur update links globally manage kiye jate hain.
* **Priority Routing Support:** Studio administrators platform integrity aur user workspace issues ko direct operational channels ke madhyam se review aur regulate karte hain.

---

## ⚖️ 6. Proprietary License, Restrictions & DMCA Enforcement

**Important Legal & Usage Boundaries:**

1. **Service Usage Only (End-User Access):**
   * Yeh application users ko web development, live testing aur multi-file project workspace run karne ke liye ek SaaS service ke taur par provide ki gayi hai.
   * User ko service ka access use karne ki permission hai, lekin iske underlying source code, UI/UX architecture, proprietary logic, ya core scripts par user ka koi intellectual ya proprietary right nahi hai.

2. **Zero Modification & Reverse Engineering:**
   * Studio ke authorized written consent ke bina code ko alter, reverse engineer, decompile, mirror ya clone karna strictly prohibited hai.
   * Koi bhi third-party entity ya user is codebase ko apne banner ya brand name ke under re-publish ya claim nahi kar sakta.

3. **Strict DMCA Take-Down Policy:**
   * **RudraX Technologies Studio™** ke assets, software binaries, layout design ya logic ka koi bhi unauthorized reproduction ya copy detect hone par immediate legally-binding **DMCA Takedown Notice** aur appropriate intellectual property legal action initiate kiya jayega.

* **Direct Security, Integrity & License Verification Vault:**  
  [Official RudraX Security & License Hub](https://github.com/RudraX-Technologies-Studio/SECURE-RUDRAX-TECHNOLOGIES-STUDIO)

---
*© RudraX Technologies Studio™. Directed and Founded by Rudra Parmar. All Rights Reserved.*
