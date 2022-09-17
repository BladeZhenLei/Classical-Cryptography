***
## Private Key Cryptography
### AES

## Public Key Cryptography
### RSA (Rivest–Shamir–Adleman) cryptosystem 
<p>
The naive version of the RSA proceeeds with taking a prime $p$ and $q$ with similar magnitude first, compute their product $n=pq$, find $k=lcm(p-1,q-1)$, and then pick another integer $e$ such that ${1}<{e}<{k}$ and $gcd(e,k)=1$. Lastly, find the multiplicatgive inverse $d=e^{-1}$ $(mod$ $k)$. Here, $d$ is the private key, $n$ and $e$ are the public keys, and $(p,q,k)$ needs also to be kept secret.
  

### DSA
### ECC
### ECDSA

