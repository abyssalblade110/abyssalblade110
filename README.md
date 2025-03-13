# 🕹️ AbyssalBlade110 Interactive Challenge

**Welcome to the AbyssalBlade110 Interactive Challenge!**  
Unlock information about **my projects**, **skills**, and **achievements** by solving some programming and cybersecurity challenges.

---

### **Challenges:**

1. **Reverse Engineering**  
    Can you solve this?

    **Question:**  
    What will this code output?
    ```javascript
    function checkCode(secret) {
        const hash = [97, 119, 123, 120, 115];
        const chars = secret.split('');
        let result = 0;
        for (let i = 0; i < chars.length; i++) {
            result += chars[i].charCodeAt(0);
        }
        return result === hash.reduce((a, b) => a + b, 0) ? 'Correct!' : 'Wrong!';
    }
    ```
    **Answer:**  
    *Your answer will be shown below after your response.*
    
    *Answer Explanation: The secret is 'Abyssal'.*

---

2. **SQL Injection Challenge**  
    **Question:**  
    What's the typical payload used to exploit a simple SQL injection vulnerability in the code below?

    ```javascript
    const query = 'SELECT * FROM users WHERE username = ' + username + ' AND password = ' + password;
    ```

    **Answer:**  
    `' OR 1=1 --`

---

### 🎉 Congratulations on Completing the Challenge!

As you solve each challenge, more information about **my projects** and **skills** will be revealed here!

---

### **Projects:**

- **Vidxtract**: A free and ad-free video downloader.
- **Hotr**: A dating app with secure messaging.
- **Metamorphosis**: Pen testing tool with multiple exploits and vulnerabilities.

---

### **Skills:**

- JavaScript, Python, SQL, HTML, CSS
- Penetration Testing & Cybersecurity Tools
- Reverse Engineering, Cryptography, and more...
