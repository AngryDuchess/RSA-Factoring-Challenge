# Project: RSA Factoring Challenge
We have sniffed an unsecured network and found numbers that are used to encrypt very important documents. It seems that those numbers are not always generated using large enough prime numbers. Your mission should you choose to accept it, is to factorize these numbers as fast as possible before the target fixes this bug on their server - so that we can decode the encrypted documents.

This project is NOT mandatory at all. It is 100% optional. Doing any part of this project will add a project grade of over 100% to your average. Your score won’t get hurt if you don’t do it, but if your current average is greater than your score on this project, your average might go down. Have fun!
## Resources

#### Read or watch:

* [RSA](https://intranet.alxswe.com/rltoken/VvijGiyWnPt8LDZjICgl1w)
* [How does HTTPS provide security?](https://intranet.alxswe.com/rltoken/vNd9XWDEu1mgexyIGDMaXQ)
* [Prime Factorization](https://intranet.alxswe.com/rltoken/kYixcru2uFRtLzb29NjiHg)
* [Why RSA?](https://intranet.alxswe.com/rltoken/JM9Zrnja-XCQwm5kEzr_xA)
## Tasks

| Task | File |
| ---- | ---- |
| 0. Factorize all the things! | [SOON](./) |
| 1. RSA Factoring Challenge | [SOON](./) |
## Tasks - details :page_with_curl:

* **0. Factorize all the things!**
Factorize as many numbers as possible into a product of two smaller numbers.

- Usage: factors <file>
    - where <file> is a file containing natural numbers to factor.
    - One number per line
    - You can assume that all lines will be valid natural numbers greater than 1
    - You can assume that there will be no empy line, and no space before and after the valid number
    - The file will always end with a new line
- Output format: n=p*q
    - one factorization per line
    - p and q don’t have to be prime numbers
    - See example
- You can work on the numbers of the file in the order of your choice
- Your program should run without any dependency: You will not be able to install anything on the machine we will run your program on
- Time limit: Your program will be killed after 5 seconds if it hasn’t finish
- Push all your scripts, source code, etc… to your repository
    - we will only run your executable factors

* **1. RSA Factoring Challenge**
RSA Laboratories states that: for each RSA number `n`, there exist prime numbers `p` and `q` such that

`n = p × q`. The problem is to find these two primes, given only `n`.

This task is the same as task 0, except:
- p and q are always prime numbers
- There is only one number in the files
How far can you go in less than 5 seconds?
