# local_tab_syncer_V1
Local tab syncer for POS written in kotlin

Hi wellcome to the local POS syncer

A few things to follow

1) The db requiered to sync up local tabs needs to be in to folder
2) Login to the merchant in question - same tenant and same location
3) Let POS idle
if running jar file *
  *) Open up cmd
  *) Navigate to the folder where the jar file lays
  *) Then run the following command: java -jar localSync.jar
  *) Note this is a cmd app it might change in feauture
  *) type list to see commands
if running exe file on windows
  *) Type list to see commands
4) TODO explain commands
   *) list - will show you current commands that are available to use
   *) data - will return the data you have entered
   *) resync_tabs - this will begin the action to add the tid, deviceUID and host tab ids
   *) sync - this will call the POS api and wil start to sync the tabs one by one
   *) 1 - this is the tenat id for now
   *) 2 - this is the device uid for now
   *) add - this gives you go ahead to add the host_tab_ids : format is eg: e9302343-268f-438b-a171-a97e5781b791, fb1fab84-2c14-438b-aeb3-15390a85842e
   *) yes - this gives you access to go ahead and adding the information
   *) exit - will close the application
6) The host tab id should only be seperated by , no needed for ""
7) Type Sync and check the local db in transactionSyncLog for it to appear
8) Shout if stuck
