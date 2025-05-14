# Some basic Scoop info

- The official [Scoop website is here](https://scoop.sh/). 

### Installing Scoop

- See [this Github Repository](https://github.com/ScoopInstaller/Install?tab=readme-ov-file#prerequisites) and run the typical installation in Powershell. You can use VS Code's terminal:

```powershell

irm get.scoop.sh | iex
# You can use proxies if you have network trouble in accessing GitHub, e.g.
irm get.scoop.sh -Proxy 'http://<ip:port>' | iex

```


- See [this Github repository for an issue about scoop not updating properly](https://github.com/ScoopInstaller/Scoop/issues/5926)

- The above item addresses an issue where Scoop is not updating due to Windows Defender intercepting

- `scoop update` only updates scoop itself to the latest version

- You can update an individual app using `scoop update <appname>`

- You can use `*` in place of the appname to update all apps. So the command will be `scoop update *`

- `scoop help` lists all commands in the CLI

```
scoop help update

Usage: scoop update <app> [options]

'scoop update' updates Scoop to the latest version.

'scoop update <app>' installs a new version of that app, if there is one.

You can use '*' in place of <app> to update all apps.

Options:

-f, --force              Force update even when there isn't a newer version
-g, --global             Update a globally installed app
-i,--independent         Don't install dependencies automatically
-k,--no-cache            Don't use the download cache
-s,--skip                Skip hash validation (use with caution!)
-q,--quiet               Hide extraneous messages
```
