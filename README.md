# ENCRYPTINATOR

A simple bash script that can encrypt and decrypt messages between friends, or just encrypt messages for your own use later (e.g. passwords, etc). 

## Usage

From your terminal, run the script: `./encryptinator`

You'll be presented with a menu, as shown below:

```
---------------------------------

               MENU

---------------------------------


Select from the following options: 

1) Encrypt a message
2) Decrypt a message
3) Quit

Selection: 
```

### Encrypting a message

- Enter the message you want to encrypt, when prompted.
- Enter the password you'd like to use, when prompted.
- The script will create a new text file you could share with a friend. This text file has the encrypted message within.
- If you want to share your message with someone else, you'll need to share the password with them. This isn't very secure, but it's just for fun anyway, right? 

### Decrypting a message

- Enter the file location's full path that needs to be decrypted (e.g. `/home/$USER/file-to-be-decrypted.txt`).
- Enter the location of the full name of your checksum to be validated here (e.g. `/home/$USER/file_sha256sum.txt`).
- The script will verify the checksum, if provided. This may be bypassed with a warning. User input required to proceed.
- Enter the password that was used to encrypt the file.
- If you're decrypting a message from a friend, you'll need the password they used to create the file.

### Future plans

- Create a more robust version with better security
- Move from symmetric to asymmetric encryption tool
- Expand capabilities
- Create a snap that can be installed and updated easily
- Kick it to the man
- `U2FsdGVkX1+C3k5hrdikpIoRCGZXXu+SpVcOWcI1BrgWTBwJ+v7mjL67Ueq4xpqP` <- Created with ENCRYPTINATOR
