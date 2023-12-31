# reset-cli

reset-cli is a powerfull package that allow you to reset your linux system.

![Discord](https://img.shields.io/discord/1138108139443593246?style=for-the-badge)
![GitHub Repo stars](https://img.shields.io/github/stars/nuageeee/reset-cli-linux?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/nuageeee/reset-cli-linux?style=for-the-badge)

## Table of contents

- [description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Roadmap](#roadmap)
- [Contributing](#contributing)

## Description

Reset-cli is a powerful package that lets you reset a linux system without reinstalling it!
To make this possible, the script, once installed and run, will download your system's base file (the root directory) and copy all the files back into their directories.

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
here is the list of available command.

```bash
# save/backup file
sudo reset-cli -s {yourfilepath}
```
That will create a folder in "/home/" named "backup" and copy the file you to save in there.

```bash
# test server response
sudo reset-cli -p [answer the question]
```
That will try to ping the server that contain the based file of your linux system.\
### I recommend to execute this command before doing anything else!

## Roadmap

This is the early development version. I am currently working on :

- [x] Possibility to backup file.
- [x] Possibility to check server response.
- [ ] Possibility to reset the system to default.


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[GPL](https://choosealicense.com/licenses/agpl-3.0/)