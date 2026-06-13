# Chef Kanchi - Portfolio Website

Professional portfolio for Chef Raja Sekhar Kanchi, Bakery Operations Specialist and Consultant.

## Deployment to Vercel (Step by Step)

### Step 1: Push to GitHub
1. Go to [github.com](https://github.com) and create an account (or sign in)
2. Click the **+** button (top right) and select **New repository**
3. Name it `chef-kanchi-portfolio`
4. Keep it **Public**
5. Click **Create repository**
6. Upload all files from this folder to the repository using the **"Upload files"** button

### Step 2: Deploy on Vercel
1. Go to [vercel.com](https://vercel.com) and sign up with your GitHub account
2. Click **"Add New Project"**
3. Select the `chef-kanchi-portfolio` repository from the list
4. Vercel will auto-detect Next.js. Just click **"Deploy"**
5. Wait 1-2 minutes. Done.

### Step 3: Your live URL
Vercel will give you a URL like: `chef-kanchi-portfolio.vercel.app`

To change it to `chefkanchi.vercel.app`:
1. Go to your project **Settings** on Vercel
2. Click **Domains**
3. Add `chefkanchi.vercel.app`

### Later: Custom Domain
When ready, buy a domain like `chefkanchi.com` from Namecheap or GoDaddy (around $10/year) and add it in the same Domains settings page on Vercel.

## Local Development (Optional)
```bash
npm install
npm run dev
```
Open http://localhost:3000

## Tech Stack
- Next.js 14
- React 18
- Deployed on Vercel
