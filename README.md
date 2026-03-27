# camport3_halcon_gentl
This software development kit provides GenTL Producer for Halcon to use Percipio Cameras.

## Documents
Please refer to [https://doc.percipio.xyz/cam/latest/getstarted/sdk-halcon-compile.html](https://doc.percipio.xyz/cam/latest/getstarted/sdk-halcon-compile.html) for more details.

## Halcon GenTL Producer Files
```
+-win_x64/percipio.cti       Implementation of Percipio GenTL Producer for windows x64
+-linux_x64/percipio.cti     Implementation of Percipio GenTL Producer for linux x64
+-halcon_samples             sample script in Halcon
+-Release.log                Release log for this repo 
```

## Supported Platform
Halcon 18.11 or later on windows-x64

## Run Samples
1. install Halcon on Windows-x64 (version 18.11 or later)
2. set cti path to environment variable GENICAM\_GENTL64\_PATH, then reboot to make it effect
3. double-click the script in the samples folder, then click the run button
