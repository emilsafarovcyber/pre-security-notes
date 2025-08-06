 Windows Fundamentals

## Key Components
- **Registry:** Central database for Windows configuration.
- **Event Viewer:** Tool to view logs and system events.
- **PowerShell:** Command-line shell and scripting language.
- **Task Manager:** Monitor running applications and system performance.

## Useful Commands
- `ipconfig` – Show IP configuration.
- `netstat` – Display network connections.
- `tasklist` – List running processes.
- `systeminfo` – Show system information.
- `sfc /scannow` – System File Checker to repair corrupted files.

## Log Files
- **System Logs:** Hardware and driver events.
- **Application Logs:** Application-level events.
- **Security Logs:** Security-related events (logins, failures).

## User and Permission Management
- Create users: `net user username password /add`
- Change group membership: `net localgroup groupname username /add`
- Permissions managed via GUI or `icacls` command.
