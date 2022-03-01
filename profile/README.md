## Windows file system and storage software

The WinFsp organization houses file system and storage solutions for use in Windows:

- The core project is [WinFsp](https://github.com/winfsp/winfsp), which is a complete file system solution that offers a Windows developer the ability to programmatically create Windows "drives" (file system volumes) that contain files that are backed up by a storage of the developer's choosing.

- The related [WinSpd](https://github.com/winfsp/winspd) project is similar to WinFsp, but instead of presenting itself as a file system to Windows it presents itself as a "disk" (block storage), which can be formatted using a standard file system (e.g. NTFS).

WinFsp and WinSpd are open source software, but also offer a commercial licensing option. Please contact Bill Zissimopoulos \<billziss at navimatics.com> for details.

## Cross-platform file system and storage software

A number of cross-platforms file system solutions are also provided. The core cross-platform project is [cgofuse](https://github.com/winfsp/cgofuse) which is MIT licensed and allows a file system (FUSE) developer to develop file systems in Go that can run on Windows, macOS, Linux, FreeBSD, NetBSD, OpenBSD.
