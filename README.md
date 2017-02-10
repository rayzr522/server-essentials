# ServerEssentials
> A simple script for installing all the essentials of a simple Spigot server

This is a simple **\*nix** script for installing all the essentials for a simple Spigot server. It downloads the latest version of:

* Spigot
* EssentialsX
* ProtocolLib
* Multiverse (Core and NetherPortals)
* PlugMan
* PermissionsEx
* Vault
* WorldEdit
* WorldGuard

It also creates a simple start script that runs your server with *4GB of RAM*, and automatically sets the EULA to agreed. (*Note: by using this script **you are agreeing to the Mojang EULA***)

## Installation
I've only tested this on *macOS Sierra 10.12.2* so far, but \*crosses fingers\* it should work on all \*nix operating systems. I'm not using anything fancy, just the basic commands as well as *curl*. You can download the script and run it yourself, it will install the server in to whatever your current directory is.

As a secondary usage, you can do the following and run it without downloading the script to your harddrive:

```bash
curl -fsSL https://raw.githubusercontent.com/Rayzr522/server-essentials/master/server-essentials | bash -
```

## Example usage

```bash
cd ~/Desktop
mkdir MyServer
cd MyServer
/path/to/the/script/server-essentials
```

**OR**

```bash
cd ~/Desktop
mkdir MyServer
cd MyServer
curl -fsSL https://raw.githubusercontent.com/Rayzr522/server-essentials/master/server-essentials | bash -
```

## Credits
My brain, with inspiration for the run-without-installing command from the [yarn installer page](https://yarnpkg.com/en/docs/install#linux).