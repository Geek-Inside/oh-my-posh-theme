# oh-my-posh-theme
Theme for terminal based on https://ohmyposh.dev/

# WSL intallation
## Install oh-my-posh

```sudo wget https://github.com/JanDeDobbeleer/oh-my-posh/releases/latest/download/posh-linux-amd64 -O /usr/local/bin/oh-my-posh```

```sudo chmod +x /usr/local/bin/oh-my-posh```

## Setup profile for bash

```nano ~/.bashrc```

Add this line and save

```eval "$(oh-my-posh init bash --config https://raw.githubusercontent.com/Geek-Inside/oh-my-posh-theme/main/glup.omp.json)"```

Now reload profile

 ```source ~/.bashrc```
 
# PowerShell intallation
## Install oh-my-posh

```winget install JanDeDobbeleer.OhMyPosh -s winget```

## Setup profile for PS

```notepad $PROFILE```

Create or update profile by adding this line

```oh-my-posh init pwsh --config https://raw.githubusercontent.com/Geek-Inside/oh-my-posh-theme/main/glup.omp.json | Invoke-Expression```

Now reload PowerShell
