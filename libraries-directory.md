# A Directory of Haskell Libraries

## Overview

This is a categorized and annotated directory of available Haskell libraries. This directory is **not comprehensive and highly opinionated**.

## Testing

 * [HUnit][HUnit]: a unit testing framework for Haskell, inspired by the JUnit tool for Java
 * [QuickCheck][QuickCheck]: random testing of program properties
 * [test-framework][test-framework]: framework for grouping, running, and displaying the output of tests
 * [test-framework-hunit][test-framework-hunit]: test-framework test runner for HUnit
 * [test-framework-quickcheck2][test-framework-quickcheck2]: test-framework test runner for QuickCheck

## Serialization

### Binary Formats

 * [binary][binary]: parser and generate arbitrary byte formats

### CSV

 * [cassava][cassava]: convert CSV files to/from Haskell data types

### JSON

 * [aeson][aeson]: parser/serializer to/from Haskell data types

### Text Formats

 * [attoparsec][attoparsec]: parser combinator library for creating parser for text formats or mixed binary/text formats, such as HTTP.

## Networking

 * [network][network]: socket and low-level networking support.

## Monitoring

 * [ekg][ekg]: remote monitoring over HTTP

## Data Structures and Algorithms

### Unicode Strings

 * [text][text]: representation for Unicode strings, including I/O support.

### Byte Strings

 * [bytestring][bytestring]: representation for byte strings, including functions for passing byte strings to C code and I/O support.

### Maps, Sets, Sequences, Graphs, and Trees

 * [containers][containers]: standard immutable data structures

### HashMaps and HashSets

 * [hashable][hashable]: type class for data types that can be cached
 * [unordered-containers][unordered-containers]: hashing-based containers that are typically faster than their ordered counterparts

### Vectors

 * [vector][vector]: boxed and unboxed vectors
 * [vector-algorithms][vector-algorithms]: several different sort algorithms for vectors

[HUnit]: http://hackage.haskell.org/package/HUnit
[QuickCheck]: http://hackage.haskell.org/package/QuichCheck
[aeson]: http://hackage.haskell.org/package/aeson
[attoparsec]: http://hackage.haskell.org/package/attoparsec
[binary]: http://hackage.haskell.org/package/binary
[bytestring]: http://hackage.haskell.org/package/bytestring
[cassava]: http://hackage.haskell.org/package/cassava
[containers]: http://hackage.haskell.org/package/containers
[ekg]: http://hackage.haskell.org/package/ekg
[hashable]: http://hackage.haskell.org/package/hashable
[network]: http://hackage.haskell.org/package/network
[test-framework-hunit]: http://hackage.haskell.org/package/test-framework-hunit
[test-framework-quickcheck2]: http://hackage.haskell.org/package/test-framework-quickcheck2
[test-framework]: http://hackage.haskell.org/package/test-framework
[text]: http://hackage.haskell.org/package/text
[unordered-containers]: http://hackage.haskell.org/package/unordered-containers
[vector-algorithms]: http://hackage.haskell.org/package/vector-algorithms
[vector]: http://hackage.haskell.org/package/vector
