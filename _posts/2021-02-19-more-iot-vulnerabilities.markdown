---
layout: single
categories: jekyll update
toc: true
title: More IoT Vulnerabilities
---
# Details
Vulnerabilities are inherent to complex software systems.  Creating secure, fast, and bug-free software is an iterative process. However, it is not unreasonable to think that that an exploit from 1994 would have been patched or ruled out in the design process. Yet, 9 out of 11 Internet of Things (IoT) TCP/IP stacks were vulnerable to the 1994 Mitnick attack according to SC Magazine. The attack tries to guess what is called the initial sequence number that is used to prevent collisions in TCP/IP connections. To prevent such attacks using a random number generator is required. The article emphasized that random number generation on IoT devices is a bit more difficult because of the computation horsepower and power required to do so. Six of the nine manufactures developed patches while others simply disable the stack or recommended against using it. 

# Opinion
I can understand have software be vulnerable to new attacks, but attacks from 1994 shows that IoT manufacturers need to set security as a top priority. The sheer quantity of IoT devices makes them the perfect target for many attacks. Having security as a side priority is foolish. I understand that random number generation can be computationally expensive, but it would be unlikely to affect normal operation considering the initial sequence number does not need to be constantly randomized. Some people in the IoT world think that internet protocols are simply to complicated for IoT devices. I can see their arguments, but I do not think that giving up internet access to IoT devices would be worth any added security/reliablity. 

# Sources
* [SC Media](https://www.scmagazine.com/home/security-news/iot/many-tcp-ip-stacks-found-vulnerable-to-mitnick-attack-some-still-unpatched/)