<div align="center">

# Hey, I'm Alejandro 👋

<a href="https://github.com/amd989">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=3000&pause=800&color=58A6FF&center=true&vCenter=true&width=520&lines=Engineer+%26+maker;I+write+software+for+things+with+wires;C%23+%C2%B7+.NET+%C2%B7+Python+%C2%B7+C%2FC%2B%2B;Homelab+tinkerer+%C2%B7+3D+printing+nerd" alt="Engineer & maker" />
</a>

<a href="https://alejandro.md"><img src="https://img.shields.io/badge/website-alejandro.md-58A6FF?style=flat-square&logo=googlechrome&logoColor=white" alt="Website" /></a>
<a href="https://blog.alejandro.md"><img src="https://img.shields.io/badge/blog-The_Maker_Shed-21759B?style=flat-square&logo=wordpress&logoColor=white" alt="Blog" /></a>
<a href="https://linktree.alejandro.md"><img src="https://img.shields.io/badge/linktree-alejandro.md-39E09B?style=flat-square&logo=linktree&logoColor=white" alt="Linktree" /></a>
<a href="https://github.com/amd989?tab=followers"><img src="https://img.shields.io/github/followers/amd989?style=flat-square&logo=github&label=followers&color=24292e" alt="GitHub followers" /></a>

</div>

### About me

Most of what I build is software for hardware I own: my multimeter, my 3D printers, my firewall, the switches on my walls.

- I write a lot of C# and .NET: Windows desktop apps, cross-platform apps with .NET MAUI, and an Outlook add-in or two
- I also solder, flash ESP8266 boards and write firmware in C and C++
- My homelab runs OPNsense, Home Assistant, Klipper and a lot of Docker containers
- Recently I've been adding MCP servers so AI assistants can talk to that hardware

### Where my code runs

The blue boxes are my projects. Everything else is the hardware or service they talk to.

```mermaid
flowchart LR
  subgraph house["Around the house"]
    direction LR
    suitchi["Suitchi wall switch"] --> ha["Home Assistant"]
    suitchi --> homekit["HomeKit"]
    dengen["Dengen"] -- ATX power --> nuc["Intel NUC"]
    flipper["Flipper Zero"] -- infrared --> infrafi["InfraFi"] --> server["Linux server"]
  end

  subgraph closet["Network closet"]
    direction LR
    opn["OPNsense"] --> ug["unifi-gateway"] --> unifi["UniFi controller"]
    opn --> wfo["widgets-for-opnsense"] --> desk["Windows, KDE and GNOME widgets"]
  end

  subgraph print["Print corner"]
    direction LR
    mariner["mariner on a Raspberry Pi"] -- USB --> mars["Elegoo Mars 3"]
    klipper["Klipper printer"] --> kc["klipper-connect"] --> prusa["Prusa Connect"]
    cams["RTSP cameras"] --> spc["scrypted-prusa-connect"] --> prusa
  end

  subgraph bench["On the bench"]
    direction LR
    meter["EEVblog 121GW multimeter"] -- Bluetooth LE --> readout["Readout"]
    readout -- MCP --> claude["Claude"]
  end

  classDef mine fill:#1f6feb,stroke:#1f6feb,color:#ffffff
  class readout,mariner,kc,spc,ug,wfo,suitchi,dengen,infrafi mine
```

Repos in the map: [Readout](https://github.com/amd989/readout) · [mariner](https://github.com/mariner3d/mariner) · [klipper-connect](https://github.com/amd989/klipper-connect) · [scrypted-prusa-connect](https://github.com/amd989/scrypted-prusa-connect) · [unifi-gateway](https://github.com/amd989/unifi-gateway) · [widgets-for-opnsense](https://github.com/amd989/widgets-for-opnsense) · [Suitchi](https://github.com/amd989/Suitchi) · [Dengen](https://github.com/amd989/Dengen) · [InfraFi](https://github.com/amd989/InfraFi)

### Elsewhere on GitHub

- [mariner3d/mariner](https://github.com/mariner3d/mariner) is a web interface for resin printers with ChiTu boards (Elegoo, Phrozen, Anycubic and others). Most of its commits over the last few months are mine, for mariner 2.
- I'm also a member of [unofficial-unifi](https://github.com/unofficial-unifi), which installs the UniFi controller on pfSense and OPNsense, and of [flipperdevices](https://github.com/flipperdevices).

### Latest from the blog

I write up most of these projects on [The Maker Shed](https://blog.alejandro.md).

<!-- BLOG-POST-LIST:START -->
- [Widgets for OPNsense: My Router on the Windows Widget Board](https://blog.alejandro.md/2026/11/widgets-for-opnsense/)
- [Readout: A Companion App for the EEVblog 121GW](https://blog.alejandro.md/2026/11/readout-a-companion-app-for-the-eevblog-121gw/)
- [Elegoo Mars 3: 04 Remote Control with Mariner 2](https://blog.alejandro.md/2026/05/elegoo-mars-3-04-remote-control-with-mariner-2/)
- [InfraFi: Sending WiFi Credentials Over Infrared with a Flipper Zero](https://blog.alejandro.md/2026/04/infrafi-sending-wifi-credentials-over-infrared-with-a-flipper-zero/)
- [The Story Behind iTunesLyrics](https://blog.alejandro.md/2026/04/the-story-behind-ituneslyrics/)
<!-- BLOG-POST-LIST:END -->

### What I use

<p>
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/Arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white" />
  <img src="https://img.shields.io/badge/ESP8266-E7352C?style=for-the-badge&logo=espressif&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Home_Assistant-18BCF2?style=for-the-badge&logo=homeassistant&logoColor=white" />
  <img src="https://img.shields.io/badge/OPNsense-D94F00?style=for-the-badge&logo=opnsense&logoColor=white" />
  <img src="https://img.shields.io/badge/Klipper-B12F35?style=for-the-badge&logo=klipper&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white" />
</p>
