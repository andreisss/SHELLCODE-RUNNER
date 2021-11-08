# SHELLCODE-RUNNER

/*	SIMPLE SHELLCODE RUNNER
description: 

	--------------------
	Injects shellcode into the current process.
     ey win32 API calls:
      - kernel32.dll:
        1: 'VirtualAlloc'
        2: 'CreateThread'
        3: 'WaitForSingleObject (WAIT_FAILED)'
