# A Directory of Haskell Libraries

## Overview

This is a categorized and annotated directory of available Haskell libraries. This directory is **not comprehensive and highly opinionated**.

## Benchmarking

 * [criterion][criterion]: statistically accurate benchmarking

## Concurrency and Parallelism

 * [async][async]: higher-level interface over threads, providing e.g. futures

## Data Stores

### Relational Databases

 * [mysql-simple][mysql-simple]: a mid-level client library for the MySQL database

### Riak

 * [riak][riak]: automated storage and conflict resolution

## Data Structures and Algorithms

### Unicode Strings

 * [text][text]: representation for Unicode strings, including I/O support.
 * [text-icu][text-icu]: ICU support
 
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

## Math

 * [mwc-random][mwc-random]: fast random number generation
 * [statistics][statistics]: comprehensive statistics library

## Monads

 * [mtl][mtl]: monads and monad transformers

## Monitoring

 * [ekg][ekg]: remote monitoring over HTTP

## Networking

 * [network][network]: socket and low-level networking support.

## Serialization

### Binary Formats

 * [binary][binary]: parser and generate arbitrary byte formats

### CSV

 * [cassava][cassava]: convert CSV files to/from Haskell data types

### JSON

 * [aeson][aeson]: parser/serializer to/from Haskell data types

### Text Formats

 * [attoparsec][attoparsec]: parser combinator library for creating parser for text formats or mixed binary/text formats, such as HTTP.
 * [base16-bytestring][base16-bytestring]: base16 encoding/decoding
 * [base64-bytestring][base64-bytestring]: base64 encoding/decoding

## Testing

 * [QuickCheck][QuickCheck]: random testing of program properties (preferred method)
 * [HUnit][HUnit]: a unit testing framework for Haskell, inspired by the JUnit tool for Java
 * [test-framework][test-framework]: framework for grouping, running, and displaying the output of tests
 * [test-framework-quickcheck2][test-framework-quickcheck2]: test-framework test runner for QuickCheck
 * [test-framework-hunit][test-framework-hunit]: test-framework test runner for HUnit

[aeson]: http://hackage.haskell.org/package/aeson
[async]: http://hackage.haskell.org/package/async
[attoparsec]: http://hackage.haskell.org/package/attoparsec
[base16-bytestring]: http://hackage.haskell.org/package/base16-bytestring
[base64-bytestring]: http://hackage.haskell.org/package/base64-bytestring
[binary]: http://hackage.haskell.org/package/binary
[bytestring]: http://hackage.haskell.org/package/bytestring
[cassava]: http://hackage.haskell.org/package/cassava
[containers]: http://hackage.haskell.org/package/containers
[criterion]: http://hackage.haskell.org/package/criterion
[ekg]: http://hackage.haskell.org/package/ekg
[hashable]: http://hackage.haskell.org/package/hashable
[HUnit]: http://hackage.haskell.org/package/HUnit
[mtl]: http://hackage.haskell.org/package/mtl
[mysql-simple]: http://hackage.haskell.org/package/mysql-simple
[mwc-random]: http://hackage.haskell.org/package/mwc-random
[network]: http://hackage.haskell.org/package/network
[QuickCheck]: http://hackage.haskell.org/package/QuichCheck
[riak]: http://hackage.haskell.org/package/riak
[statistics]: http://hackage.haskell.org/package/statistics
[test-framework-hunit]: http://hackage.haskell.org/package/test-framework-hunit
[test-framework-quickcheck2]: http://hackage.haskell.org/package/test-framework-quickcheck2
[test-framework]: http://hackage.haskell.org/package/test-framework
[text]: http://hackage.haskell.org/package/text
[text-icu]: http://hackage.haskell.org/package/text-icu
[unordered-containers]: http://hackage.haskell.org/package/unordered-containers
[vector-algorithms]: http://hackage.haskell.org/package/vector-algorithms
[vector]: http://hackage.haskell.org/package/vector
