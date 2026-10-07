# Exasol demo videos

Silent looping videos for a booth screen. The files are attached to GitHub releases, not committed to git:
GitHub refuses files over 100 MB in a normal push, and keeping the videos in releases means the repo stays
small to clone.

## For the booth TV: one file, play on repeat

Pick one file, copy it to a USB stick (or the TV's media player), and set the player to **repeat / loop one file**.
Both are 1080p, 60 fps, H.264 MP4 with no audio, so they play on practically any TV.

| Loop | What plays, in order | Length | Size | Download |
|---|---|---|---|---|
| **Version 1: all three** | Exasol introduction → Lakehouse Turbo story → Kafka to SQL | 3:51 | 58 MB | [Exasol-Booth-Loop-v1-All3-1080p.mp4](https://github.com/yuvi-ex/Demo-videos/releases/download/v2/Exasol-Booth-Loop-v1-All3-1080p.mp4) |
| **Version 2: intro + Lakehouse Turbo** | Exasol introduction → Lakehouse Turbo story | 2:42 | 183 MB | [Exasol-Booth-Loop-v2-Intro-LakehouseTurbo-1080p.mp4](https://github.com/yuvi-ex/Demo-videos/releases/download/v2/Exasol-Booth-Loop-v2-Intro-LakehouseTurbo-1080p.mp4) |

Both are in the [`v2` release](https://github.com/yuvi-ex/Demo-videos/releases/tag/v2). Download them from the
command line with:

```sh
gh release download v2 --repo yuvi-ex/Demo-videos
```

**Playing from a laptop instead of the TV:** open the file in QuickTime Player and choose **View → Loop**, or in
VLC turn on **Repeat one**. Turn off sleep and the screen saver for the day (on a Mac, run `caffeinate -di` in
Terminal and leave it open).

Version 1 was re-encoded to 1080p, 60 fps so the three parts match (the Kafka video is 4K, 30 fps on its own).
Version 2 joins its two parts without re-encoding, so it is identical in quality to the originals.

## The separate videos (v1 release)

| Video | Resolution | Length | Size | Download |
|---|---|---|---|---|
| Exasol introduction | 1920×1080 | 1:12 | 91 MB | [Exasol-Introduction-Loop-v1.mp4](https://github.com/yuvi-ex/Demo-videos/releases/download/v1/Exasol-Introduction-Loop-v1.mp4) |
| Lakehouse Turbo story | 1920×1080 | 1:30 | 91 MB | [Lakehouse-Turbo-Story-Loop-v1.mp4](https://github.com/yuvi-ex/Demo-videos/releases/download/v1/Lakehouse-Turbo-Story-Loop-v1.mp4) |
| Kafka to SQL | 3840×2160 (4K) | 1:09 | 197 MB | [Exasol-Kafka-to-SQL-Booth-Loop-4K.mp4](https://github.com/yuvi-ex/Demo-videos/releases/download/v1/Exasol-Kafka-to-SQL-Booth-Loop-4K.mp4) |

All three are H.264 MP4 with no audio track, made to loop.

Download all three from the command line:

```sh
gh release download v1 --repo yuvi-ex/Demo-videos
```
