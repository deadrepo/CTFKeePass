#CTFZIP
-------------------

How to Solve ?
-------------------

- git clone `https://github.com/deadrepo/CTFKeePass.git`

- git clone  `https://github.com/openwall/john.git`
- cd Desktop/john/run

Extract the hash of the PDF file 
-------------------
- `zip2john '/home/kali/Desktop/CTFPZIP/secret.zip' > '/home/kali/Desktop/CTFZIP/hash.txt' `

Run John The Ripper 
-------------------
- Use this command `john --wordlist='/home/kali/Desktop/CTFZIP/password_list_v2.txt' --format=zip '/home/kali/Desktop/CTFZIP/hash.txt'`

Output
-------------------
![](john.png)

Alternative
-------------------
`https://github.com/robiot/zzCrack`
