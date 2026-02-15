## CrazyAuctionsPlusX
This is an restart version of the [CrazyAuctionsPlus](https://www.spigotmc.org/resources/75655/) plugin.

Support the latest Minecraft version.

**Required Dependency:**  
- [Vault](https://www.spigotmc.org/resources/34315/)

---

### ✨ Features
- **Selling Items**: Sell your items on the global market  
- **Buying Items**: Purchase items listed by others  
- **Bidding Items**: Public auction your goods globally  
- UUID Support  
- GUI Global Market Interface  
- Custom Category Selector  
- CrazyAuctions Data Synchronization Support  
- Click Sound Effects  
- Item & Item Lore Blacklist  
- Item Repricing System  
- Configurable Tax Rate  
- Easy Shop Sign Setup  
- Simplified Command Configuration  
- **80% Customizable**: Messages, Permissions, GUI Settings, etc.  
- Permission Group Settings (Product Limits)  
- SQLite Support  
- Feature Toggle System  
- Database Backup (Manual/Auto)  
- Database Rollback (Restore from backup)  
- Tab Completion Support  
- Item Collection System  

---

> 💡 *Press `Tab` for command auto-completion*

### 🔑 Main Commands
| Command | Description |
|--------|-------------|
| `/ca view <Player>` | View all market items of a player |
| `/ca sell <Price> [Amount]` | List held item(s) for direct sale |
| `/ca bid <Price> [Amount>` | List held item(s) for auction |
| `/ca buy <Reward> [Amount] [ItemName]` | Purchase items from market |
| `/ca gui [sell/buy/bid]` | Open main market GUI |
| `/ca mail` | Manage canceled/expired items |
| `/ca listed` | View/manage your listed items |
| `/ca reload [Object]` | Reload configs/database |
| `/ca admin` | Access admin commands |
| `/ca help` | Show help menu |

### 👮 Admin Commands
| Command | Description |
|--------|-------------|
| `/ca admin backup` | Backup all plugin data locally |
| `/ca admin rollback [BackupFile]` | Restore data from backup |
| `/ca admin info [Player]` | View player information |
| `/ca admin synchronize` | Sync legacy CrazyAuctions data |
| `/ca admin itemcollection` | Manage item collection |
| `/ca admin printstacktrace` | Toggle stack trace logging |
| `/ca admin market` | Manage market data |
| `/ca admin player` | Manage player data |

### 📦 ItemCollection Commands *(Note: Typo preserved from source)*
| Command | Description |
|--------|-------------|
| `/ca admin itemcolletion add [DisplayName]` | Add item to collection |
| `/ca admin itemcolletion delete [DisplayName/UID]` | Remove item from collection |
| `/ca admin itemcolletion list` | List all collection items |
| `/ca admin itemcolletion give [DisplayName/UID] [Player]` | Give collection item to player |

### 🌐 Market Commands (Admin)
`/ca admin market clear` • `/ca admin market confirm` • `/ca admin market list [Page]`  
`/ca admin market delete [UID]` • `/ca admin market repricing [UID] [Money]`  
`/ca admin market download` *(DB mode)* • `/ca admin market upload` *(DB mode)*

### 👤 Player Commands (Admin)
`/ca admin player confirm` • `/ca admin player [name] clear [market/mail]`  
`/ca admin player [name] list [Page]` • `/ca admin player [name] delete [UID]`  
`/ca admin player [name] view` • `/ca admin player [name] download/upload` *(DB mode)*

---

### 🔄 Migration Guide: CrazyAuctions → CrazyAuctionsPlusX
1. Download `CrazyAuctionsPlusX.jar` and [`Vault.jar`](https://www.spigotmc.org/resources/34315/)
2. Place both `.jar` files into your server's `plugins/` folder
3. Start server and wait for `CrazyAuctionsPlusX/` folder generation
4. Copy `Data.yml` from original CrazyAuctions folder into `CrazyAuctionsPlusX/`
5. Run command: `/ca admin synchronize` *(may take seconds to minutes)*
6. ✅ Migration complete! All legacy data synced successfully.

---

[![bStats](https://bstats.org/signatures/bukkit/CrazyAuctionsPlusX.svg)](https://bstats.org/plugin/bukkit/CrazyAuctionsPlusX/23790)

---

### *If you want to support my work, you can subscribe my [Patreon](https://www.patreon.com/Author87668/join) membership.*