

====================
Linux Basic Commands
====================


*************
File Handling
*************


------------------------------------
con_a0060:Linux Command: Terminology
------------------------------------


'''''''''''
Description
'''''''''''


Some Terms
==========

* Terminal - GUI tool for working with command line.
* Bash - Bourne Again Shell, one of the different shells present in Linux.
            
            


.. raw:: latex

    \clearpage


------------------------------------------------
con_a0061:Linux Command: Structure of a command.
------------------------------------------------


'''''''''''
Description
'''''''''''


Linux Command Format
====================

* ``echo $PATH`` - the set of directories where the commands executable is searched
* ``type ls`` - gives the directory where ``ls`` is located
* Built in commands 
Shell has some built in commands which look like executable
``type echo``
``type printf``
``type eval``
``type type``

* Many commands started up as external command but were absorbed as builtin.
* It was done to save starting a new process, hence consuming less system resources.
* External Commands
``type ls``
``which echo``
``which which`` 
``which vim``
``which printf``    

Command Structure
==================

.. image:: images/commandline.jpg

* Whole command is called "command line"
* First past is the command
* Second part (optional) is called the options.
* Options alter the behaviour of the command
``ls -t`` - sorts the output
``ls -l`` - displays the long listing

* The command acts on arguments
``ls -l file``
``ls -l *``
``ls -l``
            


.. raw:: latex

    \clearpage


----------------------------
con_a0062:Linux Command: who
----------------------------


'''''''''''
Description
'''''''''''


``who`` - show who is logged on
--------------------------------

* Open another terminal and login
* ``who -a`` - show all the users who have logged into the system
* ``who -b`` - last system boot time


.. raw:: latex

    \clearpage


------------------------------
con_a0063:Linux Command: uname
------------------------------


'''''''''''
Description
'''''''''''


``uname`` -  print system information
-------------------------------------

* ``uname -p`` - get processors information
* ``uname -r`` - get kernels information
* ``uname -o`` - get operating system information
* ``uname -a`` - get all info in one line


.. raw:: latex

    \clearpage


----------------------------
con_a0064:Linux Command: man
----------------------------


'''''''''''
Description
'''''''''''



``man`` - an interface to the on-line reference manuals
-------------------------------------------------------

* Read man page of ``ls``

**Sections of man**

=======     ================================
Section     Subject     
=======     ================================
1           User programs
2           Kernel"""s System Calls
3           Library Functions
4           Special files in /dev/
5           Administrative file formats
6           Games
7           Macro Packages and conventions
8           Administration commands
9           Kernel routines [ non standard]
=======     ================================

**Examples**

* ``man -a`` - display the man pages in all the sections
* ``man 2 open`` - display the man page of open system call
* ``man 2 open read write`` - display the man page of open, read, wrtie one by one
* ``man 3 strlen`` - display the man page of strlen() command
* ``man 5 passwd`` - display the man page of /etc/passwd
* ``man 5 fstab`` - display the man page of /etc/fstab
* ``man -k strdup`` -  Search  the  short  descriptions  and  manual  page  names  for  the  keyword printf as regular expression.
* ``man man`` - man page of man :-)
* ``ls /usr/share/man/*`` - location of man pages
* ``man 7 backend``
* ``man 7 filesystem`` 
* ``man 8 lsusb``
* ``man 8 lspci``


.. raw:: latex

    \clearpage


----------------------------------------
con_a0065:Linux Command: whatis/apropros
----------------------------------------


'''''''''''
Description
'''''''''''

``whatis`` and ``apropros``
---------------------------

* ``apropros md5sum`` - shows short description of the command
* ``whatis ls`` - shows short description of the command ls
* Same as ``man -k``
* You can use regular expresssions as well
    ``apropros ^str*``


.. raw:: latex

    \clearpage


-----------------------------
con_a0066:Linux Command: info
-----------------------------


'''''''''''
Description
'''''''''''


``info`` - read info documents
------------------------------

* Read info page of ``uname``, ``ls``, ``rm``


.. raw:: latex

    \clearpage


------------------------------
con_a0067:Linux Command: clear
------------------------------


'''''''''''
Description
'''''''''''


`clear`` - clear the terminal screen
-------------------------------------

* Clears your screen
* Press ``ctrl+l`` for same effect


.. raw:: latex

    \clearpage


---------------------------
con_a0068:Linux Command: su
---------------------------


'''''''''''
Description
'''''''''''


``su`` - change user ID or become superuser
-------------------------------------------
* Why su?


.. raw:: latex

    \clearpage


-------------------------------
con_a0069:Linux Command: passwd
-------------------------------


'''''''''''
Description
'''''''''''

``passwd`` - change user password
---------------------------------

* Change your own password
    ``passwd``
    * Change other"""s password - you need to be root
        ``passwd otherUser``


