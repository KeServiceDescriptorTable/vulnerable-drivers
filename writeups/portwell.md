# file
name - "portwell.sys"
hash (SHA256) - "2F0B16ED90B8C15BF52A7C32699DBE0DBCD38FC02ED2DDB4E1BA35487177B6C5"
size (bytes) - 16,848

# signer
certificate name - "Portwell Inc."

# device & symbolic
device name - "\\Device\\PORTWELL_0_1"
symbolic link - "\\DosDevices\\PORTWELL_0_1"

# ioctl codes
0xEA60A454 - write physical memory
0xEA606450 - read physical memory

0xEA606458 - get bus data
0xEA60A45C - set bus data

0xEA602408 - read msr
0xEA60240C - write msr
0xEA602410 - read pmc

0xEA60A440 - read port
0xEA60A444 - read port
0xEA60A460 - read port

0xEA60A464 - write port
0xEA60A468 - write port
0xEA60A470 - write port

# imports

* ntoskrnl.exe
MmUnmapIoSpace
MmMapIoSpace
IofCompleteRequest
IoCreateSymbolicLink
IoDeleteDevice
RtlAssert
DbgPrint
KeBugCheckEx
RtlInitUnicodeString
IoCreateDevice
IoDeleteSymbolicLink
__C_specific_handler

* HAL.dll
HalSetBusDataByOffset
HalGetBusDataByOffset

**Credits:**
- https://github.com/RainbowDynamix
- https://github.com/KeServiceDescriptorTable
- https://x.com/DbgPrint
- https://x.com/rainbowdynamix