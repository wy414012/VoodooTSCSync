# VoodooTSCSync
Fork of VoodooTSCSync by RehabMan

A kernel extension which will synchronize the TSC on any Intel CPUs.

This version automatically attaches to the last CPU automatically.
Different from previous versions, no need to modify the Info.plist, just install and use.

Note: That work not done for the AMD version.  Must still set the IOCPUNumber to largest IOCPUNumber in VoodooTSCSyncAMD.kext/Contents/Info.plist.

Credit: Cosmosis Jones (origin version for Intel)<br/>
            fumoboy007 (modified version for AMD)<br/>
            RehabMan version forked from denskop @github
