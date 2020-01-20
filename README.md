# `ogymfys`
`ogymfys` stands for "ogymfys gets your music from your server"

## Introduction
This script is made for those who accumulate new music on their server, retrieve said music from their remote server, make a copy/transcode for their personal use (or not) and then store the original files as a backup (or not)

As I develop this further, I'll add more options for what this tool can do for you, however the idea will always be that this should help you sync down new music from your remote box.

## Dependencies
* `ffmpeg`
* `rsync`
* `parallel`
* `mp4v2-utils` (optional, required if you want artwork with m4a files)

Please install these using your favourite package manager.

On Ubuntu, `sudo apt install ffmpeg rsync parallel mp4v2-utils`

On Brew, probably `brew install ffmpeg rsync parallel mp4v2-utils`

## Installation
* Install dependencies
* Clone this repo into directory of choice
* Ensure ogymfys has appropriate +x rights
* Execute ogymfys for the first time and then edit the default config in `~/.ogymfys/config`

## Updating
* `git pull`
* check the diff between old and new `config.default` files
