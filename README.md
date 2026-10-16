<p align="center">
  <img src="banner.svg" alt="REDOVSKY" width="100%" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2800&pause=900&color=FF4D1A&center=true&vCenter=true&width=640&height=45&lines=%24+whoami+%E2%86%92+Redovsky;Making+plugins+for+SCP%3A+Secret+Laboratory;Custom+roles+%C2%B7+items+%C2%B7+events+%C2%B7+game+modes;Powered+by+C%23+%26+EXILED;Containment+is+optional+%F0%9F%94%A5" alt="typing" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/SCP%3A_SL-Plugin_Dev-FF4D1A?style=for-the-badge&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/EXILED-Framework-FF4D1A?style=for-the-badge&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/C%23-.NET-FF4D1A?style=for-the-badge&logo=csharp&logoColor=white&labelColor=0D1117" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Discord-redovsky__scpsl-FF4D1A?style=for-the-badge&logo=discord&logoColor=white&labelColor=0D1117" />
  <img src="https://komarev.com/ghpvc/?username=Redovsky&label=VIEWS&color=FF4D1A&style=for-the-badge&labelColor=0D1117" />
</p>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%" height="2" />

## ▌ SUBJECT FILE

```yaml
subject:    Redovsky
clearance:  Level 4
role:       SCP:SL plugin developer
framework:  EXILED
language:   C#
discord:    redovsky_scpsl
status:     ● ACTIVE
```

```diff
+ Building plugins for SCP: Secret Laboratory
+ Custom roles, items, events and server tools
+ Always learning: Harmony, optimization, new EXILED features
- NullReferenceException
- Lag on 25/25 servers
```

## ▌ TOOLBOX

<p align="center">
  <img src="https://skillicons.dev/icons?i=cs,dotnet,git,github,vscode,visualstudio,unity,docker,linux,windows&theme=dark" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/EXILED-API-FF4D1A?style=flat-square&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/HarmonyLib-patching-FF4D1A?style=flat-square&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/Mirror-networking-FF4D1A?style=flat-square&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/YamlDotNet-configs-FF4D1A?style=flat-square&labelColor=0D1117" />
  <img src="https://img.shields.io/badge/RemoteAdmin-commands-FF4D1A?style=flat-square&labelColor=0D1117" />
</p>

<details>
<summary><b>🧩 What my plugins look like</b></summary>

```csharp
using System;
using Exiled.API.Features;
using PlayerHandlers = Exiled.Events.Handlers.Player;
using Exiled.Events.EventArgs.Player;

public class Plugin : Plugin<Config>
{
    public override string Name => "Redovsky.Plugin";
    public override string Author => "Redovsky";
    public override Version Version => new Version(1, 0, 0);

    public override void OnEnabled()
    {
        PlayerHandlers.Verified += OnVerified;
        base.OnEnabled();
    }

    public override void OnDisabled()
    {
        PlayerHandlers.Verified -= OnVerified;
        base.OnDisabled();
    }

    private void OnVerified(VerifiedEventArgs ev)
        => ev.Player.Broadcast(5, $"Welcome to the Foundation, {ev.Player.Nickname}!");
}
```

</details>

## ▌ CONTACT

<p align="center">
  <img src="https://img.shields.io/badge/Discord-redovsky__scpsl-0D1117?style=for-the-badge&logo=discord&logoColor=FF4D1A" />
  <a href="https://github.com/Redovsky"><img src="https://img.shields.io/badge/GitHub-Redovsky-0D1117?style=for-the-badge&logo=github&logoColor=FF4D1A" /></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF4D1A,100:0D1117&height=110&section=footer&animation=twinkling" />
</p>
