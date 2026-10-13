# Infinite Resume for Claude

Build, improve, tailor and review a truthful resume in Claude. Claude asks one useful question at a time, writes only what is true of your experience, shows you the complete draft, and sends it to Infinite Resume only after you approve it. You then edit it, choose a template and download the PDF on [infiniteresume.com](https://www.infiniteresume.com).

## What it does

- **Builds or improves a resume** with guided questions and factual rewrites. It does not invent employers, dates, metrics or qualifications.
- **Tailors a resume to a job** by comparing the posting with experience you actually have.
- **Checks ATS readability** and points to the few edits that matter most.
- **Opens an editable preview** on Infinite Resume once you approve the full draft. This part needs an Infinite Resume account.

## Install

In your terminal:

```sh
claude plugin marketplace add sattyapatil/infinite-resume-claude-plugin
claude plugin install infinite-resume@infinite-resume-marketplace
```

Or inside a Claude Code session: `/plugin marketplace add sattyapatil/infinite-resume-claude-plugin`, then `/plugin install infinite-resume@infinite-resume-marketplace`.

## Connect your Infinite Resume account

The first time Claude uses the plugin's resume tools it opens a sign-in page on infiniteresume.com. Sign in with Google and choose **Allow connection**. Claude never sees your password. The permission covers only creating and replacing resume previews: the plugin has no tool that reads your saved resumes.

## Open your preview

The plugin returns a one-time link that expires 45 minutes after it is created. Open it in a browser signed in to the same Infinite Resume account you connected. A link opens only for that account: signed out, you are asked to sign in, and a different account is refused without using the link up.

## Your data

Only the resume you approve is sent, and only when you approve it. Contact details are optional. See the [privacy policy](https://www.infiniteresume.com/privacy-policy) and [terms](https://www.infiniteresume.com/terms), or ask for help at [infiniteresume.com/contact](https://www.infiniteresume.com/contact).

## License

The files in this repository (the skill, its reference guides and the manifests) are released under the [MIT License](LICENSE). The license does not grant rights to the Infinite Resume name or logo, or to the Infinite Resume website and service that the connection reaches.
