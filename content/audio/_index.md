---
title: Audio
---

Play audio through voice channels.

## Commands
- **[bump](#bump)** Bump a track number to the top of the queue.
- **[bumpplay](#bumpplay)** Force play a URL or search for a track.
- **[disconnect](#disconnect)** Disconnect from the voice channel.
- **[now](#now)** Now playing.
- **[pause](#pause)** Pause or resume a playing track.
- **[percent](#percent)** Queue percentage.
- **[play](#play)** Play the specified track or search for a close match.
- **[prev](#prev)** Skip to the start of the previously played track.
- **[queue](#queue)** List the songs in the queue.
- **[remove](#remove)** Remove a specific track number from the queue.
- **[repeat](#repeat)** Toggle repeat.
- **[search](#search)** Pick a track with a search.
- **[seek](#seek)** Seek ahead or behind on a track by seconds or to a specific time.
- **[shuffle](#shuffle)** Toggle shuffle.
- **[skip](#skip)** Skip to the next track, or to a given track number.
- **[stop](#stop)** Stop playback and clear the queue.
- **[summon](#summon)** Summon the bot to a voice channel.
- **[volume](#volume)** Set the volume, 1% - 150%.

## bump
```
Syntax: gary bump <index>
```
**Bump a track number to the top of the queue.**
## bumpplay
```
Syntax: gary bumpplay [play_now=False] <query>
```
**Force play a URL or search for a track.**

## disconnect
```
Syntax: gary disconnect 
```
**Disconnect from the voice channel.**
## now
```
Syntax: gary now 
```
**Now playing.**
## pause
```
Syntax: gary pause 
```
**Pause or resume a playing track.**
## percent
```
Syntax: gary percent 
```
**Queue percentage.**
## play
```
Syntax: gary play <query>
```
**Play the specified track or search for a close match.**
## prev
```
Syntax: gary prev 
```
**Skip to the start of the previously played track.**
## queue
```
Syntax: gary queue [page=1]
```
**List the songs in the queue.**
### Subcommands:
- **clean** Removes songs from the queue if the requester is not in the voice channel.
- **cleanself** Removes all tracks you requested from the queue.
- **clear** Clears the queue.
- **search** Search the queue.
- **shuffle** Shuffles the queue.
## remove
```
Syntax: gary remove <index_or_url>
```
**Remove a specific track number from the queue.**
## repeat
```
Syntax: gary repeat
```
**Toggle repeat.**
## search
```
Syntax: gary search <query>
```
**Pick a track with a search.**

Use gary search list <search term> to queue all tracks found on YouTube.
## seek
```
Syntax: gary seek <seconds>
```
**Seek ahead or behind on a track by seconds or to a specific time.**

Accepts seconds or a value formatted like 00:00:00 (hh:mm:ss) or 00:00 (mm:ss).
## shuffle
```
Syntax: gary shuffle
```
### Subcommands
**Toggle shuffle.**

**bumped** Toggle bumped track shuffle.
## skip
```
Syntax: gary skip [skip_to_track]
```
**Skip to the next track, or to a given track number.**
## stop
```
Syntax: gary stop 
```
**Stop playback and clear the queue.**
## summon
```
Syntax: gary summon
```
**Summon the bot to a voice channel.**
## volume
```
Syntax: gary volume [vol]
```
**Set the volume, 1% - 150%.**
