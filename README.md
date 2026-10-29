# GS INTERIOR STUDIO — combined files and GitHub hosting

## Publish the current website
Upload the CONTENTS of this folder to your GitHub repository. Keep site/, .github/ and the other folders at the repository root.
In GitHub Settings → Pages, choose GitHub Actions as the source. In Actions, select Deploy website → Run workflow. The workflow publishes only site/; it does not publish the document archive.
For another static host, set the publish directory to site and leave the build command empty.
For local preview: python3 -m http.server 8000 --directory site

## Contents
- site/: latest website, including the new Behind the build section and enhanced gallery, 50 blog pages, 49 optimised room photos and 30 optimised logos.
- .github/workflows/pages.yml: manually triggered GitHub Pages deployment.
- assets-original/: extracted 30-logo archive and 56-file original website picture archive.
- review-package/: complete recovered review package contents, including the working DOCX manual, existing-site text DOCX, asset ZIPs and registers.
- previous-package/: 233 verified files recovered from the earlier damaged archive, including original attachments, full-size generated images, documents, rendered PDFs, earlier website prototype and authoring files. Its README and FILES.json describe the previous package, not this combined delivery.
- authoring/: scripts and editorial status from the latest hosting delivery.
- RECOVERY_STATUS.json: exact recovery limitations.
- FILES.json: current package file list with sizes and SHA-256 checksums.

## Recovery and content status
The earlier large ZIP was truncated. Its complete entries were recovered and checked against ZIP CRCs. Six further original image files were restored by matching exact SHA-256 hashes from the logo archive. Three original generated PNG files could not be recovered; their names are in RECOVERY_STATUS.json. All 30 studio logo variants are present in assets-original/. The old hosting snapshot after the truncation is superseded by the current site/ version. The damaged ZIP itself is omitted.

This is all recoverable project material, not a guarantee that every historical byte is present. The original uploaded reference document and logo attachments are included. The current website has 50 blog articles with roughly 16,660 body words and 10 image placements per article, using repeated images. The requested 99,000-word expansion has not been completed. The working manual remains a draft. Archive room imagery is not independently verified as completed client work.

Do not upload this combined ZIP as a single file to GitHub: unzip it and commit its contents. No repository credentials or private deployment metadata are included.

## Latest update
This package includes the published photo update at source commit af670e2491bc6a5441849ada022900e5f24b94c1. Eight photographs from the supplied Google Drive folder are integrated: six on the homepage and all eight in the gallery. The site now contains 49 room/site photos and 30 logo images. The drive-photos-reviewed folder retains the 16 reviewed originals and WebP conversions. The original three missing generated image files remain unrecovered. The 99,000-word target remains unfinished.
