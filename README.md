# VSCode Snippets

## Overview

- Install snippets from the Marketplace: `@category:"snippets"`
- Location
  - Windows: `C:\Users\<username>\AppData\Roaming\Code\User\snippets`
  - macOS: `~/Library/Application\ Support/Code/User/snippets`
- Syntax： [TextMate Snippets](https://manual.macromates.com/en/snippets)

## Quick Installation

macOS

```sh
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/yutao86/VSCodeSnippets/master/install.sh)"
```

## Manual Installation

Windows

```powershell
Remove-Item "$ENV:USERPROFILE\AppData\Roaming\Code\User\snippets" -Recurse
New-Item -Path "$ENV:USERPROFILE\AppData\Roaming\Code\User\snippets" -ItemType SymbolicLink -Value "$ENV:USERPROFILE\VSCodeSnippets"
```

macOS

```sh
# todo
```

## References

- [Snippets in Visual Studio Code](https://code.visualstudio.com/docs/editor/userdefinedsnippets)
- [VScode Snippets – How to code faster and easier?](https://pagepro.co/blog/vs-code-snippets-how-to-code-faster-and-easier/)
- [Snippet Generator](https://snippet-generator.app/)

