Live for Speed DCon 0.6U
========================


www.lfs.net


Important
---------
This is a special dedicated host program for Live for Speed.

By installing this software you agree to the following:

- Live for Speed is in continual development.  Features may be
added, updated or removed at any time.  Some functional but
incomplete features may be included in order to enhance the
variety and content of the simulator.

- This software comes with no warranties of any kind.

- You install and use this software at your own risk.  The
developers of Live for Speed can not accept any responsibility for
personal injury or damage to your computer system that may arise
during the use of the software.

- The DEMO content is given to all people to use, free of charge.
The LOCKED content is for appropriately licensed users only.  You
must not make any attempt to gain access to the locked content, or
help anyone else to do so, other than by purchasing a license and
using the in-game unlocking screen.

Thank you.


Changes from DCon 0.6T to 0.6U
------------------------------
An improvement to speed up recovery when there is lag


Changes from DCon 0.6R to 0.6T
------------------------------
More robust method for connecting to the master server

InSim:

New value PMO_POSITION for IS_AXM packet to report a blank position
New packet IS_CIM reports a connection's interface / editor mode
New values PMO_SELECTION_REAL and PMO_MOVE_MODIFY for PMOFlags
New values TTC_SEL_START and TTC_SEL_STOP for IS_TTC

UCID can be set in some IS_AXM packets by an external InSim program
to make the resulting packets appear as if sent by an editing admin
- PMO_ADD_OBJECTS / PMO_DEL_OBJECTS / PMO_CLEAR_ALL


Installation
------------
To install the program, unzip the file into a suitable folder.  You
must ensure that the directory structure is preserved by using the
appropriate option in your unzip utility.  You will know that it
has been correctly unzipped if you see a data folder beside the
DCon.exe program and some more folders inside the data folder.


To run LFS DCon
---------------
Use a shortcut, batch file, etc. to start DCon.exe with a command
line.  If you do not use a command line, DCon will take its startup
options from the setup.cfg file.

You can enter text using the keyboard but it is invisible while you
type.  This is to separate stdin and stdout.

You can get a status message at any time by pressing ENTER without
typing anything.


Command line options
--------------------
A command line or a command file is required.
The commands are listed in Commands_DCon.txt in the docs folder.


Status file
-----------
While your host is running, a file host63392.txt can be found in
its folder.  It is updated whenever the info changes.

63392 is the port number of the host.
It contains the following information:

lfs=0.6U             :version
status=ingame        :offline / online / ingame
guests=4             :current number of guests
maxguests=4          :maximum guests allowed
host=Host Name       :game name as listed on master server
pass=Optional Pass   :host password
usemaster=yes        :no / yes / hidden
trackcfg=BL1         :short name for track and config
cars=[20x"0"or"1"]   :cars allowed on host (0=no / 1=yes)
qual=0               :qualifying minutes
laps=5               :number of laps
conn=Host            :player name
conn=Guest 1         :player name
conn=Guest 2         :player name
...


Copyright
---------
(c) 2002-2019 Scawen Roberts - Eric Bailey - Victor van Vlaardingen