# Yomi Fallback App

A self-contained browser app that generates the daily **Mishnah Yomi** and **Kitzur Shulchan Aruch Yomi** posts — a manual fallback if the nightly automation ever fails.

## How to use it

1. Download `yomi-fallback.html` (use the **Download raw file** button on the file's page).
2. Open the file in any browser — phone or computer. No install, no sign-in.
3. Pick a date (or use Today / Tomorrow), check the shiurim you have, and tap **Generate**.
4. Use **Copy** to paste the post into WhatsApp, or **Download .txt** to save it as a file.

The app needs an internet connection when generating: the calendars are built into the file, but the texts are fetched live from Sefaria and dates are converted via Hebcal.

## What's inside

- **Mishnah Yomi tab** — morning post + evening reminder in the exact nightly format, including the Erev Shabbos variant (Friday itself gets no reminder), cross-perek and cross-masechta days, and a manual override (pick any masechta / perek / mishnah range) for catch-up posts.
- **Kitzur Shulchan Aruch Yomi tab** — morning post + reminder, Translator's Note handling, footnotes stripped, month-length splits/merges handled the same way as the nightly job, and a manual override that can span simanim.
- Shiur lists are checkboxes: uncheck a rabbi who has no shiur that day and the numbered list renumbers itself.

## Notes

- **Text only.** The shiur names are list entries, not audio — the app does not fetch recordings.
- Everything runs in the browser; nothing is uploaded or tracked.
