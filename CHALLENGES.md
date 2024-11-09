# Challenge Summary

## OSINT
- **Training Problem: Intro to OSINT**
  - Description: A famous person is selling their house. In this market, who wouldn't? Can you tell me who owns this ...

- **I'm Hungry**
  - Description: Google is your friend.

-JD (jr.)...

## WEB
- **Training Problem: Intro to Web**
  - Description: It's nice to have some training problems.

-ProfNinja...

- **lists of JSONs**
  - Description: Web...ish...

-ProfNinja...

- **Just a day at the breach**
  - Description: ```py
import os
import json
import zlib

def lambda_handler(event, context):
    try:
       ...

- **DNS**
  - Description: This DNS server reveals a secret to a special IP. Can you make it think you’re connecting from 127.0...

- **Snake**
  - Description: To uncover the flag, either win the game or reverse the game.

-JD (sr.)...

- **Firefun 3**
  - Description: Our fireplace company was all set to take off for the moon, then we had to shut it all down.  All th...

- **Nonogram Pt. 2: Disgraced**
  - Description: Grace wrote a beautiful nonogram for us.  I made a beautiful disaster from it.  Nonogram?  More like...

## CRYPTO
- **Training Problem: Intro to RSA**
  - Description: ```py
In [9]: p = getPrime(128)
In [10]: q = getPrime(128)
In [11]: N = p*q
In [12]: bytes_to_lo...

- **Nonogram Pt. 1: Simple Enough**
  - Description: When you get past the puzzle, you now face a classic encryption / old-school stego encoding.  Wrap t...

- **ROTOLACTOR**
  - Description: "Got Milk?"

-JayV...

- **Oh Baby, A (Pythagorean) Triple!**
  - Description: I bet you never knew about the DNA of right triangles.  Found it beautiful; wrote a problem.

-Pro...

- **Hand-Made's Tale**
  - Description: She drew this, in a language of her own invention as a puzzle for you.  Pretend like you're cracking...

- **Corkscrew**
  - Description: A simple little guessy crypto: `Us_lnt10ns}1443{FTCDqsysp0srrr4up_t1`

-ProfNinja...

- **Barcode Crypto**
  - Description: These barcodes seem to be missing something, can you help me figure it out?

-AcerYeung...

- **HMAC**
  - Description: There’s a secret message being HMAC-protected, but the implementation has a serious flaw. Can you re...

