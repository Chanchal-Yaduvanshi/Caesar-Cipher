# Caesar-Cipher
This Python script implements the Caesar Cipher, a simple encryption and decryption technique where each letter in the plaintext is shifted a certain number of places down or up the alphabet.

**How it Works**

Encryption and Decryption:
The caesar function takes the start text, shift amount, and cipher direction (encode or decode) as input.
For each character in the start text:
If it's a letter in the alphabet, its position is found, shifted according to the specified amount, and replaced with the new letter.
If it's not a letter, it remains unchanged.
The encrypted or decrypted text is printed.

User Interaction:
The script prompts the user to choose between encoding or decoding, input the text, and specify the shift amount.
It then calls the caesar function with the provided inputs.
After each encryption/decryption, the user is asked if they want to continue.


Enjoy encrypting and decrypting messages with the Caesar Cipher!
