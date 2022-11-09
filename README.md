# pwdgen
A simple random password generator

## Usage

```
    pwdgen [option <argument>] ...
```

## Options

| Full Argument | Shortcut Letter | Effect                                                  |
| :---:         | :---:           | ---                                                     |
| version       | v               | show version message                                    |
| help          | h               | show this message                                       |
| key           | k               | set password generator seed (default is the time stamp) |
| char-set      | S               | provide customized charactor set                        |
| length        | l               | customize password length (default is 16)               |
| iterate       | n               | customize iteration count (default is 1)                |

## Charactor set shortcuts

| Full Argument | Shortcut Letter | Effect                       |
| :---:         | :---:           | ---                          |
| lower-case    | c               | enable lower-case letters    |
| upper-case    | C               | enable upper-case letters    |
| digit         | d               | enable digit numbers         |
| symbol        | s               | enable symbols               |
| hex           | x               | enable lower-case hex digits |
| HEX           | X               | enable upper-case hex digits |
| word          | w               | alias for `cCd`              |
| printable     | p               | alias for `cCds`             |
