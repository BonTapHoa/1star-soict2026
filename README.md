# 1STAR: AI Challenge HCMC 2026 and SOICT 2026

Project page of **1STAR**, an interactive video event retrieval system. It covers two things: the Ho Chi Minh City AI Challenge 2026 (system, finals, award day, press) and the accepted SOICT 2026 paper, **1STAR: Narrative Story Structuring for Operator-Centric Interactive Video Event Retrieval System** (paper ID 6997, oral and poster). The URL stays `/1star-soict2026/` because printed poster QR codes point to it.

Live page: https://bontaphoa.github.io/1star-soict2026/

## What is here
- `index.html`: the whole page (plain HTML and CSS, no build step). Layout: hero with the team photo and two entry cards, a timeline, Part 1 (the competition), Part 2 (the paper), posters, press and interview, team, cite.
- `assets/paper/`: the accepted manuscript (PDF) with a one-page publisher notice in front. The manuscript pages are unchanged.
- `assets/poster/`: the SOICT 2026 poster, the AI Challenge HCMC 2026 award-day poster (PDF and previews).
- `assets/figures/`: figures taken from the poster and the paper.
- `assets/media/`: two press photos (team photo, award-ceremony photo) from the school's website and Facebook page, re-encoded as WebP without metadata, with attribution on the page.
- `CITATION.cff`: citation metadata (the DOI is added after publication).

## What is not here, on purpose
- System code, DRES logs and per-team scores (organizer data), raw benchmark files, and video from the AI Challenge dataset.
- Personal contact details on the page itself. Use GitHub Issues. (The accepted manuscript PDF prints the author emails, as in the submitted paper.)

## Accepted manuscript and the publisher licence
The PDF is the Accepted Manuscript (before copy-editing). The licence allows it on an author-maintained website if it is not reformatted, carries the publisher's notice, and links to the Version of Record. The notice page is in the PDF; the DOI link is still a placeholder and must be filled in as soon as it exists (see below). The manuscript must never be shared under a Creative Commons licence.

## Updating after publication
1. Add a link to `https://doi.org/<DOI>` next to the Paper button in `index.html` and replace the DOI placeholder in the notice paragraph.
   Rebuild the notice page (`[DOI to be added after publication]`) and re-merge it in front of the manuscript PDF.
2. Fill the DOI in the BibTeX block and in `CITATION.cff`.
3. Add the "First published in [volume, pages, year] by Springer Nature" line to the footer.

## Press, photos and sources
Facts about the competition and the conference come from the school's articles, the conference site and the organisers' site, each cited on the page. The interview is paraphrased, not quoted. The photos belong to the school or its photographers and are shown with attribution; remove them on request.

## Notices
Content copyright 2026 1STAR team. The paper is published by Springer Nature. Video frames belong to the AI Challenge dataset and their original broadcasters.
