# vagrantaliases


##How to install?

clone this in your oh my zsh plugins folder
```bash
git clone https://github.com/kalehrishi/vagrantaliases.git ~/.oh-my-zsh/plugins/vagrantaliases
```


Next step is enable this plugin in `.zshrc`. You just have to add it to your existing plugins list.

```bash
# Which plugins would you like to load? (plugins can be found in ~/.oh-my-zsh/plugins/*)
# Custom plugins may be added to ~/.oh-my-zsh/custom/plugins/
# Example format: plugins=(rails git textmate ruby lighthouse)
# Add wisely, as too many plugins slow down shell startup.
plugins=(git z vagrant sublime vagrantaliases)

```


##Shortcuts
| Shortcut      | Full command                    |
| ------------- |:-------------------------------:|
| vu            | vagrant up                      |
| vh            | vagrant destroy                 |
| vpr           | vagrant global-status --prune   |
| vbl           | vagrant box list                |
| vidb75        | vagrant init debian75-x64-11    |
| vidb8         | vagrant init debian81x64-00     |
