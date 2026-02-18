# How to Publish This Skill to GitHub

**Time needed:** 10-15 minutes  
**You'll need:** GitHub account

---

## Step 1: Create GitHub Repository

1. Go to https://github.com/new
2. **Repository name:** `executive-search-skill`
3. **Description:** "AI-powered candidate research workflows for VP/C-suite Product & Engineering roles"
4. **Visibility:** ✅ Public
5. **Initialize:** ❌ Do NOT initialize (we have files already)
6. Click **"Create repository"**

---

## Step 2: Upload Files

**Option A: GitHub Web Interface (Easiest)**

1. On the new repo page, click **"uploading an existing file"**
2. Drag and drop ALL files from `/root/.openclaw/workspace/executive-search-skill/`
3. Make sure you include:
   - All `.md` files (README, SKILL, STATUS, etc.)
   - LICENSE file
   - .gitignore file
   - `examples/` folder with TechVision search
   - `templates/` folder
4. Commit message: "Initial release - v1.0.0"
5. Click **"Commit changes"**

**Option B: Command Line (If you prefer)**

```bash
cd /root/.openclaw/workspace/executive-search-skill

# Initialize git
git init

# Add all files
git add .

# First commit
git commit -m "Initial release - v1.0.0"

# Add remote (replace YOUR-USERNAME)
git remote add origin https://github.com/YOUR-USERNAME/executive-search-skill.git

# Push to GitHub
git branch -M main
git push -u origin main
```

---

## Step 3: Create Initial Release

1. Go to your repo: `https://github.com/YOUR-USERNAME/executive-search-skill`
2. Click **"Releases"** (right sidebar)
3. Click **"Create a new release"**
4. **Tag version:** `v1.0.0`
5. **Release title:** "v1.0 - First Executive Search Skill for OpenClaw"
6. **Description:**
   ```
   🚀 First executive search intelligence skill for OpenClaw!
   
   ## What's Included
   - Complete AI assistant instructions for executive search
   - 100-point candidate scoring framework
   - Company intelligence workflows
   - Boolean search generation
   - Psychology profiling (accelerator vs. stabilizer)
   - 1 full fictional example search (TechVision CTO)
   - Candidate scorecard & research templates
   
   ## Installation
   See README.md for setup instructions
   
   ## Created By
   Amie Ernst - Executive Recruiter, Riviera Partners
   Based on real VP/C-suite Product & Engineering search workflows
   ```
7. Click **"Publish release"**

---

## Step 4: Update README with Correct URLs

After publishing, update these links in README.md:

- GitHub repo URL
- Issues URL
- Discussions URL

Find/replace:
- `https://github.com/amieernst/executive-search-skill` → your actual repo URL

---

## Step 5: Submit to ClawhHub

1. Go to https://clawhub.com
2. Click **"Submit Skill"** (or similar)
3. Fill in:
   - **Skill Name:** Executive Search Intelligence
   - **GitHub URL:** Your repo URL
   - **Description:** "AI-powered candidate research for VP/C-suite Product & Engineering roles"
   - **Category:** Recruiting / HR / Business
   - **Author:** Amie Ernst
4. Submit!

---

## Step 6: Announce in OpenClaw Discord

Join the Discord: https://discord.com/invite/clawd

Post in #show-and-tell or #skills channel:

```
🚀 Just published the first Executive Search Intelligence skill for OpenClaw!

Built for VP/C-suite Product & Engineering recruiting:
✅ Company intelligence research
✅ 100-point candidate scoring
✅ Boolean search generation  
✅ Psychology profiling
✅ Availability assessment

GitHub: [your-repo-url]
ClawhHub: [clawhub-link]

Based on real executive search workflows. Fictional examples only (client-safe).

Feedback welcome! 🙏
```

---

## Step 7: Add Topics/Tags to Repo

On GitHub, add these topics to your repo (click ⚙️ next to "About"):

- `openclaw`
- `openclaw-skill`
- `recruiting`
- `executive-search`
- `ai-assistant`
- `hiring`
- `candidate-research`

This helps people discover your skill!

---

## Optional: Create a Website/Landing Page

If you want a dedicated page:
- Enable GitHub Pages (Settings → Pages → Deploy from main branch)
- Creates: `https://YOUR-USERNAME.github.io/executive-search-skill/`
- README.md becomes the homepage

---

## You're Live! 🎉

**What happens next:**
- People discover your skill via GitHub/ClawhHub/Discord
- They install and use your recruiting workflows
- README includes your contact info → leads for search work
- You're positioned as "the recruiter who gets AI"

**First mover advantage:** You're the first recruiter with an OpenClaw skill!

---

Need help with any step? Let me know! I can walk you through it.

**- Swami 🧘**
