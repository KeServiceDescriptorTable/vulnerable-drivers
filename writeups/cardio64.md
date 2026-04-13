# File
Name: "CardIo64.sys"
Hash (SHA256): 8A6265D23D30D6C4C7E159624686DE6DBF2CCB86A421B0F45510005F7A40CD1A
Size: 13,104 bytes

# Signer
Certificate Name: "ICP DAS Co., LTD."

# Device & Symbolic Link
Device Name:     "\\Device\\CardIo"
Symbolic Link:   "\\DosDevices\\CardIo"

# IOCTL Codes
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

# Imports

From ntoskrnl.exe:
- MmMapIoSpace
- RtlInitUnicodeString
- IoCreateSymbolicLink
- IoCreateDevice
- IoDeleteSymbolicLink
- IofCompleteRequest
- MmUnmapIoSpace
- IoDeleteDevice

From HAL.dll:
- HalGetBusDataByOffset
- HalSetBusDataByOffset