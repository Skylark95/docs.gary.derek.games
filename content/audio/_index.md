---
title: Audio
---

Play audio through voice channels.

## Commands
- {{% commandref bump "Bump a track number to the top of the queue." %}}
- {{% commandref bumpplay "Force play a URL or search for a track." %}}
- {{% commandref disconnect "Disconnect from the voice channel." %}}
- {{% commandref now "Now playing." %}}
- {{% commandref pause "Pause or resume a playing track." %}}
- {{% commandref percent "Queue percentage." %}}
- {{% commandref play "Play the specified track or search for a close match." %}}
- {{% commandref prev "Skip to the start of the previously played track." %}}
- {{% commandref queue "List the songs in the queue." %}}
- {{% commandref remove "Remove a specific track number from the queue." %}}
- {{% commandref repeat "Toggle repeat." %}}
- {{% commandref search "Pick a track with a search." %}}
- {{% commandref seek "Seek ahead or behind on a track by seconds or to a specific time." %}}
- {{% commandref shuffle "Toggle shuffle." %}}
- {{% commandref skip "Skip to the next track, or to a given track number." %}}
- {{% commandref stop "Stop playback and clear the queue." %}}
- {{% commandref summon "Summon the bot to a voice channel." %}}
- {{% commandref volume "Set the volume, 1% - 150%." %}}

{{% command bump "Bump a track number to the top of the queue." "<index>" %}}
{{% command bumpplay "Force play a URL or search for a track." "[play_now=False] <query>" %}}
{{% command disconnect "Disconnect from the voice channel." %}}
{{% command now "Now playing." %}}
{{% command pause "Pause or resume a playing track." %}}
{{% command percent "Queue percentage." %}}
{{% command play "Play the specified track or search for a close match." "<query>" %}}
{{% command prev "Skip to the start of the previously played track." %}}
{{% command queue "List the songs in the queue." "[page=1]" %}}
### Subcommands:
- **clean** Removes songs from the queue if the requester is not in the voice channel.
- **cleanself** Removes all tracks you requested from the queue.
- **clear** Clears the queue.
- **search** Search the queue.
- **shuffle** Shuffles the queue.
{{% command remove "Remove a specific track number from the queue." "<index_or_url>" %}}
{{% command repeat "Toggle repeat." %}}
{{% command search "Pick a track with a search." "<query>" %}}
Use gary search list `<search term>` to queue all tracks found on YouTube.
{{% command seek "Seek ahead or behind on a track by seconds or to a specific time." "<seconds>" %}}
Accepts seconds or a value formatted like 00:00:00 (hh:mm:ss) or 00:00 (mm:ss).
{{% command shuffle "Toggle shuffle." %}}
### Subcommands
**bumped** Toggle bumped track shuffle.
{{% command skip "Skip to the next track, or to a given track number." "[skip_to_track]" %}}
{{% command stop "Stop playback and clear the queue." %}}
{{% command summon "Summon the bot to a voice channel." %}}
{{% command volume "Set the volume, 1% - 150%." "[vol]" %}}
