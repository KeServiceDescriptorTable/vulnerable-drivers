# File
* name - `UDDB2B6.sys`
* hash (SHA256) - `9AF0B89C5C54EB66E5A660B61AEE7C1A25B1C92E20A310D8B16552ABCF90C0B5`
* size (bytes) - 51,392

# Signer(s)
* `TechPowerUp LLC`
* `Microsoft Windows Hardware Compatibility Publisher`

# Device & Symbolic Link
* device name - `\\Device\\UDDB2B6`
* symbolic link - `\\DosDevices\\UDDB2B6`

# IOCTL Codes
* I/O Port Read: `0x80006430`
* I/O Port Write: `0x80006434`
* MSR Read: `0x80006448`
* MSR Write: `0x8000644C`
* MmMapIoSpace (map only): `0x8000645C`
* MmUnmapIoSpace (unmap only): `0x80006460`
* Mapping/handle reference: `0x80006494`
* Physical Memory Read (MmMapIoSpace): `0x80006498`
* Physical Memory Write (MmMapIoSpace): `0x8000649C`
* PCI Read: `0x800064A0`
* PCI Write: `0x800064A4`


# Imports
**HAL**		
* HalGetBusDataByOffset
* HalSetBusDataByOffset

**ntoskrnl**		
* _vsnwprintf
* RtlInitUnicodeString
* IoDeleteDevice
* RtlCopyUnicodeString
* IoDeleteSymbolicLink
* IoRegisterShutdownNotification
* ExAllocatePoolWithTag
* IoUnregisterShutdownNotification
* ExFreePoolWithTag
* IofCompleteRequest
* IoCreateSymbolicLink
* wcsrchr
* __C_specific_handler
* MmBuildMdlForNonPagedPool
* IoAllocateMdl
* MmMapIoSpace
* MmUnmapIoSpace
* PsGetCurrentProcessId
* IoFreeMdl
* MmUnmapLockedPages
* MmMapLockedPagesSpecifyCache
* MmGetSystemRoutineAddress
* RtlFreeUnicodeString
* IoCreateDevice
* ZwClose
* ObOpenObjectByPointer
* ZwSetSecurityObject
* IoDeviceObjectType
* _snwprintf
* RtlLengthSecurityDescriptor
* SeCaptureSecurityDescriptor
* RtlCreateSecurityDescriptor
* RtlSetDaclSecurityDescriptor
* RtlAbsoluteToSelfRelativeSD
* IoIsWdmVersionAvailable
* SeExports
* wcschr
* _wcsnicmp
* RtlLengthSid
* RtlAddAccessAllowedAce
* RtlGetSaclSecurityDescriptor
* RtlGetDaclSecurityDescriptor
* RtlGetGroupSecurityDescriptor
* RtlGetOwnerSecurityDescriptor
* ZwOpenKey
* ZwCreateKey
* ZwQueryValueKey
* ZwSetValueKey
* KeBugCheckEx