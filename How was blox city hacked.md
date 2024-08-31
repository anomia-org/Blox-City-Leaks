# How was Blox City Hacked?
With all the recent leaks, a common question arises; How did this happen?

Anomia was able to get the direct source from the hackers, who kindly shared their methodologies to cracking into Blox City. Here's how it went;

### Infiltration
A common procedure of social engineering, a user pretended to be an experienced developer, and gained the trust of Kyle, whom accepted him as a developer. The developer was hired but was not given GitHub access.



### Ratting
The intruder, provided Kyle with a "reference" as proof of his work, this "reference" was malware injected with a RAT, allowing the intruder to access all of Kyle's SSH keys.

The software used is called "Creal Stealer", which was modified for this use case.
```
c/users/kyle/.ssh
```
![](https://media.discordapp.net/attachments/1279191268198711472/1279251221403926528/image.png?ex=66d3c30a&is=66d2718a&hm=d8e512025b2f58b3c64c82c9097c42470e7d3e99ec5026e2f0cd6afd3aa6334d&=&format=webp&quality=lossless&width=432&height=367)

The hacker then used the SSH keys to access Blox City's VPS

### Leak
Using the SSH Keys, a bot accesse the GitHub organization, downloaded all the content and sent it back.

![](https://media.discordapp.net/attachments/1124087949802348574/1279252926388244510/image.png?ex=66d3c4a1&is=66d27321&hm=2c92599fe7a81e6431ecb1bd95508f8e5b2f01b224cb10dc4b84b03271121b5f&=&format=webp&quality=lossless&width=660&height=546)

The VPS was attacked as well, allowing the hackers free access to the entire project structure.


### The refunds
Hackers, using the now leaked Stripe API Key (which for some reason had FULL PERMISSIONS), started running refunds to all blox-city users with the API endpoint. A total of 1.3k USD was refunded without Kyle's  knowledge, oficially placing Kyle 'in debt'.

![](https://media.discordapp.net/attachments/1124087949802348574/1279226378557849710/image.png?ex=66d3abe7&is=66d25a67&hm=ceb10155c70e2138f53ce7d9ff96f45d8630d77cbc7d4fc6ab468ad09ec6c2a8&=&format=webp&quality=lossless&width=603&height=67)

### Now what?
This is an incredibly high level leak, and Kyle is already suffering the consequences of this. 

This is one of the biggest scandals Kyle has faced so far.
