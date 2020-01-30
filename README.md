# macOS phrases for AutoKey

## FIRST! Map Control to the key left of the spacebar

Use macOS-style keyboard shortcuts for:

| Command | Shortcut | Window Filter
|---|:---:|---|
Move left and select by word | ⌥+⇧+←
Move left by word | ⌥+←
Move right and select by word | ⌥+⇧+→
Move right by word | ⌥+→
Move to beginning of line | ⌘+←
Move to end of line | ⌘+→
Select to beginning of line | ⇧+⌘+←
Select to end of line | ⇧+⌘+→

## Installation

Install [AutoKey](https://github.com/autokey/autokey) from Pamac Manager (Manjaro, AUR) or

```sh 
$ pamac install autokey
```

Clone repository and copy `macOS` folder to `~/.config/autokey/data`.

```sh
$ git clone git@github.com:kjs3/macos-autokey-phrases.git
$ cp -r macOS/ ~/.config/autokey/data/
```

