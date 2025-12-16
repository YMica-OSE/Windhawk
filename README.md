> [!IMPORTANT]
> This version of Windhawk is intended for advanced users only.
> If you are a regular user and don't have a deeper knowledge of how Windhawk itself works, use [the official and original version](https://windhawk.net/) instead.

# Windhawk
...but its UI is rebuilt using modern VSCodium binaries.

---

The main focus of this fork is to replace the original UI which was built on a 32-bit and aging version of VSCodium, with one that's built on a more up-to-date and architecture native version of it. Obviously this means it won't work on Windows 7 and 8.x due to the newer Electron/Chromium backend. 

Additionally, I've done some extra changes to make the mod editing interface [a bit more developer-friendly](https://github.com/ramensoftware/windhawk/issues/774), and also coated the whole UI with a pure-black theme. 

Instructions on how to build this yourself will be added later. Technically any fork of VSCode (even the original) should work, so long as they can run the [extension](https://github.com/YMica-OSE/Windhawk/tree/main/src/vscode-windhawk) that drives Windhawk's entire front end.
