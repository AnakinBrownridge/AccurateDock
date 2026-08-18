Download it (the original) on https://store.kde.org/p/2352806!
Or, compile the latest code for the latest features from this specific fork.

## Arch-based Systems (CachyOS, EndeavourOS, Manjaro)

If you get the error:
```
module "org.kde.plasma.private.taskmanager" is not installed
```

Check the `arch-patch` folder for the fix. Run:
```bash
cd arch-patch
sudo ./install-taskmanager-module.sh
kquitapp6 plasmashell && kstart plasmashell
```
