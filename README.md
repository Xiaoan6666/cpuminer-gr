cpuminer-gr

This version was created to support ARMv7 (ARM) and ARMv8 (Aarch64).
Code was stripped from any unnecessary algorithms and currently only
supports Ghost Rider (gr, Raptoreum) algorithm.
Algorithm removal was done to minimize size and reduce compilation time
as it **should** be compiled locally to achieve the best performance possible.
It also supports compilation with x86_64 architecture processors.


Requirements
------------

1. 64 or 32 bit Linux OS. Raspbian (Debian) is known to work and have all dependencies in their repositories. Others may work but may require more effort.

2. Stratum pool supporting stratum+tcp:// or stratum+ssl:// protocols or RPC getwork using http:// or https://. GBT is YMMV.

Supported Algorithms
--------------------

                          gr            Gr Hash (RTM)
  

Donations
---------

cpuminer-opt has no fees of any kind but donations are accepted.

BTC: 12tdvfF7KmAsihBXQXynT6E6th2c2pByTT

Happy mining!
