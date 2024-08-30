# Some basic Scoop info

### Open the terminal to do any of these

- See [this Github repositiory for an issue about scoop not updating properly](https://github.com/ScoopInstaller/Scoop/issues/5926)

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
