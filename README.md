# GCC Atlas — India GCC Intelligence

A source-linked product concept prototype for the Flexiple Product Intern assignment.

## Run locally
Open `index.html` in a modern browser. No build step or API key is required.

## Deploy to Vercel
1. Create a GitHub repository named `gcc-atlas`.
2. Upload `index.html` to the repository root.
3. In Vercel, import the GitHub repository.
4. Use the static site / Other framework preset. No build command is required; set the output directory to `.` if prompted.
5. Deploy and test the public URL in an incognito window.

## What works
- Market overview with source-linked metrics and announcements.
- GCC directory with search and filters, record details, source lineage and saved shortlist.
- City comparison with sourced directional signals and diligence gaps.
- Policy explorer with official/secondary-source distinctions and eligibility checklist.
- Provider discovery with evidence caveats and shortlist actions.
- Research copilot using curated retrieval rules and linked sources.
- Decision brief generator, saved records, copy and `.txt` download.

## Data integrity / scope
- The prototype deliberately includes a small set of real, publicly reported announcements with links and explicit limitations.
- City profiles are directional, source-linked market context, not audited composite scores.
- Policy information is not legal or tax advice; eligibility and current status must be checked from primary sources.
- The research copilot is a deterministic, curated retrieval demo, not a live LLM. It does not claim to be a live AI assistant.
- The prototype uses browser localStorage for saved records and does not transmit user input to a server.

## Source set
- JLL: https://www.jll.com/en-in/newsroom/india-s-gcc-expansion-hits-record-31-million
- MODEC: https://www.modec.com/news/2025/20250618_pr_OFS-India.html
- Trigent / Codec: https://trigent.com/news/trigent-and-codec-partner-to-launch-global-capability-centres/
- Citizens Financial / Cognizant announcement archive: https://ebs.publicnow.com/view/8279E4637B697CC7798E187F0F76A7FF049637AA
- Government of Karnataka GCC Policy portal: https://registration.eitbt.karnataka.gov.in/gcc/register
- ICAI state policy summary: https://global.icai.org/state-policy.html
- Embassy Group EMBARK announcement: https://embassygroup.com/press-release/embassy-group-launches-indias-only-integrated-gcc-platform-embark/
