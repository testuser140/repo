# LilyOfTheValley

LilyOfTheValley is a simple LKM linux kernel rootkit for kernel versions 4.X/3.X (works on x86 and x86_64)

## Features

* hiding processes
* hiding files
* hiding itself 
* granting root privileges

## Usage

[ Available Commands ] 

<br />

to see the currently supported commands use <code> cat /proc/lilyofthevalleyr00tkit <code/> 



[ Hiding Processes ] 

<br />

write <code> HideMe <code/> to <code> /proc/lilyofthevalleyr00tkit <code/> to hide your process.

<br />

[ Hiding Files ] 

<br />

just prepend \*lilyofthevalley\* string to the name of any file or directory you want to hide. 

<br />

EXAMPLES: <code> lilyofthevalley-mydir lilyofthevalleymyprog etc ... <code/>

[ Granting Root Privileges ] 

<br />

write <code> GiveMeRootPerm <code/> to <code> /proc/lilyofthevalleyr00tkit <code/>

<br />

## License
GPL


