# 🎮 **AbyssalBlade110 Interactive Challenge** 🎮

**Welcome to the AbyssalBlade110 Interactive Challenge!**  
Unlock information about **my projects**, **skills**, and **achievements** by solving some programming and cybersecurity challenges. 

The challenges are interactive and will test your **coding**, **hacking**, and **problem-solving** skills.

#### Instructions:
1. Select the challenge below.
2. Solve it and get the corresponding **hint** or **answer**.
3. As you unlock the answers, the information about me will also be revealed!

## 💻 Select a Challenge:

1. **Reverse Engineering Challenge** (Coding)
2. **SQL Injection Challenge** (Cybersecurity)
3. **Cryptography Challenge** (Coding)
4. **CTF Challenge** (Cybersecurity)

---

#### 🕹️ Click Below to Start Your Adventure!

```html
<!-- Interactive challenge code -->
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>AbyssalBlade110 Challenge</title>
    <style>
      body {
        font-family: Arial, sans-serif;
        padding: 20px;
      }
      .challenge-container {
        margin-bottom: 20px;
      }
      .result {
        margin-top: 10px;
        color: green;
        font-weight: bold;
      }
      .incorrect {
        margin-top: 10px;
        color: red;
        font-weight: bold;
      }
    </style>
  </head>
  <body>
    <h1>Welcome to the AbyssalBlade110 Interactive Game</h1>
    <div class="challenge-container">
      <button onclick="startChallenge()">Start Challenge</button>
      <div id="result"></div>
    </div>

    <script>
      // Function to start the challenge
      function startChallenge() {
        const challenge = prompt(
          "Welcome to AbyssalBlade110! Choose a challenge: \n1. Reverse Engineering\n2. SQL Injection\n3. Cryptography\n4. CTF"
        );

        switch (challenge) {
          case "1":
            reverseEngineering();
            break;
          case "2":
            sqlInjection();
            break;
          case "3":
            cryptography();
            break;
          case "4":
            ctfChallenge();
            break;
          default:
            alert("Invalid choice! Please select a valid challenge.");
        }
      }

      // Reverse Engineering Challenge
      function reverseEngineering() {
        const answer = prompt(
          "Reverse the following code. What will be the output?\n\nfunction checkCode(secret) { const hash = [97, 119, 123, 120, 115]; const chars = secret.split(''); let result = 0; for (let i = 0; i < chars.length; i++) { result += chars[i].charCodeAt(0); } if (result === hash.reduce((a, b) => a + b, 0)) { return 'Correct!'; } return 'Wrong!'; }\n\nSecret: 'Abyssal'"
        );
        const resultDiv = document.getElementById('result');
        if (answer.toLowerCase() === "correct!") {
          resultDiv.innerHTML = "🎉 You solved it! Unlocking your projects and skills...";
          showProjectsAndSkills();
        } else {
          resultDiv.innerHTML = "<span class='incorrect'>❌ Incorrect answer! Try again.</span>";
        }
      }

      // SQL Injection Challenge
      function sqlInjection() {
        const answer = prompt(
          "You need to exploit a SQL injection vulnerability. What would be your payload?\n\nCode: 'SELECT * FROM users WHERE username = '$username' AND password = '$password';'"
        );
        const resultDiv = document.getElementById('result');
        if (answer.toLowerCase() === "' or '1'='1' --") {
          resultDiv.innerHTML = "🎉 You exploited it successfully! Unlocking your projects and skills...";
          showProjectsAndSkills();
        } else {
          resultDiv.innerHTML = "<span class='incorrect'>❌ Incorrect payload! Try again.</span>";
        }
      }

      // Cryptography Challenge
      function cryptography() {
        const answer = prompt(
          "Decrypt the base64 string: 'U29ycnksIGV4Y2VsbGVudCBmb3IgdGhlIGNvbW1lbnQsIGJ1dCBkaWQgdmlhIGJlIFRldGFyLCB3aG8gaXMgYnkgaW1wYXRpb24uIFNvcnJ5IQ=='"
        );
        const resultDiv = document.getElementById('result');
        if (answer.toLowerCase() === "sorry, excellent for the comment, but did i miss something") {
          resultDiv.innerHTML = "🎉 Decryption successful! Unlocking your projects and skills...";
          showProjectsAndSkills();
        } else {
          resultDiv.innerHTML = "<span class='incorrect'>❌ Incorrect answer! Try again.</span>";
        }
      }

      // CTF Challenge
      function ctfChallenge() {
        const answer = prompt(
          "You’ve found a hidden flag in base64: 'U29ycnksIGV4Y2VsbGVudCBmb3IgdGhlIGNvbW1lbnQsIGJ1dCBkaWQgdmlhIGJlIFRldGFyLCB3aG8gaXMgYnkgaW1wYXRpb24uIFNvcnJ5IQ=='\nWhat is the flag?"
        );
        const resultDiv = document.getElementById('result');
        if (answer.toLowerCase() === "sorry, excellent for the comment, but did i miss something") {
          resultDiv.innerHTML = "🎉 CTF Solved! Unlocking your projects and skills...";
          showProjectsAndSkills();
        } else {
          resultDiv.innerHTML = "<span class='incorrect'>❌ Incorrect flag! Try again.</span>";
        }
      }

      // Unlock Projects and Skills
      function showProjectsAndSkills() {
        const resultDiv = document.getElementById('result');
        resultDiv.innerHTML += `
          <div class='result'>
            🎉 Congratulations! Here are your unlocked details:
            <ul>
              <li><strong>Projects:</strong>
                <ul>
                  <li>Vidxtract (Video Downloader)</li>
                  <li>Hotr (Dating App)</li>
                  <li>Metamorphosis (Pen testing tool)</li>
                </ul>
              </li>
              <li><strong>Skills:</strong>
                <ul>
                  <li>JavaScript, Python, SQL</li>
                  <li>Penetration Testing</li>
                  <li>Reverse Engineering</li>
                  <li>Cryptography</li>
                </ul>
              </li>
            </ul>
          </div>
        `;
      }
    </script>
  </body>
</html>
