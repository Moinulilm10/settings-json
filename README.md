{
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "C_Cpp.updateChannel": "Insiders",
  "code-runner.executorMap": {
    "c": "cd $dir && gcc $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
    "cpp": "cd $dir && g++ $fileName -o $fileNameWithoutExt && $dir$fileNameWithoutExt",
    "python": "python",
    "javascript": "node"
  },
  // auto closing tag setting json
  "html.autoClosingTags": true,
  "javascript.autoClosingTags": true,
  "typescript.autoClosingTags": true,
  // auto import setting setting json
  "javascript.suggest.autoImports": true,
  "typescript.suggest.autoImports": true,
  "typescript.updateImportsOnFileMove.enabled": "always",
  "source.organizeImports": true,
  "files.trimTrailingWhitespace": true,
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features"
  },
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "liveServer.settings.donotShowInfoMsg": true,
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "php.validate.executablePath": "C:/xampp/php/php.exe",
  "editor.formatOnPaste": true,
  "open-php-html-js-in-browser.selectedBrowser": "Chrome",
  "open-php-html-js-in-browser.customUrlToOpen": "http://localhost/${relativeDirnameDocumentRoot}/${fileBasename}",
  "open-php-html-js-in-browser.documentRootFolder": "C:\\xampp\\htdocs",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "liveSassCompile.settings.formats": [
    // This is default.
    {
      "format": "expanded",
      "extensionName": ".css",
      "savePath": "/dist/css"
    }
  ],
  "editor.formatOnType": true,
  "liveServer.settings.CustomBrowser": "chrome",
  "workbench.colorCustomizations": {
    "editor.lineHighlightBackground": "#1073cf2d",
    "editor.lineHighlightBorder": "#9fced11f"
  },
  "diffEditor.wordWrap": "on",
  "cmake.configureOnOpen": true,
  "terminal.integrated.profiles.linux": {
    "bash": {
      "path": "bash",
      "icon": "terminal-bash"
    },
    "zsh": {
      "path": "zsh"
    },
    "fish": {
      "path": "fish"
    },
    "tmux": {
      "path": "tmux",
      "icon": "terminal-tmux"
    },
    "pwsh": {
      "path": "pwsh",
      "icon": "terminal-powershell"
    }
  },
  "editor.suggestSelection": "first",
  "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
  "better-comments.highlightPlainText": true,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "tabnine.experimentalAutoImports": true,
  "[json]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "editor.wordWrap": "on",
  "editor.bracketPairColorization.enabled": true,
  "emmet.triggerExpansionOnTab": true,
  "files.associations": {
    "*html": "html"
  },
  "code-runner.runInTerminal": true,
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
    "Windows PowerShell": {
      "path": "C:\\WINDOWS\\System32\\WindowsPowerShell\\v1.0\\powershell.exe"
    },
    "C:\\Program Files\\Git\\bin\\bash.exe (migrated)": {
      "path": "C:\\Program Files\\Git\\bin\\bash.exe",
      "args": []
    },
    "Ubuntu (WSL)": {
      "path": "C:\\WINDOWS\\System32\\wsl.exe",
      "args": [
        "-d",
        "Ubuntu"
      ]
    }
  },
  // "terminal.integrated.automationProfile.windows": {
  // },
  // "terminal.integrated.automationProfile.linux": {
  // },
  // "terminal.integrated.automationProfile.osx": {
  // },
  "editor.accessibilitySupport": "off",
  "editor.cursorSmoothCaretAnimation": true,
  "editor.cursorBlinking": "phase",
  "editor.linkedEditing": true,
  "[cpp]": {
    "editor.defaultFormatter": "ms-vscode.cpptools"
  },
  "remote.SSH.defaultExtensions": [
    "gitpod.gitpod-remote-ssh"
  ],
  "remote.SSH.configFile": "C:\\Users\\MOINUL~1\\AppData\\Local\\Temp\\gitpod_ssh_config-10796-SmI9en2WosFq",
  "terminal.integrated.enableMultiLinePasteWarning": false,
  "git.autofetch": true,
  "editor.guides.indentation": true,
  "java.jdt.ls.java.home": "C:\\Program Files\\Java\\jdk-18.0.1.1",
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.cursorWidth": 2,
  "editor.stickyScroll.enabled": true,
  "terminal.integrated.gpuAcceleration": "on",
  "workbench.iconTheme": "material-icon-theme",
  "workbench.colorTheme": "Learn with Sumit Theme",
  "terminal.integrated.defaultProfile.windows": "PowerShell",
  "code-runner.saveAllFilesBeforeRun": true,
  "code-runner.saveFileBeforeRun": true,
  "http.proxySupport": "off",
  "[php]": {
    "editor.defaultFormatter": "bmewburn.vscode-intelephense-client"
  },

  // better comments
  "better-comments.multilineComments": true,
  "better-comments.tags": [
    {
      "tag": "!",
      "color": "#FF2D00",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "?",
      "color": "#3498DB",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "//",
      "color": "#474747",
      "strikethrough": true,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "todo",
      "color": "#FF8C00",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    },
    {
      "tag": "*",
      "color": "#98C379",
      "strikethrough": false,
      "underline": false,
      "backgroundColor": "transparent",
      "bold": false,
      "italic": false
    }
  ],

  "githubPullRequests.pullBranch": "never",
  "cSpell.userWords": [
    "Moinul",
    "signup"
  ],
  "editor.formatOnSave": true,
  "editor.inlineSuggest.enabled": true,
  "[python]": {
    "editor.formatOnType": true
  },
}
