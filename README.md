The AbyssalBlade110 Interactive Challenge 🚀

# 🎮 Welcome to the AbyssalBlade110 Interactive Challenge!

Welcome, **brave adventurer**. You've entered the **AbyssalBlade110 realm**, where you'll have to **solve advanced programming and cybersecurity challenges** to **unlock information** about me and the technologies I work with.

Prepare yourself. This is no ordinary game. You'll need to leverage your **coding skills**, your **hacking knowledge**, and **problem-solving abilities** to win.

**Can you handle it? Let’s begin!**

---

## 🔐 Level 1: Reverse Engineering (Coding Challenge)

### 🧩 Task 1: Break the Code

You’ve encountered an encrypted message. Can you **decrypt it** using Python? Here’s the code:


def decrypt_message(encrypted):
    key = 5
    decrypted = ''.join([chr(ord(c) - key) for c in encrypted])
    return decrypted

encrypted_message = "Jvsqj1m1"
print(decrypt_message(encrypted_message))
What will be the output when you decrypt the message?

Hint: You’ll need to think about shift ciphers (Caesar cipher) here. Solve it, and you’ll unlock basic programming skills!

⚙️ Level 2: SQL Injection (Cybersecurity Challenge)
🔍 Task 2: Exploit the Vulnerability
You're now facing a web application with a SQL injection vulnerability. The website accepts user input to log in, but there's a potential for exploitation.

Here’s the login code in PHP:


<?php
$username = $_POST['username'];
$password = $_POST['password'];
$query = "SELECT * FROM users WHERE username = '$username' AND password = '$password'";
$result = mysqli_query($conn, $query);
?>
Task:
What would be the malicious payload you could use in the username field to bypass authentication?

Hint: Think about SQL injection and single quotes. Solve it to unlock your cybersecurity expertise.

🔐 Level 3: Cryptography (Advanced Challenge)
🧠 Task 3: Encrypt and Decrypt
You’ve come across a ciphered text. Can you use your Python skills to both encrypt and decrypt the message using the Vigenère cipher? Here's the encrypted message:


Encrypted: Uv lqxx j ybt! Bz ql y jypnqc hyy.
Task:
Write a Python script to encrypt and decrypt the text using the Vigenère cipher. Use the keyword Abyssal and unlock cryptography skills.

⚙️ Level 4: Reverse Engineering (Advanced Coding)
💥 Task 4: Reversed Logic
Can you reverse-engineer this code and identify what it actually does? Here’s the challenge:


function checkCode(secret) {
  const hash = [97, 119, 123, 120, 115];
  const chars = secret.split('');
  let result = 0;
  
  for (let i = 0; i < chars.length; i++) {
    result += chars[i].charCodeAt(0);
  }

  if (result === hash.reduce((a, b) => a + b, 0)) {
    return "Correct!";
  }
  return "Wrong!";
}

console.log(checkCode("Abyssal"));
Task:
What will the function output when you run it?

Hint: You'll need to think about character encoding and string comparison.

🔥 Level 5: OSINT (Open-Source Intelligence)
🔍 Task 5: Investigate a Target
Can you perform OSINT to gather publicly available information about a target? Here’s the challenge:

Using Shodan, search for devices that expose the following vulnerabilities:

CVE-2019-0708 (BlueKeep RDP vulnerability)
CVE-2020-0601 (Windows CryptoAPI vulnerability)
Task:
List two real IPs that are vulnerable and explain how this vulnerability could be exploited. This will unlock your OSINT and ethical hacking skills.

🏆 Level 6: Capture the Flag (CTF Challenge)
🧩 Task 6: Find the Flag
Your task is to retrieve a hidden flag. Here's a base64 encoded string:


U29ycnksIGV4Y2VsbGVudCBmb3IgdGhlIGNvbW1lbnQsIGJ1dCBkaWQgdmlhIGJlIFRldGFyLCB3aG8gaXMgYnkgaW1wYXRpb24uIFNvcnJ5IQ==
Task:
What is the hidden message after decoding it? It’s related to your flag in a Capture The Flag (CTF) competition. Can you find the correct string and unlock your advanced skills?

🏁 Congratulations! You've Unlocked It All! 🎉
Congratulations, adventurer! You've successfully unlocked all levels, and now you can access all the cool info about AbyssalBlade110. You’re now ready to explore my projects, skills, and achievements:

My Projects:
Vidxtract - Free, ad-free video downloader.
Hotr - Modern dating app.
Metamorphosis - Pen testing tool for exploits like SQL injection, XSS, etc.
Skills & Tech Stack:
Languages: JavaScript, Python, TypeScript, Node.js, PHP
Tools: Burp Suite, Kali Linux, Metasploit, Nmap, Wireshark, Git, Docker
Frameworks: React.js, Node.js, Express.js, Laravel, TailwindCSS
🎮 Bonus Round! Want to Play Again?
I update the challenges regularly. Refresh the page and try to beat your previous score. The more you know, the better you’ll play.

Good luck, and may the code be with you! ⚡


---

### **What makes this badass and professional:**
1. **Cybersecurity and Programming Challenges**: The game uses real coding problems and cybersecurity scenarios. It's a practical test of skills!
2. **Deeper Knowledge**: To unlock information, users need to solve complex coding and hacking challenges (SQL Injection, Reverse Engineering, CTF, Cryptography, etc.).
3. **Advanced Interaction**: Rather than just answering basic questions, users need to **think critically** and use technical knowledge to reveal your info.

This approach ensures that the **game** isn't just fun and interactive, but it also reflects your **advanced skills** in a **badass** way. Let me know if you want to adjust any specific level or task!






