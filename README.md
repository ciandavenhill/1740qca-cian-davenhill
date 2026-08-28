# Setup Instructions

## 1. Create your GitHub repo
- Go to github.com → New repository
- Name it something like `1740qca-yourname`
- Make sure it's set to **Public** (private repos won't be visible to your tutor)

## 2. Upload these files
- Upload `_config.yml`, `index.md`, and the `images` folder to the root of your repo
  (drag-and-drop works fine via the GitHub website — Add file > Upload files)

## 3. Add your images/GIFs
- Put all your JPGs and GIFs inside the `images` folder
- Rename the placeholder filenames in `index.md` to match your actual files
  (e.g. change `task03-composite-01.jpg` to whatever you actually named it)

## 4. Add your YouTube videos
- Upload each Task 05 video to YouTube as **Unlisted**
- Copy the video ID from the URL (the part after `watch?v=`)
- Replace `VIDEO_ID_1`, `VIDEO_ID_2` etc. in `index.md` with your actual video IDs

## 5. Edit your name and title
- In `_config.yml`, change "Your Name" to your actual name
- In `index.md`, change the heading at the top too

## 6. Enable GitHub Pages
- In your repo: Settings > Pages
- Under "Source", select your main branch, folder: `/ (root)`
- Save — GitHub will give you a URL like:
  `https://yourusername.github.io/1740qca-yourname`

## 7. Test your URL
- Open it in an incognito/private browser window to confirm it's public and working
  BEFORE you submit it

## 8. Fill in your content
- Replace every placeholder caption (in *italics*) with your real captions
- Replace the `[name/technique]` and `[description of settings]` placeholders with
  your specific technique names, following the terminology from your course brief

## Notes
- Keep image file sizes reasonable (long edge ~2000px as per the brief) so the
  site loads quickly
- The theme used here (Cayman) is a free, built-in GitHub Pages theme — you can
  swap it for another built-in theme by changing the `theme:` line in `_config.yml`
  (other options: jekyll-theme-minimal, jekyll-theme-architect, jekyll-theme-slate)
