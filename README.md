[![Juice](http://goo.gl/RzkH1I)](https://github.io/cord-dev/libjuice/)

Mixin library for specific needs concerning reddit, CHAOS, Berrytube, and anything else Catman works on.


##Requirements
- SASS 3.2+
- Bourbon 2.1+

##Installation

Install [SASS](http://sass-lang.com/) and [Bourbon](https://github.com/CoRD-Dev/libbourbon/).

(Optional) Install [Neat](https://github.com/CoRD-Dev/libneat/) and [Bitters](https://github.com/CoRD-Dev/libbitters/).

`cd` to your projects local repository and run:

```bash
git submodule add https://github.com/CoRD-Dev/libjuice.git sass/juice
```
(`sass/juice` should be the directory your sass/scss files are kept +/juice.)

The generated folder will contain all Juice's files.

Import Juice after Bourbon (and Neat and Bitters if applicable) in your stylesheet. 
(There is currently no stable release of Juice.)
All additional imports should be below Juice:

```scss
@import "bourbon/bourbon";
@import "juice/juice-untested-unstable";

// All other imports
```


##Credits
Juice is maintained by [CoRD](http://cord-dev.github.io/) and [The_Catman](http://catmanix.github.io/).

##License
Juice is Kopyleft 2013 CoRD. It is free software, and may be redistributed under the terms specified in the UNLICENSE file.


