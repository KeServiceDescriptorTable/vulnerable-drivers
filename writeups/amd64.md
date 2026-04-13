# file
name - "amd64.sys"
hash (SHA256) - "2BC72D11FA0BEDA25DC1DBC372967DB49BD3C3A3903913F0877BFF6792724DFE'
size (bytes) - 24,768

# signer
certificate name - "Cybelsoft"
certificate name - "Microsoft Windows Hardware Compatibility Publisher"

# device & symbolic
device name - "\\Device\\DriversCloud_amd64"
symbolic name - "\\DosDevices\\DriversCloud_amd64"

# ioctl codes

0x80FF2000 - read port data
0x80FF2004 - write port data

0x80FF2008 - get bus data
0x80FF2020 - set bus data

0x80FF2010 - read physical memory

0x80FF2024 - read msr
0x80FF2040 - write msr

# imports
* ntoskrnl.exe
IoDeleteSymbolicLink
RtlInitUnicodeString
IoDeleteDevice
IofCompleteRequest
MmMapIoSpace
IoCreateSymbolicLink
IoCreateDevice
KeBugCheckEx
MmUnmapIoSpace
__C_specific_handler

* HAL.dll
HalSetBusDataByOffset
HalGetBusDataByOffset