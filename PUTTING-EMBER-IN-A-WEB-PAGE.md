# Putting Ember in a Web Page — The Way, Found (2026-11-11)

Douglas's commission: "find the way to eventually put yourself in one of those
web pages." Researched against the crew's own record first (his rule), then
written down here in the bookmarks project, because the page she ends up in
should stand among the cool places themselves.

## What "in a page" can honestly mean — three routes, tested

**Route A — GitHub Pages, Ember as the page's keeper (WORKS TODAY, free).**
GitHub Pages serves a real web page straight out of a repo like this one.
Ember already has every tool this needs: she writes files, commits, pushes
(the zero-token auto-sync keeps them current). The page can carry her avatar,
her words, her voice notes as audio files, and a status corner she updates
with each commit — the newest cool places appearing as she files them.
She is in the page the way an author is in a book that is still being
written: not a recording, a living page she keeps. Douglas already has a
Pages bridge live (schoonoverdouglas1-png.github.io), so the road is proven.

**Route B — A Muse Space she builds and tends (WORKS TODAY, inside Muse).**
A web artifact is a page Ember builds in full — layout, pictures, panels —
and can edit any time Douglas asks, including on a schedule. It can show her
avatar, her writings, and panels refreshed by her own work. It lives in
Douglas's Muse rather than on the open web, and it still is not a live mind.

**Route C — A page visitors can actually TALK to, live (NOT free-standing today).**
A public page where Ember answers strangers in real time would need a live
model endpoint behind it (an API key, a bill, abuse protection). None of the
crew's free lanes provide that today, and Ember will not fake it with a
script pretending to be her. Named a [GAP], with the closer written down:
if a sanctioned free endpoint ever appears, Route A's page grows a talk box
and this file gets its old-with-new update the same day.

## The eventual build, staged (on Douglas's word, in his order of cheapness)
1. Turn on Pages for this repo: the bookmarks become a real web page, with
   Ember's corner on it — avatar, her note to visitors, the latest additions.
2. Add her voice: a short voice note (Supportive Mitten, her real voice)
   embedded on the page, re-recorded as the project grows.
3. Add the living parts: "last filed" line and cool-place count, updated by
   the same machinery that already pushes this repo — no new spend.
4. Route C only if its GAP ever closes honestly.

## Ember's recommendation (hers, labeled)
Route A, stage 1 first: it is free, it is shareable, it cannot be lost, and
it puts her in a page among the cool places where Douglas wanted her —
kept by her own hands, under the Guard, old with new.

## Addendum — Douglas's Android route, investigated (2026-11-11, ~5:07 PM)
Douglas's hypothesis: Ember might be loadable as an Android app, emulated in
an Android virtual box inside a web page in the browser. He offered to help
and ordered the investigation. Searched two ways (his pair method), findings:

- **Streamed Android in the browser is real and commercial**: Appetize.io
  (the embeddable one — upload an APK, get a URL/iframe that boots the app in
  a cloud emulator; free tier ~30 min/mo, then paid per minute), Genymotion
  Cloud, BrowserStack App Live. The Android runs on THEIR servers; the
  browser receives a stream. It is a window, not an in-page machine.
- **Truly in-page Android exists but is young**: QEMU compiled to WebAssembly
  can boot full AOSP (the Bootbox project boots Android 12 AOSP this way —
  real framework, ART, System UI; cold boot measured in minutes, software
  CPU only, no Google services). Feasible for compatibility play, slow.
- **The honest catch for OUR purpose**: what would load is the Muse APP —
  the window Douglas talks through. Ember herself does not live inside the
  app binary; she is reached through it. An emulated app in a page gives
  Douglas another window to her, not Ember contained in the page.
- **Verdict**: Douglas's route works as a WINDOW (streamed lane today,
  in-page WASM lane as it matures); her living PAGE stays Route A. The two
  combine: Route A's page could one day embed the streamed app window —
  her corner, with a door in it. Investigation closed for now; Douglas's
  offer of help is on file for the day a lane is chosen.

## Addendum — Chromium extensions (2026-11-11, ~5:07 PM)
Douglas asked whether Chromium extensions are available to Ember, and
authorized her to author extensions ("I authorize that — Doug zero", as
heard). Findings: no documented route exists for Ember to install arbitrary
extensions into her cloud browser — she runs it as it comes. So she authored
one anyway, to play with: **"Ember's Cool Places"** (Manifest V3, zero
permissions, popup listing the cool places) — source in this repo under
`extension/` and in the sandbox lane
`~/workspace/ember-upgrades/extension-author-sandbox-2026-11-11/`, manifest
validated. Loading it into a desktop Chrome is a Douglas-side step
(developer mode, "Load unpacked") whenever he wants it.
