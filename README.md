# WCB aliased seabed  - Sample Simrad EK60 echo sounder data

![Lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)

## Introduction

This Simrad EK60 sample data set, recorded in the Western Core Box,
north west of South Georgia, is provided by [The British
Antarctic Survey](https://www.bas.ac.uk/) for the purposes of software
and tools experimentation and comparison.

The data were collected during cruise JR304 in December 2014 and have
been selected as a exemplar of the problem of aliased seabed.

## Data

The `JR304-metadata.toml` contains metadata and
`ZDLP-D20141202-cal.toml` calibration in [TOML
format](https://github.com/toml-lang/toml). The data files are
provided in [Simrad EK60 RAW
format](https://www.simrad.net/ek60_ref_english/default.htm) via the BAS
FTP site at
`ftp://ftp.bas.ac.uk/rapidkrill/jr304/`.

Several open source file readers exist, including those for
[Python](https://github.com/CI-CMG/pyEcholab) and
[Julia](https://github.com/EchoJulia/SimradEK60.jl).


## Acknowledgements

Our thanks to the officers, crew and scientists onboard the RRS James
Clark Ross for their assistance in collecting the data. The Western
Core Box cruises and SF are funded as part of the Ecosystems Programme
at the British Antarctic Survey, Natural Environment Research Council,
a part of UK Research and Innovation.

This work was supported by the Antarctic Wildlife Research Fund and
the Natural Environment Research Council grant NE/N012070/1.

## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

## Contact
[rapidkrill@bas.ac.uk](mailto:rapidkrill@bas.ac.uk)
