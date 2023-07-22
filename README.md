# ytm-cli, the Youtube Music CLI

## About

Frequently, I find myself download music from youtube, then manually converting to mp3 and editing the metadata, so I made a script to automate it!

## Installation

Since its just a shell script, you just need to copy the script to somewhere on your path

`doas cp ytm-cli /usr/local/bin/ # use sudo if you don't have doas`

## Usage

Simply pass the URL you want to download as the first argument, and voila!

For example:

`ytm-cli "https://youtu.be/dQw4w9WgXcQ"`

Or, to download a playlist:

`ytm-cli "https://youtube.com/playlist?list=PLnif9Rfb5Admo7tMY_XzYsvJNCfIeaB4U"`
