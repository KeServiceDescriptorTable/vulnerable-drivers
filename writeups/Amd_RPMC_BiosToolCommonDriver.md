# file
name - "Amd_RPMC_BiosToolCommonDriver.sys"
hash (SHA256) - "4E913A99B38ABEA038202C95C6BC5D8D866A6E2869101A14A05079235346D9A1"
size (bytes) - 48,248

# signer
certificate name - "Advanced Micro Devices Inc."
certificate name - "Microsoft Windows Hardware Compatibility Publisher"

# device & symbolic
device name - "\\Device\\BiosToolCommonDriver"
symbolic link - "\\DosDevices\\BiosToolCommonDriver"

# ioctl codes
0x22202C - read physical memory
0x222030 - write physical memory
0x222034 - get physical address
0x222038 - map physical memory
0x22203C - read msr
0x222040 - write msr
0x222044 - read port
0x222004 - read port
0x222048 - write port
0x222008 - write port
0x222028 - free contiguous memory
0x222024 - allocate contiguous memory
0x22200C - get bus data
0x222010 - set bus data

# imports

* ntoskrnl.exe
RtlVerifyVersionInfo	
IofCompleteRequest	
IoCreateSymbolicLink	
IoDeleteDevice	
IoDeleteSymbolicLink	
KeDelayExecutionThread	
VerSetConditionMask	
MmUnmapIoSpace	
MmAllocateContiguousMemory	
MmFreeContiguousMemory	
MmGetPhysicalAddress	
__chkstk	
DbgPrintEx	
MmMapIoSpace	
RtlInitUnicodeString	
MmGetSystemRoutineAddress	
ZwClose	
ZwSetSecurityObject	
IoDeviceObjectType	
IoCreateDevice	
ObOpenObjectByPointer	
RtlGetDaclSecurityDescriptor	
RtlGetGroupSecurityDescriptor	
RtlGetOwnerSecurityDescriptor	
RtlGetSaclSecurityDescriptor	
ExFreePoolWithTag	
SeCaptureSecurityDescriptor	
_snwprintf	
RtlLengthSecurityDescriptor	
SeExports	
RtlCreateSecurityDescriptor	
_wcsnicmp	
ExAllocatePoolWithTag	
wcschr	
RtlAbsoluteToSelfRelativeSD	
RtlAddAccessAllowedAce	
RtlLengthSid	
IoIsWdmVersionAvailable	
RtlSetDaclSecurityDescriptor	
ZwOpenKey	
ZwSetValueKey	
ZwQueryValueKey	
ZwCreateKey	
RtlFreeUnicodeString

* HAL.dll		
HalSetBusDataByOffset
HalGetBusDataByOffset