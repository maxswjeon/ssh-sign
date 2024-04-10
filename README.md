# Sign with SSH Private Key

`ssh-sign` is a utility that allows you to sign a string, file, or etc. with your ssh key.

## Where can I use `ssh-sign`?

`ssh-sign` has various usages. Example usages are listed below.

1. **To prove that you created / verified the information**  
   This is the traditional **signing** usage. Also, this method is used in [GitHub](https://github.com/) to verify your commits, saying you wrote the commits.
2. **To prove that you have the access to the private key for the given public key**  
   This is advanced usage with signing, and can be used to authorize the public key ownership.
