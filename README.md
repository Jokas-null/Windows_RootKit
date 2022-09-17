# Windows_RootKit
A windows kernel-mode rootkit with remote control;
Ideal Post-exploitation persistence on windows

Uses DKOM and IRP Hooks.
Hiding Processes, token manipulation , hiding tcp network connections by port

### Features
- [x] Elevate Process privillages to NT AUTHORITY\SYSTEM by token manipulation
- [x] Hide process by unlinking from ActiveProcessLinks
- [x] Remote command execution
- [x] A remote keylogger
- [x] Dropper
- [x] TCP connection hiding by port (IRP hooking)
