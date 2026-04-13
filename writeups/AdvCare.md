# file
name - "AdvCare.sys"
hash (SHA256) - "697D3E6D215D1ED6DC2465334502DB92E0CA77AD0B8392C945AC9E0F36509666"
size (bytes) - 21,200

# signer
certificate name - "Advantech Co., Ltd."

# device & symbolic
device name - "\\Device\\AdvCare"
symbolic link - "\\DosDevices\\AdvCare"

# ioctl codes
0x9C40283C - read port data
0x9C402840 - write port data

0x9C402844 - get bus data
0x9C402848 - set bus data

0x9C40284C - read physical memory
0x9C402850 - write physical memory

0x9C402854 - read msr
0x9C402858 - write msr

# imports

* ntoskrnl.exe
IofCompleteRequest
IoIs32bitProcess
IoCreateSymbolicLink
IoCreateDevice
strncmp
MmMapIoSpace
MmUnmapIoSpace
ExAllocatePool
ExFreePoolWithTag
RtlInitUnicodeString
ObfDereferenceObject
IoWMIQueryAllData
IoWMIOpenBlock
IoDeleteSymbolicLink
IoDeleteDevice

* HAL.dll	
HalGetBusDataByOffset
HalSetBusDataByOffset