Simple Login/Register System for FiveM Servers.

### Requirements
- [OxMySQL](https://github.com/overextended/oxmysql/releases)

### Installation
- Drag & Drop into your resource files and make sure you start it trought server config.
- Login/Register form will be triggered after player spawns. Trigger
```lua
AddEventHandler('playerSpawned', function()
    SetNuiFocus(true, true)
    SendNUIMessage({ 
        event = 'login'
    })
end)
```

![image](https://i.imgur.com/Ib6eY6c.png)