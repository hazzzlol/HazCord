A customizable Windows desktop shell for Discord.
<img width="1079" height="774" alt="image" src="https://github.com/user-attachments/assets/41fea722-a4c9-420d-992b-d32fa3fdc78d" />
Hazcord runs Discord’s web app in a native Windows window and adds controls for changing its layout and appearance. It’s designed for people who want a more personal Discord interface without installing another Electron-based app.

Hazcord is not a replacement for Discord: your account, servers, messages, and core Discord features still come from Discord.

What it includes
Customizable layout: Move the server rail, channel list, and member list; resize side panels; and choose from layout presets.
Themes and appearance controls: Use built-in themes, adjust accent colors and font size, or add custom CSS and themes.
Call-stage styling: Adjust the call backdrop, stage size, and corner rounding.
Vencord Web: A bundled browser version of Vencord provides supported plugins. Some plugins that depend on Discord’s desktop app won’t work.
Native Windows features: Use a custom title bar, system tray, quick dock, and options for minimizing or closing to the tray.
Optional microphone gain: Adjust outgoing microphone audio digitally. High gain can amplify background noise or cause distortion.
Low-overhead design: Hazcord uses Microsoft Edge WebView2 rather than bundling its own browser engine.
Getting started
Download and run Hazcord-Setup.exe, or download and extract the portable ZIP.
Start Hazcord and sign in to Discord as usual.
Open Hazcord settings from the title bar, quick dock, or tray menu.
Useful shortcuts:

Shortcut	Action
Ctrl+,	Open Hazcord settings
Ctrl+Shift+L	Open Layout Studio
Ctrl+Shift+T	Open the theme picker
F11	Toggle full screen
Requirements
64-bit Windows 10 (version 2004 / build 19041 or newer) or Windows 11
Microsoft Edge WebView2 Runtime
An internet connection to use Discord
Privacy and local data
Hazcord does not collect analytics or telemetry. Its settings and diagnostic log are stored locally. Discord’s login session is stored in Hazcord’s local WebView2 data. Discord and Vencord have their own network activity; Hazcord checks for a Vencord update only when you ask it to.

Important notes
Hazcord is unofficial and is not affiliated with Discord, Vencord, or Microsoft.
Using Vencord or other client modifications may violate Discord’s Terms of Service and could result in account action. Use client modifications at your own risk.
Hazcord’s layout customization relies on Discord’s web interface. Discord updates may change its page structure and affect layout features.
Vencord Web does not support every Vencord Desktop plugin, especially plugins that require Discord’s native desktop internals.
Hazcord does not provide desktop-only integrations such as Rich Presence or native push-to-talk.
Building from source
Hazcord is built with C# and .NET 8 on Windows. To build it, install the .NET 8 SDK and PowerShell, then run:

.\build.ps1
The build script publishes Hazcord and creates setup and portable archives.

License
Hazcord is free software licensed under the GNU General Public License v3.0. See LICENSE and THIRD-PARTY-NOTICES.md for details.
