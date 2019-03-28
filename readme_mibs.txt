***********************************************************************
SYSTEMS MANAGEMENT TOOLS AND DOCUMENTATION
MANAGEMENT INFORMATION BASE 

Version 8.1.0

Release Notes

***********************************************************************

NOTE: This readme contains updated information for the 
      Management Information Base (MIB) files for supported
      systems.

See the Support site at "dell.com/support/home" for current information.


***********************************************************************
CRITICALITY

***********************************************************************

3 = Optional

***********************************************************************
MIB DETAILS

***********************************************************************

The following chart provides information on the MIBs name, the name 
of the agent that uses each MIB, and the purpose of each MIBs:



MIB NAME      AGENT/HARDWARE SUPPORTED      PURPOSE OF EACH MIBs:
--------      ------------------------      ---------------------	
10892.mib     Server Administrator
         - Provides detailed information about the systems monitored by 
           Server Administrator Instrumentation software. 
           The 10892.mib is the primary MIB for the PowerEdge systems. 

dcs3fru.mib     Server Administrator 
	 - Provides detailed information about the system Field Replaceable Unit (FRU) 
           to SNMP management applications.

adptinfo.mib    Broadcom Gigabit NIC Management
	- Provides information about the Broadcom Gigabit network adapters.                                                

baspCfg.mib     Broadcom Gigabit NIC	  
baspStat.mib	Broadcom Gigabit NIC		   
baspTrap.mib	Broadcom Gigabit NIC
	- Collectively these MIBs provide detailed information about the 
          Broadcom Gigabit network adapters.	
	   
DcAsfSrv.mib    Baseboard Management Controller (BMC) 
	- Specifies formatting for server Platform Event Traps generated 
          by the Baseboard Management Controller.

dcs3rmt.mib     Dell Remote Access controller 5 (DRAC 5)
	- Provides detailed information about the remote access components monitored 
          by the Server Administrator Remote Access Service.

dcstorag.mib    Server Administrator Storage Management Service 	
	- Provides detailed information about the storage hardware components 
          and RAID configurations monitored by Server Administrator.                  

dellcm.mib      Server Administrator Update Service
	- Provides detailed information about the change management data monitored 
          by the Server Administrator Update Service.

INTELLAN.mib 	PRO 100S, PRO 1000XT, PRO 100+ Dual Port, PRO 1000F, PRO PCI-E Gigabit family 
	- Provides detailed information about the Intel(R) PRO 100S, PRO 1000xT, 
          PRO 100+ Dual Port, and PRO 1000F NIC adapters. 
             
rac_host.mib    Remote access out-of-band agent    
	- Provides detailed information about the components monitored 
          by the remote access out-of-band software agent.        

iDRAC-SMIv1.mib   iDRAC7
      - Provides detailed information about the SNMP data and traps supported by iDRAC7.
      - This MIB file is written in "SMv1" notation/format.

iDRAC-SMIv2.mib   iDRAC8
      - Provides detailed information about the SNMP data and traps supported by iDRAC7.
      - This MIB file is written in "SMv2" notation/format.


OME.mib      Dell OpenManage Essentials
	- Defines traps forwarded by OME, as well as internally generated alerts 
          based on health and power monitoring.

DELL-RAC-MIB.txt	Chassis Management Controller (CMC)
	- Provides information about the components monitored by 
          the Chassis Management Controller for modular chassis.
          This MIB is also the legacy iDRAC MIB. iDRACs do not
          support all of the objects and traps defined in this MIB.
          Changes are no longer made to this MIB for iDRACs.
                                                                                           
======================================================================
LEGEND
======================================================================

*   All four MIBs must be loaded for full management of the Broadcom NIC.

NOTE: All MIBs listed above reflect support for the latest available agents. 
All MIBs are backward-compatible with earlier versions of the associated agent. 
For example, the 10892.mib supports Server Agent 4.0-4.5 
and Server Administrator 1.0-5.1.


======================================================================

Copyright © 2015 Dell Inc. All rights reserved. This product is 
protected by U.S. and international copyright and intellectual property 
laws. Dell™ and the Dell logo are trademarks of Dell Inc. in 
the United States and/or other jurisdictions. 
All other marks and names mentioned herein may be trademarks of their 
respective companies.

2015 - 04

Rev. A00

