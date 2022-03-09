# GmailBruteforce

Made for bruteforcing gmail accounts.

> It needs Less Secure Apps setting turned on in order to work.

## Installation

For windows

```bash
git clone https://github.com/Sarthak2143/GmailBruteforce.git
cd GmailBruteforce/
python3 main.py
```

For Mac/Linux

```bash
git clone https://github.com/Sarthak2143/GmailBruteforce.git
cd GmailBruteforce/
chmod +x main.py
./main.py
```

## Usage

You need a target email address with less secure apps setting turned ON and a wordlist for bruteforcing.

Don't have wordlist?

Don't worry this tool comes with a wordlist file that you can use.

```
┌──(kali㉿kali)-[~/GmailBruteforce]
└─$ python3 main.py

[?] Enter email adress: test@gmail.com
[?] Enter wordlist path: wordlist.txt
Starting bruteforcing...

[!] Incorrect password: 123456
[!] Incorrect password: 12345
[!] Incorrect password: 123456789
[!] Incorrect password: password                        
[!] Incorrect password: iloveyou
[!] Incorrect password: princess
[!] Incorrect password: 1234567                         
[!] Incorrect password: 12345678                        
[!] Incorrect password: abc123
[!] Incorrect password: nicole                          
[!] Incorrect password: daniel                         
[!] Incorrect password: babygirl                       
[!] Incorrect password: monkey
[!] Incorrect password: lovely
[!] Incorrect password: jessica
[!] Incorrect password: michael
[!] Incorrect password: ashley
[!] Incorrect password: qwerty
[!] Incorrect password: 111111
[!] Incorrect password: iloveu
[!] Incorrect password: 000000
[!] Incorrect password: michelle
[!] Incorrect password: tigger
[!] Incorrect password: sunshine
[+] Correct password: chocolate
[+] Password cracked!

[*] Script finished!
[*] Time Elapsed: 18 seconds.
```
You've to specify the gmail address and the wordlist.

## Requirements

You need `git` and `python3` need on your system inorder to work.

The script will download essential packages automatically so you don't have to worry much.

**MOST IMPORTANTLY**

The E-Mail address should be of Gmail and it must have *Less secure apps turned ON*.

## TODO

- [ ] Use proxies for better efficiency.
- [ ] A command line version with flags.
