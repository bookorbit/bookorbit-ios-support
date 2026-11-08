# BookOrbit iOS release history

The current App Store version is **1.8.0 (30)**, released on November 7, 2026. The next version has not been scheduled.

Historical notes were backfilled on October 9, 2026 from the original App Store listings. Original release dates are not recorded here because they could not be verified. GitHub backfill timestamps do not represent the original App Store release dates.

| Version | Build | Status | Milestone |
| --- | --- | --- | --- |
| 1.8.0 | 30 | Released | [1.8.0](https://github.com/bookorbit/bookorbit-ios-support/milestone/11) |
| 1.7.0 | 29 | Released | [1.7.0](https://github.com/bookorbit/bookorbit-ios-support/milestone/10) |
| 1.6.0 | 28 | Released | [1.6.0](https://github.com/bookorbit/bookorbit-ios-support/milestone/9) |
| 1.5.0 | 27 | Released | [1.5.0](https://github.com/bookorbit/bookorbit-ios-support/milestone/1) |
| 1.4.0 | 23 | Released | [1.4.0](https://github.com/bookorbit/bookorbit-ios-support/milestone/8) |
| 1.3.0 | 20 | Released | [1.3.0](https://github.com/bookorbit/bookorbit-ios-support/milestone/7) |
| 1.2.0 | 18 | Released | [1.2.0](https://github.com/bookorbit/bookorbit-ios-support/milestone/6) |
| 1.1.0 | 16 | Released | [1.1.0](https://github.com/bookorbit/bookorbit-ios-support/milestone/5) |
| 1.0.2 | 14 | Released | [1.0.2](https://github.com/bookorbit/bookorbit-ios-support/milestone/4) |
| 1.0.1 | 13 | Released | [1.0.1](https://github.com/bookorbit/bookorbit-ios-support/milestone/3) |
| 1.0 | 9 | Released | [1.0](https://github.com/bookorbit/bookorbit-ios-support/milestone/2) |

## 1.8.0

Released on the App Store on November 7, 2026 as **1.8.0 (30)**.

### New

- Use BookOrbit in German, French, Spanish, Dutch, Italian, and Simplified Chinese. iOS picks the language from the device, or from Settings > BookOrbit > Language, and a Language row in Settings opens it.
- Guided View reads comics panel by panel, right to left for manga.
- Story Recap shows "Previously in" when a book opens after three days or more away, written on the device from only the pages before yours. Premium, on devices that support Apple Intelligence.
- Constellations lists the people, places, and terms met so far, cut off at the page on screen so nothing ahead shows. Ask the Book answers who or what a selected name is from only the pages already read. Premium, on devices that support Apple Intelligence.
- Find Your Page reads a page of a paper copy with the camera, or from a photo, and opens the ebook at that text.
- The book scanner reads a photographed cover to open or request the book, and a photographed shelf to mark each spine as read, reading, in your library, or ready to request.
- Your books and highlights appear in Spotlight and Siri, with shortcuts to open a book or show its highlights.
- Year in Review tells the story of your reading year in six styles that can be shared as images. It appears in Activity from December 1 to January 31, and past years stay available.
- Reading Insights is redrawn as a year orbit and a shelf, and each day opens as a ruler of its sessions.
- Bedtime mode uses the Sleep Focus to darken the reader and start a sleep timer, ask "Still listening?" every 15 minutes, and fade out and leave a bookmark where you fell asleep. Premium.
- Auto Page Turn and Auto-Scroll move through a book on their own.
- Choose what the page header and footer show, with an optional progress bar along the footer.
- Show the status bar while the reading controls are hidden.
- Text sizes go up to 48.
- Bluetooth page turners, arrow keys, and optionally the volume buttons turn pages.
- Look words up in Wikipedia, Wiktionary, and StarDict dictionaries, and review looked-up words in Notebook under More, Vocabulary.
- Contents shows how long each chapter takes, and the time left follows your own reading pace.
- In-book search can match case, whole words, and accents.
- Every jump from Contents, search, bookmarks, notebook entries, and the scrubber leaves a Return to the page you left.
- Pages can be numbered by the print edition where the book includes them.
- Paginated chapters clean up publisher styles, with options to ignore publisher margins and forced page breaks.
- Book Covers settings gain Refresh Covers.

### Fixes

- Covers and details changed on the server refresh instead of showing the old ones for up to a day.
- Read Along keeps playing across chapter boundaries instead of going silent while the clock runs.
- Narration stays paused when headphones hand off to another device while it is loading.
- The whole chapter and bookmark row is tappable in the audiobook player.
- The iPad book page shows the book and audiobook covers together.
- The Cover and Text switch appears in the iPad player and on the iPhone Duo's open display.
- The iPhone Duo no longer freezes as it rotates or unfolds, and its outer display, Home, and player fit its fold and side strip.
- A grouped series shows under its name and opens the series.
- Closing quotes and other punctuation stay with their word at the page edge.
- The translation panel stays on screen for text near the bottom of the page.
- Switching to Scrolled keeps the page on screen.
- Highlights no longer paint whole paragraph boxes, and books with malformed markup search and list their contents correctly.

Year in Review, Find Your Page, cover and shelf scanning, and saving Constellations corrections require BookOrbit server 3.7.0 or later, which also writes achievement names and the monthly challenge in the app's language. Everything else works with older servers.

### Support issues

- [#69](https://github.com/bookorbit/bookorbit-ios-support/issues/69): Show the status bar while reading controls are hidden.
- [#79](https://github.com/bookorbit/bookorbit-ios-support/issues/79): Translations.
- [#80](https://github.com/bookorbit/bookorbit-ios-support/issues/80): Narration after a Bluetooth handoff.
- [#83](https://github.com/bookorbit/bookorbit-ios-support/issues/83): Text view in the player on the iPhone Duo.
- [#84](https://github.com/bookorbit/bookorbit-ios-support/issues/84): iPhone Duo freezing as it unfolds.
- [#88](https://github.com/bookorbit/bookorbit-ios-support/issues/88): Book and audiobook covers on iPad.
- [#94](https://github.com/bookorbit/bookorbit-ios-support/issues/94): Tapping chapter rows.
- [#98](https://github.com/bookorbit/bookorbit-ios-support/issues/98): Refreshing changed covers.
- [#99](https://github.com/bookorbit/bookorbit-ios-support/issues/99): Read Along silence at chapter boundaries.

Main tracker: [#2016](https://github.com/bookorbit/bookorbit/issues/2016), [#1978](https://github.com/bookorbit/bookorbit/issues/1978), [#1962](https://github.com/bookorbit/bookorbit/issues/1962), [#1976](https://github.com/bookorbit/bookorbit/issues/1976).

## 1.7.0

Released on the App Store on October 27, 2026 as **1.7.0 (29)**.

### New

- Ebook pages can turn like paper: choose Curl under Page turns. It follows the reading direction and turns two-page spreads like a book.
- Reading History lists every finished read, rereads included, with ratings, notes, sharing and export.
- Achievements are rebuilt as medals, opening on the latest unlocks with hints for what is closest.
- The book page gives the Timeline its own row and shows the rating as a number.
- Filter the Library by read-along books.
- Smart scope date filters can use rolling "older than" dates.
- Book Request releases link to their source page and can be held for review before filing.
- Metadata searches return more provider results.
- The app adapts its navigation, readers and controls to the open iPhone Duo display.

### Fixes

- Continue Listening, Home, widgets and the library quick action resume a book as an audiobook or Read Along, the way it was last played.
- Sleep Timer options are readable in dark mode and open beside the moon button.
- Orbit Voices retries a dropped or refused connection and says what still fails.
- Downloaded audiobooks keep their chapter lists while offline.
- Read Along books restore the bookmark button and mark the sentence being spoken.
- A reading position saved offline no longer replaces a newer one from another device.
- Requests made from a book's page show the book's cover.

BookOrbit server 3.6.0 or later enables the complete Reading History, read-aloud filtering,
rolling date filters and grouped progress experience.

### Support issues

- [#66](https://github.com/bookorbit/bookorbit-ios-support/issues/66): Page curl turn animation.
- [#71](https://github.com/bookorbit/bookorbit-ios-support/issues/71): Resume the audiobook or Read Along that was last played.
- [#72](https://github.com/bookorbit/bookorbit-ios-support/issues/72): Orbit Voices stopping mid-playback.
- [#73](https://github.com/bookorbit/bookorbit-ios-support/issues/73): Sleep Timer readability in dark mode.
- [#74](https://github.com/bookorbit/bookorbit-ios-support/issues/74): iPhone Duo support.
- [#75](https://github.com/bookorbit/bookorbit-ios-support/issues/75): Offline audiobook chapters.
- [#77](https://github.com/bookorbit/bookorbit-ios-support/issues/77): Read Along bookmark button.

Main tracker: [#1647](https://github.com/bookorbit/bookorbit/issues/1647), [#1630](https://github.com/bookorbit/bookorbit/issues/1630), [#1583](https://github.com/bookorbit/bookorbit/issues/1583), [#1751](https://github.com/bookorbit/bookorbit/issues/1751), [#1438](https://github.com/bookorbit/bookorbit/issues/1438).

## 1.6.0

Released on the App Store on October 20, 2026 as **1.6.0 (28)**.

### New

- Connect through Cloudflare Access, Pangolin, and custom-header access gates.
- Add multiple verified addresses for one server, so BookOrbit can connect at home or away.
- Update outdated downloaded books in place without removing and downloading them again.
- Choose squiggly highlights and see each highlight style in the picker.
- Audiobook chapter lists now open at the chapter currently playing.
- Siri can resume the audiobook last played, whether streamed or downloaded.
- Read Along starts faster by streaming narration instead of downloading every audio file first.
- Each narration engine now has its own named playback speeds.
- AZW3 books now show their chapters in Contents.
- Read Along titles display their book and audiobook covers together.
- Read Along books now appear as audiobooks in CarPlay.
- When another device moves an audiobook, BookOrbit can ask before following the newer position.

### Fixes

- Vertical-writing EPUBs and mixed reading directions now turn pages correctly.
- Briefly locking the screen or switching apps no longer splits one reading session into many.
- Paused Read Along books recover correctly after a long time in the background.
- Adjusting a text selection keeps the highlight menu available.
- Highlights changed on another device refresh correctly, including highlights shared between editions.
- Scrolled reading keeps the selected text size and no longer treats a short flick as a page turn.
- Large tables of contents open without freezing.
- PDF and comic scrolling, fitting, progress tracking, and interrupted downloads are more reliable.
- Audiobook positions and bookmarks sync more safely across devices.
- Book Requests and uploads remain current and recover more reliably from interruptions.
- Widgets, Activity, Home, offline search, Apple Watch, and CarPlay receive additional reliability improvements.

Read Along narration started on another device appears in CarPlay's Continue list with BookOrbit server 3.5.0 or later.

### Support issues

- [#21](https://github.com/bookorbit/bookorbit-ios-support/issues/21): Cloudflare Access and custom-header access gates.
- [#60](https://github.com/bookorbit/bookorbit-ios-support/issues/60): Chapter list opens at the playing chapter.
- [#61](https://github.com/bookorbit/bookorbit-ios-support/issues/61): Highlight menu after adjusting a selection.
- [#63](https://github.com/bookorbit/bookorbit-ios-support/issues/63): Vertical-writing EPUB page turns.
- [#67](https://github.com/bookorbit/bookorbit-ios-support/issues/67): Read Along after a long time in the background.
- [#68](https://github.com/bookorbit/bookorbit-ios-support/issues/68): Reading sessions split by screen lock.

Main tracker: [#1847](https://github.com/bookorbit/bookorbit/issues/1847), [#1840](https://github.com/bookorbit/bookorbit/issues/1840), [#1775](https://github.com/bookorbit/bookorbit/issues/1775), [#1687](https://github.com/bookorbit/bookorbit/issues/1687), [#1571](https://github.com/bookorbit/bookorbit/issues/1571).

## 1.5.0

Released on the App Store on October 13, 2026 as **1.5.0 (27)**.

### New

- Rebuilt Home Screen widgets for every iPhone and iPad size, plus Control Center controls.
- Edit every book field, including ISBN, and match values from metadata providers.
- Follow the narration as text in the audiobook player.
- Read Along can keep playing in the mini-player while browsing the app.
- One player replaces the reader footer while narration runs.
- Request an ebook and its audiobook together.
- Filter Library and Search by book language.
- Keep the screen awake while reading ebooks.
- Book covers keep their original shape.
- Saved metadata search results are marked, with an option to search again.
- Comics can be included in ebook request preferences.

### Fixes

- Orbit Voices text to speech works again.
- Read Along resumes correctly after a pause.
- Watch audiobook progress syncs back to the phone and server.
- Reader pages and the book panel keep their layout when returning to the app on iPad.
- Continue Reading includes books with progress but no reading status.
- Refreshed ISBNs are applied and reminder preferences stay in sync.
- EPUBs with a malformed package now open.
- The book page stays smooth while downloads run.

Language filters require BookOrbit server 3.4.0 or later. Saved metadata search indicators and fresh searches appear on servers that support metadata search caching.

### Support issues

- [#29](https://github.com/bookorbit/bookorbit-ios-support/issues/29): Read Along pause and resume.
- [#40](https://github.com/bookorbit/bookorbit-ios-support/issues/40): Full metadata editing.
- [#44](https://github.com/bookorbit/bookorbit-ios-support/issues/44): Read Along mini-player.
- [#49](https://github.com/bookorbit/bookorbit-ios-support/issues/49): Keep the screen awake.
- [#50](https://github.com/bookorbit/bookorbit-ios-support/issues/50): Reader layout after reopening the app.
- [#54](https://github.com/bookorbit/bookorbit-ios-support/issues/54): Filter by language.
- [#55](https://github.com/bookorbit/bookorbit-ios-support/issues/55): Orbit Voices playback.
- [#56](https://github.com/bookorbit/bookorbit-ios-support/issues/56): Orbit Voices playback.
- [#58](https://github.com/bookorbit/bookorbit-ios-support/issues/58): Orbit Voices playback.

Main tracker: [#1712](https://github.com/bookorbit/bookorbit/issues/1712), [#1582](https://github.com/bookorbit/bookorbit/issues/1582).

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
