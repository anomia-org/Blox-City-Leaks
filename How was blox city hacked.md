# How was Blox City Hacked?
With all the recent leaks, a common question arises; How did this happen?

Anomia was able to get the direct source from the hackers, who kindly shared their methodologies to cracking into Blox City. Here's how it went;

### Infiltration
A common procedure of social engineering, a user pretended to be an experienced developer, and gained the trust of Kyle, whom accepted him as a developer. The developer was hired but was not given GitHub access.

### Ratting
The intruder, provided Kyle with a "reference" as proof of his work, this "reference" was malware injected with a RAT, allowing the intruder to access all of Kyle's SSH keys
```
c/users/kyle/.ssh
```

The hacker then used the SSH keys to access Blox City's VPS

### Leak
Using the SSH Keys, a bot accesse the GitHub organization, downloaded all the content and sent it back.

The VPS was penetrated as well, allowing the hackers free access to the entire project structure.

### Now what?
This is an incredibly high level leak, and Kyle is already suffering the consequences of this. 

This is one of the biggest scandals Kyle has faced so far.
