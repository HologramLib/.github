<div align="center">
  <a href="https://github.com/HologramLib/HologramLib"><img width="650px" src="https://github.com/user-attachments/assets/3d5feb84-ff80-42d2-9293-9bea07bc954c" alt="HologramLib Banner"></a>

[![Discord](https://img.shields.io/badge/Discord_Server-7289DA?style=flat&logo=discord&logoColor=white)](https://discord.gg/2UTkYj26B4)
[![Latest Release](https://img.shields.io/github/v/release/HologramLib/HologramLib?color=blue&label=Latest%20Release)](https://github.com/HologramLib/HologramLib/releases)
[![License](https://img.shields.io/github/license/HologramLib/HologramLib?color=green)](https://github.com/HologramLib/HologramLib/blob/master/LICENSE)
[![JavaDocs](https://img.shields.io/badge/API-Docs-2ECC71)](https://hologramlib.github.io/HologramLib/)
[![Wiki](https://img.shields.io/badge/Documentation-Wiki-2dad10)](https://github.com/max1mde/HologramLib/wiki)

</div>

## What is HologramLib?

HologramLib is a modern hologram library for Minecraft servers (1.19.4 → 1.21.8) using display entities.  
It is designed for Paper, Purpur, and Folia.

### What Features Does HologramLib Offer?

- Text, Block & Item Holograms
- Text animations with MiniMessage & ItemsAdder emoji support
- Packet-based implementation for optimal performance
- Per-player hologram visibility
- Automated leaderboard generation
- Advanced customization options
- Entity attachment support

<br>
<a href="https://github.com/HologramLib/HologramLib/releases/download/1.8.0/HologramLib-1.8.1.jar">
  <img width="200px" src="https://github.com/HologramLib/Addons/blob/main/download_jar.svg" alt="Download"/>
</a>

<br>
<br>

## 📦 Dependencies (Required)  
- **[PacketEvents](https://www.spigotmc.org/resources/80279/)**

<br>

## Extend HologramLib via addons?
Not a developer but want to use HologramLib or add more features? 
Check out: [HologramLib Addons](https://github.com/HologramLib/Addons)

<br>

## 🚀 Quick Start
Add to your build.gradle:
```gradle
repositories {
    maven { url 'https://jitpack.io' }
}

dependencies {
    implementation 'com.github.HologramLib:HologramLib:1.7.1'
}
```

Basic usage:
```java
HologramManager manager = HologramAPI.getManager().get();

TextHologram hologram = new TextHologram("unique_id")
    .setMiniMessageText("<aqua>Hello world!")
    .setSeeThroughBlocks(false)
    .setShadow(true)
    .setScale(1.5F, 1.5F, 1.5F)
    .setTextOpacity((byte) 200)
    .setBackgroundColor(Color.fromARGB(60, 255, 236, 222).asARGB())
    .setMaxLineWidth(200);

manager.spawn(hologram);
```

<br>

## 📚 Learning Resources

| Resource | Description | 
|----------|-------------|
| [📖 Complete Wiki](https://github.com/HologramLib/HologramLib/wiki) | Setup guides • Detailed examples • Best practices |
| [💡 Example Plugin](https://github.com/HologramLib/ExamplePlugin) | Production-ready implementations |
| [💻 Javadocs](https://hologramlib.github.io/HologramLib/) | API Reference |

<br>

## 💬 Support
Found an issue? [Open an issue](https://github.com/HologramLib/HologramLib/issues) or join the [Discord server](https://discord.gg/2UTkYj26B4) to get support.  

<br>

<div align="center">
  <sub>Used by 80+ servers | 7,000+ downloads across platforms</sub><br>
  <a href="https://www.spigotmc.org/resources/111746/">SpigotMC</a> •
  <a href="https://hangar.papermc.io/maximjsx/HologramLib">Hangar</a> •
  <a href="https://modrinth.com/plugin/hologramlib">Modrinth</a> •
  <a href="https://maximjsx.com/projects/hologramlib">Maxim.jsx</a> •
  <a href="https://github.com/HologramLib/HologramLib/releases/latest">Latest Release</a> •
  <a href="https://discord.gg/2UTkYj26B4">Support</a><br>
  <sub>License: GPL-3.0 | © 2025 <a href="https://github.com/maximjsx/">Maxim</a></sub>
</div>

