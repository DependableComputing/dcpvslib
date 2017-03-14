## Overview ##

This repository contains four libraries:

* measurements: The measurements library is designed to facilitate automatic
dimensional analysis by PVS.

* meas2: This library is the same as the measurements library but uses
templates for tracking systems of measurement

* extensions: This library mainly focuses on lookup tables

* ext2: This is an alternate version of extensions that uses structures
for representing lookup tables - expect it to be slower than extensions

## Use ##

To use the Dependable Computing library, you will need to adjust your
`PVS_LIBRARY_PATH` to:

    <path-to-nasalib>:<path-to-dcpvslib>

