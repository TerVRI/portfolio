# Publish to github.com/TerVRI/portfolio

## One-time setup

```bash
cd "/Users/tmad/Documents/Coding/Cursor Projects/Careers/github-portfolio"

# Create repo on GitHub (if it doesn't exist)
gh repo create TerVRI/portfolio --public --description "Terry Madigan — product & AI portfolio index" --source=. --remote=origin --push
```

If the repo already exists:

```bash
cd "/Users/tmad/Documents/Coding/Cursor Projects/Careers/github-portfolio"
git init
git remote add origin https://github.com/TerVRI/portfolio.git
git add README.md
git commit -m "Add public portfolio index"
git branch -M main
git push -u origin main
```

## Pin on your profile

1. Go to https://github.com/TerVRI
2. **Customize your pins** → pin **portfolio** (and optionally **IrishSignLanguage**)

## GitHub profile settings

1. **Settings → Profile → Include private contributions on my profile** → **On**  
   (Shows activity without exposing private code.)

2. Optional bio:
   ```
   AI product studio · Enterprise pre-sales · 3 patents · CISSP · Dublin
   Portfolio → github.com/TerVRI/portfolio
   ```

## After publishing

- CV link: `github.com/TerVRI/portfolio`
- Verify: open the URL in a private/incognito window (no login)
