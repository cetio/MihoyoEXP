# MihoyoEXP

> [!Warning]
> Do not bother with trying to use this, the driver is guaranteed detected on any decent anticheat and will require being able to load an unsigned driver, as the certificate was revoked.
>
> **It would be simpler to do just about anything else, or use any other exposed driver.**

This is a highly outdated exploit library for Mhyprot2, the old Genshin Impact anticheat which was vulnerable to IOCTL commands from foreign sources due to horrible encryption and poorly engineered internals. 
This library, prior to around 2022 was capable of:

- Load driver without administrator privileges using Windows exploits
- Kernel level read and write
- Process enumeration
- Thread enumeration
- Pattern/signature scanning arbitrary memory
- Kernel dispatch and load/unloading kernel segments
