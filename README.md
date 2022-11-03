# install-uninstall-windows-service
How to install - copy only the debug folder in service project. locate the InstallUtil.exe folder location and type the command below with the path of your service .exe 

C:\Windows\Microsoft.NET\Framework\v4.0.30319>InstallUtil.exe C:\notifServiceTest\LookupNotificationService.exe
Microsoft (R) .NET Framework Installation utility Version 4.7.3062.0
Copyright (C) Microsoft Corporation.  All rights reserved.


Running a transacted installation.

Beginning the Install phase of the installation.
See the contents of the log file for the C:\notifServiceTest\LookupNotificationService.exe assembly's progress.
The file is located at C:\notifServiceTest\LookupNotificationService.InstallLog.
Installing assembly 'C:\notifServiceTest\LookupNotificationService.exe'.
Affected parameters are:
   logtoconsole =
   logfile = C:\notifServiceTest\LookupNotificationService.InstallLog
   assemblypath = C:\notifServiceTest\LookupNotificationService.exe
Installing service Notif Service...
Service Notif Service has been successfully installed.
Creating EventLog source Notif Service in log Application...

The Install phase completed successfully, and the Commit phase is beginning.
See the contents of the log file for the C:\notifServiceTest\LookupNotificationService.exe assembly's progress.
The file is located at C:\notifServiceTest\LookupNotificationService.InstallLog.
Committing assembly 'C:\notifServiceTest\LookupNotificationService.exe'.
Affected parameters are:
   logtoconsole =
   logfile = C:\notifServiceTest\LookupNotificationService.InstallLog
   assemblypath = C:\notifServiceTest\LookupNotificationService.exe

The Commit phase completed successfully.

The transacted install has completed.

___________________________________________________________________________________________________________________________

How to uninstall - locate the InstallUtil.exe folder location and type the command below with the path of your service .exe

C:\Windows\Microsoft.NET\Framework\v4.0.30319>InstallUtil.exe -u C:\notifServiceTest\bin\Debug\LookupNotificationService.exe
Microsoft (R) .NET Framework Installation utility Version 4.7.3062.0
Copyright (C) Microsoft Corporation.  All rights reserved.

Exception occurred while initializing the installation:
System.IO.FileNotFoundException: Could not load file or assembly 'file:///C:\notifServiceTest\bin\Debug\LookupNotificationService.exe' or one of its dependencies. The system cannot find the file specified..

C:\Windows\Microsoft.NET\Framework\v4.0.30319>InstallUtil.exe -u C:\notifServiceTest\LookupNotificationService.exe
Microsoft (R) .NET Framework Installation utility Version 4.7.3062.0
Copyright (C) Microsoft Corporation.  All rights reserved.



The uninstall is beginning.
See the contents of the log file for the C:\notifServiceTest\LookupNotificationService.exe assembly's progress.
The file is located at C:\notifServiceTest\LookupNotificationService.InstallLog.
Uninstalling assembly 'C:\notifServiceTest\LookupNotificationService.exe'.
Affected parameters are:
   logtoconsole =
   logfile = C:\notifServiceTest\LookupNotificationService.InstallLog
   assemblypath = C:\notifServiceTest\LookupNotificationService.exe
Removing EventLog source Notif Service.
Service Notif Service is being removed from the system...
Service Notif Service was successfully removed from the system.

The uninstall has completed.



Force Stop Service:

Type this command - C:\>sc queryex "Notif Service" 

result shoul be:
SERVICE_NAME: Notif Service
        TYPE               : 10  WIN32_OWN_PROCESS
        STATE              : 4  RUNNING
                                (STOPPABLE, NOT_PAUSABLE, ACCEPTS_SHUTDOWN)
        WIN32_EXIT_CODE    : 0  (0x0)
        SERVICE_EXIT_CODE  : 0  (0x0)
        CHECKPOINT         : 0x0
        WAIT_HINT          : 0x0
        PID                : 16600
        FLAGS              :

Type this command again - C:\>taskkill /pid 16600 /f

Result should be:
SUCCESS: The process with PID 16600 has been terminated.

C:\>

