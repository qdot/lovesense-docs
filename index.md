# Lovense Hardware and Protocol Documentation

## Contents

```eval_rst
.. toctree::
   :maxdepth: 2

   models
   bluetooth
   protocol
 ```
 
## Introduction

This document contains information about Lovense sex toy hardware, and
the common bluetooth protocol used in all Lovense toys. This
information can be used to access Lovense toys and create new
libraries for controlling features and receiving information from
them.

## Lovense Library Info

lovesense is a library for controlling Lovense sex toys. The library
allows users to control all aspects of the toy
(vibration/rotation/inflation, depending on the toy), as well as
retrieving information like device type, status, battery level, and
accelerometer readings.

The library is currently available in the following languages:

-  [Python](http://github.com/metafetish/lovesense-py)
-  [Max/MSP](http://github.com/metafetish/lovesense-max)
-  [Rust (with C Headers)](http://github.com/metafetish/lovesense-rs)
-  [Javascript/Node.js](http://github.com/metafetish/lovesense-js)

If you need an implementation in a language not currently supported by
lovesense, please file an issue on the [github tracker of the
lovesense-docs projects](http://github.com/metafetish/lovesense-docs/issues)

Please note that this project has no direct relation to the Lovense
company. These drivers have been developed/supported by the open source
community. Lovense has had no direct participation in this project and
most likely will not be able to answer questions or provide support for
any of the Lovesense drivers.

If you require commercial support for programming for Lovense products,
it is recommended you go through the [Official Lovense Developer
Program](https://www.lovense.com/sextoys/developer).

## Disclaimer

The Lovesense project is in no way affiliated with Lovense or any of
its partners. The documentation and libraries here have been produced
via clean room reverse engineering methods, and are provided with no
guarantees, as outlined by the license agreement. Usage of these
libraries and information is in no way condoned by Lovense and may
void the warranty of your toy.

## License

Lovesense documentation is covered under
the
[Creative Commons 4.0 Attribution License](https://creativecommons.org/licenses/by/4.0/).
