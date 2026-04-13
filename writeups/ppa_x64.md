# file
name - "ppa_x64.sys"
hash (SHA256) - "988960E31A258EA71CF93A7791AE8C91C8CEFB6AD8A50CDBD1B07F73B524AA61"
size (bytes) - 15,560

# signer
certificate name - "Remko Weijnen"

# device & symbolic
device name - "\\Device\\PhyMem"
symbolic link - "\\DosDevices\\PhyMem"

# ioctl codes
0x80002000 - map physical memory to usermode
0x80002004 - unmap physical memory from usermode

0x80002008 - read port
0x8000200C - write port

# imports

* ntoskrnl.exe		
KeWaitForSingleObject
IofCallDriver
IoBuildSynchronousFsdRequest
KeInitializeEvent
IoDeleteDevice
IoCreateSymbolicLink
IoCreateDevice
RtlInitUnicodeString
ExAllocatePool
IofCompleteRequest
ExFreePoolWithTag
IoFreeMdl
MmUnmapLockedPages
MmUnmapIoSpace
MmMapLockedPages
MmBuildMdlForNonPagedPool
IoAllocateMdl
MmMapIoSpace
IoDeleteSymbolicLink
MmMapLockedPagesSpecifyCache
IoGetDeviceObjectPointer