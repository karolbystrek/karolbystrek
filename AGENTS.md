# Repository context

- Karol Bystrek's professional portfolio as a software engineer.
- Deployed on Vercel at https://www.karolbystrek.pl.
- Visual inspiration: https://grugbrain.dev. Keep the design simple and professional.
- Professional profile: https://www.linkedin.com/in/karol-bystrek/.
- GitHub: https://github.com/karolbystrek.
- The page serves as a concise resume for recruiters considering Karol for junior software engineering roles. Keep claims specific and defensible; structure About, Experience, Projects and Achievements, and Skills so their text can be reused in a resume.

## Design guidelines

- Follow [grugbrain.dev](https://grugbrain.dev)'s plain, text-first style: a single reading column, browser-default serif typography, white background, and dark gray text.
- Keep the reference's body baseline: `max-width: 768px`, `margin: 40px auto`, `padding: 0 10px`, `font-size: 20px`, `line-height: 1.6`, `color: #444`; headings use `line-height: 1.2`.
- Use semantic HTML: `header`, `main`, one `h1` with a `small` subtitle, `h2` sections, `h3` entries, `p`, `ul`/`li`, and ordinary `a` links. Let native element margins provide spacing.
- Keep native link colors; underline on hover, active, and keyboard focus. Preserve visible focus indicators.
- Use a 120px-high portrait floated left with a 20px right margin on desktop; stack it above the title on narrow screens. Use CSS for presentation and meaningful image alt text.
- Keep styling in a small embedded stylesheet. Favor normal document flow and native HTML over cards, decorative effects, custom fonts, frameworks, or JavaScript for static content.
