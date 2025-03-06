---
title: "Music Sheets"
date: 2025-03-06
showDate: false
draft: false
tags: ["music", "life"]
resources:
  - src: "black-parade.pdf"
    title: "Welcome to the Black Parade"
    params:
      icon: "pdf"
---

## Music tracker
| Title | Type | Practiced | Rehearsed | Where |
|---|---|---|---|---|
| Guardians of Liberty | March | Yes | Yes | Orchestra |
| Smoke on the water | Song | No | No ||

### Music sheets of my own
- {{< a src="/content/music/music-sheets/black-parade.pdf">}}
    Black Parade Sheet
  {{< /a>}}
- {{ with .Resources.Get "/black-parade.pdf" }}
    {{ .Content }}
  {{ end }}
- [Welcome to the Black Parade](https://andreafonso.pt/content/music/music-sheets/black-parade.pdf)