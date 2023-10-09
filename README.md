# Caesar-cipher-

Working of the Caesar Cipher in Python:

Key Selection: Choose a fixed number, known as the "shift" or "key," which determines how much each letter in the plaintext will be shifted. For example, if the key is 3, 'A' becomes 'D,' 'B' becomes 'E,' and so on.

Input: Take the plaintext message that you want to encrypt as input. Ensure that it contains only letters (ignoring spaces, numbers, and special characters).

Encryption:

For each letter in the plaintext, apply the shift based on the chosen key.
Wrap around the alphabet if needed, so that 'Z' shifted by 1 becomes 'A.'
Preserve the case of the letter (uppercase or lowercase).
Output: The result is the ciphertext, which is the encrypted form of the plaintext message.

Decryption:

To decrypt the ciphertext, apply the reverse shift (subtract the key) to each letter.
Similar to encryption, wrap around the alphabet if necessary.
The result is the original plaintext.
