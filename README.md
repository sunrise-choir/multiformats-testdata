# Legacy Value Test Data

This repository contains test data for the ssb [multiformats](https://spec.scuttlebutt.nz/datatypes.html).

There's a directory for each format, and each of them contains subdirectories `yay` and `nay`. A correct parser must accept all data in the `yay` directories, and reject all data in the `nay` directories.

The data has been generated by fuzzing the rust implementation of these formats.
