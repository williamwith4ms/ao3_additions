[![GitHub License](https://img.shields.io/github/license/williamwith4ms/ao3_additions)](https://github.com/williamwith4ms/ao3_additions/blob/main/LICENSE)
[![GitHub Release](https://img.shields.io/github/v/release/williamwith4ms/ao3_additions)](https://github.com/williamwith4ms/ao3_additions/releases/latest)
[![GitHub Issues or Pull Requests](https://img.shields.io/github/issues/williamwith4ms/ao3_additions)](https://github.com/williamwith4ms/ao3_additions/issues)

# Ao3 Additions
Currently adds:
- History tracking
- History Statistics
- Tag Blocking
- Highlights already-read works on search

## Usage
- Works can be marked/unmarked as read by clicking the "(un)Mark as Read" button on the work page. (Has the extension icon next to it)
- The history page can be accessed by clicking the extension icon and then clicking "History"
  - Same for the options page and the stats page
- Tags can be blocked by clicking the "Block Tag" button on the tag page, or by adding them to the list in the options page.

## TODO (not in any particular order)
- [x] Import history and merge for a way to kinda share between devices
- [ ] History tag searching
- [x] History statistics e.g. most common tags, most common fandoms, etc.
  - [ ] Add extra stats e.g. compare to actual books, estimate reading hours, etc.
- [x] Search tag blocking
  - [ ] better UI for blocking tags
- [ ] Automatic mark as read when reaching the end of a work
- [ ] Per chapter mark as read
- [ ] use `browser.storage.sync` to sync history (would require only storing the id and then having a system to fetch the work data from the id)
  - could also use a third party service e.g. google drive or my server 
- [ ] actually publish it to the mozilla store
- [x] have an icon for the extension
- [ ] make it look pretty
- [x] organise the files better
- [ ] track the time spent reading and use the word count to estimate reading speed
- [ ] dark mode

Disclaimer: This is not an official extension.