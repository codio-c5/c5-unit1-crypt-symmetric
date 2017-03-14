**Task**: Think about what it takes to decrypt a ciphertext that is obtained using the substitution cipher under these scenarios:

- **Ciphertext only attacks** – How can you proceed to break the cipher if all you have is the ciphertext ?
- **Known plaintext attacks** – You know that HELLO encrypts to MYZZK. Can you find the key? How can you proceed to find the key?
- **Chosen plaintext attacks** – You have the opportunity to choose a plaintext and get its ciphertext (without knowing the key). What would you choose for the plaintext?
- **Chosen ciphertext attacks** – You have the same ability as with chosen plaintext attacks, plus you have the opportunity to choose a ciphertext and get the plaintext for it (without knowing the key). What would you choose for the ciphertext?


||| guidance
- **Ciphertext only attacks** – Brute forcing is not feasible, as shown in the previous slide. A different, more analytical approach is using frequency analysis which is described in upcoming slides. Students will also have an assignment on it.
- **Known plaintext attacks** – You know that HELLO encrypts to MYZZK. Can you find the key? Answer: This reveals that M should be replaced by H, Y by E, L by Z, and K by O. Substitute these and see if it helps to figure out the others. Do frequency analysis if necessary.
- **Chosen plaintext attacks** – You have the opportunity to choose a plaintext and get its ciphertext (without knowing the key). What would you choose for the plaintext? Answer: Choose the whole alphabet for the plaintext.
- **Chosen ciphertext attacks** – You have the same ability as with chosen plaintext attacks, plus you have the opportunity to choose a ciphertext and get the plaintext for it (without knowing the key). What would you choose for the ciphertext? Answer: Choose the whole alphabet for the ciphertext.


