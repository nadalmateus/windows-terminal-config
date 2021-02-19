# My config: 😊

{ "$schema": "https://aka.ms/terminal-profiles-schema", "defaultProfile": "{574e775e-4f2a-5b96-ac1e-a2962a402336}",

    "theme": "dark",
    "copyOnSelect": false,
    "copyFormatting": false,
    "showTabsInTitlebar": false,
    "showTerminalTitleInTitlebar": false,
    "alwaysShowTabs": true,
    
    "profiles": {
      "defaults": {   
        "fontFace": "Fira Code",
        "fontSize": 11,
        "useAcrylic": true,
        "acrylicOpacity": 0.8     
      },
      "list": [
        {
          "guid": "{61c54bbd-c2c6-5271-96e7-009a87ff44bf}",
          "name": "Windows PowerShell",
          "commandline": "powershell.exe",
          "hidden": false
        },
        {
        
          "guid": "{0caa0dad-35be-5f56-a8ff-afceeeaa6101}",
          "name": "Prompt de comando",
          "commandline": "cmd.exe",
          "hidden": false
        },
        {
          "guid": "{b453ae62-4e3d-5e58-b989-0a998ec441b8}",
          "hidden": false,
          "name": "Azure Cloud Shell",
          "source": "Windows.Terminal.Azure"
        },
        {
          "guid": "{574e775e-4f2a-5b96-ac1e-a2962a402336}",
          "hidden": false,
          "name": "PowerShell",
          "source": "Windows.Terminal.PowershellCore"
        }
      ]
    },   
    "keybindings": [
     
      {
        "command": {
          "action": "copy",
          "singleLine": false
        },
        "keys": "ctrl+c"
      },
      {
        "command": "paste",
        "keys": "ctrl+v"
      },
      
      {
        "command": "find",
        "keys": "ctrl+shift+f"
      },
     
      {
        "command": {
          "action": "splitPane",
          "split": "auto",
          "splitMode": "duplicate"
        },
        "keys": "alt+shift+d"
      }
    ]
    }
