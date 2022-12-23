# BOCU

The Binary Ordered Compression for Unicode (BOCU) concept was developed in 2001 by Mark Davis and Markus Scherer for the ICU project. The main premise of BOCU-1 is to encode each Unicode character as the difference from the previous character, and to represent small differences in fewer bytes than large differences. By encoding differences, BOCU-1 achieves the same compression for all small alphabetic scripts, regardless of the block in which they reside ([Ewell, 2004; Scherer & Davis, 2002](http://www.unicode.org/notes/tn6/)).

See also [Unishox](https://github.com/siara-cc/Unishox) which provides better compression ratio.
