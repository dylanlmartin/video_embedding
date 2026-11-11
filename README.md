# Clip player

A one-page player that plays a single segment of a YouTube video (start to end), for
study notes. Served by GitHub Pages.

Usage: `index.html?v=VIDEO_ID&start=14:22&end=15:05&title=Sample%20space`
(times in seconds or m:ss).

Why this exists: YouTube only honours end times in its embed player, and the embed
player refuses to play when opened directly (Error 153). It has to be embedded in a
real web page, which is all this is.

## Public use
This player is a shared utility: anyone may link to it, including courses
built from [agent_tutor](https://github.com/dylanlmartin/agent_tutor). It
is a static page with no analytics, cookies or tracking; the video itself
streams from YouTube's official embedded player. The URL and its
`?v=&start=&end=&title=` format are kept stable so existing links keep
working. Prefer to host your own? Fork this repo and enable GitHub Pages.
