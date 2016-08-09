# Environment Setup

A modulair approach to initialize a (development) environment. Some plugins like homebrew, iterm and quicklook will only work on osx. It is possible to disable them in the [environment.conf](environment.conf) file. 

The goal of this approach is to make it easy to custimize and creation of custom plugins.

## Gettings started

Start by cloning the repo:

	git clone https://github.com/patrickkempff/environment-setup.git && cd environment-setup

and run the setup by typing the following command, the plugins configured in [environment.conf](environment.conf) will be installed

	./install


## Plugins

To enable/disable certain plugins take a look at the [environment.conf](environment.conf) file.

Example:

```
environment_install homebrew
environment_install macos
environment_install rvm
environment_install nvm
environment_install iterm
environment_install vagrant
environment_install macdown
environment_install adobe
environment_install apps
environment_install quicklook
environment_install vscode
environment_install docker
```


### Homebrew

The homebrew plugin will install homebrew itself and several homebrew packages like GNU moreutils, bash 4, wget and git. Take a look in [plugins/homebrew](plugins/homebrew) for more information.

### macOS

The macos will set several osx preferences like disabling autocorrect, showing hidden files, save screenshots in a custom folder and more. Take a look in [plugins/macos](plugins/macos) for more information.
	
### RVM

Installs RVM. See [plugins/rvm](plugins/rvm) for more information.
	
### NVM

Installs NVM. See [plugins/nvm](plugins/nvm) for more information.

### Vagrant

Installs vagrant and virtualbox with virtualbox extension pack. More info [plugins/vagrant](plugins/vagrant)

### iTerm

Installs iTerm and adds the DimmedMonokai theme. See [plugins/iterm](plugins/iterm) for more information.

### MacDown

Installs the latest version of MacDown. See [plugins/macdown](plugins/macdown) for more information.

### Visual Studio Code

This plugin installs the latest version of Visual Studio Code. See [plugins/vscode](plugins/vscode) for more information.

### Docker

This plugin installs the latest version of Docker. See [plugins/docker](plugins/docker) for more information.
	
### Adobe Creative Cloud 

This plugin installs the creative cloud app which can be used to install Photoshop, Illustrator, Lightroom, After Effects and more. See [plugins/adobe](plugins/adobe)			
	
### Apps

Installs the latest versions of the following apps:

* 1Password
* Google Chrome
* Firefox
* Skype

For more information see [plugins/apps](plugins/apps).
		
### Quicklook

Install developer friendly quick look plugins; see [https://github.com/sindresorhus/quick-look-plugins](https://github.com/sindresorhus/quick-look-plugins)
		