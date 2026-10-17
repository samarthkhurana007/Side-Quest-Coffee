
# Side Quest Coffee Co. - MIS 301

Welcome. This repository is yours. It was created for you when you accepted the assignment, and nobody else in the class (except for me) can see it.

**The full assignment instructions are in Canvas, not here.** This page is orientation: what this place is, what you are going to put in it, and the two mistakes that cannot be undone.

> [!IMPORTANT]
> **Read the assignment instructions in Canvas before you start building.**
> They contain the client brief, the business data you must reproduce exactly, the Definition of Done, and the reflection questions. This README is a map, not the assignment.

---

## Where you are

You are looking at a **repository**, or repo: storage for one project's files plus a permanent record of every change made to them. Two things live here, and keeping them straight matters.

| | What it is | Who can see it |
|---|---|---|
| **This repository** | Your source files and their full change history | You and your instructor |
| **Your GitHub Pages site** | The published website built from those files | Anyone with the address |

You will turn on the published site in Stage 2. Right now you only have the repository.

> [!NOTE]
> **This README is not your website.** GitHub displays it nicely, which fools people. Your website is `index.html`. Leave this file alone; it does not affect what visitors see.

---

## What you are building

Four things, at the top level of this repository:

```
index.html      the homepage
games.html      The Game Shelf page
style.css       appearance, shared by both pages
images/
  ├── your logo
  └── your second image
```

| File | What it does |
|---|---|
| `index.html` | Content and structure of the homepage. This exact filename is what GitHub Pages looks for. |
| `games.html` | The Game Shelf page. Both pages link to each other. |
| `style.css` | Colors, fonts, spacing. **Both HTML pages must use this same file.** |
| `images/` | A folder holding your two AI-generated image files. |

> [!TIP]
> Filenames are case-sensitive on a web server. `images/logo.png` and `Images/Logo.PNG` are two different files. This is the single most common reason an image works on your laptop and not on the published site.

---

## Publishing

Once your files are uploaded, go to **Settings → Pages** and set:

- **Source:** Deploy from a branch
- **Branch:** `main`
- **Folder:** `/ (root)`

Save, wait a few minutes, and refresh. GitHub will show your public web address.

> [!NOTE]
> **Publishing is slow, and that is normal.** Deployment commonly takes several minutes. A page that has not updated yet does not mean you broke something. Check that your change actually committed, then refresh again before changing anything else.

Full click-by-click steps and troubleshooting are in the **GitHub Setup Instructions** document in Canvas.

---

## STOP: two things worth getting right

> [!WARNING]
> **Capture your BEFORE evidence before you make the manager's change.**
>
> Once your site is published and working, and *before* you edit anything else, you must capture:
>
> 1. A **screenshot of your live published homepage**, with the browser address bar visible
> 2. The **URL of the commit** that produced it - the one containing `/commit/`
>
> The moment you edit the site, the BEFORE state stops existing anywhere. There is no way to recover it. This is the most common way students lose points on this assignment, and it is entirely preventable.
>
> The **Evidence Tracker** posted in Canvas has a labeled blank for both. Use it.

> [!CAUTION]
> **In Stage 4, ask AI for a fragment. Do not let it rebuild your page.**
>
> You may use AI to get the small piece of HTML you need. You may not hand it your whole `index.html` and paste back whatever it returns.
>
> **Good:** *"Give me the HTML for a noticeable closure notice I can paste at the top of my homepage. Use an inline style attribute. Do not rewrite my page."*
>
> **Not this:** *"Here is my index.html, add a closure notice and give me the updated file."*
>
> A regenerated page throws away every correction you made earlier. The Tuesday closure and the invented awards come right back, and your commit history shows the whole file was replaced.

---

## Do not

- **Do not rename this repository.** Its name links your work to the gradebook. Renaming it breaks that link.
- **Do not create a second repository.** This one is the one that counts.
- **Do not make this repository public.** Your source stays private; your published website is what goes public. That distinction is part of what the assignment is teaching.
- **Do not delete this README.** It costs you nothing to leave it.

---

## Before you submit

- [ ] `index.html` and `games.html` both load from the public address
- [ ] Navigation works in both directions
- [ ] Both pages use the same `style.css`
- [ ] Both images display on the published site
- [ ] Both images have meaningful alt text
- [ ] All business data matches the brief exactly, including the Tuesday closure
- [ ] All eight games appear with their supplied player counts and play times
- [ ] BEFORE screenshot and BEFORE commit URL captured **before** the Stage 4 change
- [ ] AFTER screenshot and AFTER commit URL captured after it
- [ ] Everything pasted into the submission quiz in Canvas

The complete Definition of Done is in the assignment instructions. This is the short version.

---

## Stuck?

Post on the Canvas discussion board or come to office hours. Deployment problems are configuration problems, not intelligence tests, and professionals ask colleagues about them constantly.

If your site will not deploy after you have worked the troubleshooting checklist, **ask** rather than changing unrelated code hoping things fix themselves.

---
