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
  </head>
  <body>
    <h1>Welcome to the AbyssalBlade110 Interactive Game</h1>
    <button onclick="startChallenge()">Start Challenge</button>

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
        if (answer.toLowerCase() === "correct!") {
          alert("You solved it! Unlocking your projects and skills...");
          showProjectsAndSkills();
        } else {
          alert("Wrong answer! Try again.");
        }
      }

      // SQL Injection Challenge
      function sqlInjection() {
        const answer = prompt(
          "You need to exploit a SQL injection vulnerability. What would be your payload?\n\nCode: 'SELECT * FROM users WHERE username = '$username' AND password = '$password';'"
        );
        if (answer.toLowerCase() === "' OR '1'='1' --") {
          alert("You exploited it successfully! Unlocking your projects and skills...");
          showProjectsAndSkills();
        } else {
          alert("Wrong payload! Try again.");
        }
      }

      // Cryptography Challenge
      function cryptography() {
        const answer = prompt(
          "Decrypt the base64 string: 'U29ycnksIGV4Y2VsbGVudCBmb3IgdGhlIGNvbW1lbnQsIGJ1dCBkaWQgdmlhIGJlIFRldGFyLCB3aG8gaXMgYnkgaW1wYXRpb24uIFNvcnJ5IQ=='"
        );
        if (answer.toLowerCase() === "sorry, excellent for the comment, but did i miss something") {
          alert("Great job! Unlocking your projects and skills...");
          showProjectsAndSkills();
        } else {
          alert("Incorrect answer! Try again.");
        }
      }

      // CTF Challenge
      function ctfChallenge() {
        const answer = prompt(
          "You’ve found a hidden flag in base64: 'U29ycnksIGV4Y2VsbGVudCBmb3IgdGhlIGNvbW1lbnQsIGJ1dCBkaWQgdmlhIGJlIFRldGFyLCB3aG8gaXMgYnkgaW1wYXRpb24uIFNvcnJ5IQ=='\nWhat is the flag?"
        );
        if (answer.toLowerCase() === "sorry, excellent for the comment, but did i miss something") {
          alert("CTF Solved! Unlocking your projects and skills...");
          showProjectsAndSkills();
        } else {
          alert("Incorrect flag! Try again.");
        }
      }

      // Unlock Projects and Skills
      function showProjectsAndSkills() {
        alert("Here are your unlocked details:\n\n1. **Projects**:\n- Vidxtract (Video Downloader)\n- Hotr (Dating App)\n- Metamorphosis (Pen testing tool)\n\n2. **Skills**:\n- JavaScript, Python, SQL\n- Penetration Testing\n- Reverse Engineering\n- Cryptography\n\nGreat work!");
      }
    </script>
  </body>
</html>
