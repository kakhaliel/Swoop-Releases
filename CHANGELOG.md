# What's new in Swoop

## v0.3.0 — 2026-11-25

- New: Swoop updates itself. It checks for a new version at launch and every few hours, shows what's new, and installs it with one click (Install and Restart). Running downloads are paused and pick up again after the restart. You can also check from Swoop → Check for Updates…, the menu bar, or Settings → General.
- New: after an update that brings a new browser extension, Swoop reminds you to click Reload and opens Chrome's extensions page for you.
- Note: from 0.2.2 or older, download this version by hand once. Every update after it arrives by itself.

## v0.2.2 — 2026-11-25

- Fixed: Instagram reels and posts download whole, with picture and sound and the post's own title. Before, a piece of another reel could be saved instead.
- Improved: videos that come as VP9, AV1 or MKV (Instagram, some YouTube qualities) are converted to H.264 MP4 after downloading, so QuickTime and every Mac app play them. You can turn this off in Settings → Video.
- Improved: portrait videos (reels, shorts) get the quality you picked. A 1080×1920 reel counts as 1080p instead of dropping to 540p.
- Improved: when a site is slow or the connection drops, Swoop tries again by itself (up to 3 times) before giving up.
- Note: after updating, click Reload on the Swoop extension in chrome://extensions.

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
