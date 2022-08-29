# scala-cli-bloop-sbt-crypto-gzip-compress-rsa-encrypted

## Description
Encrypt and decrypt password with RSA.
To compress the encrypted text gzip was used.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- scala
- bloop-sbt

## Docker stack
- openjdk:8-jdk-alpine

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
- [RSA Code](https://www.geeksforgeeks.org/asymmetric-encryption-cryptography-in-java/)
- [GZIPCompression](https://stackoverflow.com/questions/16351668/compression-and-decompression-of-string-data-in-java)
