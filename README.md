# WSLRegisterDistribution-Failed-with-Error-0x8007019e
WSLRegisterDistribution Failed with Error: 0x8007019e



wsl --install

dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart

dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart

wsl --set-default-version 2
