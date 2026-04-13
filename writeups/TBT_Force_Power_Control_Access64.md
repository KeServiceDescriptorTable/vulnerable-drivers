# file
name - "TBT_Force_Power_Control_Access64.sys"
hash (SHA256) - "4C776F34C6042D943BAEC3C13D7154A245AAE8DD95E1933211FD19352C770676"
size (bytes) - 15,400

# signer
certificate name - "Wistron Corporation"

# device & symbolic
device name - "\\Device\\TEACCESS"
symbolic link - "\\DosDevices\\TEACCESS"

# ioctl codes

0x222010 - port read
0x222014 - port read
0x222018 - port read

0x22201C - port write
0x222020 - port write
0x222024 - port write

0x222000 - map physical memory to usermode
0x222004 - unmap physical memory from usermode

0x222028 - get bus data
0x22202C - set bus data

0x222030 - read msr
0x222034 - write msr

# imports

* ntoskrnl.exe	
MmFreeContiguousMemory
MmUnmapIoSpace
MmGetPhysicalAddress
MmMapIoSpace
IoDeleteDevice
IoCreateSymbolicLink
IoCreateDevice
MmAllocateContiguousMemory
KeBugCheckEx
RtlInitUnicodeString
IofCompleteRequest
IoDeleteSymbolicLink

* HAL.dll		
HalSetBusDataByOffset
HalGetBusDataByOffset