# Nhan's Fall 2026 Class Schedule (Edmonds College)

A single-page schedule + assignment tracker. No account, no sign-in. It runs in any
web browser, works offline once loaded, and can be **installed like an app** on a phone.

Term: **Sep 21 – Dec 11, 2026** · Courses: Drawing I/II (ART 101/102), Microbiology w/Lab
(BIOL&260), Intro Organic/Biochem (CHEM&131).

## What it shows
- **Weekly meeting grid** — day, time, room + building, class number.
- **Assignment & exam check-off** — every item with its due date/time and points.
  Tap to mark done; a **Hide done** toggle removes finished items from the list.
  Progress is saved in that phone/browser (private to the device).
- **QR code** on the page (and in `qr.html`) that opens the hosted link.

## How to open it
- **Just view:** open `https://drakesbanereal1.github.io/schedule/` — or scan the QR.
- **Install as an app (works offline after):**
  - Android/Chrome: open the link → menu (⋮) → **Install app / Add to Home screen**.
  - iPhone/Safari: open the link → **Share** → **Add to Home Screen**.
- **Fully offline from files:** download this folder and double-click `index.html`.

## Files
| File | What it is |
|---|---|
| `index.html` | The schedule page — open this. |
| `manifest.webmanifest` | Makes it installable (app name, icon, colors). |
| `sw.js` | Service worker — caches the page so it works offline. |
| `icon.svg` | App icon (home-screen / tab). |
| `qr.html` | A printable full-page QR that opens the hosted link. |
| `schedule.html` | Backup copy of the page (same content as index.html body). |

## Hosting (GitHub Pages)
Repo **Drakesbanereal1/schedule**, Public. Pages: Settings → Pages → Deploy from a
branch → **main** / **root**. Live at `https://drakesbanereal1.github.io/schedule/`.
The QR/link work with no login and with the owner's PC off.

## Updating
Manual: when new Canvas dates post, the schedule data in `index.html` (the `COURSES`
list) is refreshed and the file is re-uploaded to the repo. Same URL, same QR.

*Not affiliated with Edmonds College or Instructure/Canvas. If any item conflicts with
official Canvas, follow the official source.*
