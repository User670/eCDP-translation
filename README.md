# Deprecation Notice
This is a late notice, but this repo seems to be deprecated. Please join the eCDP Discord server here: [https://discord.gg/3MkYyFnkqG](https://discord.gg/3MkYyFnkqG) to discuss about translations. Also you'll be directly editing game files, so get your hex editor ready.

# eCDP Translation
This is a repo that aims to help translating McDonald Japan's eCDP training game on the Nintendo DS.

# Text files
Text files in this repo are texts found in the game's files, converted from binary to readable files using the scripts in the scripts folder.

One text file may contain multiple pieces of text; they are separated by `===#===`.

# Scripts
There are two Python 3 scripts in the scripts folder.

parse.py takes all files in `./original`, converts them into txt files, and put them in `./txt`.

builder.py takes all files in `./txt`, converts them back into binary, and put them in `./modified`.

The script doesn't traverse folders within the folders (and treats them as if files, and potentially throw errors). Contributions that implement traversing folders within the folders are more than welcome.

# Contributing
If you would like to make a one-off contribution, just make a pull request **to the `translation` branch**. If you would like to work on a number of files for a longer period of time, first open an issue so that people know what files you are working on and not do repeated work. (Also check issues and PRs for work that has been done or is in progress before you start.)

You may also request direct write permissions.

Contribution to the scripts are also welcome.
