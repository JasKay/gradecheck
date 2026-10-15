# GradeCheck

A privacy-first, static student grade reconciliation web app. Upload XLSX/CSV or paste tables. D1 is the reference; (1) matches blank marker and (2) matches Resub. Export the results as XLSX.

## Publish

Upload this folder to a GitHub repository and import it into Vercel as an **Other** framework project, with no build command. Alternatively host index.html on any static host.

## Privacy

Processing happens in the browser. XLSX parsing/export uses the SheetJS library loaded from a CDN; network access is needed to load it. No student records are transmitted by application code.
