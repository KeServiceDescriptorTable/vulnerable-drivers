# file
name - "energydriver.sys"
hash (SHA256) - "6665B05E6FD430B729326A0B125CFCB70C387DBEE46EF3F768F7DBDF0E0A6BAB'
size (bytes) - 18,544

# signer
certificate name - "Microsoft Windows Hardware Compatibility Publisher"

# device & symbolic
device name - "\\Device\\EnergyDriver"
symbolic name - "\\DosDevices\\EnergyDriver"

# ioctl codes

0x22E002 - read msr
0x22E00E - write msr
0x22E016 - read physical memory

# imports

* ntoskrnl.exe		
RtlInitUnicodeString
DbgPrint
KeRevertToUserAffinityThreadEx
KeSetSystemGroupAffinityThread
KeRevertToUserGroupAffinityThread
KeSetSystemAffinityThreadEx
KeQueryActiveProcessorCountEx
KeGetProcessorNumberFromIndex
MmMapLockedPagesSpecifyCache
MmMapIoSpace
MmUnmapIoSpace
IofCompleteRequest
IoCreateDevice
IoCreateSymbolicLink
IoDeleteDevice
IoDeleteSymbolicLink
__C_specific_handler