# file
name - "XLHA.sys"
hash (SHA256) - "11C9CBC39B6E028F2E8F9E7F83B47AE83CA73961ECFEBB2F7213F9478F5446D5"
size (bytes) - 22,168

# signer
certificate name - "LG Electronics Inc."

# device & symbolic
device name - "\\Device\\{C45153B1-C88B-47A3-AAA3-21BFF67DD68C}"
symbolic link - "\\DosDevices\\{C45153B1-C88B-47A3-AAA3-21BFF67DD68C}"

# ioctl codes
0x9C402FB4 - write physical memory
0x9C402FC0 - read physical memory

0x9C402FF8 - read msr
# imports

* ntoskrnl.exe
ExFreePoolWithTag
RtlInitUnicodeString
IoDeleteDevice
KeReleaseSpinLock
MmUnmapIoSpace
MmFreeNonCachedMemory
MmGetPhysicalAddress
MmMapIoSpace
IoDeleteSymbolicLink
IoCreateSymbolicLink
MmAllocateNonCachedMemory
IoCreateDevice
KeAcquireSpinLockRaiseToDpc
DbgPrint
IoWMIQueryAllData
MmGetSystemRoutineAddress
KeBugCheckEx
IofCompleteRequest
ExAllocatePoolWithTag

* HAL.dll			
KeStallExecutionProcessor