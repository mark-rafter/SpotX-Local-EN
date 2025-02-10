<p align="center">
  <a href="https://github.com/SpotX-Official/SpotX/releases"><img src="https://spotx-official.github.io/images/logos/logo.png" /></a>
</p>

<p align="center">        
      <a href="https://t.me/spotify_windows_mod"><img src="https://spotx-official.github.io/images/shields/SpotX_Channel.svg"></a>
      <a href="https://t.me/SpotxCommunity"><img src="https://spotx-official.github.io/images/shields/SpotX_Community.svg"></a>
      <a href="https://github.com/SpotX-Official/SpotX-Bash"><img src="https://spotx-official.github.io/images/shields/SpotX_for_Mac&Linux.svg"></a>
      <a href="https://telegra.ph/SpotX-FAQ-09-19"><img src="https://spotx-official.github.io/images/shields/faq.svg"></a>
      </p>

   <h2> <div align="center"><b> Modified Spotify Client for Windows </b></div> </h2>

# System requirements

- <strong>OS: Windows 7-11</strong>
- <strong>Spotify: latest official [versions](https://cutt.ly/8EH6NuH)</strong>
- <strong>For Windows Desktop only (Microsoft store version is not suitable).</strong>
- <strong>PowerShell: version 5 and above recommended</strong>

# Features

- <strong>Blocks all banner, video and audio ads in the client</strong>
- <strong>Hiding podcasts, episodes and audiobooks from the homepage (optional)</strong>
- <strong>Block Spotify automatic updates (optional)</strong>
- <strong>More experimental features have been activated ([see the full list](https://github.com/SpotX-Official/SpotX/discussions/50))</strong>
- <strong>Disabled sentry's console log/error/warning messages to Spotify developers, halted user interaction logging, eliminated right-to-left CSS rules for simplification, and performed code minification</strong> 

# Installation

Open a PowerShell terminal in this folder, and run:
```ps1
# optional
New-NetFirewallRule -DisplayName "Block PowerShell Outbound" -Direction Outbound -Program "C:\Windows\System32\WindowsPowerShell\v1.0\powershell.exe" -Action Block

Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Scope Process

.\run.ps1
```
 
# Uninstall

- Just run [Uninstall.bat](https://raw.githack.com/amd64fox/SpotX/main/Uninstall.bat)
or reinstall Spotify ([Full uninstall Spotify](https://github.com/amd64fox/Uninstall-Spotify) recommended)

# FAQ

 Read [FAQ](https://telegra.ph/SpotX-FAQ-09-19)

# Credits

 Some tricks were taken from <a href="https://github.com/khanhas/spicetify-cli">spicetify-cli</a>, many thanks to the contributors.

# Disclaimer

 SpotX is a modified version of the official Spotify client, provided as an evaluation version, you use it at your own risk.
