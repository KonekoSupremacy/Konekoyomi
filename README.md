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
* **Automatic cleanup:** spelling variants of the same tag (`sci_fi`, `Sci fi`, `Sci-Fi`) merge on their own, and a starter list of common synonyms is built in.
* **Tags screen** (Settings, Library, Tags): every tag with its count, sort by count or name, search, undo any merge, and a review list of suggested merges.
* **Tag filter:** type in the library search and matching tags appear with counts, for example `+ Isekai (508)`. Tap to include a tag, long-press to exclude it. Start with `-` (for example `-romance`) to pick tags to exclude. Included tags are green with a `+`, excluded tags are red with a `-`, and the chips sit under the search bar and combine with AND.
* **Adding tags to an entry:** the Add tags box in Edit info suggests tags from your library with counts as you type.
* **Tag from an entry:** tap a tag on an entry page, choose Search, and the library opens filtered by it.
* **Library search syntax:** AND, OR (`||`), exclusion (`-`), quotes, nested brackets, `tag:` and `genre:` prefixes, and comparisons like `unread>100`.
* Merges are saved in backups as an optional field, so stock Mihon can still read the backup.

### App

* Default extension stores, including the Koneko store, and a starter extension installed on first launch
* In-app updates from the releases page, signed with a stable key so updates install over each other
* Nothing is sent off your phone by the app

## Download

Get the app from the [releases page](https://github.com/KonekoSupremacy/Konekoyomi/releases/latest). Pick the `arm64-v8a` APK for almost every modern phone, or the `universal` APK if you are not sure.

