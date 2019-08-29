```javascript
const info = await fetch("https://superpeoplesearch.org/luxwarp")
  .then(res => res.json())
  .then(data => data);

console.log(info);
```

```json
{
  "name": "Mikael 'Luxwarp' Carlsson",
  "birth": 19900325,
  "address": {
    "street": "Citrongatan 14 B",
    "zip": 44155,
    "city": "Alingsås",
    "country": "Sweden"
  },
  "phone": "+46709393498",
  "email": "mikael.m.carlsson@gmail.com",
  "website": "https://codeiolo.org"
}
```

```shell
luxwarp@luxlop:~$ whoami --biography
```

```output
About 'Luxwarp'
===============================================================

My name is Mikael Carlsson, I am 29 years old and
I live in Alingsås, 50km north of Gothenburg, Sweden.

In my whole life I have been interested in computers,
tech and development. My greatest passion
is web development. I can build websites, web applications
and handle both front-end and back-end development.

On my spare time when I don’t sit behind the computer
I love to walk and train my dogs and spending
time with my fiancee.

I am a positive person who is very stubborn and
tries to solve problems that may arise. With the
ability to quickly take in new information and
knowledge, I quickly learn systems and tasks. I’m
always willing to learn new things because the
brain can not be full.
```

```shell
luxwarp@luxlop:~$ myskills --render-console
```

```output
# Skills for user 'Luxwarp'       Rendered: 0.2s
===============================================================

# Web

HTML:          =======================================>80%
CSS:           ====================================>70%
JS/Node:       ====================================>70%
PHP:           ==============>40%
_______________________________________________________________

# Frameworks

VueJS:         =============================>60%
ExpressJS:     =============================>60%
_______________________________________________________________

# Tools

Git:           ====================================>70%
NPM:           ====================================>70%
Inkscape:      =======================>50%
VS Code:       =================================>65%
_______________________________________________________________

# Operating systems

Ubuntu:        ====================================>70%
OSX:           =================================>65%
Windows:       =============================>60%

```

```javascript
const info = await fetch("https://myedu.io/luxwarp")
  .then(res => res.json())
  .then(data => data);

info.renderAs("structured-console");
```

```output
Education                                    1/1
==============================================================

Göteborgs Tekniska Institut

Aug 2008 – May 2011

Learning operating system, native and web development,
networking, PC-support, and networks.

https://gti.se
```

```javascript
const info = await fetch("https://myjobs.io/luxwarp")
  .then(res => res.json())
  .then(data => data);

info.renderAs("structured-console");
```

```output
Work
==============================================================

Freelancer

Jun 2013 – present

Working as a freelance IT consult and web developer.
Building web applications and helping people with
tech problems.

https://codeiolo.org                                       1/7
______________________________________________________________

Securitas

Jun 2015 – May 2019

Working as a security guard on patrol in Gothenburg and Lerum.

https://securitas.se                                       2/7
______________________________________________________________

Crazyride

Nov 2013 – March 2015

Customer service for web shop selling led lights.

https://crazyride.se                                       3/7
______________________________________________________________

MacSupport

Jul 2011 – Jan 2013

IT Consultant to corporate customers,
network management,servers and clients.
Also worked a lot with deployment to
school clients (K12 / one-to-one system.).
Internal IT responsible for mail server,
file server, network and cloud services.

https://macsupport.se                                      4/7
______________________________________________________________

Intern
==============================================================

Warpnine

Oct 2010 – Dec 2010

Web developer and some internal IT support.

http://www.warpnine.se/                                    5/7
______________________________________________________________

Micropter

April 2010 – Jul 2010

PC-technician and web developer                            6/7
______________________________________________________________

SalesOnNet

Aug 2006 – May 2008

PC-technician                                              7/7
______________________________________________________________
```

```shell
luxwarp@luxlop:~$ sudo shutdown --output-log
```

```output
Misc
==============================================================

Languages
  * English
    * Speak: Good
    * Write: Good
  * Swedish
    * Speak: Fluently
    * write: Fluently


I have driver license for car and have my own car.

References
==============================================================

Securitas Göteborg

John Bohman - Group leader

0702997309
______________________________________________________________

MacSupport

Jan Ringedal - Office manager

j.ringedal@macsupport.se

031-7264300
```
