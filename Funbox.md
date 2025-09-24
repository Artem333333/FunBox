lets go!!!!!!


Step 1
nmap -sC -sV -p- ip machine

![1](image.png)

Step 2

gobuster dir --url http://10.0.2.7 --wordlist /usr/share/wordlists/dirb/common.txt 

![2](image-2.png)

Step 3 

![admin](image-3.png)
![secret](image-4.png)
![store](image-6.png)
![robots.txt](image-7.png)


Step 4 
Exploit CSE Bookstore
![Exp1](image-9.png)
![Exp2](image-10.png)
![Exp](image-12.png)
 python3 exploit.py http://10.0.2.7/store
![exp store](image-13.png)

Step 5

RCE $ 
![rce](image-14.png)

![reverse shell](image-15.png)
![1](image-16.png)


Python didn't work, let's try Perl
![pearl reverse](image-17.png)

Step 6
![1](image-18.png)

TONY
![tony](image-19.png)

![Password](image-20.png)

ssh tony@10.0.2.7 pass:yxcvbnmYYY
![tony](image-21.png)
![1](image-22.png)


Step 7

![gtfobins](image-23.png)
try yelp
it didn't work out
try time
worked with
![root](image-24.png)
![root1](image-25.png)
![root2](image-26.png)