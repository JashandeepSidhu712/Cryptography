# DES
DES, which stands for Data Encryption Standard, is a symmetric-key block cipher encryption algorithm.

DES is a symmetric-key encryption algorithm, meaning the same key is used for both encryption and decryption.

DES is an implementation of a Feistel Cipher. It uses 16 round Feistel structure.

![image](https://github.com/JashandeepSidhu712/Cryptography/assets/117754690/7f633e21-9dc0-4aca-bc5e-c8c5b0db6612)

# WORKING OF DES

Initial Permutation (IP): The 64-bit plaintext block is permuted based on a predefined pattern to distribute the data.

Rounds: DES iterates through multiple rounds, each consisting of expansion, key mixing, substitution, and permutation steps. These operations mix and transform the data in a complex manner.

Subkeys: For each round, a 48-bit subkey is derived from the main 56-bit encryption key. These subkeys are used for XOR operations and S-box substitutions in each round.

S-Box Substitution: The S-boxes introduce non-linearity to the encryption process by replacing 6 bits of data with 4 bits, based on predefined tables. This step adds confusion to the encryption.

Permutations: The data is rearranged using fixed permutations (P-boxes) in each round, making it challenging for an attacker to reverse the encryption.

Final Permutation (FP): After all rounds are completed, a final permutation is applied to the data to generate the 64-bit ciphertext block.

![image](https://github.com/JashandeepSidhu712/Cryptography/assets/117754690/1e647540-de69-430d-badc-5acda09bbc63)

# ROUND FUNCTION

![image](https://github.com/JashandeepSidhu712/Cryptography/assets/117754690/209ae148-8b04-4e74-9ee0-6333285cda52)

# PERMUTATION LOGIC

![image](https://github.com/JashandeepSidhu712/Cryptography/assets/117754690/071ad39f-6d11-4d82-ad30-452d30069425)




