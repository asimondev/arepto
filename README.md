# Free Oracle Performance Tool AREPTO
This is a main page of *AREPTO*, the free interactive tool for getting performance details 
about SQL cursors. The tool helps as well to search for specific details in ASH.

This program is written completely in C++ using Oracle OCI API and UNIX Curses library. 
This allows *AREPTO* to run on every UNIX terminal. After downloading the tool, you can 
immediately start to use it, if the environment variables (**ORACLE_HOME**, **PATH**,
**LD_LIBRARY_PATH**, **ORACLE_SID** etc) are set correctly. 

**If SQL*Plus can run, then AREPTO should execute as well.**

The tool executes only SELECT statements, so that you can easily test and use it on any database.

Why shall I use this tool additionally to OEM, SQL Developer etc? The answers could be:

* Sometimes you have got only a UNIX terminal (like a PuTTY window). This could be a case,
  if only the SSH port is allowed or if you work over VPN connection.
* You are comfortable with the Oracle dynamic views. You could of course just use SQL*Plus. 
  But using AREPTO is sometimes easier.
* You are already using a UNIX terminal for your work. So If you want to check some information,
  it's faster to use AREPTO instead of starting a GUI or a browser.
* AREPTO provides some reports (text and HTML), so that you can quickly collect the information 
  and analyze it later.
* If you already use AMON, you would like to find in this tool the missing details about SQL cursors and ASH.

Starting with *AREPTO* version 2 only the Linux executable files will be provided. At the moment
the version 2 supports Oracle Release 19c on:
* Oracle Linux 7.
* Ubuntu 22.04 LTS using Oracle Instant Client for Linux x86-64.

## How to start AREPTO.

You should download the latest AREPTO release and copy the corresponding file to your Linux server.
After setting Oracle environment you can start AREPTO: `./arepto_19c_ol7`. You would see the 
AREPTO start window with all options.

![AREPTO start window.](https://github.com/asimondev/arepto/blob/master/screenshots/arepto_start.png)

You can always quit AREPTO by pressing **"q"** key. You can use cursor movement keys, tab key, 
page down, page up keys and Return key as usual.

Further *AREPTO* documentation:

***

This tool is developed by *Andrej Simon*, Oracle ACS Germany in my free time. If you have any 
questions or comments, please contact me directly (*andrej.simon@oracle.com*).

***

**Freeware disclaimer**: The author, Andrej Simon, of this freeware accepts no responsibility for 
damages resulting from the use of this product and makes no warranty or representation, 
either express or implied, including but not limited to, any implied warranty of merchantability 
or fitness for a particular purpose. This software is provided "AS IS", and you, its user, 
assume all risks when using it.