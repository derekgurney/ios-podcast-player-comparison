# iOS Podcast Player / Client Comparison

🔔 As of July 18, 2024, this is simply copied over from [Podlove's Matrix](https://docs.google.com/spreadsheets/d/1c2L14UVH1xtN4iDG4awheLbMgPCQgaKEamUauWs1gps/edit?gid=0#gid=0) and may be outdated.

🚨 Many features of Overcast have been removed in the latest release which are only partially documented here.

Please help keep this updated by [leaving a comment](https://github.com/hbmartin/ios-podcast-player-comparison/issues) or by [editing this doc](https://github.com/hbmartin/ios-podcast-player-comparison/edit/main/README.md)!

* [Chapters and Notes](#chapters-and-notes)
* [Playback and Playlists](#playback-and-playlists)
* [File Formats, Devices, and Subscriptions](#file-formats-devices-and-subscriptions)
* [Controls and Downloads](#controls-and-downloads)
* [Sync and Import / Export](#sync-and-import--export)
* [Other](#other)
* [Articles and Reviews](#articles-and-reviews)

✅ = supported

🚫 = not supported

⚠️ = partial support

## Chapters and Notes

|                  | Paged Feeds | Chap. Mark | MP3 Chap. Mark | Auto Chap. | Chap. Dura-tion | Chap. Start Time | Chap. End Time | Chap. Pics | Notes for DL'd | Notes w/o DL |
| ---------------- | ----------- | ---------- | -------------- | ---------- | --------------- | ---------------- | -------------- | ---------- | -------------- | ------------ |
| Overcast         |             | ✅          | ✅              | 🚫          |                 |                  |                | ✅          | ✅              |              |
| Castro           |             | ✅          | ✅              | 🚫          | ✅               |                  |                | ✅          | ✅              | ✅            |
| Downcast         | 🚫           | ✅          | ✅              | 🚫          | ✅               | ✅                | 🚫              | ✅          | ✅              | ✅            |
| iCatcher!        |             | ✅          | ✅              | 🚫          | ✅               | ✅                | 🚫              |            | ✅              | ✅            |
| Pocket Casts     | ✅           | ✅          | 🚫              |            | ✅               | 🚫                | 🚫              | ✅          | ✅              | ✅            |
| Procast          |             |            |                |            |                 |                  |                |            |                |              |
| Pod Wrangler     |             |            |                |            |                 |                  |                |            |                |              |
| Apple Podcasts   |             | ⚠️          | 🚫              | 🚫          | 🚫               | 🚫                | 🚫              | ✅          | ✅              | 🚫            |
| RSSRadio Premium |             | ✅          |                | 🚫          | 🚫               | ✅                | 🚫              | ✅          | ✅              | ✅            |
| Podcaster 7      |             | ✅          | 🚫              |            | ✅               | 🚫                | 🚫              |            | ✅              |              |
| SleekCast        | ✅           | ✅          | ✅              | 🚫          | 🚫               | 🚫                | 🚫              | ✅          | ✅              | ✅            |
| Mocast           |             |            |                |            |                 |                  |                |            |                |              |
| Podcat           |             | ✅          | ✅              |            |                 |                  |                |            |                |              |
| Podcatchr        |             | ✅          | 🚫              | ✅          | ✅               | ✅                | ✅              | ✅          | ✅              | ✅            |

## Playback and Playlists

|                  | Sleep Timer | Radio Mode | Play Speed | Gap-less Play | Vol. Boost | Book marks | Personal Playlist | Personal Smart Playlist | Predef. Smart Playlist |
| ---------------- | ----------- | ---------- | ---------- | ------------- | ---------- | ---------- | ----------------- | ----------------------- | ---------------------- |
| Overcast         | ✅           | 🚫          | ✅          | ✅             | ✅          |            | ⚠️               | ⚠️                     |               |
| Castro           | ✅           | 🚫          | ✅          | ✅             | ✅          | 🚫          | ✅                 | ✅                       | ✅           |
| Downcast         | ✅           | 🚫          | ✅          | 🚫             | ✅          | 🚫          | ✅                 | ✅                       | ✅           |
| iCatcher!        | ✅           | 🚫          | ✅          |               | 🚫          | ✅          | ✅                 | ✅                       | ✅            |
| Pocket Casts     | ✅           | 🚫          | ✅          | ✅             | 🚫          | 🚫          | ✅                 | ✅                       | ✅           |
| Procast          |             |            |            |               |            |            |                   |                         |                        |
| Pod Wrangler     |             |            |            |               |            |            |                   |                         |                        |
| Apple Podcasts   | ✅           |            | ✅          |               | 🚫          | 🚫          | ✅                 | ⚠️                       | ✅             |
| RSSRadio Premium | 🚫           | 🚫          | ✅          |               | ✅          | ✅          | ✅                 | 🚫                       | ✅            |
| Podcaster 7      | ✅           |            | ✅          |               | 🚫          | 🚫          | ✅                 | ✅                       | ✅             |
| SleekCast        | ✅           | 🚫          | ✅          |               | 🚫          | ✅          | ✅                 | ✅                       | 🚫            |
| Mocast           |             |            |            |               |            |            |                   |                         |                        |
| Podcat           |             |            |            |               |            |            |                   |                         |                        |
| Podcatchr        | ✅           | 🚫          | ✅          | ✅             | 🚫          | ✅          | ✅                 | 🚫                       | ✅           |

## File Formats, Devices, and Subscriptions

|                  | Air-Play | Car-Play | Audio Scrub. | iPad | Land-scape | Inline Browser | Push new eps. | Custom Sub. Sort | Alpha. Sub. Sort | Video |
| ---------------- | ------- | ------------ | ---- | ---------- | -------------- | ------------- | ---------------- | ---------------- | --------------- | --------------- |
| Overcast         | ⚠️      | ⚠️    |              | ✅   |            |                | ✅             |                  |              |                |
| Castro           | ✅       |        |              | 🚫    |            | ✅              | ✅             | 🚫                | ✅       | 🚫               |
| Downcast         | ✅       |        |              | ✅    | ✅          | ✅              | ✅             | ✅                | ✅      | ✅               |
| iCatcher!        | ✅       |        |              | ✅    | ✅          | ✅              | 🚫             | ✅                | ✅      | ✅               |
| Pocket Casts     | ✅       |        | 🚫            | ✅    | ✅          | ✅              | ✅             | ✅                | ✅     | ✅               |
| Procast          |         |         |              |      |            |                |               |                  |                  |                 |
| Pod Wrangler     |         |         |              |      |            |                |               |                  |                  |                 |
| Apple Podcasts   | ✅       |        |              | ✅    | 🚫          | 🚫              | 🚫             | ✅                | 🚫      |✅               |
| RSSRadio Premium | ✅       |        | ✅            | ✅    | ✅          | ✅              | ✅             | 🚫                | ✅     | ✅               |
| Podcaster 7      | ✅       |        |              |      | ✅          | ✅              |               |                  | ✅          |✅               |
| SleekCast        | ✅       |        | ✅            | 🚫    | ✅          | ✅              | ✅             | ✅                | 🚫     | ✅               |
| Mocast           |         |         |              |      |            |                |               |                  |                  |                 |
| Podcat           |         |         |              |      |            |                |               |                  |                  |                 |
| Podcatchr        | ✅       |        | ✅            | 🚫    | ✅          | ✅              | ✅             | ✅                | ✅     | ✅               |

## Controls and Downloads

|                  | Touch Controls | OS Play Controls | Skip Intro | Play DL'ing Ep. | Parallel DL's | Episode stream | Pass. pro-tected | Auto. DL Opts | Disk Space Mgmt |
| ---------------- | -------------- | ---------------- | ---------- | --------------- | ------------- | -------------- | ---------------- | ------------- | --------------- |
| Overcast         |                | ✅                |            |                 |               | 🚫 |                  |               | 🚫 |
| Castro           | ✅              | ✅                |            | ✅               | ✅             | ✅              |                  | ✅             | ✅        |
| Downcast         | ✅              | ✅                | ✅          | ✅               | ✅             | ✅              | ✅                | ✅             | ⚠️     |
| iCatcher!        | ✅              | ✅                | ✅          | ✅               | ✅             | ✅              | ✅                | ✅             | ⚠️     |
| Pocket Casts     | ✅              | ✅                | ✅          | ✅               | ✅             | ✅              | 🚫                | ✅             | ✅     |
| Procast          |                |                  |            |                 |               |                |                  |               |                 |
| Pod Wrangler     |                |                  |            |                 |               |                |                  |               |                 |
| Apple Podcasts   | ✅              |                  |            | ✅               | ✅             | ✅              | 🚫                | ✅             | 🚫        |
| RSSRadio Premium | ✅              | ✅                | ✅          | 🚫               | ✅             | ✅              | ✅                | ✅             | 🚫     |
| Podcaster 7      | ✅              |                  |            | ✅               | 🚫             | ✅              |                  | ✅             | 🚫         |
| SleekCast        | ✅              | ✅                | ✅          | ✅               | ✅             | ✅              | 🚫                | ✅             | ✅     |
| Mocast           |                |                  |            |                 |               |                |                  |               |                 |
| Podcat           |                |                  |            |                 |               |                |                  |               |                 |
| Podcatchr        | ✅              | ✅                | 🚫          | ✅               | ✅             | ✅              | 🚫                | ✅             | ✅     |

## Sync and Import / Export

|                  | Cross Device Sync | Sync Tech. | Import Music Lib. | OPML Export | OPML Import | Pod-cast Dir. | Atom Feed |
| ---------------- | ----------------- | ---------- | ----------------- | ----------- | ----------- | ------------- | --------- |
| Overcast         |                   |            |                   | 🚫 | 🚫 |               |           |
| Castro           | 🚫                 |            |                   | ✅           | ✅           | ✅        |           |
| Downcast         | ✅                 | iCloud     | ✅                 | ✅           | ✅           | ✅        | ✅         |
| iCatcher!        | ✅                 | iCloud     |                   | ✅           | ✅           | ✅         |           |
| Pocket Casts     | ✅                 | Prop.      | ✅                 | ✅           | ✅           | ✅        | 🚫         |
| Procast          |                   |            |                   |             |             |               |           |
| Pod Wrangler     |                   |            |                   |             |             |               |           |
| Apple Podcasts   | ✅                 | iCloud     | ✅                 | 🚫           | 🚫           | ✅       |           |
| RSSRadio Premium | ✅                 | iCloud     | ✅                 | ✅           | ✅           | ✅        |           |
| Podcaster 7      |                   |            | 🚫                 | ✅           | ✅           | ✅        |           |
| SleekCast        | ✅                 | Prop.      | 🚫                 | ✅           | ✅           | ✅        | 🚫         |
| Mocast           |                   |            |                   |             |             |               |           |
| Podcat           |                   |            |                   |             |             |               |           |
| Podcatchr        | ✅                 | Prop.      | 🚫                 | ✅           | ✅           | ✅        | ✅         |

## Other

|                  | Price     | Tran-scripts | Social Share | Per Podcast Settings | Add Ep. to Playlist w/o sub. | App subscription URI scheme            | Wikidata ID                                            |
| ---------------- | --------- | ------------ | ------------ | -------------------- | ---------------------------- | -------------------------------------- | ------------------------------------------------------ |
| Overcast         | $10 /yr   | 🚫            |              |                      |                              | overcast://x-callback-url/add?url=     | [Q20707973](https://www.wikidata.org/wiki/Q20707973)   |
| Castro           | $25 /yr   |              | ✅            | ✅                    | ✅                            | castro://subscribe/                    | [Q100576609](https://www.wikidata.org/wiki/Q100576609) |
| Downcast         |           |              | ✅            | ✅                    | ✅                            | downcast://                            |                                                        |
| iCatcher!        |           |              | ✅            | ✅                    |                              | icatcher://                            |                                                        |
| Pocket Casts     | $40 /yr ¹ |              | ✅            | ✅                    | 🚫                            | pktc://subscribe/feed-url-without-http |                                                        |
| Procast          |           |              |              |                      |                              |                                        |                                                        |
| Pod Wrangler     |           |              |              |                      |                              |                                        |                                                        |
| Apple Podcasts   | 🚫         | ✅            | ⚠️            | ✅                    | ✅                            | pcast://                               | [Q70058728](https://www.wikidata.org/wiki/Q70058728)   |
| RSSRadio Premium |           |              | ✅            | ✅                    | ⚠️                            | rssradio://                            |                                                        |
| Podcaster 7      |           |              | ✅            | ✅                    |                              | ?                                      |                                                        |
| SleekCast        |           |              | ✅            | ✅                    | 🚫                            |                                        |                                                        |
| Mocast           |           |              |              |                      |                              |                                        |                                                        |
| Podcat           |           |              |              |                      |                              | podcat://                              |                                                        |
| Podcatchr        |           |              | ✅            | ✅                    | 🚫                            |                                        |                                                        |

1. 50% off first year

## Acronyms

* Chap = Chapter
* DL = Download
* PL = Playlist
* Ep = Episode

## Articles and Reviews

* https://amplify.matchmaker.fm/what-is-the-best-podcast-app/
* https://www.pcmag.com/picks/the-best-podcast-player-apps
* https://www.descript.com/blog/article/best-podcast-app
* https://www.lifewire.com/best-podcast-apps-ios-4169824
