## FlavoredProject

A test project containing different flavors and variants intended for testing the [build-variant-matrix](https://github.com/Nilzor/build-variant-matrix) plugin

The project contains the following modules with the following flavors-build-variant setups:

|Module|Dimension1|Dimension2|BuildTypes|
|---|---|---|
|:app|dev/qa/prod|-|debug/release|
|:bravo|dev/qa/prod|-|debug/release|
|:bravo:SubBravo|-|-|debug/release|
|:libmodule|dev/qa/prod|free/paid|debug/release|
|:libplain|-|-|debug/release|