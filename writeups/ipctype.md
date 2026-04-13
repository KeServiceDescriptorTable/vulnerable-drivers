# file
name - "ipctype.sys"
hash (SHA256) - "8E2ACCE10D704C8B511C8B6211A2BE5D8E4ADE91EBCBDA2AC10018E4C0AE99FB"
size (bytes) - 14,096

# signer
certificate name - "Digital Electronics Corporation"

# device & symbolic
device name - "\\Device\\IPCType"
symbolic link - "\\DosDevices\\IPCType"

# ioctl codes
0x80102040 - map physical memory into usermode
0x80102044 - unmap physical memory from usermode

# imports

* ntoskrnl.exe
MmUnmapLockedPages
ExAllocatePoolWithTag
IoDeleteSymbolicLink
RtlInitUnicodeString
IoDeleteDevice
IoIs32bitProcess
MmUnmapIoSpace
MmBuildMdlForNonPagedPool
IoFreeMdl
MmMapLockedPagesSpecifyCache
ExFreePool
MmMapIoSpace
IofCompleteRequest
IoCreateSymbolicLink
IoCreateDevice
IoAllocateMdl
KeBugCheckEx
__C_specific_handler