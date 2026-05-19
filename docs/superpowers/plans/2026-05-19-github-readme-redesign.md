# GitHub README Redesign Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Rewrite README.md as a clean, emoji-free, space/cosmic-themed profile centered on AI Generalist / AI Software Engineer identity.

**Architecture:** Single file rewrite (`README.md`). Built section by section, committed at the end. No external dependencies beyond shields.io badge URLs and existing GitHub stats services.

**Tech Stack:** Markdown, HTML (inline, GitHub-flavored), shields.io badges, readme-typing-svg, github-readme-streak-stats, capsule-render.

---

## File Structure

| Action | File | Responsibility |
|---|---|---|
| Modify | `README.md` | Full profile README — all sections |

---

## Task 1: Header

**Files:**
- Modify: `README.md` (replace entire file contents — start fresh)

- [ ] **Step 1: Replace README.md with header section only**

Open `README.md` and replace all contents with:

```markdown
<div align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=98FB98&center=true&vCenter=true&width=550&lines=AI+Generalist;AI+Software+Engineer;Prompt+%26+Context+Engineer;Agentic+AI;Building+at+the+AI+Frontier;1%25+Better+Every+Day" alt="Typing SVG" />
  </a>
</div>

![Banner](https://github.com/user-attachments/assets/a4e0e85c-67b7-4b95-beb5-f367a598d88f)
```

- [ ] **Step 2: Verify in browser**

Push to GitHub (or use a local Markdown preview) and confirm:
- Typing SVG animates through all 6 lines
- `#98FB98` pale green color renders correctly
- Banner GIF displays

If the banner GIF is broken or you want a different one, find a space-themed GIF and re-upload it via GitHub Issues image upload, then replace the URL.

---

## Task 2: Who I Am Section

**Files:**
- Modify: `README.md` (append after header)

- [ ] **Step 1: Append divider + Who I Am section**

Append to `README.md`:

```markdown

<img width="100%" height="50" src="https://i.imgur.com/dBaSKWF.gif"/>

## Who I Am

<p align="center"><i>You've reached Mike's signal in the void — an AI Generalist and Software Engineer building at the frontier of what's possible.</i></p>

- **Role:** AI Generalist / AI Software Engineer @ Dietz Webdesign (Remote, Germany)
- **Stack:** LLMs · Agentic AI · Prompt & Context Engineering · Web Design · Automation & Augmentation
- **Mission:** Ship real things. Improve 1% daily. Go further.
```

- [ ] **Step 2: Verify**

Confirm in preview:
- No emojis anywhere in this section
- Italic opener renders correctly
- 3 bullets display cleanly

---

## Task 3: Tech Arsenal — AI + Languages Badges

**Files:**
- Modify: `README.md` (append after Who I Am)

- [ ] **Step 1: Append Tech Arsenal section — AI category**

Append to `README.md`:

```markdown

<img width="100%" height="50" src="https://i.imgur.com/dBaSKWF.gif"/>

## Tech Arsenal

**AI**

<div align="center">
  <img src="https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white"/>
  <img src="https://img.shields.io/badge/AI_Agents-FF5733?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/Prompt_%26_Context_Engineering-6E0D25?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google_Antigravity-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white"/>
  <img src="https://img.shields.io/badge/Generative_AI-FF9A00?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/LLMs-5C5C5C?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/ChatGPT-74AA9C?style=for-the-badge&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/Codex-412991?style=for-the-badge&logo=openai&logoColor=white"/>
</div>
```

- [ ] **Step 2: Append Languages & Frameworks category**

Append to `README.md`:

```markdown

**Languages & Frameworks**

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white"/>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
  <img src="https://img.shields.io/badge/Astro-FF5D01?style=for-the-badge&logo=astro&logoColor=white"/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white"/>
  <img src="https://img.shields.io/badge/Liquid-7AB55C?style=for-the-badge&logo=shopify&logoColor=white"/>
</div>
```

- [ ] **Step 3: Verify both badge rows render**

Check in GitHub preview that all badges load (no broken images). If a badge logo is missing, remove the `&logo=X` param — the badge will still render with color + text only.

---

## Task 4: Tech Arsenal — Data + Tools + Hosting Badges

**Files:**
- Modify: `README.md` (append after Languages)

- [ ] **Step 1: Append Data (supporting) category**

Append to `README.md`:

