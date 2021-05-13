# ExplNode

## A web application seeded with vulnerabilities, rootkits, back doors, and data leaks

Explnode is a Node.js-based application seeded with security vulnerabilities (e.g., OWASP Top 10, business logic flaws, rootkits, and data leaks). This application can be used by security professionals to test [Ocular](https://ocular.shiftleft.io) or developers who want to understand the processes behind securing web applications.

## Common Vulnerabilities

| File | Description |
| - | - |
| [`dep-lodash.js`](https://github.com/conikeec/explnode/blob/master/vulnerabilities/dep-lodash.js) | Prototype Pollution Attack caused due to OSS dependency LogDash |
| [`exec.js`](https://github.com/conikeec/explnode/blob/master/vulnerabilities/exec.js)             | RCE Command Injection Exploit                                   |
| [`loop.js`](https://github.com/conikeec/explnode/blob/master/vulnerabilities/loop.js)             | Denial of Service Exploit                                       |
| [`nosqli.js`](https://github.com/conikeec/explnode/blob/master/vulnerabilities/nosqli.js)         | NoSql Injection Attack                                          |
| [`redirect.js`](https://github.com/conikeec/explnode/blob/master/vulnerabilities/redirect.js)     | Information Disclosure, Exfiltration Channel                    |
| [`redos.js`](https://github.com/conikeec/explnode/blob/master/vulnerabilities/redos.js)           | Regex Denial of Service Attack                                  |
| [`sqli.js`](https://github.com/conikeec/explnode/blob/master/vulnerabilities/sqli.js)             | Sql Injection Attack                                            |
| [`xss.js`](https://github.com/conikeec/explnode/blob/master/vulnerabilities/xss.js)               | Cross Site Scripting Attack                                     |
| [`xxe.js`](https://github.com/conikeec/explnode/blob/master/vulnerabilities/xxe.js)               | XXE Attack                                                      |

### Threat Modeling Queries

[`Queries`](https://github.com/conikeec/explnode/blob/master/ocular_notebook/README.md)

## :warning: Disclaimer

We do not take responsibility for the way you use this application. We have made the purpose of the application clear and you should not use it in a malicious manner.
