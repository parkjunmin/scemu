# TODO

- clear breakpoint bug
- md accept registers
- md memory check the string filter
- mr mw options can crash the console
- fix instruction breakpoint 
- more apis
- in self.execption() put a message self.exception(msg)
- improve seh command
- better api implementations
- change xmm to f128
- winhttp
- implement a basic decompiler in rust.
- remove expect() on implemented instructions, just break;
- stack_push and stack_pop assumes the stack is in the memory map stack
- step over
- more fpu and xmm
- on WriteProcessMemory/recv save the payload written to disk
- stack command more clever and command v
- remove non printable bytes from strings
- set the entry point
- randomize initial register for avoid targeted anti-amulation
- support guloader
- scripting
- intead of panic spawn console
- set the code base addr
- on every set_eip of a non branch dump stack to log file
- implement scas & rep on movz and others.
- check pf flag bug
- save state to disk and continue
- command to exit the bucle or to see  next instruction
- optimize loop counter
