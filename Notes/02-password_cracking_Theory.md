# Password Attack Technique and prevention

## 1. Password Gussing

- Password guessing is a technique used to target online protocols and services.It may cause an account to be locked out if the system is designed and configured securely.

- most vulnerable in `online shopping website`

## 2. Password Cracking

- Password cracking is a technique performed locally or on systems controlled by the attacker.

- eg. Zip passwords, USB stick Password

# Password Profiling

## 1. Default password

- Manufacturers set default passwords with products and equipment such as switches, firewalls, routers.
- eg. Huawei router default password `telecomadmin:admintelecom`


## 2. Weak Password

#### Weak Password list

- Professionals collect and generate weak password lists over time and often combine them into one large wordlist. Lists are generated based on their experience and what they see in pentesting engagements. 
- eg `password123`


## 3. Leaked Password

- Sensitive data such as passwords or hashes may be publicly disclosed or sold as a result of a breach. These public or privately available leaks are often referred to as 'dumps'. 
-  The following are some of the common password lists that have weak and leaked passwords, including `webhost`, `elitehacker`,`hak5`, `Hotmail`, `PhpBB` companies' leaks:

`https://github.com/danielmiessler/SecLists/tree/master/Passwords/Leaked-Databases`




# How to prevent your credential from attackers

#### 1. `Unique account, unique password`
#### 2. Use multi-factor authentication
#### 3. Use password Manager and Generate Strong Password
- Bitwarden
- LastPass
- KeePass
#### 4. Never Share `OTP` with anyone



