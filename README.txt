CATALYTIC DISCIPLESHIP LESSONS — WEB APP KIT
Union Church of Manila · Design and Development by Ernie Agtarap / Mulberry Lane Creative

WHAT THIS IS
The complete CDL site (Coach's and Learner's Manuals) packaged so UCM can host it on
its own website. When hosted over HTTPS, people can add it to their phone's home screen,
where it opens full-screen with its own icon and keeps working without internet after
the first visit.

HOW TO PUBLISH
1. Upload everything in this folder, keeping the folder structure, to a folder on UCM's
   website, for example:  https://www.unionchurch.ph/cdl/
2. The site must be served over HTTPS (needed for offline use and home-screen install).
3. Open the address on a phone to check it.

ADD TO HOME SCREEN
- iPhone / iPad (Safari): tap Share, then "Add to Home Screen".
- Android (Chrome): tap the ⋮ menu, then "Install app" or "Add to Home screen".

WHAT'S INSIDE
index.html            The whole site in one file
manifest.webmanifest  App name, colors and icons for home-screen install
sw.js                 Keeps the site working offline after the first visit
icons/                App icons (1024, 512, 192, 180 for Apple, favicon)
audio/                127 recorded Scripture readings (ESV)
pdf/                  The Coach's and Learner's Manual PDFs (letter size)

UPDATING
When the site changes, replace index.html (and any changed files) and change
CACHE='cdl-v1' to 'cdl-v2' in sw.js so phones fetch the new version.

NOTES
- Everything people type (answers, notes, lists) stays in their own browser on their
  own device. Nothing is sent to UCM or anyone else.
- Scripture quotations are from the ESV. Please confirm with Crossway that the recorded
  audio readings are covered by UCM's permission before publishing them publicly.
- An App Store app would need a native wrapper and Apple review (guideline 4.2).
