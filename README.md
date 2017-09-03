capturebate-node
================

capturebate-node lets you follow and archive your favorite models' shows on chaturbate.com

### Requirements
[RTMPDump(ksv)](https://github.com/BurntSushi/rtmpdump-ksv) used to capture the streams

[Node.js](https://nodejs.org/download/) used to run capturebate-node, hence the name

### Setup

1. Install Node.js (tested with 7.9.0 and 8.1.3)
2. Clone this repository and `cd` to it
3. Run `npm install`
4. Edit config.yml and enter your username & password

### Running & Output

Careful: when capturing many streams at once, make sure you have plenty of disk space and bandwidth available or you'll end up dropping a lot of frames and your captures will become useless.

Before you can start capturing streams you first need to [follow](https://i.imgur.com/o9QyAVC.png) the models that you want
to record.

To start capturing streams you need to run `node main.js`.

Standard output should look something like this:

	[04:20:00] Start searching for new models.
	[04:21:06] Found these live followed models: model69
	[04:21:06] Create recording process.
	[04:21:06] model69 is online >>> start recording.
