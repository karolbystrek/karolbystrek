# Repository context

- Karol Bystrek's professional portfolio as a software engineer.
- Deployed on Vercel at https://karolbystrek.pl; this bare domain is the primary URL, with www redirecting to it.
- Visual inspiration: https://grugbrain.dev. Keep the design simple and professional.
- Professional profile: https://www.linkedin.com/in/karol-bystrek/.
- GitHub: https://github.com/karolbystrek.
- The page serves as a concise resume for recruiters considering Karol for junior software engineering roles. Keep claims specific and defensible; structure About, Experience, Projects and Achievements, and Skills so their text can be reused in a resume.
- This repository also supplies the GitHub profile README. Keep README.md to a prominent heading linking to the website; the GitHub bio carries the brief introduction.

## Content and metadata maintenance

- When changing the name, professional title, location, or summary, review the HTML title, meta description, and Open Graph title and description for consistency. Metadata must reflect the visible content.
- When changing the primary URL, update the canonical link, og:url, and absolute og:image URL together.
- When changing the portrait, name, title, or location, update sharing-preview.png to match. Keep it 1200 × 630 and keep og:image dimensions and alt text accurate. Preserve the large-image sharing card metadata.
- Keep robots.txt permissive for this public portfolio. For indexing problems or substantial published changes, use Google Search Console to inspect the primary homepage and request indexing if needed.
- Keep the site without a favicon, as requested.
- Use gh CLI for GitHub interactions. Group requested commits by independent change; include referenced assets with their HTML metadata.

## Design guidelines

- Follow [grugbrain.dev](https://grugbrain.dev)'s plain, text-first style: a single reading column, browser-default serif typography, white background, and dark gray text.
- Keep the reference's body baseline: `max-width: 768px`, `margin: 40px auto`, `padding: 0 10px`, `font-size: 20px`, `line-height: 1.6`, `color: #444`; headings use `line-height: 1.2`.
- Use semantic HTML: `header`, `main`, one `h1` with a `small` subtitle, `h2` sections, `h3` entries, `p`, `ul`/`li`, and ordinary `a` links. Let native element margins provide spacing.
- Link the full role or achievement heading to its supporting LinkedIn post instead of adding a separate [post] or [link] label. Keep descriptive visible link text and noopener noreferrer for links opening a new tab.
- Keep native link colors; underline on hover, active, and keyboard focus. Preserve visible focus indicators.
- Use a 120px-high portrait floated left with a 20px right margin on desktop; stack it above the title on narrow screens. Use CSS for presentation and meaningful image alt text.
- Keep styling in a small embedded stylesheet. Favor normal document flow and native HTML over cards, decorative effects, custom fonts, frameworks, or JavaScript for static content.
