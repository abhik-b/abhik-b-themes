# Green Accent Writer Theme README

This theme is mainly designed for writing **MARKDOWN**. This is a dark theme. This theme is built for my own needs. I will highly encourage you to use it for writing purposes.

## ScreenShots

![](/screenshots/Screenshot%201.png)
![](/screenshots/Screenshot%202.png)

## How to customize ?

You can customize the UI Colors of vscode by changing the properties in `settings.json`. To open `settings.json` , open command pallete & search for **"Preferences : Open User Settings (JSON)"** & then customize the properties like below(example):

> Note : This will customize only this theme colors

```json
"workbench.colorCustomizations": {
    ["Green Accent Writer Theme"]:{
        "editor.background": "#22272e",
        "editor.foreground": "#eee",
        "activityBar.activeBorder": "#3aac72",
        "activityBarBadge.background": "#3aac72",
        "tab.activeBorder": "#3aac72",
  }
},

  "editor.tokenColorCustomizations": {
    ["Green Accent Writer Theme"]:{
        "textMateRules": [
            {
            "name": "Support type",
            "scope": [
                "support.type.property-name",
            ],
            "settings": {
                "foreground": "#ddd"
            }
            },
            {
            "name": "Support",
            "scope": "support.function",
            "settings": {
                "foreground": "#06d6a0"
            }
            },
            {
            "name": "Attribute class",
            "scope": [
                "entity.other.attribute-name.class.css",
            ],
            "settings": {
                "foreground": "#ffe74e"
            }
            },
            {
            "name": "Attribute IDs",
            "scope": [
                "entity.other.attribute-name.id",
                "entity.other.attribute-name.id.css"
            ],
            "settings": {
                "fontStyle": "italic",
                "foreground": "#cd69ff"
            }
            },
            {
            "name": "Tags",
            "scope": [
                "entity.name.tag",
                "entity.name.tag.css"
            ],
            "settings": {
                "foreground": "#58afff"
            }
            },
            {
            "name": "markup.italic.markdown",
            "scope": "markup.italic.markdown",
            "settings": {
                "fontStyle": "italic",
                "foreground": "#fc5ff7"
            }
            },
            {
            "name": "markup.bold.markdown",
            "scope": "markup.bold.markdown,punctuation.definition.bold.markdown",
            "settings": {
                "fontStyle": "bold",
                "foreground": "#fcea5f"
            }
            },
            {
            "name": "[VSCODE-CUSTOM] Markdown headings",
            "scope": [
                "entity.name.section.markdown",
                "punctuation.definition.heading.markdown"
            ],
            "settings": {
                "foreground": "#fe4863"
            }
            },
            {
            "name": "punctuation.definition.list.begin.markdown",
            "scope": "punctuation.definition.list.begin.markdown",
            "settings": {
                "foreground": "#06d6a0"
            }
            },
            {
            "name": "[VSCODE-CUSTOM] Markdown Link Title/Description",
            "scope": "string.other.link.title.markdown,string.other.link.description.markdown",
            "settings": {
                "foreground": "#42a2fd"
            }
            },
            {
            "name": "Integers",
            "scope": "constant.numeric",
            "settings": {
                "foreground": "#ffdb93"
            }
            },
            {
            "name": "js/ts variable.other.constant",
            "scope": "variable.other.constant",
            "settings": {
                "foreground": "#ddd"
            }
            },
        ]
    }
  },
```
