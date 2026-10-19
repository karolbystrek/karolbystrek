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
- Use semantic HTML: `header`, `main`, one `h1` with a `small` subtitle, `h2` sections, `h3` entries, `p`, `ul`/`li`, and ordinary `a` links. Use a shared spacing scale: 2rem before sections, 0.75rem below section headings, 1.5rem before entries, 0.375rem below entry headings, and 1rem between body blocks. Suppress the following block’s top margin after headings and the first entry’s top margin directly after a section heading. Keep 0.5rem below the main name heading.
- In Projects and Achievements, keep headings unlinked and put available links in a separate paragraph directly below each heading, ordered Website | Repository | LinkedIn post. Omit unavailable links and omit the paragraph when there are none. Keep links out of descriptions. Keep Experience role headings unlinked; show dates directly below them. Keep descriptive visible link text and noopener noreferrer for links opening a new tab.
- Keep native link colors; underline on hover, active, and keyboard focus. Preserve visible focus indicators.
- Place the portrait on the right of the desktop header, preserving its proportions and matching the height of the name, title, and contact line. Keep location on its own line, with email, GitHub, and LinkedIn below it separated by |; stack the 120px-high portrait above the text and allow contacts to wrap on narrow screens. Use CSS for presentation and meaningful image alt text.
- Keep styling in a small embedded stylesheet. Favor normal document flow and native HTML over cards, decorative effects, custom fonts, frameworks, or JavaScript for static content.
