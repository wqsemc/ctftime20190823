# ctftime20190823
Official URL: https://hackcon.online/   **NOTE: The timings are Friday 23 August, 2019 01:15 am IST - Friday 23 August 2019 6:30 pm IST**




Cryto========
OTP
100
hackerman is so dank that he decided to play around with OTPs.
he did the following:
message1 ^ key = cipher1
message2 ^ key = cipher2

He gives you cipher1 and cipher2 and challenges you to find the concatenation of messages 1 and 2.
Are you dank enough to find this?
Oh and also, 'meme' is so popular that hackerman used the word in both his messages.
cipher1 is '\x05F\x17\x12\x14\x18\x01\x0c\x0b4'
cipher2 is '>\x1f\x00\x14\n\x08\x07Q\n\x0e'
Both without quotes

Noki
198
I was told Vigenère Cipher is secure as long as length(key) == length(message). So I did just that!
Break this: g4iu{ocs_oaeiiamqqi_qk_moam!}e0gi

AgainAndAgainAndAgain
467
Someone was thinking encrypting again and again helps, prove them wrong.
c = 196353764385075548782571270052469419021844481625366305056739966550926484027148967165867708531585849658610359148759560853

Edit: the flag format is slightly different

q1.py download

Ez Pz
484
easiest crypto points ever
nc 68.183.158.95 7777

Time Travel
496
Alpha is a n00b coder but also can time travel, we were somehow able intercept his space-time but we can't make any sense of it.

q2.zip download

DEStroy
500
Here is a file that would show you how one would normally implement DES. But we ain't normal, are we!? We are dank. So we decided to change stuff a little.
Great, now all you have to do is decrypt this! But ... but don't you need a key for that? Ah what a weakling. You're so weak that I decided I need a key that is just like you.
Enough clues? I guess. Oh by the way. I know I gave you a file which basically explains everything you got to do, but I'm afraid you're going to have to dig deeper if you want to last 'fewer rounds' with me in a boxing contest.
okay so now you have this, an encrypted message: [9, 135, 35, 24, 209, 134, 39, 37, 8, 215, 10, 106, 192, 93, 208, 218, 222, 6, 206, 141, 79, 56, 156, 122, 88, 44, 165, 220, 227, 211, 71, 5, 76, 18, 108, 1, 233, 116, 206, 181, 40, 37, 153, 113, 158, 160, 126, 148]

DES2.py download

Secsy curves
500
nc 68.183.158.95 6969

pwn========
baby b0f
100
It's a b0f , Can't be easier than that.
Service : nc 68.183.158.95 8989
pwn-q1 download

babypwn
451
You don't need eip control for every pwn. Service : nc 68.183.158.95 8990
pwn-q2 download

Not So Easy B0f
469
I have stack canaries enabled, Can you still B0f me ? Service : nc 68.183.158.95 8991
pwn-q3 download

2 small 2 Pwn
494
I just read and write , Can you still Pwn me ?
Service is running at nc 68.183.158.95 8992
pwn-q4 download

Reversing========
babyrev
100
What comes before main , I wonder .... Note: flag format : flag{XXXXXXX}
q1 download

Break It Baby
304
Just break the password and submit in the flag format: d4rk{PASSWORD}c0de

 ctfQues download

OpenMePloxx
490
Can you find my key
q2 download

SuperEncryptor
494
My friend used this SuperEncryptor to hide his secret. Can you please find his secret.
flag.enc download, q3 download

Misc========
Discord
1
Join our Discord and follow us on Twitter

Weird Text
100
Someone sent me this file (mysterious.txt) .It contains only ><+-.,[] symbols and no other letters or numbers.
mysterious.txt download

Invisible Programming
361
Is this really a C program?
hello_world.cpp download

Weird EXE file
489
There is something fishy with this EXE file.
d4rkc0de download

Jorge Luis Borges
490
Bruh, do you even read books, lol? Then solve this: ++++++++++[>+>+++>+++++++>++++++++++<<<<-]>>>>++++++++++++++++++++.<++++++++++++++++++++++++.<++++++++++++++++++++++.-------.++++++.--.+++.>>.<.<-.--------.+++++++.+++++..------.>>.<.<+.-----.++++++++++.++.----.-.>>.<<---------.++++++++++++.----.-.--.+++++++++++++.-------------.
file1.txt download, file2.txt download, desc.txt download

Forensics========
GIFe_me_time
484
A renowned hacker, John, has hidden all the credentials of his website as he decided to pause his work. Can you find the credentials before he secures his website?
PS: Maybe what you find first is not always the answer :)

Stego========
Small icon much wow
100
One of my friends like to hide data in images.Help me to find out the secret in image.
stego.jpg download

Too cold for steg
287
The challenge name is enough for you to solve it. Everything you need is present in the text file.
final.txt download

GIMP IT
446
One of my logo designer left his job in the middle and hide my flag in it.Help me to get the flag.
stego1.xcf download

Web========
Secret Agent
100
Not so secret after all?   http://68.183.158.95/secret_agent/
