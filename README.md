# ServerEssentials
> A simple script for installing all the essentials of a simple Spigot server

This is a simple **\*nix** script for installing all the essentials for a simple Spigot server. It downloads the latest version of:

* Spigot(http://spigotmc.org)
* EssentialsX(https://www.spigotmc.org/resources/essentialsx.9089/)
* ProtocolLib(https://www.spigotmc.org/resources/protocollib.1997/)
* Multiverse (Core(https://www.spigotmc.org/resources/multiverse-core.390/) and NetherPortals(https://dev.bukkit.org/projects/multiverse-netherportals))
* PlugMan(https://dev.bukkit.org/projects/plugman)
* PermissionsEx(https://dev.bukkit.org/projects/permissionsex)
* Vault(https://dev.bukkit.org/projects/vault)
* WorldEdit(https://dev.bukkit.org/projects/worldedit)
* WorldGuard(https://dev.bukkit.org/projects/worldguard)

It also creates a simple start script that runs your server with *4GB of RAM*, and automatically sets the EULA to agreed. (*Note: by using this script __you are agreeing to the Mojang EULA__*)

## Demo

![demo](demo.gif)

## Installation
Requirements: `curl`

Tested on a _Kali Linux VM_, a _Raspberry Pi_, and my _MacBook Pro_ (running _macOS Sierra 10.12.2_)

You can run it without downloading the script to your harddrive:

```bash
curl -fsSL https://raw.githubusercontent.com/Rayzr522/server-essentials/master/server-essentials | bash -
```

Or you can simply download the script, put it _somewhere_ in your `PATH`, and run it like any other command.

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
Rayzr522, for the base code.
My brain, with inspiration for the run-without-installing command from the [yarn installer page](https://yarnpkg.com/en/docs/install#linux).
