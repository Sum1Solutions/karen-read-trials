# Karen Read Trial Evidence Tracker

A static site comparing evidence and arguments presented to the jury in the first Karen Read trial (2024) and the retrial (2025). Built for clarity, transparency, and accessibility.

## Features

- **Landing page** (`index.html`) links to:
  - The original evidence table (ChatGPT-3.5/o3 summary)
  - The updated, LLM-generated table (ChatGPT-4.1/Cascade LLM)
- **LLM Table** (`llm_trial_fact_table.html`):
  - Fully referenced with links to all public sources
  - Mobile-friendly and responsive for all devices
  - Prominent link to the [WCVB evidence gallery](https://www.wcvb.com/article/karen-read-murder-trial-see-read-evidence-shown-to-jurors-in-courtroom/60793160)
  - Ready for future mapping to official trial exhibit numbers (add to the "Exhibit(s)" column as available)
- **Style** (`style.css`):
  - Optimized for readability, accessibility, and mobile use

## Deploy on Cloudflare Pages

1. Push all HTML and CSS files to your Git repository.
2. In Cloudflare → Pages, create a project and connect your repo.
3. Build settings: Framework **None**, leave build command blank, output dir `./`.
4. Deploy.

## Contributing

- If you have the official exhibit list or want to help map facts to exhibits, submit a pull request or open an issue.
- For corrections, source suggestions, or feature requests, please open an issue.

_Last updated: 2025-05-14_
