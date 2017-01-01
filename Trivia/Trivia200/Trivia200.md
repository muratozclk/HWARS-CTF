## Hacking Wars CTF - Trivia 200 - Ping me not

Bu yazýda sizlere Trivia 200 sorusunu çözerken uyguladýðýmýz yöntemlerden bahsedeceðim.

Soruda bize þu þekilde bir açýklama verilmiþti.

![alt tag](https://github.com/muratozclk/HWARS-CTF/blob/master/Trivia/Image/menot.png?raw=true)

'ping -l 65000' ile Google' da kýsa bir araþtýrma yapýnca karþýmýza DDoS ataklarýnýn çýktýðýný gördük.

![alt tag](https://github.com/muratozclk/HWARS-CTF/blob/master/Trivia/Image/ping.png?raw=true)

Yaptýðýmýz kýsa bir araþtýrma sonucunda bu atak çeþidinin ping of death olduðunu öðrendik.

Bir kaç denemeden sonra cevabýmýzýn 'ping_of_death' olduðunu öðrendik.

### FLAG :  ctf_{cb4fbcabb087e25739a3b24f88d749a343a5ea73}