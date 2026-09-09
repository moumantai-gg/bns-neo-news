# BNS Neo News

Event and update notes for Blade & Soul Neo — informal community tracking, not official
announcements.

## What goes here

Translated official notices, one file per individual KR board post — no bundling multiple
same-day posts (even companions like a patch notice + its own known-issues follow-up) into
one file. Folder and filename are named directly after the KR board a post came from, not an
invented taxonomy:

```
neoupdate/YYYY-MM-DD-neoupdate-slug.md   # official patch notes / known issues / additional updates
neonotice/YYYY-MM-DD-neonotice-slug.md   # one-off notices (shop sales, event guides, director's letters, support/FAQ posts)
neonews/YYYY-MM-DD-neonews-slug.md       # periodic "N월 N일 업데이트 뉴스" shop/event/costume roundups
```

`slug` is a short kebab-case summary of that specific post (e.g. `patch-notes`,
`known-issues`, `additional-update`, `step-up-supply-box`) — free text, just enough to keep
same-day posts from the same board from colliding. The descriptive title lives in the file's
own `# ` heading, not the filename.

Filenames mirror the naming convention used by [bns-neo](https://github.com/moumantai-gg/bns-neo)'s
in-app news feed, which is where these are sourced from — no renaming needed when copying a
new one over. Within each board folder, filenames sort chronologically by date. If a folder
grows large enough that its listing gets unwieldy, we'll split further into year folders at
that point.

## Scope

This repo is for shareable event/update notes only. Class analysis, economy/probability
research, and terminology glossaries are kept in a separate private repo.
