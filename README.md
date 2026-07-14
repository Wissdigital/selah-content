# Selah Content Database

The full content database for the Selah app (Bible text, promises, prayers, word studies,
Strong's lexicon + concordance). Not bundled in the app itself — downloaded once on first
launch and cached on-device from here, so the installed app stays small and the content can
be updated without a store release.

Built by `data-pipeline/build-db.js` in the main Selah repo. Bible text is public domain
(KJV, BSB, WEB, ASV). Word-occurrence data is STEPBible-Data (Tyndale House / STEPBible.org),
CC BY 4.0 — see the app's About screen for full credits.

`version.json` — bump `dbVersion` whenever `selah.db` changes; the app compares this to decide
whether to re-download.
