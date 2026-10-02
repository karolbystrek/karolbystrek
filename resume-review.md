# Resume review — 2 October 2026

Reviewed `Resume 2026.pdf` against the local portfolio and the linked project repositories. The PDF is one page and its contact, project, and achievement links are clickable. Its internship and project experience provides a credible basis for junior Java/backend and full-stack applications.

## Changes to carry into the resume

Use the updated About, Experience, Projects and Achievements, Skills, Education, and Languages text in `index.html` as the shared source. Keep the existing employer names, role titles, employment dates, and contact details.

- Replace the summary: it currently omits IBM and relies on unsupported qualifiers such as “results-oriented,” “proven track record,” and “enterprise-grade.” The new summary names both internships, the main application stack, the award track, and the target role.
- Use two IBM bullets and three Ocado bullets. The updated wording merges overlapping platform/stack descriptions and removes the separate IBM collaboration bullet, which provides less evidence than the delivered pipeline.
- Use “Joint First Place, Asseco Track” in the hackathon heading. The award was within that track; avoid implying an overall win across the event. Spell out retrieval-augmented generation (RAG) on first use if space allows.
- Label Kairos “B.Sc. Project — In Progress.” This context appears on the website but is absent from the PDF. Keep the distinction between tracking without an app installation and the optional customer PWA.
- Use the updated Private Cloud Resource Manager description: batch job execution, quotas, logs, and artifact storage explain what the platform actually does more clearly than “provisions institutional hardware.” Repository functionality does not establish which individual authored each feature, so the wording retains your stated technical-lead contribution without assigning every feature to you.
- Rename “Expertise” to “Skills.” Include Terraform and Tekton, which your experience supports but the PDF's skills list omits. Ruby is supported by the IBM description. Replace the broad “Agile” entry with concrete tools; the website now includes Git and automated testing.
- Write “Expected graduation 2027” rather than “Exp. 2027.” Keep “English — C1” and “Polish — Native” consistent across both versions.

## One-page presentation

The current document fits, but the sidebar occupies roughly one third of the page, the portrait uses substantial space, and the main text is small and justified. This creates uneven word spacing and compresses the strongest material.

1. Prefer a single column with a compact contact line: email, phone, Kraków, website, LinkedIn, and GitHub. Add the currently missing portfolio link, `karolbystrek.pl`. Keep the phone in the resume; there is no need to publish it on the website.
2. Order sections: short summary, Experience, Projects and Achievements, Education, Skills, Languages. Use ordinary headings, left-aligned body text, and bullets for experience. Keep employer, title, and date together.
3. Aim for 10–11 pt body text and comfortable margins. Remove the timeline decoration and reduce or omit the portrait before shrinking the text. Avoid expanded letter spacing in body text.
4. Retain all three projects initially. If space is tight, remove the secondary-school entry from the resume first, then shorten the summary. The website can keep the full education history. Keep the university, degree, and expected graduation.
5. Use the same core wording on both surfaces. Tailor project order and the skills order to each vacancy: emphasize Java/Spring Boot and the cloud project for backend roles; React/TypeScript and Kairos for full-stack roles.

The revised core copy is shorter, but its final one-page fit needs checking in your resume editor. No revised PDF was generated or substituted for your original.

## Evidence and remaining limits

- [Kairos README](https://github.com/karolbystrek/kairos/blob/HEAD/README.md): separate Spring Boot API, Next.js staff panel and customer PWA; authenticated staff access and account-free customer tracking. The API dependency file also supports PostgreSQL usage.
- [Private Cloud Resource Manager README](https://github.com/karolbystrek/private-cloud-resource-manager/blob/HEAD/README.md) and implementation: Spring Boot control plane, Nomad batch execution, quota accounting, job log endpoints, and stored output artifacts. Inspected through `gh` CLI.
- [Organizer's results](https://hackathon.warsaw.ai/wyniki-hackathonu-2025/) list two equally rewarded Asseco teams; [your LinkedIn post](https://www.linkedin.com/posts/karol-bystrek_mamy-to-1-miejsce-ex-aequo-na-warsawai-share-7401326912570118144-qH4h) states joint first place. The frontend/backend contribution and extraction details remain your supplied account; a hackathon code repository was not available in the supplied links.
- Employment responsibilities, leadership, education, and language proficiency remain self-reported. Public repositories cannot verify private employer work. No invented adoption, performance, savings, or scale metrics were added.
- If you can substantiate and disclose them, add one useful measure to each internship: images/environments scanned, reporting cadence, users supported, or migration scope. A precise feature or technical constraint is also useful when metrics are unavailable.
- PDF extraction inserted spaces between individual letters and placed sidebar material before the main experience. This is an observed parsing issue, not proof that every applicant tracking system will fail. After re-exporting, copy all text into a plain-text editor and check names, keywords, dates, and reading order; verify every hyperlink again.

The emphasis on concise, factual, scannable wording follows [Harvard's resume guidance](https://careerservices.fas.harvard.edu/resources/create-a-strong-resume/). No wording or layout can guarantee interviews; relevance to the vacancy and defensible evidence matter most.
