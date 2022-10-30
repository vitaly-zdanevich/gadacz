# gadacz

A Terminal User Interface (TUI) for playing audiobooks (and other audio files)

## Features

- remembers the last file (or m4a/m4b chapter) played and position inside it
- displays information from tags
- playback speed control
- bookmarks
- supports m4a/m4b files with chapters

## Requirements

- gstreamer and its plugins

```
# On Arch
sudo pacman -S gstreamer gst-plugins-base gst-plugins-good
```

- Rust

## Installation

Currently there are no provided binaries. Please install from source.

```
git clone https://github.com/rareitems/gadacz
cd gadacz
cargo install --path .
```

## Usage

```
gadacz <path_to_your_audiobook>
```
Press '?' for a complete list of keymap.
