# Protocol Buffers, Objective C iOS5

This is a modified ARC enabled version of the [Protocol Buffers in Objective C][protobuf-objc] project. 
It is optimized for iOS5 and up. This version is updated for Protobuf 2.5.  It also contains several
new convenience functions on the generated classes.  Most notably:

- `storeToDictionary:(NSMutableDictionary *)dict` will store all fields that are present into a standard Cocoa dictionary.

Protocol Buffers are a way of encoding structured data in an efficient yet extensible format.
This project is based on an implementation of Protocol Buffers from Google.  See the
[Google protobuf project][g-protobuf] for more information.

[g-protobuf]: http://code.google.com/p/protobuf/
[protobuf-objc]: https://github.com/booyah/protobuf-objc

# Credits

Synapse Product Development
-------------------------------------------------------------------------------
- Rachel Blackman
- Nate True

davidby
-------------------------------------------------------------------------------
- David Bonnefoy

Regwez Inc.
-------------------------------------------------------------------------------
- Ragy Eleish <ragy@regwez.com>

Booyah Inc.
-------------------------------------------------------------------------------
- Jon Parise <jon@booyah.com>


Google Protocol Buffers, Objective C
-------------------------------------------------------------------------------
- Cyrus Najmabadi  (http://code.google.com/p/metasyntactic/wiki/ProtocolBuffers)
- Sergey Martynov  (http://github.com/martynovs/protobuf-objc)


Google Protocol Buffers
-------------------------------------------------------------------------------
- Kenton Varda, Sanjay Ghemawat, Jeff Dean, and others