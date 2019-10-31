uutransfer
==========

uutransfer can transfer files using an existing screen / tmux session.

 * [./uutransfer-tmux] for tmux
 * [./uutransfer-screen] for GNU screen

## Install

Requirements: ruby 2.6

```
curl TBD -o /path/to/bin/uutransfer
```

### Usage

```
uutransfer-tmux [window_index | pane_id]

$ uutransfer 1 # read active pane on window 1
$ uutransfer %13 # read pane %13
```

```
uutransfer-screen [window num]

$ uutransfer 1 # read window 1
```

## License
MIT (c) cho45@lowreal.net

