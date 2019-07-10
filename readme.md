# Frome Tech Shed

A home for content and projects from the Tech Shed meet & amker group in Frome, UK.

## Domain and hosting notes

Original CNAME and ALIAS records pointed to holding page at:
pixie.porkbun.com

| Entry | Host | Answer | Priority |
| - | - | - | - |
| ALIAS | techshedfrome.org	| techshedfrome.github.io |	 |
| CNAME | www.techshedfrome.org | techshedfrome.org | |
| MX | techshedfrome.org	| fwd1.porkbun.com	 | 1 |
| MX | techshedfrome.org	| fwd2.porkbun.com	| 1 | 
| SRV	| _autodiscover._tcp.techshedfrome.org |	10 443 webmail.porkbun.com | 10 |
| TXT	| techshedfrome.org	| v=spf1 mx ~all | |

* Original Porkbun nameservers:
* curitiba.porkbun.com
* fortaleza.porkbun.com
* maceio.porkbun.com
* salvador.porkbun.com

Ideally we reverse-proxy all the tools we're using so we get slack.techshedfrome.org, trello.techshedfrome.org etc. working & make things easier to find.