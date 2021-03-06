---
title       : Simple Ether Valuation Tool
subtitle    : Version 1.0
author      : Nick Oswald
job         : Data Scientist
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Why Ethereum and Why this app?

1. Cryptographically Secure Decentralized Platform and Strong Team
2. Hype, More Background on cryptocurrencies
3. Why the app?

--- .class #id 
## Cryptographically Secure, Decentralized Trust, Strong Team

The power of Bitcoin and other Blockchain technologies is the concept of decentralized trust.
Whereas traditionally people would trust escrow services (when buying a home), banks (for storing and transferring money),
and the legal system to enforce laws, decentralized applications allow people to interact directly with each other while
using the power of cryptography to secure transactions.

Whereas Bitcoin is seen primarily as a decentralized currency independent of any government, Ethereum strives to be 
a platform for building any type of decentralized application. Examples could include cryptocurrencies, a decentralized
DropBox, escrow services, smart contracts that execute automatically and precisely following code, etc.

Unlike Bitcoin (whose create remains anonymous), everyone knows the team that has created Ethereum. The chief software architect
is a Thiel Fellow (Peter Thiel, the co-founder of PayPal), and the team includes Prof. Merkel, one of the world's experts in cryptography.
As of 7/24, the team has raised over $4M in less than 48 hours towards completion of the project.

---
## Strong Team / My tool

Venture Capitalists, developers, crypto-currencies enthusiasts and others have all talked highly about this project and look forward to its success.

For more information on Bitcoin and Ethereum, you can go to the following websites:

http://www.bitcoin.org
http://www.ethereum.org

My tool is a simple one that will allow someone using some basic parameters to estimate their potential rate of return on an Ethereum investment.
This tool is valuable since this project is very new and people do not know how to value something like this.
However, since the software isn't even fully created yet, this is very speculative.
The team is raising money to help get this towards completion (like http://www.kickstarter.com)

---
## Why my tool?


My tool takes four inputs and calculates the expected return over a time period specified by the user. The main function calculates the ending value of one's initial investment using the following formula: (ethercount*dollaretherprice)*(1+annualPctInc)^Yrs 

Below is an example calculation and output:


```r
set.seed(1234)
ethercount = 2000
dollaretherprice = 10
annualPctInc = 0.05
Yrs = 5
output = (ethercount*dollaretherprice)*(1+annualPctInc)^Yrs
print(output)
```

```
## [1] 25526
```

Depending on what users want, additional graphs and functionality can be added.

Any suggestions about the app (if you liked it or not) can be emailed to me directly at nick.oswald@gmail.com

Enjoy!

