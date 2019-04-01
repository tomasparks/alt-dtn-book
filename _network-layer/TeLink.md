---
title: TeLink
---
>  MODEM7 sent the filename as normal text, which meant it could be corrupted by the same problems that XMODEM was attempting to avoid. This led to the introduction of TeLink by Tom Jennings, author of the original FidoNet mailers.
>  TeLink avoided MODEM7's problems by standardizing a new "zero packet" containing information about the original file. This included the file's name, size, and timestamp, which were placed in a regular 128 byte XMODEM block. Whereas a normal XMODEM transfer would start with the sender sending "block 1", the TeLink header packet was labeled "block 0".
>  The basic "block 0" system became a standard in the FidoNet community, and was re-used by a number of future protocols like SEAlink and YMODEM.
- <https://en.wikipedia.org/wiki/XMODEM>
