# Hindholistics website: go-live and update guide

The website is this whole folder: `index.html`, the `assets` folder, `robots.txt` and `sitemap.xml`.
Always upload **the whole folder**, never just `index.html`.

---

## Step 1: Own the domain hindholistics.com

- Check whether hindholistics.com is free, or whether you already bought it, at any registrar:
  GoDaddy, Hostinger, Namecheap, BigRock or Cloudflare.
- A `.com` usually costs around ₹800–1,500 a year. Turn on **auto-renew** so it never lapses.
- Keep the registrar login safe. You will need it once, in Step 3.

## Step 2: Put the site online with Netlify (free)

Netlify is free for a site like this, gives you free HTTPS (the padlock), and can deliver your form messages to your email.

1. Go to **netlify.com** and sign up (with your Gmail or GitHub).
2. Click **Add new site → Deploy manually**.
3. Drag this whole website folder onto the page.
4. In under a minute you get a free test address like `something.netlify.app`. Open it on your phone and check everything.
5. In **Site configuration → Change site name**, set the name to `hindholistics`.

## Step 3: Connect www.hindholistics.com

1. In Netlify: **Domain management → Add a domain** → type `hindholistics.com`.
2. Netlify shows you the exact DNS records to add, either new **nameservers** or an **A record + CNAME**.
3. Log in to your domain registrar → DNS settings → enter exactly what Netlify shows.
4. Wait 1–24 hours. Netlify then turns on HTTPS automatically.
5. Both `hindholistics.com` and `www.hindholistics.com` will open your site.

## Step 4: Receive form messages by email

1. In Netlify: **Forms → Enable form detection**, then upload the folder again (Deploys → drag the folder).
2. **Forms → Form notifications → Add notification → Email** → `hind.holistics@gmail.com`.
3. Test the form on the live site once. You should get the email, and it also appears in Netlify → Forms.
   (The free plan covers about 100 messages a month, plenty to start with.)

## Step 5: Get onto Google

The site already includes the pieces Google looks for: page title, description, organisation and founder details, share preview, `sitemap.xml` and `robots.txt`.

1. Go to **search.google.com/search-console** → **Add property → Domain** → `hindholistics.com`.
2. Google gives you a TXT record. Add it in your registrar's DNS (same place as Step 3) and click **Verify**.
3. **Sitemaps** → enter `sitemap.xml` → Submit.
4. **URL inspection** → paste `https://www.hindholistics.com/` → **Request indexing**.
5. Create a free **Google Business Profile** (business.google.com) for Hindholistics with the same name, phone and website. This helps a lot for Google Search and Maps.
6. Optional: do the same at **Bing Webmaster Tools** (it can import from Google in one click).

### What to expect

- Searching **"Hindholistics"** should show your site within a few days to a few weeks.
- Ranking for general words like "healthcare startup India" takes months, and it depends on the next section.

### What actually makes it rank higher

1. **Links from other places to your site.** Put `www.hindholistics.com` in your Instagram, YouTube, LinkedIn and X bios and in video descriptions. Also ask the NGOs you founded or worked with, your colleges and any news coverage to link to it.
2. **Regular new content.** Health-awareness articles, updates on your NGO work, team announcements and job openings. Each new page is another way for people to find you on Google.
3. **Social profiles.** Send me the links and I'll add them to the site (footer, and the hidden "sameAs" list Google reads).
4. **Consistent name, phone and email everywhere.** Use exactly the same details on every profile.

---

## How to update the website regularly

### Simple way (start with this)

1. Open this folder in the Claude app and tell me what to change in plain words. For example: "add a new team member", "post this announcement", "change this line".
2. I make the change and show you a preview.
3. Upload it: Netlify → your site → **Deploys** → drag the whole folder onto the page. It's live in about a minute.

### Automatic way (later, recommended)

Connect the folder to **GitHub** and link GitHub to Netlify. After that, every change I save goes live by itself, with no dragging needed. Each version is also kept, so any mistake can be undone. Ask me to set this up when you are ready.

### Good things to add over time

- **News / updates:** milestones, events, NGO camps
- **Articles:** health awareness written by you (great for Google)
- **Careers:** real open positions for "Join Hindholistics"
- **Team:** photos and roles as the medical army grows
- **Gallery / videos:** clips from your content creation

---

## Files in this folder

| File | What it is |
|---|---|
| `index.html` | The website itself |
| `assets/` | Logo, logo pieces for the animation, founder photo |
| `robots.txt` | Tells Google it may read the whole site |
| `sitemap.xml` | List of pages for Google. Update the date when you add pages |
| `GUIDE.md` | This guide (it's fine if it gets uploaded too) |
