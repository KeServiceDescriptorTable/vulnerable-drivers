# file
name - "AsrCDDrv.sys"
hash (SHA256) - "04CC7DF4077E36199B04AFA39204C8F568F7F66F045E73010FB9B7685324442F'
size (bytes) - 16,904

# signer
certificate name - "ASROCK Incorporation"

# device & symbolic
device name - "\\Device\\AsrCDDrv"
symbolic name - "\\DosDevices\\AsrCDDrv"

# ioctl codes

0x222868 - read control register (cr0, cr2, cr3, cr4, irql)
0x22286C - write control register (cr0, cr3, cr4, cr8)

0x222848 - read msr
0x22284C - write msr

0x222834 - read physical memory
0x222838 - write physical memory

0x222858 - allocate contiguous memory
0x22285C - free contiguous memory

0x222800 - write port
0x222804 - write port
0x222808 - write port

0x22280C - read port
0x222810 - read port
0x222814 - read port

# imports
* ntoskrnl.exe
RtlInitUnicodeString
IoDeleteDevice
MmUnmapIoSpace
MmGetPhysicalAddress
MmMapIoSpace
MmFreeContiguousMemorySpecifyCache
IoCreateSymbolicLink
IoCreateDevice
MmAllocateContiguousMemorySpecifyCache
KeBugCheckEx
IofCompleteRequest
IoDeleteSymbolicLink

* HAL.dll		
KeStallExecutionProcessor