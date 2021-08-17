install dotnet 5.0 SDK

connect board in BOOTLOADER mode
 
use Zadig to update WinUSB drivers

in priviledged CMD:
>dotnet --list-sdks
>dotnet tool install WIldernessLabs.Meadow.CLI --global
>meadow install dfu-util
>meadow download os
>meadow install os
- connecting to COM 6
....Lots of teal info
  ..download
  ..flashing
Mono runtime successfully flashed.
Transferring 
   MeadowComms.bin, 
   bootloader.bin
   partition-table.bin
Updated Meadow to OS: 0.5.1.0 (Jun 19 2021 01:49:23)

In VS2019 install extension 'Meadow'
Ensure 4.7.2 SDK and targetting pack individual components
Create new Meadow App
Ensure nuget packages are the latest Meadow.F7 and Meadows.Foundation
