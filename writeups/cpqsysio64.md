# file
name = "cpqsysio64.sys"
hash (SHA256) - "4024B090CEBCABAAB884C84EC80FFB15622D12632F236383A9B0A470BFF9FE33"
size (bytes) - 15,168

# signer
certificate name - "Hewlett-Packard Company"

# device & symbolic
device name - "\\Device\\cpqsysio"
symbolic link - "\\DosDevices\\cpqsysio"

# ioctl codes
0x152EF0 - read physical memory
0x153E80 - allocate & map physical memory to usermode
0x153E84 - free & unmap physical memory from usermode

# imports

* ntoskrnl.exe	
IoDeleteSymbolicLink
RtlInitUnicodeString
IoDeleteDevice
MmFreeContiguousMemory
IofCompleteRequest
IoCreateSymbolicLink
IoCreateDevice
ZwMapViewOfSection
MmUnmapIoSpace
MmGetPhysicalAddress
ZwUnmapViewOfSection
MmMapIoSpace
ZwClose
ZwOpenSection
MmAllocateContiguousMemory
KeBugCheckEx