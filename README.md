#CTFZIP
-------------------

How to Solve ?
-------------------

- git clone `https://github.com/deadrepo/CTFZIP.git`

- git clone  `https://github.com/openwall/john.git`
- cd Desktop/john/run

Extract the hash of the PDF file 
-------------------
- pdf2john '/home/kali/Desktop/CTFPdf/pay.pdf' > '/home/kali/Desktop/CTFPdf/hash.txt' 

Run John The Ripper 
-------------------
- Use this command `john --wordlist='/home/kali/Desktop/CTFZIP/password_list_v2.txt' --format=zip '/home/kali/Desktop/CTFZIP/hash.txt'`

Output
-------------------
![](john.png)

Alternative
-------------------
`https://github.com/robiot/zzCrack`
