# New Crystal Structure Short Paper Generator

Browser-only tool for drafting short crystal-structure reports from real CIF/checkCIF data.

## Features

- Upload a CIF file and extract core crystallographic metadata.
- Optionally upload a checkCIF report and summarize alert risk.
- Fill in CCDC number, authors, affiliation, synthesis route, and structure notes.
- Generate a New Crystal Structures-style short manuscript draft.
- Export Word-compatible `.doc` and Markdown files.
- Runs fully in the browser; no server upload is required.

## GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html`, `README.md`, and `.nojekyll`.
3. Go to **Settings -> Pages**.
4. Choose **Deploy from a branch**.
5. Select branch `main` and folder `/root`.
6. Save and wait for the Pages URL.

## Important Limitations

This tool does not create crystallographic evidence. The following must be real and checked manually:

- CIF file
- CCDC number
- checkCIF alerts and explanations
- Hydrogen bonds, torsion angles, packing, coordination environment, and structure comments
- References

Do not use generated text for submission before manual crystallographic review.
