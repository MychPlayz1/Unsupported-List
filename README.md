# Unsupported-List
Disabling or Removing Cortana:

What happens: Cortana is more integrated into Windows 10 than in later versions (like Windows 11). Disabling or removing it can cause system instability and issues with Windows search or voice commands.
Why it can corrupt: Cortana handles certain tasks, like searching the system, and removing it can break key system functionalities like the search bar or indexing service.
Removing Microsoft Store (UWP Apps):

What happens: The script removes UWP apps (Universal Windows Platform) like OneDrive, Xbox, and Skype. While it might remove them successfully, some UWP apps are tightly integrated with Windows 10 and removing them can break certain system features.
Why it can corrupt: The Microsoft Store and certain built-in apps are crucial for managing UWP updates and maintaining app integrity. Removing these may break automatic updates or app installations, leading to issues down the line.
Disabling Windows Defender:

What happens: Disabling Windows Defender (Microsoft Defender Antivirus) could expose your system to vulnerabilities, as it disables real-time protection against malware and other threats.
Why it can corrupt: In some cases, disabling Windows Defender can trigger Windows 10 to automatically disable other critical security features, leaving your system vulnerable and possibly leading to performance degradation.
Disabling/Removing Services:

What happens: Services like DiagTrack (Diagnostic Tracking), WSearch (Windows Search), and others play important roles in keeping the system operational.
Why it can corrupt: Removing or disabling some of these services might cause system performance issues, search functionality to break, or the inability to collect diagnostic data for troubleshooting. Additionally, services related to updates and core Windows functionality could be disrupted.
Modifying or Deleting Registry Keys Unknowingly:

What happens: The script makes certain registry modifications (such as privacy-related changes), which might be compatible with Windows 11 but could cause issues on Windows 10 if applied incorrectly.
Why it can corrupt: Windows 10 might rely on different registry values or have different system configurations that, if altered inappropriately, could lead to crashes, errors, or performance issues.
Removing/Disabling Critical Built-in Windows Apps (e.g., Microsoft Edge, Store, etc.):

What happens: Attempting to remove built-in apps like Microsoft Edge, Mail, Calendar, and others might cause the system to lose functionality.
Why it can corrupt: These apps are built into the operating system, and some of them are required for system stability and update functionality. Removing them could result in errors or break system features.
Disk Cleanup with Sagerun Settings:

What happens: Running Disk Cleanup with /sagerun:1 is a useful feature, but not all settings are compatible across versions of Windows. In some instances, it could delete or modify system files unintentionally.
Why it can corrupt: Certain cleanup configurations might remove system files or cached data that are required by Windows 10 for proper functioning, potentially breaking key features or reducing performance.
Disabling Windows Update:

What happens: Although this is not directly in the script, if users add custom code to disable updates, they could inadvertently prevent critical security patches and updates from being installed.
Why it can corrupt: Disabling Windows Update will prevent the system from receiving important security updates, potentially exposing it to malware or vulnerabilities. This can also lead to compatibility issues with newer software or hardware.
Additional Notes:
System Integrity: Always remember that actions like disabling or removing essential system services, applications, or updates in Windows 10 can lead to instability and a higher risk of data corruption or performance problems.
Built-in Windows Apps: Some apps and services are embedded into Windows 10 to ensure smooth operation. Removing these can create unanticipated problems with system management, security, or networking.
Recommended Precautions:
Backup: It's always a good idea to create a full system backup or restore point before performing any debloating or modifications.
Check Dependencies: Ensure you understand the dependencies of certain services and applications before disabling them.
