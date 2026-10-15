# AI Daily Job Finder (n8n)

An n8n workflow that finds remote jobs for you every few hours, scores them against your skills with AI, and emails you the best matches.

Built because I was tired of finding a perfect remote role, then seeing "US only" at the bottom.

## What's new in v2 (October 2026)

- **- Pulls 300+ jobs from 5 job boards: Remotive, RemoteOK, We Work Remotely, Jobicy and Himalayas
- **Location check:** the AI scores skill fit and location separately, and doesn't trust a "worldwide" label unless the job description supports it. Each job is labelled eligible, restricted or unclear, with a quote from the posting.
- **Clear tags in the email:** every job is marked "Open worldwide" or "Location unclear, check before applying". Restricted jobs are removed.
- **Full descriptions:** the clean nodes keep up to 4,000 characters, so the AI sees location rules hidden lower in the post.
- **More reliable:** each job board retries 3 times, then the workflow continues with the other sources if one is down.
- **Rate-limit safe:** AI scoring runs one job at a time with a short pause between requests.

**Why:** v1 ran without errors but still sent jobs that were US only. A workflow that runs isn't the same as a workflow that's right.
