# Konekoyomi

Konekoyomi is a fork of a free and open source manga reader for Android 8.0 and above. It focuses on usability and extra features, with a new library search, default extension stores and in-app updates from its own releases.

## Features

### Reading and library

* Online reading from a variety of sources, and local reading of downloaded content
* A configurable reader with multiple viewers, reading directions and other settings
* Categories to organize your library, and dynamic categories to view it in multiple ways
* Tracker support: MyAnimeList, AniList, Kitsu, MangaUpdates, Shikimori, Bangumi and Hikka
* Scheduled library updates for new chapters, and a Latest tab for up to 5 sources
* Source migration, merging the same manga from different sources, and manga recommendations
* Local backups, plus restore from existing Mihon, Tachiyomi or Konekoyomi backups
* The library sorts by Date Added, newest first, by default

### Tags

* **Tag merging:** a tag can be shown as another tag everywhere without touching the entry's stored tags. For example, Reincarnation and Transmigration show as Isekai. Entries are found by either name, entry pages show the merged name, and everything is case-insensitive.
* **Automatic cleanup:** spelling variants of the same tag (`big_breasts`, `Big breasts`, `Big Breasts ♀`) merge on their own, and a starter list of common synonyms is built in.
* **Tags screen** (Settings, Library, Tags): every tag with its count, sort by count or name, search, undo any merge, and a review list of suggested merges.
* **Tag filter:** type in the library search and matching tags appear with counts, for example `Isekai (508)`. Tap to include a tag, long-press to exclude it. Chips sit under the search bar and combine with AND.
* **Saved filters:** save a set of chips under a name and apply it again with one tap.
* **Tag from an entry:** tap a tag on an entry page, choose Search, and the library opens filtered by it.
* **Library search syntax:** AND, OR (`||`), exclusion (`-`), quotes, nested brackets, `tag:` and `genre:` prefixes, and comparisons like `unread>100`.
* Merges and saved filters are saved in backups as optional fields, so stock Mihon can still read the backup.

### Pawchive

* The Pawchive extension from the Koneko store is installed on first launch (Android asks you to confirm).
* **Followed creators stay in sync:** the creator tag on each Pawchive entry, written like `Name (patreon 123)`, is added to Pawchive's Followed creators list automatically. Other tags such as `Anal` are ignored. Creators you add by hand are kept, and a creator is removed again only if the app added it and no entry uses it any more. To follow a creator manually, add a custom tag in that same shape to any Pawchive entry.

### App

* Default extension stores, including the Koneko store
* In-app updates from the releases page, signed with a stable key so updates install over each other
* Nothing is sent off your phone by the app

## Download

Get the app from the [releases page](https://github.com/KonekoSupremacy/Konekoyomi/releases/latest). Pick the `arm64-v8a` APK for almost every modern phone, or the `universal` APK if you are not sure.

