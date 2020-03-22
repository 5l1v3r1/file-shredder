# File Shredder

PowerShell script for shredding files.

If you have more than enough disk space, your files will most likely still be recoverable - even after shredding.

Have a good read about this topic [here](https://www.streetdirectory.com/travel_guide/124464/hardware/understanding_file_shredding_and_the_wipe_disk_process.html).

Tested with PowerShell v5.1.18362.628 on Windows 10 Enterprise OS (64 bit).

Made for educational purposes. I hope it will help!

## How to Run

To start the PowerShell, run the following command from your Command Prompt:

```batch
START PowerShell -ExecutionPolicy Unrestricted -NoProfile
```

To execute the script, run the following command from your PowerShell:

```pwsh
& .\file_shredder.ps1 .\somefile.txt
```
 
 ## Images

![Shredding](https://github.com/ivan-sincek/file-shredder/blob/master/img/shredding.jpg)
