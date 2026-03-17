# Caesar-Cipher
The Caesar cipher is a simple encryption technique that was used by Julius Caesar to send secret messages to his allies. It works by shifting the letters in the plaintext message by a certain number of positions, known as the "shift" or "key".

# Caesar Cipher — Cyber Security Lab
A simple browser-based Caesar Cipher tool built for my Cyber Security lab at IEM Kolkata.
No frameworks, no backend — just HTML, CSS and vanilla JavaScript.

# What it does
- Encrypt any text using a shift key (1–25)
- Decrypt ciphertext back to plaintext
- Brute force attack — shows all 25 possible decryptions
- Live substitution map updates as you change the shift key

# How to run
Just open `index.html` in any browser. That's it.
No installation, no server, no dependencies.

# How to use
1. Type your message in the left box
2. Set the shift key using the slider (default is 3 — Caesar's original key)
3. Hit **Encrypt** or **Decrypt**
4. To test brute force, paste any ciphertext and click **Brute Force Attack**

# Algorithm
Encrypt:  C = (P + K) mod 26
Decrypt:  P = (C - K + 26) mod 26
P = plaintext letter index (A=0, B=1 ... Z=25)  
K = shift key  
C = ciphertext letter index

# Why Caesar Cipher is weak
The key space is only 25 values.
An attacker can try all of them in seconds — no computing power needed.
This is why modern encryption (AES, RSA) uses keys with billions of possible values.

# Tech used
- HTML5
- CSS3
- Vanilla JavaScript (no libraries)
