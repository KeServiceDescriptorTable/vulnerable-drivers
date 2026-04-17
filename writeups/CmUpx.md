# file
name - "CmUpx.sys"
hash (SHA256) - "CDF38928A13DFE0E6DE054F0229945B9F7DB9F88EB7269ECEFDCEB4B5FAB4BFA'
size (bytes) - 30,184

# signer
certificate name - "Realtek Semiconductor Corp."
certificate name - "Microsoft Windows Hardware Compatibility Publisher"

# device & symbolic
device name - "\\Device\\CmUpx"
symbolic name - "\\DosDevices\\CmUpx"

# ioctl codes

0x222800 - read physical memory
0x222804 - write physical memory

# imports

* ntoskrnl.exe
RtlInitUnicodeString
KeInitializeEvent
KeWaitForSingleObject
KeAcquireSpinLockRaiseToDpc
KeReleaseSpinLock
ExAllocatePoolWithTag
ExFreePoolWithTag
MmProbeAndLockPages
MmUnlockPages
MmBuildMdlForNonPagedPool
MmMapLockedPagesSpecifyCache
MmUnmapLockedPages
MmMapIoSpace
MmUnmapIoSpace
IoAllocateMdl
IoBuildDeviceIoControlRequest
IoBuildSynchronousFsdRequest
IofCallDriver
IoCancelIrp
IofCompleteRequest
IoCreateDevice
IoCreateSymbolicLink
IoDeleteDevice
IoDeleteSymbolicLink
IoFreeMdl
IoGetDeviceObjectPointer
IoGetRelatedDeviceObject
ObReferenceObjectByHandle
ObfDereferenceObject
ObQueryNameString
FsRtlIsNameInExpression
__C_specific_handler
IoFileObjectType

* HAL.dll
KeStallExecutionProcessor