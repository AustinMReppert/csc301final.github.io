---
layout: single
categories: jekyll update
toc: true
---
# Details
With the increasing number of protections around cookies, websites are looking for alternative ways to fingerprint and track you. This usually involves getting information about your device such as screen details, hardware, browser configuration, etc. In general, the safest means to avoid such profiling is to disable scripts. If there is no API to give the website information, it must do so with obscure strategies called side-channel attacks. The Hacker News reports one such new obscure tracking technique called CSS Prime+Probe that works even when scripts are disabled.  The attack begins by sending an initial request to the server. In the HTML is a string with a certain class that will occupy the entire CPU’s cache. Then a CSS selector is used to search the entire string. After the search, another request is sent. Artificial intelligence is then used to correlate the timing to a particular CPU. The timings are usually directly correlated with the cache of a platform. Cache has been utilized in many attacks to perform side-channel attacks in the past few years. Although these attacks are rarely seen in the wild. The attack can be accurate, but it seems to vary a lot from platform to platform. On some platforms like AMD and Samsung the graph showed --, which presumably means it did not work at all.  Browser developers have a few ideas on how the attacks can be mitigated, but no clear strategy. 

# Opinions
I do not think this attack is particularly important in the sense that almost no one has scripts disabled. So why would attackers resort to such complicated tracking methods? I think only nation states would dedicate so much effort to these types of attacks. If you want to be almost entirely secure you should just be using a text-based browser like Lynx. These side-channel based attacks really show that developers need some sort of abstraction to hide the cache capabilities of a CPU. Speed has always been a priority, so it will likely take a while for kernel/OS level abstractions around it.  I do not think this is something that should concern average users.

# Sources
* [The Daily Swig]( https://portswigger.net/daily-swig/research-how-json-parsers-can-create-security-risks-when-it-comes-to-interoperability)