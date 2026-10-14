DAY 04: CRYPTOGRAPHY

1. What is Cryptography?
Cryptography uses mathematical techniques to protect information and communications.

2. Key Terms
Plaintext: readable original information.
Ciphertext: information transformed by encryption.
Encryption: converts plaintext into ciphertext.
Decryption: converts ciphertext back into plaintext.
Key: information used by a cryptographic algorithm.
Hash: fixed-length digest used for integrity checks; a hash is not encryption.

3. Symmetric vs Asymmetric Encryption
Symmetric encryption uses the same secret key to encrypt and decrypt.
Asymmetric cryptography uses a public/private key pair and can support key exchange and digital signatures.

4. Hashing and Integrity
SHA-256 can help detect changes to a file.

Safe local exercise:
echo "Cybersecurity practice" > sample.txt
sha256sum sample.txt
echo "Changed content" >> sample.txt
sha256sum sample.txt

Compare the two outputs.

5. Important Cautions
DES is obsolete for new security systems. Playfair is a historical educational cipher, not suitable for modern security. Use well-reviewed modern cryptographic tools and protocols.

LEARNING OUTCOME
Distinguish encryption, decryption, hashing, symmetric encryption, and asymmetric cryptography.
