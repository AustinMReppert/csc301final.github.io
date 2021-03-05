---
layout: single
categories: jekyll update
toc: true
---
# Details/Opinions
Json or JavaScript Object Notation is a file format that can store JavaScript object like data. The files are in plain text and can encode objects, key value pairs, and arrays. They are easy to parse, read, write, and use in code. I have nearly 28,000 Json files on my machine right now. If there is a language, that language most likely has a Json parser. Even in languages like c++, Json libraries are among the top used libraries like nlohmann_json on the [Conan Center]( https://conan.io/center/). The Daily Swig has reported that flaws within the parsing logic can lead to a number of vulnerabilities. The article also pointed out that while most languages have stricter Json parsers, they are slower, so developers opt for faster 3rd party libraries. The main reason for these vulnerabilities is a lack of strictness within the Json specification itself.  I think that programmers like to live in an ideal world where all data is well formed, however this is often not the case. Hackers in particular love to send malformed data, which often breaks logic in parsers, firewalls, sanitizers, etc. The specification should be stricter, but developers should also keep security in mind. Especially when they are taking in data from users.

# Sources
* [The Daily Swig]( https://portswigger.net/daily-swig/research-how-json-parsers-can-create-security-risks-when-it-comes-to-interoperability)