.. raw:: latex

    \clearpage


-------------------------------
con_a0070:Linux Command: script
-------------------------------


'''''''''''
Description
'''''''''''


``script`` - record your session
--------------------------------

* ``script`` - saves the session in file typescript
* ``script filename`` - saves the session in the file
* ``less -fr filename`` - for viewing the file, vim shows some extra characters


.. raw:: latex

    \clearpage


-----------------------------------------
con_a0071:Linux Command: combine commands
-----------------------------------------


'''''''''''
Description
'''''''''''

Combining Commands
------------------

* ``who ; ls -l`` - separate by semicolon, the commands will run one after the other;
* ``(who; ls -l) > note`` - combine their output to be rediredcted.


.. raw:: latex

    \clearpage


---------------------------
con_a0074:Linux Command: cd
---------------------------


'''''''''''
Description
'''''''''''


``cd`` - changing directories
-----------------------------

* ``cd ..`` - takes you to parent directory.
* ``cd .`` - you stay there itself.
* ``cd /sbin`` - takes you to the ``/sbin``  directory.
* ``cd`` - takes you to home directory.
* ``cd -`` - go back to the ``$OLDPWD``.
* ``cd ~/Music`` - takes you to the ``Music`` directory in the home directory.


.. raw:: latex

    \clearpage


----------------------------
con_a0075:Linux Command: pwd
----------------------------


'''''''''''
Description
'''''''''''

``pwd`` - print name of current/working directory
-------------------------------------------------

* ``pwd`` - print the absolute path of the present working directory.
* ``$PWD`` - has the same value.
        ``echo $PWD``


.. raw:: latex

    \clearpage


-------------------------------
con_a0076:Linux Command: mktemp
-------------------------------


'''''''''''
Description
'''''''''''

``mktemp`` command
------------------
* Helps you in generating unique temporary files


.. raw:: latex

    \clearpage


------------------------------
con_a0077:Linux Command: mkdir
------------------------------


'''''''''''
Description
'''''''''''


``mkdir`` - make directories 
----------------------------

* ``mkdir dirName`` - make directory with the name
* ``mkdir -p dirParent/dirChild/dirChild2`` - make the driectory subtree if not present
* ``mkdir /test`` - gives error as you are not allowed to write to ``/``
* ``mkdir /home/userName/dirName`` - makes the directory


.. raw:: latex

    \clearpage


---------------------------
con_a0078:Linux Command: ls
---------------------------


'''''''''''
Description
'''''''''''


``ls`` - list directory contents
--------------------------------

**Go to practice/ls directory in your system**

* ``ls -R``  - recursively iterate in all sub directories
* ``ls -l``  - show details like Permissions, Links, Owner, Group Owner, Size, Last Modified Time, Filename
* ``ls -t``  - arrange according to time stamps
* ``ls -i``  - show inode numbers
* ``ls -lh`` - show human readable sizes
* ``ls -a``  - show hidden files 
* ``ls -S`` - sort by file sizes
* ``ls -t`` - sort by modified time
* ``ls -tr`` - reverse sort
* ``ls -lu`` - show access time instead of modified time 
* ``ls -lut`` - sort according to access time
* ``ls -lc`` - show last inode modification time


