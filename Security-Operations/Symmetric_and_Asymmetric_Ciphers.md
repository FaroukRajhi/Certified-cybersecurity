# symmetric ciphers

Two ciphers formalized ny NIST:
  - Data encryption standard (DES):
      - No longer considered secured.
      - 64 bit key.
  - Advanced encryption standard (AES):
      - Replaced oldest standards.
      - Commonly used today.
      - Three different key sizes 128 bits / 192 bits / 256 bits.
      - Size dependent on protection needed.

Fast and strong:
  - Substitution and permutation simple.
  Mathematics faster for computers to process.

# Asymmetric ciphers

Overcomes key distribution problems.
Public keys are shared:
  - Directories.
  - Certificates.
Each key can be used once in an operation; if a file is encrypted with a subject's public key, it must be decrypted with corresponding private key.
Example of asymmetric ciphers include:
  - RSA.
  - Diffie-Hellman.
Asymmetric key sizes are usually much larger.
Weaker bit for bit than symmetric ciphers.
Slower to computer than symmetric ciphers.