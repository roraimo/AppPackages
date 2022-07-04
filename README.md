# SupportHub iDesktop Client Release 1.3
## Features:
- Health Check Integration
- Survey channel from POC3

### Release 1.3.3.0 (closed)
 - WinService HealthCheck job disabled by parameter
 - GUI HealthCheck panel hidden by parameter
 - Toast message Survey with duration long 25s hardcoded
 - Change Build type to Release
 - Updated .bat script to release
 - Change labeling method to #3 values ex. 1.2.3.0 (last will be always 0 to align with Odyssey)
 - Package creation 32709ITHelpSupportHub-1.3.3.0.msi

### Release 1.3.2.3 (closed)
 - Added procedure for release labelling using scripting files
 - Added 1 sec delay when pushing for HC balloons
 - Improved color contrast in control switch
 - Fix GUI OKB local DB error when running
 - Added Log limit to 7/10240Kb and verbosity option
 - Package creation 32709ITHelpSupportHub-1.3.2.3.msi

### Release 1.3.2.2 (closed)
 - Added procedure for release labelling in Docs Release-1.3.md
 - Package creation 32709ITHelpSupportHub-1.3.2.2.msi

### Release 1.3.2.1 (closed)
 - Added option key Healt Check event delay (default 20s)
 - Fix Remediation Job improved Objext exception stability for ExecuteRemetiationAlgorithm and RunVerificationAlgorithm
 - Package creation 32709ITHelpSupportHub-1.3.2.1.msi

### Release 1.3.2.0 (closed)
 - HealthCheck integration featuring basic flow: 3 times NotificationOK 3 times RemediationPostpone
 - POC3 Survey integration with Desktop Notification WebApp 1.3.2
 - Fix WPFGui 0Kb localbase.db restore
 - Package creation 32709ITHelpSupportHub-1.3.2.0.msi

### Release 1.3.1.0 (closed)
- Introduced HealthCheck integration with basic functionalities OverallStatus and Notification events
- Created full structure HealthCheck integration database tables ItemsList-HealthScore-History
- Performed partial refactoring on code structure
- Package creation SupportHubInstaller-IDC-1.3.1.0.msi