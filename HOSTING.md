# Free hosting options for sharing your decision tree

Your project is a single static HTML file, so any of these will work.

---

## Option 1: Surge.sh (fastest – one command)

1. Open a terminal in this folder (`AES_decisionTree`).
2. Run:
   ```bash
   npx surge . --domain aes-decision-tree-<yourname>.surge.sh
   ```
   (Replace `<yourname>` with your name or any slug; Surge will suggest one if you omit `--domain`.)
3. When prompted, enter an email and choose a password (first time only).
4. You’ll get a live URL like `https://aes-decision-tree-yourname.surge.sh` to share.

No GitHub or account signup required beyond Surge’s one-time prompt.

---

## Option 2: Netlify Drop (no CLI)

1. Go to [https://app.netlify.com/drop](https://app.netlify.com/drop).
2. Sign in with GitHub, Google, or email.
3. Drag the **AES_decisionTree** folder onto the page.
4. Netlify will give you a URL like `https://random-name-123.netlify.app` (you can rename it in the dashboard).

---

## Option 3: GitHub Pages (good if you already use Git/GitHub)

1. Create a new repo on GitHub (e.g. `AES_decisionTree`).
2. Push this folder to the repo.
3. In the repo: **Settings → Pages** → Source: **Deploy from a branch** → Branch: **main** (or **master**) → **Save**.
4. Your site will be at `https://<username>.github.io/<repo-name>/`.

---

## Option 4: Vercel

1. Go to [https://vercel.com](https://vercel.com) and sign in (e.g. with GitHub).
2. Click **Add New → Project** and import your repo, or use **Vercel CLI**:  
   `npx vercel` in this folder and follow the prompts.
3. You’ll get a URL like `https://aes-decision-tree-xxx.vercel.app`.

---

**Recommendation:** Use **Surge** for a one-off share in under a minute, or **Netlify Drop** if you prefer a drag-and-drop in the browser.