```markdown

**Data** *(supporting)*

<div align="center">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Excel%2FCSV-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white"/>
</div>
```

- [ ] **Step 2: Append Tools category**

Append to `README.md`:

```markdown

**Tools**

<div align="center">
  <img src="https://img.shields.io/badge/Git%2FGitHub-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/Shopify-96BF48?style=for-the-badge&logo=shopify&logoColor=white"/>
  <img src="https://img.shields.io/badge/GSC_MCP-4285F4?style=for-the-badge&logo=googlesearchconsole&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google_Ads_MCP-4285F4?style=for-the-badge&logo=googleads&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google_Business_Profile-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google_Workspace-4285F4?style=for-the-badge&logo=google&logoColor=white"/>
  <img src="https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=canva&logoColor=white"/>
  <img src="https://img.shields.io/badge/Photoshop-31A8FF?style=for-the-badge&logo=adobephotoshop&logoColor=white"/>
  <img src="https://img.shields.io/badge/REST_APIs-FF5733?style=for-the-badge&logoColor=white"/>
</div>
```

- [ ] **Step 3: Append Hosting category**

Append to `README.md`:

```markdown

**Hosting**

<div align="center">
  <img src="https://img.shields.io/badge/IONOS-0040E6?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/Namecheap-DE3723?style=for-the-badge&logo=namecheap&logoColor=white"/>
  <img src="https://img.shields.io/badge/Cloudflare_Pages-F38020?style=for-the-badge&logo=cloudflare&logoColor=white"/>
</div>
```

- [ ] **Step 4: Verify all badge categories render**

All 5 categories should be visible and no badges broken. Fix any missing logos by removing the `&logo=X` param.

---

## Task 5: GitHub Stats (Streak Widget)

**Files:**
- Modify: `README.md` (append after Tech Arsenal)

- [ ] **Step 1: Append streak widget**

Append to `README.md`:

```markdown

## GitHub Stats

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=mikeascendx&theme=tokyonight&hide_border=true" alt="GitHub Streak" width="500"/>
</div>
```

- [ ] **Step 2: Verify streak widget loads**

Check in browser on github.com/mikeascendx that the widget shows:
- Total Contributions count
- Current Streak count
- Longest Streak count

If the widget shows an error, the service may be temporarily down — leave it in and check again later.

---

## Task 6: Quote + Contact + Footer

**Files:**
- Modify: `README.md` (append remaining sections)

- [ ] **Step 1: Append quote section**

Append to `README.md`:

```markdown

---

> *"Dwell on the beauty of life. Watch the stars, and see yourself running with them."*
>
> — Marcus Aurelius
```

- [ ] **Step 2: Append contact section**

Append to `README.md`:

```markdown

## Connect

- **Email:** [johnmikeasuncion17@gmail.com](mailto:johnmikeasuncion17@gmail.com)
- **LinkedIn:** [linkedin.com/in/mikeascendx](https://www.linkedin.com/in/mikeascendx/)
- **GitHub:** [github.com/mikeascendx](https://github.com/mikeascendx)
- **DataCamp:** [datacamp.com/portfolio/johnmikeasuncion17](https://www.datacamp.com/portfolio/johnmikeasuncion17)
- **Facebook:** [facebook.com/mikekaizennn](https://www.facebook.com/mikekaizennn)
```

- [ ] **Step 3: Append footer**

Append to `README.md`:

```markdown

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&section=footer"/>
```

- [ ] **Step 4: Verify full README in browser**

Open `github.com/mikeascendx` and do a full pass:
- No emojis anywhere
- Exactly 2 animated dividers (after header, before Tech Arsenal)
- No GIF grid at bottom
- No "Kaizen" word
- Quote renders as blockquote
- All contact links are clickable and correct
- Footer wave renders

---

## Task 7: Final Cleanup + Commit

**Files:**
- Modify: `README.md` (fix any issues found in Task 6 Step 4)

- [ ] **Step 1: Fix any issues from visual review**

If any badge is broken, emoji slipped through, or link is wrong — fix it now.

- [ ] **Step 2: Commit**

```bash
git add README.md
git commit -m "docs: redesign github profile readme — storytelling cosmic layout"
```

- [ ] **Step 3: Verify on GitHub**

Open `github.com/mikeascendx` in browser. Confirm the live profile matches the spec. Done.
