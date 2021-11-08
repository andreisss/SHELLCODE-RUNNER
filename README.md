# SHELLCODE-RUNNER

YoU can compile it using C:\Windows\Microsoft.NET\Framework\v4.0.30319 csc.exe with admin credentials.
csc.exe "C:\Users\Andrea\source\repos\ConsoleApp1\ConsoleApp1\Program.cs"


/*	SIMPLE SHELLCODE RUNNER
description: 

	--------------------
	Injects shellcode into the current process.
     ey win32 API calls:
      - kernel32.dll:
        1: 'VirtualAlloc'
        2: 'CreateThread'
        3: 'WaitForSingleObject (WAIT_FAILED)'
