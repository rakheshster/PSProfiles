## What is this?

Just a place to put my PowerShell profile files. 

Am reading about Git submodules & submodules. Once I've got a hang of these I plan to incorporate my profile related repositories into here so I have everything in one place and anyone can download the whole bunch at one go. 

## Installation

Here's what I do on each of my computers.

1. Clone this repository someplace. For example to `c:\Users\me\code\PSProfiles`.

2. Delete the `WindowsPowerShell` folder (in my case it had only the profile files but double check to ensure your folder doesn't have anything else of use). 

3. From an admin command prompt do the following:

        mklink /D c:\Users\me\Documents\WindowsPowerShell c:\Users\me\code\PSProfiles
