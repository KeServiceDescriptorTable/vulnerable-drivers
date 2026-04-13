# file
name - "SONiXDDRx64.sys"
hash (SHA256) - "85A4CE446D9CCD93C2F14D2E0F30EA673812CE740438ABB199A8047510614A76'
size (bytes) - 44,640

# signer
certificate name - "SONIX TECHNOLOGY CO., LTD."
certificate name - "Microsoft Windows Hardware Compatibility Publisher"

# device & symbolic
device name - "\\Device\\SONiXDDR_0_0_0_1"
symbolic name - "\\DosDevices\\SONiXDDR_0_0_0_1"

# ioctl codes

0x9C406684 - Physical memory read (restricted `:(`)

0x9C402118 - Read MSR
0x9C4024D4 - Write MSR

0x9C4021D4 - Read PMC

0x9C4065E0, 0x9C406080, 0x9C4064C8 - I/O Port Read
0x9C40A094, 0x9C40A158, 0x9C40A15C - I/O Port Write

0x9C4062AC - Read PCI
0x9C4040EC - Write PCI

# imports
* ntoskrnl.exe		
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
__C_specific_handler
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
IoDeleteSymbolicLink
IoDeleteDevice
IoCreateSymbolicLink
RtlCopyUnicodeString
DbgPrintEx
IofCompleteRequest
MmUnmapIoSpace
MmMapIoSpace
SeExports
RtlInitUnicodeString

* hal.dll		
HalSetBusDataByOffset
HalGetBusDataByOffset

* WDFLDR		
0000000140003018		WdfVersionBindClass
0000000140003020		WdfVersionBind
0000000140003028		WdfLdrQueryInterface
0000000140003030		WdfVersionUnbind
0000000140003038		WdfVersionUnbindClass