.. raw:: latex

    \clearpage


---------------------------
con_a0080:Linux Command: df
---------------------------


'''''''''''
Description
'''''''''''

``df`` - report file system usage 
----------------------------------

* ``df`` - usage stats of file system
* ``df -a`` - usage stats of all file systems
* ``df -h`` - human readable format
* ``df --total`` - produce a grand total
* ``df --sync`` - sync before getting stats
* ``df --type fuseblk`` - get information of fuseblk type file system (for NTFS)
* ``df --type ext4`` - get information about ext4 type file system
* ``df -i`` - get inode usage statistics


.. raw:: latex

    \clearpage


---------------------------
con_a0081:Linux Command: du
---------------------------


'''''''''''
Description
'''''''''''



``du`` - estimate file space usage 
-----------------------------------

* ``du -a`` - get sizes for all files not only directories
* ``du -sh *`` - shows in terms of 4K blocks
* ``du -b *`` - to get the correct size of each file, here we make the block size as 1 byte
* ``du --exclude=*.txt -a -b`` - get the size in bytes for all file other than txt
* ``du -d`` - get the summary for d depth


.. raw:: latex

    \clearpage


-----------------------------
con_a0082:Linux Command: file
-----------------------------


'''''''''''
Description
'''''''''''


``file`` - determine file type
------------------------------

* ``file ascii`` - tells you the file format of file named as ascii in practice directory
* ``file unicode`` - tells you about the file format of file named as unicode in practice directory
* ``file `which ls``` - tells you about the file format of ``ls`` command
* ``file presentation.odp`` - file type of presentation.odp
* ``file spreadsheet.ods`` - file type of spreadsheet.ods
* ``file spreadsheet.xls`` - file type of spreadsheet.xls
* ``file word.odt`` - file type of word.odt


.. raw:: latex

    \clearpage


---------------------------
con_a0083:Linux Command: cp
---------------------------


'''''''''''
Description
'''''''''''


``cp`` - copy files and directories
-----------------------------------

* ``-u`` - copy the file only if source file is newer
* ``-r`` - copy directories
* ``-v`` - verbose
* ``-i`` - interactive


.. raw:: latex

    \clearpage


---------------------------
con_a0084:Linux Command: rm
---------------------------


'''''''''''
Description
'''''''''''

``rm`` - remove files or directories
------------------------------------

* ``-r`` - recursively delete files and directories
* ``-R`` - recursively delete files and directories
* ``-f`` - force, dont prompt before deleting
* ``-i`` - interactive, ask before deleting


.. raw:: latex

    \clearpage


---------------------------
con_a0085:Linux Command: mv
---------------------------


'''''''''''
Description
'''''''''''

``mv`` - move (rename) files
----------------------------

* ``-u`` - move only if source is newer
* ``-v`` - verbose
* ``-f`` - force, dont prompt before overwriting
* ``-i`` - prompt before over write


.. raw:: latex

    \clearpage


------------------------------
con_a0086:Linux Command: rmdir
------------------------------


'''''''''''
Description
'''''''''''


``rmdir`` - remove empty directories
------------------------------------
* Same utility as ``rm -r`` but works only on directories.


.. raw:: latex

    \clearpage


---------------------------
con_a0087:Linux Command: ln
---------------------------


'''''''''''
Description
'''''''''''

``ln`` - make links between files
---------------------------------

* More than one file name for a file
* All links for a file point to the same copy
* All have the same inode number
* All have the same size in ``ls -lh``

**Examples**

* ``ln a.sh b.sh`` - a.sh (target) b.sh (link)
* ``ls -i`` - shows the inode numbers which are same
* Cant span accross file systems 
``ln a.sh /media/work/b.sh``
* Cant link directories
``ln Videos /media/work/video``
* Symbolic links solves the issues
* Both the links have different inode numbers
* Both the links have different file sizes
* ``ln -s a.sh /media/work/b.sh``
* ``ln -s Videos /media/work/videos``


