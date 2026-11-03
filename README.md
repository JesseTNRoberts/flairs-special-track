# FLAIRS-40 Special Track: Deliberative and Generative AI: Hybrids and Foundations

Call-for-papers site for the FLAIRS-40 special track (St. Pete Beach, FL, May 24–27, 2027).

Live site: https://jessetnroberts.github.io/flairs-special-track/

- Conference: https://www.flairs-40.info/
- Submissions: https://easychair.org/conferences/?conf=flairs40 (choose this track)

## Files

| File | Purpose |
|---|---|
| `index.html` | The whole site: one self-contained page |
| `cfp.txt` | Plain-text CFP for mailing lists, WikiCFP, etc. |
| `paper/` | The motivating ACS-2026 paper (camera-ready PDF) and its first-page thumbnail |
| `fonts/` | Self-hosted Source Serif 4 and Public Sans (SIL Open Font License) |
| `og.png` | Preview image shown when the link is shared |
| `sitemap.xml`, `robots.txt` | Help search engines find and index the page |
| `.nojekyll` | Serve files as-is (no Jekyll build) |

## Deploy

1. Create a public repo named `flairs-special-track` under `JesseTNRoberts`.
2. Push these files to the `main` branch, at the repo root.
3. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.

If you use a different repo name, update the URL in `index.html` (canonical, `og:url`, `og:image`, JSON-LD), `sitemap.xml`, `robots.txt` and `cfp.txt`.

## Helping people find it

- Send the URL to the FLAIRS-40 Special Tracks Coordinator so it is linked from the conference's special tracks page.
- Add the URL to the repo's "About" box, with topics such as `flairs`, `call-for-papers`, `llm`, `search`.
- Register the site in Google Search Console and submit `sitemap.xml`.
- Post `cfp.txt` to WikiCFP and the relevant mailing lists.

## When the ACS-2026 proceedings go online

In `index.html`, add the proceedings link next to the "Read the paper" button (section `#paper`), or point the button at it and delete `paper/fisher-moore-roberts-acs2026.pdf`.
