# Marvel German Shepherds Website

Clean, professional multi-page static website for Marvel German Shepherds.

## Pages Included

- **index.html** – Home / Hero / Overview
- **about.html** – Full About Us content you provided
- **dogs.html** – All breeding dogs (Hanther + 6 females) + outside studs section + mother-daughter note for Salza & Addie
- **pairings.html** – Future / current pairings with pricing from your Deposit Agreement
- **available.html** – Placeholder for currently available puppies (easy to update)
- **application.html** – Full interactive Puppy Application form based on your PDF
- **contact.html** – Contact + summary of contracts
- **styles.css** – Navy blue + gold theme (deep navy header, gold accents & headings)

## How to Use / Host

### Option 1: Netlify (Recommended – Free & Easy)
1. Go to [netlify.com](https://www.netlify.com) and sign up (free).
2. Drag the entire `marvel-gsd-website` folder onto the Netlify dashboard, **or** connect a GitHub repo.
3. Your site will be live in seconds with a free HTTPS domain (you can later connect a custom domain like marvelgermanshepherds.com).
4. To make the application form actually send emails:  
   - Change the `<form>` tag in `application.html` to use Netlify Forms (I left comments in the file showing exactly how).

### Option 2: Vercel
Same idea – drag & drop or Git deploy. Also free for static sites.

### Option 3: Local Preview
Just open `index.html` in any browser. All pages will work offline.

## Adding & Optimizing Your Photos

1. Create a folder named `images` inside `marvel-gsd-website`.
2. Export your watermarked photos as **WebP** (preferred) or optimized JPEG:
   - Width: 800–1200 px
   - File size: aim for under 150–200 KB each
   - Keep your watermark (subtle lower corner works best on the web)
3. In `dogs.html` (and other pages), replace the placeholder boxes with:

```html
<img src="images/hanther.webp" alt="Hanther" style="width:100%; height:200px; object-fit:cover;" loading="lazy">
```

The `loading="lazy"` attribute makes pages load faster by only downloading images when they come into view.

## Updating Content Later

All text is plain HTML – just open the relevant .html file in any text editor (VS Code, Notepad, etc.) and edit. No special tools required.

## Contracts

I did **not** put the full legal Deposit Agreement or Purchase Agreement text on public pages (to avoid people treating the website as the signed contract). The Contact page summarizes them and points people to ask you for the official PDFs during the process. If you want dedicated public pages with the full text, just say the word and I’ll add them.

---

Built for you by Grok. Ready to upload.
