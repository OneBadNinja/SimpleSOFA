<img src='https://onebadninja.github.io/sofasonix/images/logo.png' width="50%">

![Python](https://img.shields.io/badge/Python%20Support-2.7%2C%203.4%2C%203.5%2C%203.6%2C%203.7-green.svg)
![License](https://img.shields.io/badge/License-BSD%203-orange.svg)

SOFASonix is an advanced Python API for the Spatially-Oriented Format for Acoustics (SOFA Format) as defined by AES69-2015 - www.sofaconventions.org.

SOFASonix was initially developed as a supplementary tool for usage alongside an undergraduate project at Southampton University's Institute of Sound and Vibration Research (ISVR). The enhanced and refined version of this is now the official SOFASonix API.

## Features

- Support for the majority of [standardised and stable SOFA conventions](#supportedConventions).
- Reading/Writing of SOFA Files for each of the supported conventions.
- Built-in **convention-specific validation** to ensure correct file format for export!
- Powered by the lightweight and powerful SQLite3, providing support for different versions of each convention.
- Simple syntax for quickly generating / reading SOFA files.

## Supported Conventions

<span id="supportedConventions">The following</span> conventions are currently supported by SOFASonix for reading and writing, as per the [SOFAConventions website](https://www.sofaconventions.org/mediawiki/index.php/SOFA_conventions):

|Convention|Version|SOFAConventionsVersion|
|---|---|---|
|GeneralFIR|1.0|1.0|
|GeneralTF|1.0|1.0|
||0.5|0.1|
|SimpleFreeFieldHRIR|1.0|1.0|
||0.6|0.4|
||0.5|0.3|
|GeneralFIRE|1.0|1.0|
||0.6|0.1|
|MultiSpeakerBRIR|1.0|0.3|
||0.6|0.2|
||0.6|0.1|
|SimpleHeadphoneIR|1.0|0.2|
||0.6|0.1|
||0.5|0.1|
|SimpleFreeFieldTF|1.0|1.0|
||0.6|0.4|
|SimpleFreeFieldSOS|1.0|1.0|
|SingleRoomDRIR|1.0|0.3|
|SingleRoomDRIR|0.5|0.1|

**Note:** While some of these versions are deprecated according to [SOFAConventions](http://www.sofaconventions.org), they have been included to maintain backwards compatibility for both older SOFA files and older applications that may be using them. It is always recommended to use the latest versions for generating files for storage.

## Documentation
SOFASonix documentation and example usage is available over at the [SOFASonix Wiki page](https://github.com/OneBadNinja/SOFASonix/wiki).

## Contribute
You may contribute any improvements and fixes via regular pull-requests. These will be reviewed as per standard procedure before integration.

## License
SOFASonix is licensed under BSD-3 - see the LICENSE.md file for details. Alternatively you may visit https://opensource.org/licenses/BSD-3-Clause

## Authors
I.G Laghidze (Founder) - developer@artisan-one.com
