# epics-opi

This repo includes epics OPI for different modules, every folder contains two sub-folders, `local` and `upstream` (optional). I use this for test.

## test
some test opi

## mrfioc2
Based on the OPI files from this commit [epics-modules/mrfioc2](https://github.com/epics-modules/mrfioc2/commit/28d3076424c70e6a348944fcbd77d4f746e1cd4f)

#### Supported HW
- EVM-MTCA-300 (Embedded EVR)
- EVR-MTCA-300U
- EVR-PCIE-300DC (TODO)

## picoscope
Based on [https://gitlab.esss.lu.se/icshwi/picoscope-opi](https://gitlab.esss.lu.se/icshwi/picoscope-opi)

## asyn
Based on asyn `R4-44-2`

## How to

- How to use `color.def`

Modify Phoebus setting

```ini
# On Windows, the path should be like this
org.csstudio.display.builder.model/color_files=C:/path/to/color.def
```
