# fetch-installer-pkg

This is a script based [on Greg Neagle's `installinstallmacos.py`](https://github.com/munki/macadmin-scripts/blob/main/installinstallmacos.py).

This script will find the latest macOS Big Sur entry in Apple's software update catalogs and download the "InstallAssistant" pkg which installs the "Install macOS Big Sur" application on your system.

When you run the script it will present you with all the Big Sur Installers it finds in the software update catalog. Choose one by entering the number and it will download the pkg file.

```
./fetch-installer-pkg.py
```

Add the `--help` argument for further options.

### Credits

Many thanks to Greg Neagle for the [original script](https://github.com/munki/macadmin-scripts/blob/main/installinstallmacos.py) and lots of advice and Mike Lynn for helping me figure out the software update catalog.
