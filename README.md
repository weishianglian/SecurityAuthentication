# Security and Authentication
## Question 1
**Explain what is an active security attack and a passive security attack. Give an example of an active and a passive attack.**  

A passive attack is eavesdropping. They do not midify the data stream. They are difficult to detect, the best protection is prevention.  
An active attack, modifies the content of the message. They are less difficult to detect than passive attacks. An example is data content modfication.  

---

**Explain when an encryption algorithm is computational safe.**  

An encryption algorithm is computational safe if:  
* cost of breaking the cipher is much greater than value of the encrypted information  
* time to break the cipher is much longer than the useful lifetime of the encrypted information  

---

**When using encryption a mode of operation is using an Electronic Code Book. Explain this mode of operation. Explain if it is secure or not. Give an alternative mode od operation and explain when would you use this alternative mode of operation.**  

Is when a block cioher is used to encrypt blocks od data one at the time without relating to the overall content of the message. The codebook is the collection of all the unique plaintext, ciphertext blocks. Identical plaintext blocks result in identical ciphertext blocks. If the ciphertext is highly structed a cryptanalyst can use these regularities to break the code. There are several alternative modes of operation. The Cipher Block Chaining where the cipher text (n) is uesd to encrypt the message (n+1). Used if we want full error propagation if there is an error in the cipjertext. Other mode is the Cipjer Feedback Mode. Used as "stream" cipher (8bits). Again the ciphertext and plaintext are related by using the cipher texte (n) to encrypt the plaintext (n+1). Used for speed and if we want to restrict the propagation of an error in the cipher text gets cottupterd.

---

**Explain how to use a hash algorithm tocreate a one-time pad encryption algorithm.**



