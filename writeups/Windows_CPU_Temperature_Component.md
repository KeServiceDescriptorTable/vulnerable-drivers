# file
* name - "Windows CPU Temperature Component(SW).sys"
* hash (SHA256) - "4CEA52C32579869D0209F18CED0B9CC9AD8F86CAC29E0FB63B3D60EB64801BDA'
* size (bytes) - 36,864

# signer
* certificate name - "Guangzhou Shirui Electronics Co., Ltd."
* certificate name - "Microsoft Windows Hardware Compatibility Publisher"

# device & symbolic
device name - `\\Device\\WinRing0_1_2_0`
symbolic name - `\\DosDevices\\WinRing0_1_2_0`

# ioctl codes

* 0x9C406104 - Physical memory read (restricted `0xC0000`–`0xFFFFF`)

* 0x9C402084 - Read MSR
* 0x9C402088 - Write MSR

* 0x9C40208C - Read PMC

* 0x9C4060CC, 0x9C4060D0, 0x9C4060D4 - Read I/O Port (byte/word/dword)

* 0x9C40A0D8, 0x9C40A0DC, 0x9C40A0E0 - Write I/O Port (byte/word/dword)


# imports
**ntoskrnl**		
* IofCompleteRequest
* IoCreateDevice
* IoCreateSymbolicLink
* IoDeleteDevice
* MmUnmapIoSpace
* _vsnwprintf
* __C_specific_handler
* KeBugCheckEx
* MmMapIoSpace
* IoDeleteSymbolicLink
* RtlInitUnicodeString

**HAL**		
* HalSetBusDataByOffset
* HalGetBusDataByOffset