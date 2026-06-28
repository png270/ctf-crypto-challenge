## Writeup – All Things Onion

This is a steganography challenge involving image metadata and classical cryptography, centered around a chef’s obsession with onions. The objective is to extract hidden information from an image and decrypt it to unlock an encrypted file embedded within the image.

---

### Step 1: Inspect the Provided Image
Unzip the provided image file and analyze it using `exiftool` to inspect its metadata.

Pay close attention to the **Author/Artist** and **Comment** fields. The Comment field provides the key information needed to identify the cipher and perform decryption.

---

### Step 2: Decrypt the Ciphertext
Use the identified cipher and key to decrypt the extracted ciphertext. The decrypted output serves as the password required to unlock the encrypted file.

---

### Step 3: Retrieve the Flag
After unlocking the file, identify the esoteric programming language used within. Modify the code as required, using values referenced in the challenge description, and execute it to obtain the flag.

You may use **Esolang Park** to run the code:  
https://esolangpark.vercel.app/

Upon successful execution, the flag will be revealed.


