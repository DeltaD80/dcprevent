DCPrevent (Universal) prevents illegitimate mouse clicks.

This build auto-detects the Minecraft Bedrock version at runtime. It is confirmed on
1.26.13, 1,26,20, 1.26.21, 1.26.31 and 1.26.32, and will attempt to self-resolve on other
versions automatically.

IMPORTANT - ALWAYS CHECK THE CONSOLE/LOG ON A NEW VERSION:
When you run it, the console (and dcprevent.log) prints one of:
  [DCPrevent] handler resolved via pin 1.26.xx   <- known version, exact
  [DCPrevent] handler resolved via scan (consensus N/M)  <- new version, self-resolved
  [DCPrevent] could not resolve handler ... unsupported or changed MC version
If you see "could not resolve", DCPrevent is NOT active on that version. Do not assume you are protected unless you
see a "resolved via pin" or "resolved via scan" line AND your click data appears.

TO USE:
1. Extract the zip file.
2. Open Minecraft.
3. Run the DCPrevent-v2.exe file.

Closing the .exe/cmd prompt window or closing Minecraft turns off DCPrevent. You must
run the exe again in order to turn it back on.

LOGGING:
You can see your live click data in the cmd prompt window.
Pressing ";" saves your current click data to /logs.
Closing the .exe or Minecraft window writes session click data to /logs.
dcprevent.log updates click data live and is never auto-deleted.

IMPORTANT NOTES:
Do not rename the dll or exe.
Do not move the dll or exe into different folders.
Do not place other dlls into this folder.
Do not move or delete the logs folder.

SHA-256 (official releases):

DCPrevent-Universal.dll:
ab69662ccf9c878cfd492aede31ed7724840971ca1a85c19860e6a0fc1161c3f

DCPrevent-v2.exe:
488715d397c5651b1cc7d119ba5241a402c2ec8d3f27ef034e871cd155a7a553
