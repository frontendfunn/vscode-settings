### Complete list of settings - `settings.json` file

```
{
    "highlight-matching-tag.highlightSelfClosing": true,
    "highlight-matching-tag.styles": {
        "opening": {
            "full": {
                "custom": {
                    "color": "yellow"
                }
            }
        },
        "closing": {
            "full": {
                "custom": {
                    "color": "yellow"
                }
            }
        }
    },
    "editor.formatOnSave": true,
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "editor.fontSize": 16,
    "editor.fontFamily": "'JetBrains Mono',Consolas, 'Courier New', monospace",
    "editor.fontLigatures": true,
    "[javascriptreact]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "workbench.iconTheme": "material-icon-theme",
    "[vue]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "editor.wordWrap": "on",
    "javascript.updateImportsOnFileMove.enabled": "always",
    "explorer.compactFolders": false,
}
```

## List of Extensions / Plugins used

- ## Plugins / Extensions

  - [Highlight Matching Tag](https://marketplace.visualstudio.com/items?itemName=vincaslt.highlight-matching-tag) - used for highlighting the <b>opening</b> and <b>closing</b> tags of the html tags.

  Note :- change the <b>yellow</b> color if needed.

  ```
  {
  "highlight-matching-tag.highlightSelfClosing": true,
      "highlight-matching-tag.styles": {
          "opening": {
              "full": {
                  "custom": {
                      "color": "yellow"
                  }
              }
          },
          "closing": {
              "full": {
                  "custom": {
                      "color": "yellow"
                  }
              }
          }
      }
  }
  ```

- ## Editor Settings

  - [Jet Brains Mono](https://www.jetbrains.com/lp/mono/) - developer font from JetBrains

  ```
  {
      "editor.formatOnSave": true,
      "editor.fontSize": 16,
      "editor.fontFamily": "'JetBrains Mono',Consolas, 'Courier New', monospace",
      "editor.fontLigatures": true,
      "editor.wordWrap": "on",
  }
  ```

- ## Workbench Icon Theme

  - [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) - used for file icons in the explorer menu

  ```
    {
        "workbench.iconTheme": "material-icon-theme",
    }
  ```

- ## Language Specific Formatter

  - [prettier-vscode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) - used for code formatting

  ```
  {
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
        },
    "[javascriptreact]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[vue]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
  }
  ```
