## sJSON python library

**Fork of project https://bitbucket.org/Anteru/sjson/overview**

SJSON is a simplified version of JSON which is easier to read/write (http://bitsquid.blogspot.nl/2009/10/simplified-json-notation.html). This library provides a Python reader/writer similar to the Python JSON library.

sJSON changes (in contrast with JSON):
* Assume an object definition at the root level (no need to surround entire file with { } ).
* Commas are optional
* Quotes around object keys are optional if the keys are valid identifiers
* Replace ':' with '='

## Notes:
* Supports python 2.6+ and 3
* Missing JSON features: javascript text encoding
* Implementation is very simple, and it is not supposed to be performance/memory effective
* Object is represented as python dictionary, e.g. it does not keep an order of keys
* Tests are out-dated now

**Original author: Matthäus G. Chajdas**
**License: 3-clause BSD**
