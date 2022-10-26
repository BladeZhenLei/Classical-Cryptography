***
## Introduction
There are mainly two types of crytographies: Symmetric Key Cryptography and Asymmetric Key Cryptography.
The former uses the same keys for both the encryption of plaintext and the decryption of ciphertext. 
The later, sometimes also called public key crytography, is far more important and widely used in computer security. 
It uses pairs of related keys, and each key pair consists of a public key and a corresponding private key, generated with one-way functions. 
The concepts behind these can be tremendously difficult math problems often related to number theory.

## Symmetric Key Cryptography
### AES

## Asymmetric Key Cryptography
### RSA cryptosystem 
The naive version of the RSA protocol proceeeds first with taking two primes $p$ and $q$ with similar magnitude, compute their product $n=pq,$ find $k=lcm(p-1,q-1),$ and then pick another integer $e$ such that ${1}{<}{e}{<}{k},$ and $gcd(e,k)=1.$ Lastly, find the multiplicatgive inverse $d=e^{-1}(mod k).$ Here, ${d}$ is the private key, $n$ and $e$ are the public keys, in addition, $p$, $q$, and $k$ also need to be kept secret.

### DSA
### ECC
### ECDSA
  
  
<p/><p align="center">...TO BE CONTINUED...<p/>
<p/><script type="text/javascript" charset="utf-8" src=" https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML, https://vincenttam.github.io/javascripts/MathJaxLocal.js"></script>
