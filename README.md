# Features
- Encrypts files with AES256
- Automatically shred file, overwriting 32 times, then again with 0's
- Pack directory upon encryption, recursively shred
- Automatically unpack directory upon decryption

# WARNING
**WILL SHRED AND DELETE ALL FILES PASSED TO IT, INCLUDING DIRECTORIES.**

**YOU HAVE BEEN WARNED**

# Usage

`./crypto.sh -e[ncrypt] <infile>` - to encrypt, overwrite, and delete file

`./crypto.sh -d[ecrypt] <infile>` - to decrypt file
