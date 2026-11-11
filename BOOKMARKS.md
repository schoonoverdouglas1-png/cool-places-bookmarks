# Cool Sites Bookmarks — Emulators and Old Code
Saved 2026-11-11 at Douglas's direction ("make certain to bookmark all these sites that you visited that are cool for later").
These are the sites Ember actually visited/used in the Nov 11, 2026 emulator sessions. A bookmark file in the workspace is the verified copy; browser-native bookmarks are not agent-verifiable from here.

## Ran live today
- PC DOS 1.00 — PCjs Machines: https://www.pcjs.org/software/pcx86/sys/dos/ibm/1.00/
  (DOS 1.00, DIR with 38 files, VER answers "Bad command or file name", BASIC.COM + BASICA.COM on the disk)
- PC DOS 2.00 — PCjs Machines: https://www.pcjs.org/software/pcx86/sys/dos/ibm/2.00/
  (DOS 2.00, DIR with volume line + bytes-free footer, VER works, BASICA A2.00 ran PRINT 2+2 = 4 and the HELLO loop; TEST.BAS saved, DELeted, gone)
- PCjs Machines (home of the DOS machines): https://www.pcjs.org
- Cray-1 — emulators.org: https://emulators.org/emulator/cray-1/
  (in-browser Cray-1, CC0, boots running "Vector add & dot product"; pause "." / resume "R" / single-step "S" keys; debugger with breakpoints)
- Emulators Online (the full hall of browser emulators): https://emulators.org/online/

## Code we pulled and read
- Microsoft MS-DOS source (GitHub, official): https://github.com/microsoft/MS-DOS
  (v1.25 = 7 source files; v2.0 tree incl. DEV.ASM / DEVDRIV.txt — the device-driver bridges; also cloned to ~/workspace/ember-upgrades/dos-basic-study-2026-11-11/)
- Microsoft GW-BASIC source (GitHub, official): https://github.com/microsoft/GW-BASIC
- Computer History Museum — Microsoft MS-DOS early source code: http://www.computerhistory.org/atchm/microsoft-ms-dos-early-source-code

## Found, queued for the emulator work-through (Microsoft + Cray first, per Douglas's commission)
- CrayCore — CRAY YMP-EL emulator: https://ccore.sourceforge.net/
- Hackaday — Running Cray OS and UNICOS on your own Cray simulator instance (Andras Tantos's simulator, X-MP/Y-MP/J90/SV1): https://hackaday.com/2023/01/23/running-cray-os-and-unicos-on-your-own-cray-simulator-instance/
- AOSP TerminalApp source (the Android Linux Terminal, packages/modules/Virtualization): listed in ~/workspace/google-open-source-connector/FORKS.md

[Ember's note] Rule that goes with this list, Douglas's own: sandbox everything in the browser where possible — in these places you can't hurt anything, and it's free and faster.
