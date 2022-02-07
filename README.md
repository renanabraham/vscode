{
    "workbench.colorTheme": "Dracula",
    "php.validate.executablePath": "C:\\laragon\\bin\\php\\php-7.4.19-Win32-vc15-x64\\php.exe",
    "workbench.iconTheme": "material-icon-theme",

        // Is git enabled
        "git.enabled": true,

        // Path to the git executable
        "git.path": "C:\\laragon\\bin\\git\\bin\\git.exe",
    
        // other settings

    //codigo para o terminal do laragon
    "terminal.integrated.profiles.windows": {
        "PowerShell": {
            "source": "PowerShell",
            "icon": "terminal-powershell"
        },
        "Command Prompt": {
            "path": [
                "${env:windir}\\Sysnative\\cmd.exe",
                "${env:windir}\\System32\\cmd.exe"
            ],
            "args": [],
            "icon": "terminal-cmd"
        },
        "Git Bash": {
            "source": "Git Bash"
        },
        "laragon": {
            "path": "C:\\laragon\\bin\\cmder\\cmder.bat",
            "args": [
                "."
            ],
        },
    },
    "terminal.integrated.defaultProfile.windows": "laragon"
}
