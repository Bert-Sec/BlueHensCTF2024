# Training Problem: Intro to RSA
**Category**: CRYPTO

**Value**: 50

**ID**: 159

## Challenge Description
```
```py
In [9]: p = getPrime(128)
In [10]: q = getPrime(128)
In [11]: N = p*q
In [12]: bytes_to_long(flag) < N
Out[12]: True
In [13]: print(pow(bytes_to_long(flag), 65537, N), N)
9015202564552492364962954854291908723653545972440223723318311631007329746475 51328431690246050000196200646927542588629192646276628974445855970986472407007
```

-ProfNinja
```

Write-up available at [bertsec.com](https://bertsec.com)
