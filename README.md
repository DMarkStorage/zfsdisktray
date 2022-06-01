# Zfsdisktray

# Zfsdisktray

This program requests data from `ZFS Storage appliance` this program prints out disk tray information. 

## USAGE
`zfsdisktray_show` will show you the Chassis informations available on the storage. 
    (e.g. Name, chassis status, Manufacturer, Model)

## Requirements

```
# Install docopt using pip

`pip install docopt`
```
Check [install docopt](https://pypi.org/project/docopt/) for more information. 


### Usage Example
## Run the program

```
# Show Chassis information
 
  python zfsdisktray_show.py -s <STORAGE> --diag
  
  *<STORAGE> - your zfs storage appliance

# Show options
    python -h || --help
```

