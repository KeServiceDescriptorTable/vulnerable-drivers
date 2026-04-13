# file 
name - "CardIo64.sys"
hash (SHA256) - "8A6265D23D30D6C4C7E159624686DE6DBF2CCB86A421B0F45510005F7A40CD1A"
size (bytes) - 13,104

# signer
certificate name - "ICP DAS Co., LTD."

# device & symbolic
Device Name - "\\Device\\CardIo"
Symbolic Link - "\\DosDevices\\CardIo"

# ioctl codes

0x80102040 - Read Physical Memory
0x80102044 - Write Physical Memory

0x80102054 - Write Port Data
0x80102058 - Write Port Data
0x8010205C - Write Port Data

0x80106048 - Read Port Data
0x8010604C - Read Port Data
0x80106050 - Read Port Data

0x80106060 - Get Bus Data
0x8010A064 - Set Bus Data

# imports

* ntoskrnl.exe
MmMapIoSpace
RtlInitUnicodeString
IoCreateSymbolicLink
IoCreateDevice
IoDeleteSymbolicLink
IofCompleteRequest
MmUnmapIoSpace
IoDeleteDevice

* HAL.dll
HalGetBusDataByOffset
HalSetBusDataByOffset