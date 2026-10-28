SRX CREATIVE — COMPLETE PORTFOLIO (VERCEL)

INCLUDED
- 20 browser-compatible, optimized MP4 video files with preview thumbnails
- 8 graphic design images in the "POSTER SHOW PHOTOS" gallery
- Video categories: Product Ads (MAR + Filter), Wedding Films, Podcast Edits, Cinematic Edits
- Responsive dark cinematic website with video and image lightboxes
- Static site: no build step, database, or backend required

IMPORTANT BEFORE PUBLISHING
- Replace the placeholder hello@srxcreative.com email in index.html.
- Replace the generic Instagram link with your actual profile.
- Some video titles are temporary names like Edit 03 because the uploaded files had generic names. You can change these titles in the video data in index.html.
- Confirm you have permission to publicly publish all media and any third-party music, artwork, or trademarks used in your portfolio.
- Videos have been compressed for faster playback. Keep your original source videos separately.

VERCEL DEPLOYMENT (GITHUB RECOMMENDED)
1. Extract the ZIP. The extracted folder should contain index.html, vercel.json, and media/.
2. Create a GitHub repository, e.g. srx-creative-portfolio, and upload the contents of the extracted folder to the repository root. Large uploads are easier using Git on a computer than the GitHub browser uploader. Do not upload the ZIP as the only repository file.
3. Sign in to https://vercel.com/new and import the GitHub repository.
4. Select Framework Preset: Other. No build command is required. Keep Root Directory as ./ and default output settings.
5. Click Deploy. Your live site will be available at a *.vercel.app URL.
6. Future commits to the connected GitHub repository will trigger deployments.

ALTERNATIVE — VERCEL CLI
Install Node.js and run in the extracted folder:
  npx vercel
Follow prompts; then deploy to production with:
  npx vercel --prod

Note: Free hosting and bandwidth have usage limits. With 20 self-hosted videos, streaming traffic can grow quickly. For higher traffic, consider external video hosting (YouTube/Vimeo/Cloudinary) and embedding videos instead.
