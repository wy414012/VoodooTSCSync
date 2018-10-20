# VoodooTSCSync

Fork of VoodooTSCSync by RehabMan

A kernel extension which will synchronize the TSC on any Intel CPUs.

This version automatically attaches to the last CPU automatically.
Different from previous versions, no need to modify the Info.plist, just install and use.

Credit: Cosmosis Jones (origin version for Intel)<br/>
            fumoboy007 (modified version for AMD)<br/>
            RehabMan version forked from denskop @github

### Downloads:

Downloads are available on Bitbucket:

https://bitbucket.org/RehabMan/VoodooTSCSync/downloads/

### Change Log:

2018-10-19 v1.5.0

- fork from denskop version

- automatically attach only to last CPU object

- add version info in ioreg, announce loading in kernel logs

- remove AMD version

- misc source code/kernel log cleanup
