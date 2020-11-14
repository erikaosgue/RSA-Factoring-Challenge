# RSA Factoring Challenge

## Resources:books:
### Read or watch:
* [RSA](https://en.wikipedia.org/wiki/RSA_cryptosystem%29)
* [How does HTTPS provide security?](https://stackoverflow.com/questions/3968095/how-does-https-provide-security)
* [Prime Factorization](https://privacycanada.net/mathematics/prime-factorization/)

## Requirements
### General
* You can choose the language of your choice.
* OS needs to be Standard Ubuntu 14.04 LTS, 64-bits (see VMs).


## Tasks
<br>

[0. Factorize all the things!]()

Factorize as many numbers as possible into a product of two smaller numbers.

* Usage: `factors <file>`

    * where `<file>` is a file containing natural numbers to factor.
    * One number per line
    * You can assume that all lines will be valid natural numbers greater than 1
    * You can assume that there will be no empy line, and no space before and after the valid number
    * The file will always end with a new line

* Output format: n=p*q

    * one factorization per line
    * p and q don’t have to be prime numbers

* You can work on the numbers of the file in the order of your choice
* Your program should run without any dependency: You will not be able to install anything on the machine we will run your program on
* Time limit: Your program will be killed after 5 seconds if it hasn’t finish

<br>
<br>

[1. RSA Factoring Challenge]()

RSA Laboratories states that: for each RSA number n, there exist prime numbers p and q such that

n = p × q. The problem is to find these two primes, given only n.

This task is the same as task 0, except:

* p and q are always prime numbers
* There is only one number in the files
How far can you go in less than 5 seconds?

Read: RSA Factoring Challenge
