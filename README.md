# OWON-SDS1022-Instrument-Driver
Inofficial LabVIEW Instrument Driver for OWON SDS1022 created with LV2023.

Implemented:
Initialize, Close
Configure: Channel, Timebase, Autosetup, Averaging, Acquisition Mode, Cont Acqu, Edge Trigger, Memory Depth
Data: Read Waveform Singe & Multiple, Read BMP, Read Deep Memory

Unfortunately the scope does not send complete set of deep memory and bmp after query. IMHO this is an error in OWON's device firmware.

Despite mentioned in SDS1000_Oscilloscopes_SCPI_Protocol.pdf, the device firmware does not support other IEEE488.2 commands than *RST and *IDN?

## Requirements

JDP JSONtext

## Install
Unzip OWON SDS1022.zip to pathToLabVIEW/instr.lib


