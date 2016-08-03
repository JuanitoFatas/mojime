# Mojime

Outputs random emojis.

The primary purpose of this project is to provide all the emojis that can be used by any ascii
language. To view the list of all the emojis, please open the [emojis.json file](/emojis.json).
It lists all the emojis in json format and you can use this json as per your need.

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
