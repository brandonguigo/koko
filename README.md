# Koko

Koko is a management system for your laptop.

## Workspaces

Koko works on the principle of workspaces : you can have one workspace or you can inherit workspaces.
A workspace start with a `main.json` file inside a directory. At least 1 workspace needs to be declared.

All JSON configuration files will have the same schema :
```json
{
    "name": "main",
    "decription": "My main workspace",
    "items": [
      {
        "type": "mas",
        "bottles": [
          "GoodNotes"
        ]
      },
      {
        "type": "brew",
        "bottles": [
          "kubectl"
        ]
      }
    ],
    "preferences": []
}
```
This schema will define the configuration of your workspace.
