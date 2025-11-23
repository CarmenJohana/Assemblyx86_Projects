# Different types of memory locations

For NASM the main types of memory locations are:

	- db
		Data bytes take up 8 bits (1 byte). It's limited to numbers between 0 and 255.
	
		This directive is also used to enter characters into memory. The directive recognizes:
			
			- Single quotes '' <- Strings enclosed is this way support C-style escape sequences

				Example: db 'Hello world\0' (which is equivalent to "Hello world", 0

			- Double quotes ""
			- Backquotes ``
			
	
	- dw
		Data words take up 16 bits

	- dd
		
		
