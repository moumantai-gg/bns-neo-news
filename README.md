# BNS Neo News

Event and update notes for Blade & Soul Neo — informal community tracking, not official
announcements.

## What goes here

Translated official notices, one file per board per day. Same-day companion posts from
the same board (a patch notice + its own known-issues follow-up, a director's letter +
its companion notices, several same-day shop guides) are bundled into that one file as
appended sections, in whatever reading order makes sense — usually the primary post
first, companions after. Folder and filename are named directly after the KR board a
post came from, not an invented taxonomy:

```
neoupdate/YYYY-MM-DD-neoupdate.md   # official patch notes / known issues / additional updates
neonotice/YYYY-MM-DD-neonotice.md   # one-off notices (shop sales, event guides, director's letters, support/FAQ posts)
neonews/YYYY-MM-DD-neonews.md       # periodic "N월 N일 업데이트 뉴스" shop/event/costume roundups
```

Date + board is already unique per day, so the filename needs no extra slug. This is
deliberate: with one file per individual KR post, same-day ordering had no natural
signal to sort on other than the post's own slug text, which is arbitrary. Bundling
means reading order is just prose order within one document, decided once by whoever
writes the doc.

Filenames mirror the naming convention used by [bns-neo](https://github.com/moumantai-gg/bns-neo)'s
in-app news feed, which is where these are sourced from — no renaming needed when copying a
new one over. Within each board folder, filenames sort chronologically by date. If a
folder grows large enough that its listing gets unwieldy, we'll split further into year
folders at that point.

## Scope

This repo is for shareable event/update notes only. Class analysis, economy/probability
research, and terminology glossaries are kept in a separate private repo.
