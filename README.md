# reset-cli

reset-cli is a powerfull package that allow you to reset your linux system.

## Installation

- archlinux : 

To install this script on archlinux, just follow the instruction bellow this message :

```bash

# clone the repo
git clone https://github.com/nuageeee/reset-cli-linux reset-cli
# enter in the folder
cd reset-cli
# select the arch folder
cd arch
# then, build the pakage
makepkg -si
```

Once it's done, you will be allow to run reset-cli with this command :
```bash
sudo reset-cli -h
```

## Usage
For the moment, you can just make a backup of certain file.

```bash
sudo reset-cli -s {yourfilepath}
```

That will create a folder in "/home/" named "backup" and copy the file you to save in there.
## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[GPL](https://choosealicense.com/licenses/agpl-3.0/)