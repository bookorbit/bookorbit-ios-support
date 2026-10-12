# BookOrbit iOS release history

The current App Store version is **1.4.0 (23)**. The next planned release is **1.5.0**.

Historical notes were backfilled on October 9, 2026 from the original App Store listings. Original release dates are not recorded here because they could not be verified. GitHub backfill timestamps do not represent the original App Store release dates.

| Version | Build | Status | Milestone |
| --- | --- | --- | --- |
| 1.5.0 | Not assigned | Planned | [1.5.0](https://github.com/bookorbit/bookorbit-ios-support/milestone/1) |
| 1.4.0 | 23 | Released | [1.4.0](https://github.com/bookorbit/bookorbit-ios-support/milestone/8) |
| 1.3.0 | 20 | Released | [1.3.0](https://github.com/bookorbit/bookorbit-ios-support/milestone/7) |
| 1.2.0 | 18 | Released | [1.2.0](https://github.com/bookorbit/bookorbit-ios-support/milestone/6) |
| 1.1.0 | 16 | Released | [1.1.0](https://github.com/bookorbit/bookorbit-ios-support/milestone/5) |
| 1.0.2 | 14 | Released | [1.0.2](https://github.com/bookorbit/bookorbit-ios-support/milestone/4) |
| 1.0.1 | 13 | Released | [1.0.1](https://github.com/bookorbit/bookorbit-ios-support/milestone/3) |
| 1.0 | 9 | Released | [1.0](https://github.com/bookorbit/bookorbit-ios-support/milestone/2) |

## 1.5.0

Planned for the next App Store release. Build 25 is on TestFlight (`testflight/1.5.0-25`); the App Store build and release date have not been assigned.

### New

- Keep the screen awake while reading ebooks, with an optional reader setting.
- Continue Read Along in the mini-player while browsing the app.
- Edit full book metadata, including ISBN, and choose values from metadata providers.
- Follow the narrated text in the audiobook player.
- Request an ebook and its audiobook together.
- A single reader footer player while narration runs.
- Book covers keep their original shape.
- Filter Library and Search by book language when the server provides language options.
- Identify saved metadata provider results and request a fresh search on supported servers.
- Include comic formats in ebook request preferences.

### Fixes

- Read Along resumes correctly after pausing on iPhone.
- Continue Reading includes books with reading progress even without a saved reading status.
- Metadata refresh applies ISBN changes and reminder preferences stay in sync.
- Reader pages and book panels keep their layout when returning from the background on iPad.
- Watch audiobook playback progress syncs back to the phone and server.
- Open EPUBs with a malformed package namespace.

### Support issues

- [#29](https://github.com/bookorbit/bookorbit-ios-support/issues/29): Read Along pause and resume.
- [#40](https://github.com/bookorbit/bookorbit-ios-support/issues/40): Full metadata editing.
- [#44](https://github.com/bookorbit/bookorbit-ios-support/issues/44): Read Along mini-player.
- [#49](https://github.com/bookorbit/bookorbit-ios-support/issues/49): Keep the screen awake.
- [#50](https://github.com/bookorbit/bookorbit-ios-support/issues/50): Reader layout after reopening the app.
- [#54](https://github.com/bookorbit/bookorbit-ios-support/issues/54): Filter by language.


## 1.4.0

Released on the App Store as **1.4.0 (23)**. [Release milestone](https://github.com/bookorbit/bookorbit-ios-support/milestone/8).

### New

- A new Notebook brings each book's highlights, notes, bookmarks, review and journal together
- Search and review your Notebook across the library, star favourite highlights and name your colours
- A rebuilt Search on iPhone and iPad, with a top result, quick actions and clearer filters
- Review uploads before sending, with book previews and a library choice for each file
- Choose an upload library from the share extension
- Scan a book's ISBN barcode to find it or request it
- Request managers can approve and reject requests, pick releases and follow downloads
- A reading timeline for every book and Listening History in the audiobook player
- Read KEPUB books online and offline
- Choose edge taps, one-handed tapping or swipe-only navigation for ebooks and comics
- An optional page footer shows pages left in the chapter
- Read Along gains Voice Boost and an option to turn off automatic playback
- At the end of an ebook, PDF or audiobook, open the next book in the series
- Home shows available app updates and server updates for administrators

### Fixes

- Smoother ebook page turns and transitions into the next chapter
- Nearby chapters load ahead of time in streamed ebooks
- KEPUB books open with their own saved progress and compatible shared annotations
- CarPlay opens Now Playing when the book is ready and keeps chapter and speed controls current
- Read Along progress stays intact when using text to speech
- Clearing a highlight note and editing EPUB bookmarks sync correctly
- Cached covers stay visible when switching between them
- Upload queues keep moving after a file is refused
- Book Request searches, queue updates and decisions stay in step
- Clearer feedback when a book cannot be deleted

Support issues: [#30](https://github.com/bookorbit/bookorbit-ios-support/issues/30), [#34](https://github.com/bookorbit/bookorbit-ios-support/issues/34), [#35](https://github.com/bookorbit/bookorbit-ios-support/issues/35), [#36](https://github.com/bookorbit/bookorbit-ios-support/issues/36), [#38](https://github.com/bookorbit/bookorbit-ios-support/issues/38), [#42](https://github.com/bookorbit/bookorbit-ios-support/issues/42), [#43](https://github.com/bookorbit/bookorbit-ios-support/issues/43).

The complete Kobo progress sync and deletion fixes also require BookOrbit server 3.3.0.

## 1.3.0

Released on the App Store as **1.3.0 (20)**. [Release milestone](https://github.com/bookorbit/bookorbit-ios-support/milestone/7).

### New

- Lifetime owners can now add Family Sharing with the Lifetime Family upgrade
- CarPlay: listen to your audiobooks in the car
- PDF and comic settings move to a compact tune bar, so the page stays in view
- At the end of a comic, open the next issue in the series
- Comic pages slide under your finger on iPhone
- A rebuilt book page on iPhone, lit by the book's cover
- Downloads on iPhone is now a list sorted by reading progress
- Chapter progress on the Lock Screen and in Control Center
- A new Silver Orbit app icon for Premium

### Fixes

- Pinch to zoom on comics stays anchored under your fingers
- Read Along starts from the page you are on and shows its chapter and cover in Now Playing
- Resuming a Read Along book opens the right file
- Recently opened PDFs open faster
- Comics keep your page in scroll and webtoon modes
- Downloaded audiobooks play from Home without your server
- Audiobook playback stops when you sign out or remove its download
- Audiobook chapter countdown and resume position are more accurate
- Playback speeds are kept per book for each account
- Clearer messages when an audiobook download cannot start
- Fewer repeated controls across the readers and player

Support issues: [#14](https://github.com/bookorbit/bookorbit-ios-support/issues/14).

## 1.2.0

Released on the App Store as **1.2.0 (18)**. [Release milestone](https://github.com/bookorbit/bookorbit-ios-support/milestone/6).

BookOrbit now runs natively on iPad.

### iPad

- Every screen is designed for the larger display and follows your window in portrait, landscape, and resizable windows
- Two pages side by side in the reader, with a side panel for contents, notes, and search
- PDF and comic readers with page spreads, a Pages panel, and find in PDF
- A Library with a sidebar of libraries, series, authors, smart scopes, and collections
- Book Details that keep the cover and actions in view
- Now Playing, Downloads, Activity, Search, Book Requests, and Settings rebuilt for iPad
- Keyboard shortcuts, trackpad swipes, and pointer support

### New

- A Home Screen and Lock Screen widget to pick up your current book
- Home adds Up Next in Series, Want to Read, pinned smart scopes and collections, and a daily Discover pick
- Open books with the reading controls hidden
- Choose the statistic shown in the page footer
- Set page margins in 1% steps
- Zoom and pan images in books
- Turn off the offer to return to your last listening position
- An author's books are listed in series order by default
- Hide Book Requests when your library does not use them

### Fixes

- An open book no longer rolls back reading progress made on another device
- Tapping a highlight no longer also turns the page
- Manga and other fixed-layout books turn pages with edge taps and swipes
- Changing the page direction no longer leaves a book stuck on "Opening book"
- Comic pages no longer disappear while you read
- PDF search results are marked on the page

Support issues: [#4](https://github.com/bookorbit/bookorbit-ios-support/issues/4), [#11](https://github.com/bookorbit/bookorbit-ios-support/issues/11), [#12](https://github.com/bookorbit/bookorbit-ios-support/issues/12), [#18](https://github.com/bookorbit/bookorbit-ios-support/issues/18), [#23](https://github.com/bookorbit/bookorbit-ios-support/issues/23), [#24](https://github.com/bookorbit/bookorbit-ios-support/issues/24), [#27](https://github.com/bookorbit/bookorbit-ios-support/issues/27).

Lifetime Family also became available in 1.2.0 (18).

## 1.1.0

Released on the App Store as **1.1.0 (16)**. [Release milestone](https://github.com/bookorbit/bookorbit-ios-support/milestone/5).

Customize EPUB reading with new display controls, per-book settings, and more font choices. Manga EPUBs now have improved reading options. Enjoy refreshed audiobook screens on iPhone and Apple Watch, plus confirmation before removing downloads. This update also improves downloaded EPUB playback and includes reliability fixes.

Support issues: [#2](https://github.com/bookorbit/bookorbit-ios-support/issues/2), [#7](https://github.com/bookorbit/bookorbit-ios-support/issues/7), [#8](https://github.com/bookorbit/bookorbit-ios-support/issues/8), [#9](https://github.com/bookorbit/bookorbit-ios-support/issues/9), [#13](https://github.com/bookorbit/bookorbit-ios-support/issues/13), [#17](https://github.com/bookorbit/bookorbit-ios-support/issues/17), [#20](https://github.com/bookorbit/bookorbit-ios-support/issues/20).

## 1.0.2

Released on the App Store as **1.0.2 (14)**. [Release milestone](https://github.com/bookorbit/bookorbit-ios-support/milestone/4).

Added a first-party More tab, offline controls across readers, refreshed Activity styling, clearer reader chapter ticks, and simpler Home customization. This update also improves upload permissions, voice filters, download paywalls, and format handling.

## 1.0.1

Released on the App Store as **1.0.1 (13)**. [Release milestone](https://github.com/bookorbit/bookorbit-ios-support/milestone/3).

Updated the app icon.

## 1.0

Released on the App Store as **1.0 (9)**. [Release milestone](https://github.com/bookorbit/bookorbit-ios-support/milestone/2).

Initial App Store release.
