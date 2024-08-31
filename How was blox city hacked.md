# How was Blox City Hacked?
With all the recent leaks, a common question arises; How did this happen?

Anomia was able to get the direct source from the hackers, who kindly shared their methodologies to cracking into Blox City. Here's how it went;

### Infiltration
A common procedure of social engineering, a user pretended to be an experienced developer, and gained the trust of Kyle, whom accepted him as a developer. The developer was hired but was not given GitHub access.


This document is still in the works. Kyle has confirmed that the SSH keys were not exposed, meaning the section below is FALSE. We are currently investigating the incident to figure it out better.

For now, the 'estimated guess' of what happened is the following;

- A fed up staff member (most likely wavegod) gave access to the Github to a series of people. 
- Since the source code contained keys and secrets to the services B.C relies on, they managed to get API access to Stripe.
- It is suspected the 'hackers' gained access to the database as well.



SECTION BELOW IS THE ORIGINAL "STATEMENT" FROM THE HACKERS
---
~~### Ratting~~
~~The intruder, provided Kyle with a "reference" as proof of his work, this "reference" was malware injected with a RAT, allowing the intruder to access all of Kyle's SSH keys~~
```
c/users/kyle/.ssh
```

~~The hacker then used the SSH keys to access Blox City's VPS~~

~~### Leak~~
~~Using the SSH Keys, a bot accesse the GitHub organization, downloaded all the content and sent it back.~~

~~The VPS was penetrated as well, allowing the hackers free access to the entire project structure.~~

### Now what?
This is an incredibly high level leak, and Kyle is already suffering the consequences of this. 

This is one of the biggest scandals Kyle has faced so far.
