# Deploy to GitHub + Vercel

## 1. Put the code on GitHub

1. **Create a new repo on GitHub**
   - Go to [github.com/new](https://github.com/new)
   - Repository name: e.g. `voice-therapy-site` or `SpeechBusiness`
   - Leave it empty (no README, no .gitignore — you already have them)
   - Create repository

2. **Push this folder to it** (run these in a terminal, in this project folder):

   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git branch -M main
   git push -u origin main
   ```

   Replace `YOUR_USERNAME` with your GitHub username and `YOUR_REPO_NAME` with the repo name you chose. If GitHub shows you a different URL (e.g. SSH), use that instead of the `https://` one.

## 2. Deploy on Vercel

1. Go to [vercel.com](https://vercel.com) and sign in (use “Continue with GitHub”).
2. Click **Add New…** → **Project**.
3. **Import** the GitHub repo you just pushed (e.g. `voice-therapy-site`).
4. Leave the defaults — Vercel will detect it’s static (no build step). Click **Deploy**.
5. When it’s done, you’ll get a URL like `voice-therapy-site-xxx.vercel.app`. That’s your live site.

Later you can add a custom domain in the Vercel project **Settings → Domains**.
