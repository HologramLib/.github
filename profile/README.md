<div align="center">
  <img width="650px" src="https://github.com/HologramLib/HologramLib/blob/master/assets/banner.png?raw=true" alt="HologramLib Banner">

[![Discord](https://img.shields.io/badge/Discord_Server-7289DA?style=flat&logo=discord&logoColor=white)](https://discord.gg/2UTkYj26B4)
[![Latest Release](https://img.shields.io/github/v/release/HologramLib/HologramLib?color=blue&label=Latest%20Release)](https://github.com/HologramLib/HologramLib/releases)
[![License](https://img.shields.io/github/license/HologramLib/HologramLib?color=green)](https://github.com/HologramLib/HologramLib/blob/master/LICENSE)
[![JavaDocs](https://img.shields.io/badge/API-Docs-2ECC71)](https://hologramlib.github.io/HologramLib/)
[![Wiki](https://img.shields.io/badge/Documentation-Wiki-2dad10)](https://github.com/max1mde/HologramLib/wiki)

</div>

## ⚡ About HologramLib

HologramLib is a modern hologram library for Minecraft servers (1.19.4 → 1.21.4) using display entities.  
Designed for Paper, Purpur, and Folia servers, it offers:

- Text, Block & Item Holograms
- Text animations with MiniMessage & ItemsAdder emoji support
- Packet-based implementation for optimal performance
- Per-player hologram visibility
- Automated leaderboard generation
- Advanced customization options
- Entity attachment support

<br>

<a href="https://github.com/HologramLib/HologramLib/releases/download/1.7.1/HologramLib-1.7.1.jar">
  <img width="100px" src="https://github.com/HologramLib/Addons/blob/main/download.svg" alt="Download"/>
</a>

<br>
<br>

## 📦 Dependencies (Required)  
- **[PacketEvents](https://www.spigotmc.org/resources/80279/)**

<br>

## ⚙️ Addons
Not a developer but want to use HologramLib or add even more features?  
Check out: [HologramLib Addons](https://github.com/HologramLib/Addons)

<br>

## 🚀 Quick Start
Add to your build.gradle:
```gradle
repositories {
    maven { url 'https://jitpack.io' }
}

dependencies {
    implementation 'com.github.maximjsx:HologramLib:1.7.1'
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
| [🧑💻 Javadocs](https://hologramlib.github.io/HologramLib/) | API Reference |

<br>

## 💬 Support
Found an issue? [Open an issue](https://github.com/HologramLib/HologramLib/issues) or join the [Discord server](https://discord.gg/2UTkYj26B4)  
