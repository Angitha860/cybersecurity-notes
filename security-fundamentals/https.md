# HTTPS (HyperText Transfer Protocol Secure)

HTTPS is the secure version of HTTP.

It protects communication between a browser and a website using encryption and digital certificates.

## Why HTTPS is Needed

HTTP sends data in plain text.

Attackers may be able to read:

- Usernames
- Passwords
- Messages
- Sensitive information

HTTPS protects this data.

## How HTTPS Works

### Step 1

The browser connects to the website.

### Step 2

The website sends:

- Digital Certificate
- Public Key

### Step 3

The browser verifies the certificate.

Checks include:

- Validity
- Trusted Certificate Authority
- Expiration date

### Step 4

The browser generates a Session Key.

Example:

ABC123

### Step 5

The browser encrypts the Session Key using the website's Public Key.

### Step 6

The website decrypts the Session Key using its Private Key.

### Step 7

Both sides now know the Session Key.

Communication continues using Symmetric Encryption.

## Why HTTPS Uses Both Encryption Types

### Asymmetric Encryption

Used for:

- Secure key exchange

### Symmetric Encryption

Used for:

- Fast communication

## Benefits of HTTPS

- Protects confidentiality
- Prevents eavesdropping
- Verifies website identity
- Secures online communication

## What I Learned

- HTTPS stands for HyperText Transfer Protocol Secure.
- HTTPS uses Digital Certificates.
- HTTPS uses both Asymmetric and Symmetric Encryption.
- A Session Key is used for encrypted communication.
