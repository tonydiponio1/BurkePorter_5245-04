2026-05-07
- Made 2 updates to Rbt CTRL routines sent by Dave M. to prevent sending th rbt to Lane pick in manual and sending the rbt to Maint position from the Conveyor HMI while the lane access door was down.

2026-05-06
- Added counter for camera fails (request from Hari to Dave M).  One rung per lane at the end of the Main routine.
- Updated camera data output tool to match the bitmap of the ascentialytics software on Lane 2 & 3 cameras.  Still need camera tools added once they are setup in the cameras by Keyence.
  

2026-05-05
- Added "NotchTapeLLFold.O_atHomePosn" to Notch tape Dispense Control 'Part in Place' output.  This was to ensure the Tab fold was completed before we send the Vertical tape arm down to apply the tape.  There is a clearance issue if the Fold cyclinder in still at work when we send the tape arm down.


2026-05-04
- Updated camera data output tool to match the bitmap of the ascentialytics software on Lane 1 cameras


2026-04-30
- Updated PLC & HMIs for new camera comm faults
 

2026-04-29
- Updated PLC for Status.Fail logic, ProcessStarted OTU logic, tag descriptions for ProcessStarted, Cycle inspection logic for 5 camera system, Conveyor WIP count failsafe logic.  
 

2026-04-28
- Updated HMIs & PLC for WARN about both WIP nests full [308], & FAULT for Part stuck in reject chute [309]


2026-04-27
- Updated HMIs camera screen to show 5 cameras
  

2026-04-24
- Updated incorrect messages on all HMIs for robot access door
- Updated the Ascentialytics UDT and routines


2026-04-21
- Updated PLC Lanes 2&3 for 5 camera system
- Updated all HMIs for 5 camera system

2026-04-20
- Updated PLC Lane 1 for 5 camera system
- Updated Ascentialytics UDT and tested with Ascentialytics team on Lowers Lane 1
  

2026-04-17
- Updated all HMIs for 4 camera system
- Added extra Cycle_Inspection step [4] to reset cameras
- Added changes for CycleStep_HMI routines from uppers.
- Added names to cameras to clearly identify and get ready for FTP server
  

2026-04-16
- Updated the Andon HMI Global object to match the v1.1 AOI
- Added 6 new camera modules to the I/O Config.
- Added new camera routines, updated Cycle_Inspection routine. 


2026-04-15
- Bypassed all the cameras since they were moved.
- Updated the Andon AOI to v1.1
- Updated the Ascentialytics logic
 

2026-04-10
- Migrated updates from Upper PLC (Not extra camera logic)
- Updated HMIs (Overview sceer bug, WIP scaling screen issue)


2026-04-06
- Migrated all Upper PLC improvements to this PLC program.  Downloaded and establish comms.
- Renamed HMIs terminals to match Upper naming convention
- Gained Control power on Conveyor zones 1,2, & 3
- Gained Control power on Lane 3.  Homed machine successfully.  
- Ran robot path to Home, Maintenance, & Reject in Teach.  All clearances OK.
- Lane 2 13101Laser has an error.


2026-03-30
- Loaded backups from local storage

