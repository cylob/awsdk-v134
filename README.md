# ActiveWorlds Software Development Kit 7, Build 134 (Archived)
This SDK archive was requested and curated by members of the **ActiveWorlds modding and developer communities**, in recognition of the SDK’s importance in:

- Preserving the technical legacy of early virtual worlds development
- Supporting engineering, maintenance and preservation of historical and educational works
- Documenting the evolution of the ActiveWorlds platform

The **ActiveWorlds SDK** was first introduced in **1998**, enabling developers to create bots, tools, and services that interacted with the ActiveWorlds 3D virtual universe. Over the years, the SDK evolved through numerous versions, supporting the expansion of the platform and its community.

The SDK allows C/C++ developers to interact with the ActiveWorlds universe by managing avatars, objects, chat, events, and more via an external application or bot.

This particular build — **Version 7 Build 134** — represents one of the later SDK releases (pre-2021) before major changes were introduced to the platform.

### Deprecated SDK
This version is preserved **as-is** and is **not intended for use in current production environments**.

- **No longer supported by ActiveWorlds Inc.**
- **Incompatible with modern universe servers and browsers**
- **Useful for archival research, emulation, and modding legacy worlds**


## Why this archive exists
The Active Worlds Software Development Kit (SDK), first released on September 8th, 1998, is a Client-API (Application Interface for programming client applications) targeted at the programmer community within Activeworlds.

It provides an easy way for programmers to develop applications that function within the Active Worlds virtual environment. The most common type of application for the SDK is a bot (typically an avatar that inhabits a virtual world and interacts with users, but which is driven by a computer program instead of a human being), however there are many other potential applications. For example, the SDK could be used to develop an automated program that explores a world and creates a map. Also, the SDK allows universe administrators to develop administration utilities to help manage their own Active Worlds universes.

The core component of the SDK is the file aw.dll, a Windows DLL that implements the entire Active Worlds client/server protocol. To develop an application using the Active Worlds SDK, a programmer simply writes a C program which includes the header file aw.h and links to the import library aw.lib. The compiled executable can be run from any PC anywhere as long as that PC has a network connection to the Active Worlds Universe and aw.dll is available on that PC.

**SDK Versions**

The standard C/C++ and PHP/COM versions of the SDK are available. The SDK can be loaded directly from script engines like Python, node.js, PHP, and many more without a wrapper.


First time users of the SDK should start by downloading the version of the SDK appropriate for them, then reading over these help files and reviewing the sample programs.(1)(2 and PHP)

> This repository serves as a **community archive** of the **ActiveWorlds Software Development Kit (SDK) Version 7 Build 134**, originally released by ActiveWorlds Inc.  
> **This version is not compatible with the current ActiveWorlds platform** and is preserved here for **historical reference and modding community use**.

---

## Contents

| File         | Description |
|--------------|-------------|
| `AW.DLL`     | Core SDK dynamic-link library. Must be in the same directory as your app. |
| `AW.LIB`     | Import library used at link time in C++ projects. |
| `AW.H`       | SDK C/C++ header. Include in any source files accessing the SDK. |
| `LICENSE.TXT`| Original license agreement. Use of the SDK implies acceptance. |
| `README.TXT` | Original plaintext README from the SDK release. |
| `README.md`  | This file — a GitHub-friendly version with historical context. |

## Version compatibility

- Compatible with: ActiveWorlds 3D Browser 4.1 and later (as of release)
- Backward compatible with: Build 65 and newer
- Incompatible with modern ActiveWorlds universes (post-2021)

##  Legacy Setup (for reference only)

If you are exploring the SDK for archival or educational purposes:

1. **Include the Header**
   ```c
   #include "aw.h"
   ```

---

## License

This SDK was copyrighted by ActiveWorlds Inc.
You should read and agree to the terms in LICENSE.TXT before using the SDK, even in historical or educational contexts.

## Community & Preservation

This repository is maintained by the community as a historical archive and modding reference. It is not affiliated with or endorsed by ActiveWorlds Inc.

If you have additional SDK versions, bot source code, or documentation to contribute, consider submitting a pull request or opening an issue with your version a subdirectory named after the specific version.
