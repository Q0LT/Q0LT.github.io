---
title: "Injection Attacks"
---
# Command Injection 

Explained:
: Exploits vulnerabilities in programs that allow the execution of external commands on the server.

## Ways of injecting OS Commands (Windows and Unix):
- &
- &&
- pipe (|)
- double pipe (||)

## Ways of injecting OS Commands (Unix):
- ;
- newline (0x0a or \n)
- `
- $(


## Commands to try

| Purpose               | Linux                 | Windows        |
|-----------------------|-----------------------|----------------|
| Name of current user  | whoami                | whoami         |
| Operating System      | uname -a              | ver            |
| Network configuration | ifconfig              | ipconfig /all  |
| Network connections   | netstat -an           | netstat -an    |
| Running processes     | ps -ef                | tasklist       |


## Resources
[OWASP](https://owasp.org/www-community/attacks/Command_Injection)
[HACKTRICKS](https://book.hacktricks.xyz/pentesting-web/command-injection)
[PORTSWIGGER](https://portswigger.net/web-security/os-command-injection)
[OSCP NOTES](https://gabb4r.gitbook.io/oscp-notes/cheatsheet/command-injection-cheatsheet)
