# Git Hub
A brief description of what this Git hub and how install & set up git . 



## Generating A GPG key & Setup :

### Ubuntu install comamnd :
```bash
sudo apt-get install gnupg  # For Ubuntu/Debian
```


### Generate a new GPG key
```bash
gpg --full-generate-key
```
This will prompt you for a series of options :

a. Select the key type <br>
Choose the default option, which is usually (1) RSA and RSA, and press Enter. <br>
set : (1) RSA and RSA <br>

b. Choose the key size <br>
You will be prompted to select the key size. The recommended size is 4096 bits for security: <br>
set : 4096 <br>

c. Set the key expiration date <br>
You can choose an expiration date for your key. It is recommended to set a time limit, like 1 year: <br>
set : 1y <br>

d. Enter your user information <br>
Next, you'll be asked to provide your name and email address. Ensure these match the details you use for GitHub. <br>
- Example: <br>
Real Name: masudrana03 <br>
Email Address: 920mash@gmail.com <br>

e. Choose a passphrase <br>
You’ll be prompted to enter a passphrase to protect your key. <br>
It's highly recommended to use a strong passphrase to prevent unauthorized access. <br>


### List your GPG keys
```bash
gpg --list-secret-keys --keyid-format LONG
```

You should see output similar to this:
```bash
/home/user/.gnupg/secring.gpg
------------------------------
sec   4096R/<Your-GPG-Key-ID> 2024-11-11 [expires: 2025-11-11]
uid                          masudrana03 <920mash@gmail.com>
ssb   4096R/<Subkey-ID> 2024-11-11
```

### Export your public key
```bash
gpg --armor --export <Your-GPG-Key-ID>
```

You should see output similar to this:
```bash
-----BEGIN PGP PUBLIC KEY BLOCK-----

mQINBFjCxzkBEAD8U7Cjw...
...
-----END PGP PUBLIC KEY BLOCK-----
```

## This below command will use after export GPG keys :

### Git which GPG key to use: 
```bash
git config --global user.signingkey <Your-GPG-Key-ID>
```

### Configure Git to sign your commits by default:
```bash
git config --global commit.gpgSign true
```