.. raw:: latex

    \clearpage


------------------------------
con_a0089:Linux Command: chown
------------------------------


'''''''''''
Description
'''''''''''


``chown`` - change file owner and group
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

* Every file must have a owner, **generally** the creator of the file.
* **Generally** because the owner can be changed at a later stage.
* ``chown`` command can change the owner of the files
* Only the owner or ``root`` user can change the owner of a file.

**Examples**

* ``chown rishi *`` - changes the owner to rishi for all the files in the directory.
* ``chown rishi filename`` - changes the owner to rishi for ``filename``.
* ``chown -R rishi *`` - changes the owner to rishi recursively.
* ``chown -R rishi:member *``- changes the owner to rishi and group to member recursively for all files.


.. raw:: latex

    \clearpage


------------------------------
con_a0090:Linux Command: chgrp
------------------------------


'''''''''''
Description
'''''''''''



``chgrp`` - change group ownership
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

* ``chgrp rishi filename`` - changes the group to rishi for filename.
* ``chgrp rishi *`` - changes the group to rishi for all the files in the directory.
* ``chgrp -R rishi *`` - changes the owner to rishi recursively.


.. raw:: latex

    \clearpage


------------------------------
con_a0091:Linux Command: chmod
------------------------------


'''''''''''
Description
'''''''''''


``chmod`` - change file mode bits
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

* Format is ``chmod category operation permission file(s)``
* ``Category``- of user whose permissions have to be changed.
* ``Operation`` to be performed on the permissions.
* ``Permisson type (read, write, execute)`` - type of permissions

.. image:: images/chmod.jpg

* ``chmod u+x small`` - add execute permissions for user of small file
* ``chmod u+r small`` - add read permission for users of small file
* ``chmod u-w small`` - remove write permissions of users of small file
* ``chmod go-r small`` - remove read permissons for groups of small file
* ``chmod u-rwx small`` - remove read write executre permissioons of small 

.. raw:: pdf

PageBreak

===========     =============================   ==========
Category        Operation                       Permission
===========     =============================   ==========
U -user         + assign permissons             r -read
g - group       - removes permissions           w - write
o - others      =assigns absolute permissions   x - execute
a - all
===========     =============================   ==========

.. raw:: pdf

PageBreak

**Multiple expressions**

* ``chmod a+r,u+w small`` 

* ``chmod u-w,g+wx,o+x small``

**Absolute Assignments**

* When you do not know the current permissions and want to set 
* ``chnmod ugo=r small``
* ``chmod a=r small``
* ``chmod =r small``

**Octal Notation**

* ``4`` - read
* ``2``- write
* ``1`` - execute
* When you want to give permissions add the numbers 
* For read+write add 4 + 2 i.e. 6
* For rwx add 4+2+1 i.e. 7

* ``chmod 777 small`` - rwx to all
* ``chmod -R 777 *`` - do it recursively


.. raw:: latex

    \clearpage


-----------------------------
con_a0093:Linux Command: date
-----------------------------


'''''''''''
Description
'''''''''''


``date`` - print or set the system date and time
------------------------------------------------
* ``date`` - prints the date
* ``date -s"20121214 10:00:01"`` - sets the date to 14th Dec 2012, 10:01:01 AM
* ``date -s"20120712"`` - sets the date to 12th July 2012, midnight


.. raw:: latex

    \clearpage


----------------------------
con_a0094:Linux Command: cal
----------------------------


'''''''''''
Description
'''''''''''


``cal`` - displays a calendar and the date of Easter
----------------------------------------------------

* ``cal`` - see current month with highlighted today
* ``cal apr 2012`` - see April month of 2012
* ``cal jan 1`` - see January of Year 1
* ``cal jan 9999`` - see January of Year 9999


.. raw:: latex

    \clearpage
