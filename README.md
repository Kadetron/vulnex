# Vulnex
<p align="center">
  <img src="https://i.imgur.com/PI1AoHB.jpg" alt="lock"/>
</p>
<h3 align="center">Find SQLi vulnerabilty in the URLs in the domain </h3>

> Searches for .php files by scrapping the domain website upto a depth of 2

>Appends (' ") after .php files and checks for SQL errors.

## Usage
```bash
$ vulnex
```
![vulnex](https://i.imgur.com/lzCjt05.png)
```bash
$ vulnex <domain>.<tld>
```
![vulnex_domain](https://i.imgur.com/Ge1Sv04.png)

## Installation
```bash
  git clone https://github.com/Kadetron/vulnex  
  cd vulnex
  sudo mv vulnex /usr/local/bin
  cd ..
  rm -r ./vulnex
```

## Dependency
- awk
- curl
- grep
- sed
- uniq
