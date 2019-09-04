# teststand-user-interfaces

Modified teststand user interfaces


## Branch "ui-with-fixed-sequence"

### Motivations

The basic user interface allows the operator to select the teststand sequence to be run. There were motivation to prevent the operator from doing this in the first place because the test sequence is distributed and can be changed. The idea is therefore to limit as much as possible the interaction of the operator with the original test sequence file.

At the moment, the file path is still displayed but this can be easily hidden as the open and start sequences button were hidden.

### Resources: 
http://zone.ni.com/reference/en-XX/help/370052W-01/tsuiref/reftopics/applicationmgr_opensequencefile_m/
https://forums.ni.com/t5/LabVIEW/Using-Teststand-UI-Controls-to-load-a-sequence-file-in-Labview/td-p/3250151?profile.language=en
https://forums.ni.com/t5/NI-TestStand/Modifying-the-LV-TestStand-Simple-UI-to-start-Teststand/td-p/3797648?profile.language=en
https://forums.ni.com/t5/NI-TestStand/List-possible-sequences/m-p/512385?profile.language=en#M14782
https://forums.ni.com/t5/NI-TestStand/Programmatically-loading-and-executing-a-sequence-file-in/td-p/512537?profile.language=en
https://forums.ni.com/t5/NI-TestStand/How-to-programmatically-read-the-SequenceFile-currently-open/td-p/2009473?profile.language=en
https://forums.ni.com/t5/NI-TestStand/Monitoring-activity-of-Login-Logout-button-in-LabVIEW-Simple-OI/m-p/2404332?profile.language=en
https://forums.ni.com/t5/NI-TestStand/Send-CurrentUser-Name-to-TestStand-User-Interface/td-p/2653813?profile.language=en
https://forums.ni.com/t5/NI-TestStand/Post-Expression-Execution/td-p/55529?profile.language=en
https://forums.ni.com/t5/NI-TestStand/Step-limits-expression-evaluation/td-p/2230048?profile.language=en