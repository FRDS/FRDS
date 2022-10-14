
# CTR-ModSDK

A toolkit to create mods for Crash Team Racing (PS1) in C.

[![Contributors][contributors-badge]][contributors-link] [![Discord Server][discord-badge]][discord]

[contributors-link]: https://github.com/CTR-Tools/CTR-ModSDK/graphs/contributors
[contributors-badge]: https://img.shields.io/github/contributors/CTR-Tools/CTR-ModSDK

[discord]: https://discord.gg/WHkuh2n
[discord-badge]: https://img.shields.io/discord/527135227546435584?color=%237289DA&logo=discord&logoColor=ffffff

This project has been made possible with the [CTR Decompilation Project](https://github.com/CTR-tools/CTR-ModSDK#CTR-in-C), make sure to check it out.

This SDK uses [psx-modding-tools](https://github.com/mateusfavarin/psx-modding-toolchain) by [mateusfavarin](https://github.com/mateusfavarin).

Watch our mod showcases: 

[![Mod Showcases](https://img.youtube.com/vi/BeuqK96udfs/hqdefault.jpg)](https://www.youtube.com/watch?v=AXJuTpw373g&list=PL2jaTxWyUt6yOsEhidU4zAENmCXetvbNW&index=1)

# Features 📃

## As End-user
- ✔ 60 FPS
- ✔ Nitros Oxide as a playable character
- ✔ Playable bosses on Adventure Mode
- ✔ Character Class/Engine swapping
- ✔ Updated physics brought from Nitro-Fueled
- ✔ In-Game Timer and Practice Tools for Speedrun
- ✔ Custom Texture
- ✔ Custom Cups
- ✔ Virtual Reality Play
- ⏳ Custom Character Model
- ⏳ Custom Level
- ⏳ OnlineCTR: Real-time non-Splitscreen Online Multiplayer

Check out our [latest releases](https://github.com/CTR-tools/CTR-ModSDK/releases/latest).

## As Modder/Developer

- Extract and build ISO in few steps
- Easy mod installation and deployment
- Supports all retail versions and more
- Compile C code into any address and overlays
- Hot Swap: Swap mods while the game is running

# 🏁 How to Start Modding

## Requirements

- python 3+

## Downloading the SDK

Clone this repository:
`$ git clone https://github.com/CTR-Tools/CTR-ModSDK.git`

You can find [example mods](https://github.com/CTR-tools/CTR-ModSDK/tree/main/psx-modding-toolchain/games/CrashTeamRacing/mods) in our repo.


# CTR-in-C

Work-in-progress project to decompile Crash Team Racing into human-readable C code.

[![Decompile Overview](https://img.youtube.com/vi/V9QlFzSVDAU/hqdefault.jpg)](https://www.youtube.com/watch?v=V9QlFzSVDAU)

## 📊 Progress
### Research and Decompilation

Decompiling the assembly assisted by Ghidra, researching how it works and adding comments for guidelines.

![](https://progress-bar.dev/97/?width=300&title=USA&suffix=%%20done)

### Code Rewrite

Rewriting Ghidra output to human-readable C Code and testing if it matches.
Most of the source code are shared between versions.

- ![](https://progress-bar.dev/92/?scale=1171&width=300&title=USA&suffix=%20functions%20out%20of%201171*)
- ![](https://progress-bar.dev/22/?scale=1171&width=300&title=PAL&suffix=%20functions%20out%20of%201200*)
- ![](https://progress-bar.dev/94/?scale=1171&width=300&title=JPN&suffix=%20functions%20out%20of%201200*)

* These are not accurate numbers and subject to change.

## 🤝 Contributing

Are you interested in contributing? Have any experience in C programming language? You're welcome to join!

Get in touch with us through our [Discord](https://discord.gg/WHkuh2n) or you can directly take a look at our [decomp directory](https://github.com/CTR-tools/CTR-ModSDK/tree/main/psx-modding-toolchain/games/CrashTeamRacing/decompile). 
