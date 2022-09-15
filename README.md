***
## Private Key Cryptography
### AES

## Public Key Cryptography
### RSA (Rivest–Shamir–Adleman) cryptosystem 
As one of the most famous and oldest encryption scheme developed in 1977. Its encryption key is public and distinct from the decryption key, which is kept secret. An RSA user creates and publishes a public key based on two large prime numbers, along with an auxiliary value. The prime numbers are kept secret. Messages can be encrypted by anyone, via the public key, but can only be decoded by someone who knows the prime numbers.
<br/>
The security of RSA relies on the difficulty of factoring the product of two large prime numbers, the "factoring problem". Breaking RSA encryption is known as the RSA problem. Whether it is as difficult as the factoring problem is an open question. There are no published methods (as for classical computers) to defeat the system if a large enough key is used.
<br/>
RSA is a relatively slow algorithm. Because of this, it is not commonly used to directly encrypt user data. More often, RSA is used to transmit shared keys for symmetric-key cryptography, which are then used for bulk encryption–decryption.

### DSA
### ECC
### ECDSA

