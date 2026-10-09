# AI Daily Job Finder (n8n)

An n8n workflow that finds remote jobs for you every few hours, scores them against your skills with AI, and emails you the best matches.

Built because I was tired of finding a perfect remote role, then seeing "US only" at the bottom.

## What it does

- Pulls 200+ jobs from Remotive, RemoteOK and We Work Remotely
- Cleans them into one format
- Removes senior roles, unrelated fields and old postings
- Skips jobs it has already sent you
- Scores each job from 0 to 100 against your skills with AI, and explains why
- Emails you the best matches, ranked
- Alerts your phone if it ever stops running

## What you need

- n8n (self-hosted or n8n Cloud)
- An email account to send from (Gmail works)
- An OpenRouter API key for the AI scoring
- A free healthchecks.io account for the uptime alert (optional)

## Quick start

1. Download `workflow.json` from this repo
2. In n8n, go to **Workflows → Import from File** and select it
3. Add your own email credentials and OpenRouter key
4. Edit the skills and keywords to match your profile
5. Activate the workflow

> Never commit your API keys. The key placeholder in this file is `YOUR_OPENROUTER_KEY`.

## Need help setting it up?

Not technical, or short on time? I can help:

- **Step-by-step setup guide** with screenshots for every step
- **Done-for-you setup** on a live call, so it's running before we hang up
- **Custom version** for your job focus, extra job boards, or alerts on WhatsApp instead of email

The same approach also works for businesses: screening leads, sorting invoices or organising support tickets.

**Message me on LinkedIn:** [linkedin.com/in/oluwasegunadedeji](https://www.linkedin.com/in/oluwasegunadedeji)
**Email:** seguna670@gmail.com

---

Built by Oluwasegun Adedeji, Data & Automation Analyst, Lagos.
