Run the VS - Command Prompt as the Administrator:-



C:\>installutil -i C:\Users\Anbarasu\source\repos\WindowsServiceHost\WindowsServiceHost\bin\Debug\WindowsServiceHost.exe

C:\>installutil -u C:\Users\Anbarasu\source\repos\WindowsServiceHost\WindowsServiceHost\bin\Debug\WindowsServiceHost.exe

--------------------------------------------------------********--------------------------------------------------------

C:\>installutil -i C:\Users\Anbarasu\source\repos\WindowsServiceHost\WindowsServiceHost\bin\Debug\WindowsServiceHost.exe
Microsoft (R) .NET Framework Installation utility Version 4.7.2556.0
Copyright (C) Microsoft Corporation.  All rights reserved.


Running a transacted installation.

Beginning the Install phase of the installation.
See the contents of the log file for the C:\Users\Anbarasu\source\repos\WindowsServiceHost\WindowsServiceHost\bin\Debug\WindowsServiceHost.exe assembly's progress.
The file is located at C:\Users\Anbarasu\source\repos\WindowsServiceHost\WindowsServiceHost\bin\Debug\WindowsServiceHost.InstallLog.
Installing assembly 'C:\Users\Anbarasu\source\repos\WindowsServiceHost\WindowsServiceHost\bin\Debug\WindowsServiceHost.exe'.
Affected parameters are:
   i =
   logfile = C:\Users\Anbarasu\source\repos\WindowsServiceHost\WindowsServiceHost\bin\Debug\WindowsServiceHost.InstallLog
   assemblypath = C:\Users\Anbarasu\source\repos\WindowsServiceHost\WindowsServiceHost\bin\Debug\WindowsServiceHost.exe
   logtoconsole =
Installing service HelloWindoesService...
Service HelloWindoesService has been successfully installed.
Creating EventLog source HelloWindoesService in log Application...

The Install phase completed successfully, and the Commit phase is beginning.
See the contents of the log file for the C:\Users\Anbarasu\source\repos\WindowsServiceHost\WindowsServiceHost\bin\Debug\WindowsServiceHost.exe assembly's progress.
The file is located at C:\Users\Anbarasu\source\repos\WindowsServiceHost\WindowsServiceHost\bin\Debug\WindowsServiceHost.InstallLog.
Committing assembly 'C:\Users\Anbarasu\source\repos\WindowsServiceHost\WindowsServiceHost\bin\Debug\WindowsServiceHost.exe'.
Affected parameters are:
   i =
   logfile = C:\Users\Anbarasu\source\repos\WindowsServiceHost\WindowsServiceHost\bin\Debug\WindowsServiceHost.InstallLog
   assemblypath = C:\Users\Anbarasu\source\repos\WindowsServiceHost\WindowsServiceHost\bin\Debug\WindowsServiceHost.exe
   logtoconsole =

The Commit phase completed successfully.

The transacted install has completed.

--------------------------------------------------------********--------------------------------------------------------

C:\>installutil -u C:\Users\Anbarasu\source\repos\WindowsServiceHost\WindowsServiceHost\bin\Debug\WindowsServiceHost.exe
Microsoft (R) .NET Framework Installation utility Version 4.7.2556.0
Copyright (C) Microsoft Corporation.  All rights reserved.



The uninstall is beginning.
See the contents of the log file for the C:\Users\Anbarasu\source\repos\WindowsServiceHost\WindowsServiceHost\bin\Debug\WindowsServiceHost.exe assembly's progress.
The file is located at C:\Users\Anbarasu\source\repos\WindowsServiceHost\WindowsServiceHost\bin\Debug\WindowsServiceHost.InstallLog.
Uninstalling assembly 'C:\Users\Anbarasu\source\repos\WindowsServiceHost\WindowsServiceHost\bin\Debug\WindowsServiceHost.exe'.
Affected parameters are:
   logtoconsole =
   logfile = C:\Users\Anbarasu\source\repos\WindowsServiceHost\WindowsServiceHost\bin\Debug\WindowsServiceHost.InstallLog
   assemblypath = C:\Users\Anbarasu\source\repos\WindowsServiceHost\WindowsServiceHost\bin\Debug\WindowsServiceHost.exe
Removing EventLog source HelloWindoesService.
Service HelloWindoesService is being removed from the system...
Service HelloWindoesService was successfully removed from the system.
Attempt to stop service HelloWindoesService.

The uninstall has completed.