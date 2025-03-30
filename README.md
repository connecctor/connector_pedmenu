### 📝 Docs
- Visit : https://connector.mintlify.app

##

### 👕 Ped Menu
- Version 1.0.0
- ESX/QBCore Compatible
- ox_lib Required

##

### 🔨 Usage  
- #### 💻 Installation
     ```bash
     cd resources
     git clone https://github.com/connecctor/connector_pedmenu.git
     ensure connector_pedmenu
     ```
- #### ⚙️ Configuration
      1. Edit `config.lua` to add/remove characters
      2. Set Discord role ID or `false` to disable
      3. Use `/pedmenu` in-game

##  

### 🏆 Features
- 🔄 Appearance Restoration
- 🛡️ Role-Based Permissions
- 🎨 OX_LIB Context Menu

##   

### ❓ Roadmap

- Add Discord Webhook Logging 
- Add support for custom animations
- Create character preview system

##

### 📚 API Reference
```lua
-- Client exports
exports('ped-changer'):StoreAppearance()
exports('ped-changer'):RestoreAppearance()

-- Server event
TriggerClientEvent('pedchanger:openMenu', playerId)
```

##

<p align="center"> <img src="https://badges.frapsoft.com/os/v3/open-source.svg?v=103" alt="Open Source"> <img src="https://img.shields.io/badge/Lua-2C2D72?style=flat&logo=lua&logoColor=white"> <img src="https://img.shields.io/badge/FiveM-compatible-green"> </p>
