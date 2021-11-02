# How to analyze code for Vulnerabilities

> To see video Click [here](https://youtu.be/A8CNysN-lOM?t=830)
> 

# Prereqsite :

 

![Untitled](How%20to%20analyze%20code%20for%20Vulnerabilities%208bd9e4bc7d5e49cba6ec8eea73b93851/Untitled.png)

![Untitled](How%20to%20analyze%20code%20for%20Vulnerabilities%208bd9e4bc7d5e49cba6ec8eea73b93851/Untitled%201.png)

## Concept of Sources and Sinks

![Untitled](How%20to%20analyze%20code%20for%20Vulnerabilities%208bd9e4bc7d5e49cba6ec8eea73b93851/Untitled%202.png)

Source - Source is a code that allows a vulnerability to happen 

Sink - Where the vulnerability actually happens 

As an  example **Command Injection vulnerability** :

Source in this case could be the function that takes user input Whereas a sync would be functions that execute arbitrary commands.   

If untrusted user input can flow from source to sink without proper validation or sanitization then there is command Injection vulnerability and many **vulnerabilities can be identified by tracking this data flow from appropriate sources to corresponding sinks.**

A lot of SAS  actually work this way as well. What is SAS ?