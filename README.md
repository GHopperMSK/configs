## ~/.bashrc
Exports PS1 command prompt with *user@host + current_location + git_branch* colorful information.

## ~/.gitconfig
Sets vim as default editor. Fills name and email global vars.

## ~/.vimrc
Sets tab as 4 spaces and quite convenient status bar.

## vs_code
Configuration files for Visual Studio Code IDE.

### ~/.config/Code/User/keybindings.json
Binds familiar shortcuts for Prev/Next tab switching.

### ~/.config/Code/User/settings.json
Open a file / unfold directory by double clicking.

### extensions list
```
$ code --list-extensions
Anjali.clipboard-history
alefragnani.Bookmarks
felixfbecker.php-debug
felixfbecker.php-intellisense
slevesque.vscode-multiclip
vscodevim.vim
whatwedo.twig
```

### xDebug configuration
```json
"configurations": [
    {
        "name": "Listen for XDebug",
        "type": "php",
        "request": "launch",
        "port": 9000,
        "pathMappings": {
            "server_path": "${workspaceRoot}"
        }
    }
]
```
