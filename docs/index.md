
Most Powerful, Robust and Efficient tool on the Internet for bruteforcing Gmail accounts written in `python3`.

**NOTE: This tool will not work from now as Google changed it's policies. [READ HERE](https://support.google.com/accounts/answer/6010255?hl=en-GB&dark=1&visit_id=637903517594769878-544557905&p=less-secure-apps&rd=1)**

### Installation

**Pre requisties:** 
- [git](https://git-scm.com/downloads)
- [python3](https://www.python.org/downloads/)

1. For windows

```bash
git clone https://github.com/Sarthak2143/GmailBruteforce
cd GmailBruteforce/
python3 main.py
```
1. For Mac/Linux

```bash
git clone https://github.com/Sarthak2143/GmailBruteforce
cd GmailBruteforce/
chmod +x main.py
./main.py
```
## NOTE

In order to bruteforce any gmail account with this tool the victim account must have **Less Secure Apps** turned on.

For more details see [Why you need to turn ON less secure apps?](https://support.google.com/accounts/answer/6010255?hl=en)

Read this [article by devanswers](https://devanswers.co/allow-less-secure-apps-access-gmail-account/) to turn ON **Less secure apps.**

## Usage

**Pre requisties:**  

- Victim's Gmail account.
- Wordlist for bruteforcing.

This tool comes with a wordlist pre-installed.

```bash
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

You've to specify the Gmail address and path to wordlist in the input section.

## TODO

- Use proxies for better efficiency.
- Commamd line version with flags.

## Support

Having trouble with Tool? [Report an Issue](https://github.com/Sarthak2143/GmailBruteforce/issues/new).
