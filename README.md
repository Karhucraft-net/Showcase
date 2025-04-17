[![Header](https://i.imgur.com/your-header-image.png)](https://karhucraft.net)
*(Click the banner to visit our website!)*

Welcome to the official GitHub repository for **Karhucraft**, Finland's newest and most exciting Minecraft survival server! Here you'll find our custom plugins, configurations, and development resources.

## 🌐 Server Information
- **IP**: `karhucraft.net`
- **Version**: 1.21.5
- **Game Type**: Enhanced Survival with Economy
- **Discord**: [Join our community](https://discord.gg/karhucraft)

## 🔥 Server Features
- Custom survival experience with quality-of-life improvements
- Player-driven economy with shops and auctions
- Unique custom items and weapons
- Land protection system
- Quests and achievements system
- Active and friendly community

## 🛠️ Featured Projects

Upcoming...

<!--
### Core Systems
[![Karhucraft-Core](https://github-readme-stats.vercel.app/api/pin/?username=yourusername&repo=Karhucraft-Core&theme=dark)](https://github.com/yourusername/Karhucraft-Core)
Our main server core handling economy, ranks, and core functionalities.

### Custom Items
[![Custom-Items](https://github-readme-stats.vercel.app/api/pin/?username=yourusername&repo=Karhucraft-Items&theme=dark)](https://github.com/yourusername/Karhucraft-Items)
Plugin for all our unique weapons, tools, and armor with special abilities.

### Shop System
[![Shop-System](https://github-readme-stats.vercel.app/api/pin/?username=yourusername&repo=Karhucraft-Shops&theme=dark)](https://github.com/yourusername/Karhucraft-Shops)
Advanced player shop and auction house system.
-->
## 💻 Code Highlights

### Custom Rank System
```java
public enum PlayerRank {
    KARHU(5, Arrays.asList("3 homes", "basic particles")),
    KARHU_PLUS(10, Arrays.asList("5 homes", "creative plots")),
    KARHU_PLUS_PLUS(25, Arrays.asList("10 homes", "/fly in hub")),
    KARHU_KING(50, Arrays.asList("unlimited homes", "custom warps"));
    
    private final double price;
    private final List<String> perks;
    
    // Constructor and getters
}
