# 🕵️‍♂️ Network Forensics Challenge — Quantum Heist

## 📄 Overview
A hacker team named **Crimson Sparrow** was detected performing suspicious activity on a private online game. The developers recorded network activity showing logins, small downloads, and a short encoded chat message. Your task is to analyze the provided capture and find the answers.

**🗂 Provided File:** `Network_Challenge.pcapng`

## 🎯 Your Mission
Open the PCAP in **Wireshark** and answer the following five questions.

## ❓ Challenge Questions
1. What is the Fully Qualified Domain Name (FQDN) of the game server?  
2. How many unique players were connected to the server?  
3. What port number was the server using to host the match?  
4. What is the filename of the game asset that the client tried to download immediately after the login attempt?  
5. What is the decoded message (the flag) from the Base64 string found in the chat traffic? **Submit your answer starting with `flag{`**  



## 🔐 Final combined flag format (READ THIS CAREFULLY)
You must submit **one combined flag** in this exact format:

`flag{<FQDN>|<num_players>|<port>|<filename>|<chat-flag-body>}`


- `<chat-flag-body>` = **only** the inner contents of the chat flag you decode from the Question 5.  
  Example: if the chat decodes to `flag{ABC123}`, then `<chat-flag-body>` = `ABC123` (do **not** include `flag{}` again).  
- Use the pipe `|` character (no spaces) between fields.  
- Wrap the entire result with `flag{` at the start and `}` at the end.


## ✅ Example (DOES NOT CONTAIN REAL ANSWERS — format only)
Do **not** use these values to answer the challenge; this is only an example of the submission format.

