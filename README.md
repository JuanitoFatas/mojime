# Mojime

Outputs random emojis.

The primary purpose of this project is to provide all the emojies that can be used by any ascii language
To view the list of all the empjies please open the emojies.json file 
it lists all the emojies in jason format and ypu can use this jason as per your need
## Usage

```
# Output an emoji text randomly
$ mojime
:heart_eyes:

# Output two emojis text randomly
$ mojime --number 2
:smirk: :blush:

# Output two emojis text randomly without spaces in between
$ mojime --number 2 --no-spaces
:smirk::blush:

# Output an emoji char randomly
$ mojime --char
😀

# Output four emoji chars randomly
$ mojime --char --number 4
😀 😁 😂 😃
```

## Licenses

[emojis.json](/emojis.json) modified from https://github.com/muan/emojilib, MIT LICENSED.

Other files - CC0 Public Domain
