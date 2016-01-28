SharpJson
=================================

SharpJson is a JSON parser for C#.
Its main principles is to provide a lightweight and powerful API that is easy to integrate with any project.

SharpJson is based on Patrick van Bergen original JSON parser.

http://techblog.procurios.nl/k/news/view/14605/14863/how-do-i-write-my-own-parser-(for-json).html

It was optimized and refactored, but still keeping the simplicity of the original API.


Improvements made from original parser
---------------------------------------

 * Optimized parser speed (deserialize roughly near 3x faster than original)
 * Added support to handle lexer/parser error messages with line numbers
 * Added more fine grained control over type conversions during the parsing
 * Refactory API (Separate Lexer code from Parser code and the Encoder from Decoder) 


Goals
---------------------------------------

* Easy to integrate (one single source code file)
* Provide good performance for big and small JSON files


License
---------------------------------------
SharpJson is distributed under the [MIT License](https://opensource.org/licenses/MIT).
Use of the spec, either as-defined or a customized extension of it, is intended to be commercial-friendly.
