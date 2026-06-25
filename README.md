<div align="center">

<br/>

<img src="https://img.shields.io/badge/Claude-Skills-0f7b5f?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude Skills"/>

# Run your job search like a system, not a scramble

**Two skills that find roles, tailor your resume, and get smarter every time you hear back.**

<br/>

![job-search-os](https://img.shields.io/badge/Skill_1-job--search--os-0f7b5f?style=flat-square)
![resume-tailor](https://img.shields.io/badge/Skill_2-resume--tailor-2f63b8?style=flat-square)
![5 min read](https://img.shields.io/badge/⏱_read_time-5_min-b07918?style=flat-square)

</div>

---

Looking for a job is exhausting, right? You tweak the same resume forty times, you lose track of what you applied to, and every rejection feels like it taught you nothing. I went through exactly that — so I built a little system to take the chaos out of it.

These two skills are that system, packaged up for you.

> **Every application is a labelled data point. Most people just throw the label away.**

---

## Table of contents

- [Why these exist](#why-these-exist)
- [What each skill does](#what-each-skill-does)
- [How to set up](#how-to-set-up)
- [Day-to-day use](#day-to-day-use)
- [The files it creates](#the-files-it-creates)
- [How to customise](#how-to-customise)
- [Quick-start recap](#quick-start-recap)

---

## Why these exist

Job searching is one of those things that *should* get easier the longer you do it — but somehow never does.

You apply, you hear nothing, you move on, and the next application starts from zero. No memory, no learning. You're basically re-inventing yourself from scratch every time, and making the same mistakes you made three weeks ago without even knowing it.

The idea here is simple. **Treat every application as a data point.** A rejection and a callback are both information. If you capture what you led with, then later capture what happened, you slowly learn which roles, which framings, and which keywords actually get you in the door. The system gets a little sharper every week.

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│    Apply    │────▶│    Track    │────▶│    Learn    │────▶│   Sharpen   │
│ tailor+send │     │  log role   │     │   outcome   │     │  next wins  │
└─────────────┘     └─────────────┘     └─────────────┘     └──────┬──────┘
       ▲                                                            │
       └────────────────── (every loop, sharper) ──────────────────┘
```

The second idea is about **truth**. These skills never invent a metric or a job you didn't have. They take your *real* achievements and reframe them to fit the role in front of you. If a job wants something you don't have, the system flags it as a gap honestly — so you can speak to it in the interview instead of getting caught out. (Trust me, that's the better trade.)

---

## What each skill does

| | `job-search-os` | `resume-tailor` |
|---|---|---|
| **Role** | Your search command centre | Your resume writer |
| **Input** | Your background, targets, outcomes | A job description (text, URL, or file) |
| **Output** | Scored role list, tracked applications, pattern insights | Tailored resume + optional cover letter |
| **Superpower** | **Checks each listing is live** before you waste a click | Leads with your strongest-matching proof every time |
| **Gets smarter?** | Yes — learns your patterns from logged outcomes | Yes — reads outcomes back from job-search-os |

<details>
<summary><strong>job-search-os — more detail</strong></summary>

<br/>

Your search command centre. It interviews you once and builds living files: who you are, what you're targeting, where to look, what you're learning.

Then it:
- **Finds roles** matching your background and targets
- **Checks each listing is actually live** — so you stop wasting clicks on dead links
- **Scores and explains** why each role fits (so you can push back when it gets you wrong)
- **Tracks your applications** and outcomes in one place
- **Tells you what's working** after a few weeks of data

</details>

<details>
<summary><strong>resume-tailor — more detail</strong></summary>

<br/>

Your resume writer. Give it a job description as text, a link, or a file and it builds a tailored resume that:

- Mirrors the role's **exact language** (the words recruiters and ATS systems scan for)
- **Leads with your strongest-matching proof** — not just chronological order
- **Reuses phrasing that already worked** from your keyword ledger
- Flags any **genuine gaps** so you can prep for them in the interview
- Writes a **matching cover letter** in your voice — but only after the resume feels right

> Resume first, always.

</details>

<br/>

> **They're better together.** `job-search-os` builds and maintains your files. `resume-tailor` reads those same files and writes outcomes back into them. Install both and the loop closes. But each one works perfectly fine on its own — don't stress if you only want one to start.

---

## How to set up

> **One honest note first.** These work best in **Cowork with a folder connected**, or inside a **Claude Project**. That's because the living files need to stick around between chats. In a normal one-off chat they still run, but nothing carries over — and that memory is what makes them useful. Connect a folder if you can.

<br/>

**Step 1 — Install both skills**

Download `job-search-os.skill` and `resume-tailor.skill` from this repo, then open each file in Claude and hit **Save skill**. That's it. They're available in every chat from that point.

**Step 2 — Connect a folder**

In Cowork or a Claude Project, connect a local folder. This is where the living files will live. It doesn't need to be organised — just needs to exist.

**Step 3 — Run the setup interview**

Start a chat and say: *"help me set up my job search."*

It asks a focused batch of questions about your background, what you're targeting, and your biggest wins with real numbers. **Give it proper metrics here.** The more honest detail you put in, the better everything downstream gets. (Vague in, vague out.)

> **Heads up:** the first run feels like an interview, not magic. That's the setup tax. Once your files exist, every run after is fast. Don't judge it by minute one.

---

## Day-to-day use

Once setup is done, this is the loop you run:

**Finding roles**

> *"find roles for me"* or *"what should I apply to"*

It searches, weeds out dead listings, scores what's left, and tells you *why* each one fits.

**Tracking a role you found yourself**

> *"track this for me"* + paste the job description or a URL

Found something on your own? Paste the JD text or drop in the URL (if the page isn't blocked) and the skill logs it to your tracker — same format as anything it finds itself, so everything stays in one place.

**Tailoring your resume**

> *"tailor my resume for this"* + paste the job description

You get a resume back, plus a note on the angle it led with and any gaps to prep for. Ask for a cover letter only once the resume feels right.

**Logging outcomes — the part everyone skips**

> *"I got rejected from the X role"* or *"the Y company booked a recruiter call"*

Every time you hear back (ghosted, rejected, recruiter call, interview) — tell it. It logs the signal and slowly figures out what's working for you. After a few weeks, your resumes get noticeably sharper because they're learning from real results, not guesses.

> **One quiet rule it follows:** would a tired recruiter, skimming for 20 seconds, instantly see why you fit *this exact* role? If not, it re-orders until they would. That's the bar.

---

## The files it creates

After setup, you'll have a folder of plain markdown files. They're yours — open and edit any of them by hand anytime.

<details>
<summary><strong>profile.md — your achievement bank</strong></summary>

<br/>

This is the one to invest in. Every metric and bullet in every resume comes from here.

If a number is wrong, fix it here. If a win is missing, add it here. Everything downstream updates automatically. Think of it as your source of truth — not just a resume, but *everything you've done* that might ever be relevant.

</details>

<details>
<summary><strong>resume-format.md — your layout rules</strong></summary>

<br/>

Controls how your resume gets built: fonts, layout, do's and don'ts. Point it at your best existing resume as the template and it matches that look every time.

If you hate a particular formatting choice, fix it here once and it never comes back.

</details>

<details>
<summary><strong>search-config.md — what you're hunting for</strong></summary>

<br/>

Titles, locations, salary floor, the domains you want and the ones you don't.

Edit this whenever your search shifts — maybe you've decided to drop a title, or you've opened up to a new city. The next run reads it fresh, no re-setup needed.

</details>

<details>
<summary><strong>keyword-ledger.md — the learning brain</strong></summary>

<br/>

Tracks which framings led to callbacks versus auto-rejections. You don't really edit this one manually — you let it fill up as outcomes come in.

It's fascinating to read back after a month. You start seeing patterns you never would have noticed.

</details>

---

## How to customise

Good news: you barely have to. The customisation mostly happens *by using it.*

Two ways to steer it:

**Just tell it** — *"stop showing me on-site roles"* or *"I want to lean more into product strategy."* It updates the config and remembers. Your direct feedback always outranks its own guesses.

**Edit the file** — Open `search-config.md` or `profile.md` and change it yourself. Both routes end up in the same place.

---

## Quick-start recap

That's the whole thing. Not complicated — just a system that *remembers*, which turns out to be the part most job hunts are missing.

If you only remember five things:

- **Install both** by saving the two `.skill` files
- **Connect a folder** (Cowork or a Project) so it keeps memory
- **Start with** *"help me set up my job search"* and give it real numbers
- **Use it** by pasting a job description and saying *"tailor my resume for this"*
- **Feed it outcomes** every single time you hear back — that's what makes it smart

Do that, and in a few weeks you'll have a job search that's actually working *for* you instead of you working it. Go get it. 💪

---

<div align="center">
  <sub>Made with ♥ by Dave &nbsp;·&nbsp; <a href="https://github.com/deewang/Job-Search-OS/issues">shout if anything feels off</a></sub>
</div>
