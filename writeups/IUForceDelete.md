# file
name - "IUForceDelete.sys"
hash (SHA256) - "30F5D03E37D22C7DECE8BB8240EDC8566F2BE7FE76D3C7F97EECEB60D889EE06'
size (bytes) - 21,080

# signer
certificate name - "Microsoft Windows Hardware Compatibility Publisher"

# device & symbolic
device name - "\\Device\\IUForceDelete123"
symbolic name - "\\DosDevices\\IUForceDelete123"

# ioctl codes

0x8016E000 - force delete file

# imports

* ntoskrnl.exe		
ExAllocatePoolWithTag
ExFreePoolWithTag
ZwReadFile
MmGetSystemRoutineAddress
ZwCreateFile
ExAllocatePool
IoGetCurrentProcess
ZwClose
ZwQueryInformationFile
ObOpenObjectByPointer
IoDeleteSymbolicLink
IoGetRelatedDeviceObject
RtlInitUnicodeString
IoDeleteDevice
KeSetEvent
IoCreateFile
KeInitializeEvent
IoFileObjectType
RtlPrefixUnicodeString
IofCompleteRequest
ObReferenceObjectByHandle
KeWaitForSingleObject
IoFreeIrp
IoAllocateIrp
IoCreateSymbolicLink
ObfDereferenceObject
IoCreateDevice
DbgPrint
IofCallDriver
KeBugCheckEx