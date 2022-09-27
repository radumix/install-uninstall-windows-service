# install-uninstall-windows-service


Microsoft Windows [Version 10.0.14393]
(c) 2016 Microsoft Corporation. All rights reserved.

C:\Windows\system32>cd C:\Users\usr_devcsg\Desktop\notif windows service test\bin\Debug

C:\Users\usr_devcsg\Desktop\notif windows service test\bin\Debug>InstallUtil.exe LookupNotificationService
'InstallUtil.exe' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\usr_devcsg\Desktop\notif windows service test\bin\Debug>InstallUtil LookupNotificationService.exe
'InstallUtil' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\usr_devcsg\Desktop\notif windows service test\bin\Debug>LookupNotificationService.exe --install

C:\Users\usr_devcsg\Desktop\notif windows service test\bin\Debug>cd\

C:\>cd C:\Windows\Microsoft.NET\Framework\v4.0.30319

C:\Windows\Microsoft.NET\Framework\v4.0.30319>InstallUtil.exe C:\Users\usr_devcsg\Desktop\notif windows service test\bin\Debug\LookupNotificationService.exe
Microsoft (R) .NET Framework Installation utility Version 4.7.3062.0
Copyright (C) Microsoft Corporation.  All rights reserved.

Exception occurred while initializing the installation:
System.IO.FileNotFoundException: Could not load file or assembly 'file:///C:\Users\usr_devcsg\Desktop\notif' or one of its dependencies. The system cannot find the file specified..

C:\Windows\Microsoft.NET\Framework\v4.0.30319>InstallUtil.exe C:\notifServiceTest\bin\Debug\LookupNotificationService.exe
Microsoft (R) .NET Framework Installation utility Version 4.7.3062.0
Copyright (C) Microsoft Corporation.  All rights reserved.


Running a transacted installation.

Beginning the Install phase of the installation.
See the contents of the log file for the C:\notifServiceTest\bin\Debug\LookupNotificationService.exe assembly's progress.
The file is located at C:\notifServiceTest\bin\Debug\LookupNotificationService.InstallLog.
Installing assembly 'C:\notifServiceTest\bin\Debug\LookupNotificationService.exe'.
Affected parameters are:
   logtoconsole =
   logfile = C:\notifServiceTest\bin\Debug\LookupNotificationService.InstallLog
   assemblypath = C:\notifServiceTest\bin\Debug\LookupNotificationService.exe
Installing service Notif Service...
Service Notif Service has been successfully installed.
Creating EventLog source Notif Service in log Application...

The Install phase completed successfully, and the Commit phase is beginning.
See the contents of the log file for the C:\notifServiceTest\bin\Debug\LookupNotificationService.exe assembly's progress.
The file is located at C:\notifServiceTest\bin\Debug\LookupNotificationService.InstallLog.
Committing assembly 'C:\notifServiceTest\bin\Debug\LookupNotificationService.exe'.
Affected parameters are:
   logtoconsole =
   logfile = C:\notifServiceTest\bin\Debug\LookupNotificationService.InstallLog
   assemblypath = C:\notifServiceTest\bin\Debug\LookupNotificationService.exe

The Commit phase completed successfully.

The transacted install has completed.

C:\Windows\Microsoft.NET\Framework\v4.0.30319>InstallUtil.exe -u C:\notifServiceTest\bin\Debug\LookupNotificationService.exe
Microsoft (R) .NET Framework Installation utility Version 4.7.3062.0
Copyright (C) Microsoft Corporation.  All rights reserved.



The uninstall is beginning.
See the contents of the log file for the C:\notifServiceTest\bin\Debug\LookupNotificationService.exe assembly's progress.
The file is located at C:\notifServiceTest\bin\Debug\LookupNotificationService.InstallLog.
Uninstalling assembly 'C:\notifServiceTest\bin\Debug\LookupNotificationService.exe'.
Affected parameters are:
   logtoconsole =
   logfile = C:\notifServiceTest\bin\Debug\LookupNotificationService.InstallLog
   assemblypath = C:\notifServiceTest\bin\Debug\LookupNotificationService.exe
Removing EventLog source Notif Service.
Service Notif Service is being removed from the system...
Service Notif Service was successfully removed from the system.

The uninstall has completed.

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

C:\Windows\Microsoft.NET\Framework\v4.0.30319>

C:\Windows\Microsoft.NET\Framework\v4.0.30319>