- **Simon Says**
  - Description: [https://gist.github.com/AndyNovo/7c172b8c5bdfcdce6c66cd0bdae53584](https://gist.github.com/AndyNovo...

## REVERSING
- **Training Problem: Intro to Reverse**
  - Description: Just a classic flagchecker.

-ProfNinja

(Try using dogbolt.org)...

- **🅱️rainrot.c**
  - Description: I would like to apologize for the crimes that have been committed upon humanity and the mental traum...

- **Hogwarts Stairs**
  - Description: If you lived in Hogwarts I bet navigating those moving stairs would feel something like this problem...

- **Cut The Flag**
  - Description: [https://spacegames3.itch.io/cut-the-flag](https://spacegames3.itch.io/cut-the-flag)

pwd: `bluehe...

- **G.G.**
  - Description: *Unlock the Power
 -Codemasters*
 
 Flag Format altered due to limited character set: `UDCTF/UPPE...

- **Texting IRL**
  - Description: How do you even open a WORD file?

-ProfNinja

P.S. I would love to see the most beautiful solut...

## MISC
- **Welcome Letter**
  - Description: Welcome to the CTF.  A few notes: 

```
* I made 10 XOR School problems, we're a uni so teaching ...

- **AlgebrarbeglA**
  - Description: `78! - k = k - !87`

Solve for `k` flag format is `udctf{k}`

-ProfNinja

Dedicated to Wrath o...

- **You're such a Rube**
  - Description: 💀

JD (jr.)...

- **Bees in Space**
  - Description: Imagine if the Bee Movie happened in space 🤯... okay it probably wouldn't be that great because ever...

- **Sticky Keys**
  - Description: `GEJYU?<d0 go.5 Ekrpat 4bf,afZ+`

-Malloc...

- **Polar Opposites**
  - Description: Thres somethin backwards bout this audio... (Wrap what you find in UDCTF{})

-SpiegelHalter...

- **Font-inary**
  - Description: Have you ever struggled to read someone's handwriting? Well, whoever created this font didn't care, ...

- **An ode to Alejandro and Kristin**
  - Description: Do you like puzzles?

-The Cyber Frat  (We went nuts on speed jigsaws this summer)...

- **Scottish Ham**
  - Description: You scream into the void, and it responds with this...

~skyefi...

## XOR SCHOOL
- **XS1: XOR without XOR**
  - Description: ![xorwithoutxor.png](/files/6613f7653f188567028f4bb7d6ad29ab/xorwithout.png)

This is how XOR make...

- **XS2: Looper**
  - Description: `11010210041e125508065109073a11563b1d51163d16060e54550d19`

*This series of problems is called the...

- **XS3: Roman Xor**
  - Description: [https://gist.github.com/AndyNovo/309325b566b2df42b984e2401fedbaab](https://gist.github.com/AndyNovo...

- **XS6: CTR Mode is just XOR**
  - Description: [https://gist.github.com/AndyNovo/23d509307fc55fcebae1fd522ed04295](https://gist.github.com/AndyNovo...

- **XS8: CBC Encrypted?**
  - Description: [https://gist.github.com/AndyNovo/84580af56a6294ed2576366018dc557c](https://gist.github.com/AndyNovo...

- **XS7: Alternating Current**
  - Description: ```py
In [5]: cipher = DES.new(ky, DES.MODE_OFB)

In [6]: cipher.encrypt(msg).hex()
Out[6]: 'ee7...

- **XS4: Hexy**
  - Description: ```py
In [1]: xor(flag + key + hashlib.sha256(flag).hexdigest().encode(), key).hex()
Out[1]: '1a0c...

- **XS5: Old School**
  - Description: I used an old, common, prng.  Knowledge of the solvability of this problem helps you deduce...

[h...

- **XS9: ROX LOOHCS**
  - Description: ```py
In [69]: print(xor(flagmsg, flagmsg[::-1]).hex())
051c1b7f4652001b3008525d1b7f135c3216001545...

- **XS10: PHP XOR**
  - Description: I could have kept going, maybe even make a pure XOR CTF but I think 10 is enough.  Hope you enjoyed ...

## PWN
- **Training Problem: Intro to PWN**
  - Description: Classic win function pwn.

-ProfNinja

(I originally released this with a canary, took away the ...

- **Pure Write-What-Where PWN**
  - Description: Straight to the point.

-ProfNinja...

- **ret2bf**
  - Description: I heard an interview with Tame Impala where he said, *"for a song to make an album, it has to have b...

- **thetv**
  - Description: The dude at 777 needs some help with his remote, he heard you worked in IT... so make sure you fix i...

- **thelight**
  - Description: It's the same guy again, ugh, this time he needs some help with his light switch, it's been on the f...

- **Flaming Lips**
  - Description: She likes her hair to, be real orange...

-ProfNinja and printf(name);...

## FORENSICS
- **Whispers of the Feathered Messenger**
  - Description: In a world where secrets flutter through the air, the bluehen carries a hidden message.  A message t...

- **Inner Demons**
  - Description: I can't seem to sleep at night... Maybe I need to dig further within.

-pleasework.sh...

- **RGBinary**
  - Description: Some planes are flying, some planes are grounded.

-AcerYeung

(Capital `UDCTF{}`)...

- **Giraffical Image Format**
  - Description: A student disagreed with my pronunciation of gif.  They said, snarkily, how do you pronounced Graphi...

- **The Immortal Game**
  - Description: ```
THE IMMORTAL GAME CTF
    184.60.121.146:53
    make your move.
```

MAKE YOUR MOVE.

-r...

