{
    "name": "FreqTrade Development Environment",
    "image": "freqtradeorg/freqtrade:stable",
    "forwardPorts": [8000],
    "mounts": [
        "source=${localEnv:USERPROFILE}/ft_userdata/freqtrade/config.json,target=/freqtrade/user_data/config.json,type=bind,consistency=cached"
    ],
    "remoteUser": "ftuser",
    "settings": {
        "terminal.integrated.shell.linux": "/bin/bash",
        "editor.insertSpaces": true,
        "files.trimTrailingWhitespace": true,
        "[markdown]": {
            "files.trimTrailingWhitespace": false
        },
        "python.pythonPath": "/usr/local/bin/python"
    },
    "extensions": [
        "ms-python.python",
        "ms-python.vscode-pylance",
        "davidanson.vscode-markdownlint",
        "ms-azuretools.vscode-docker",
        "vscode-icons-team.vscode-icons"
    ],
    "onCreateCommand": "pip install --user -e .",
    "postCreateCommand": "freqtrade create-userdir --userdir user_data/"
}
