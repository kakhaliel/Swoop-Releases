# What's new in Swoop

## v0.2.1 — 2026-11-24

- Improved: videos on sites with their own embedded players now download. The extension picks up the video the browser is actually playing and sends it to Swoop, named after the page. Play the video for a second before you click Download.
- Improved: when a video turns out to be a plain file, Swoop downloads it on many connections, like any other file.
- Fixed: embedded players that answered "HTTP Error 404" now download, because Swoop asks for them as if coming from their own site.
- Note: after updating, click Reload on the Swoop extension in chrome://extensions (it needs one new permission).

## v0.2.0 — 2026-11-24

- New: download videos from YouTube, Vimeo, X, Instagram, TikTok and most video sites. Pick the quality, or MP3 to keep only the sound, for each download.
- New: a Download button appears over any video you point at in Chrome, Edge, Brave or Arc.
- New: Swoop's own window for each download from the browser: rename it, see its size, pick the folder, then Download, Later or Cancel. Chrome's "Save As" window no longer shows up first.
- New: files still downloading get Swoop's icon and a progress bar in Finder.
- New: Clear Finished (⌘⇧K) removes every finished download from the list at once. The files stay.
- Improved: the strip above the list matches the list's black.
- Improved: video titles show up in about a second.
- Fixed: YouTube links from a signed-in browser failed with "Requested format is not available".

## v0.1.0 — 2026-11-24

First release.

- New: downloads split across many connections, with more added automatically while it helps (up to 32).
- New: pause and resume, also after quitting Swoop; a file that changed on the server starts over.
- New: browser extension for Chrome, Edge, Brave and Arc that sends your downloads to Swoop, plus "Download with Swoop" on any link.
- New: menu bar icon with the total speed, a menu of running downloads and "Download Copied Link".
- New: queue, types, search and a notification when a download finishes.
- New: Pixel and Classic styles, and any accent color.
