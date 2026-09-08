---
title: Help
sitemap:
    lastmod: '30-08-2026 19:40'
---




How to add wallpaper post · MD
# How to Add a New Journal Post in Grav
 
> **Note:** This folder was originally used for Ian's monthly wallpaper releases (hence the "Wallpaper" page template and naming pattern below). Going forward, no new wallpapers will be released — this will be used for regular blog-style journal posts instead. The steps and template are the same; just treat the "Wallpaper Image" section as optional (skip it if a post doesn't have a dedicated wallpaper file), and use a natural post title instead of the old "Wallpaper Month Year" pattern.
 
This guide walks through adding a new entry to the Journal section, using the Grav admin panel. It assumes you're already logged in.
 
---
 
## 1. Go to the Journal section
 
1. In the left sidebar, click **Pages**.
2. Find and click into the **Journal** folder (`/journal`) — this is where all the Wallpaper entries live, alongside other journal-type content.
## 2. Add a new page
 
1. At the top right of the Journal page list, click **+ Add**. A pop-up window titled **Add Page** appears.
2. Fill in the fields:
   - **Page Title** — a natural, descriptive title for the post (previously these followed a "Wallpaper Month Year" pattern, e.g. `Wallpaper January 2019` — that convention is retired now that these are regular journal posts, not monthly wallpaper releases).
   - **Folder Name** — Grav usually auto-fills this from the title (e.g. `wallpaper-january-2019`). Leave it as generated unless there's a reason to change it.
   - **Parent Page** — this is important: click the folder icon and choose **Journal** from the list (you'll see a "Parents" browser pop-up showing Home, Art, Books, Journal, etc. — click **Journal**, then **Continue**). If this is left as `<root>`, the new page won't land in the right place alongside the other Wallpaper entries.
   - **Page Template** — choose **Wallpaper** from the dropdown.
   - **Visible** — leave on **Auto** unless told otherwise (this controls whether the page shows in site navigation menus; Auto follows the theme's default behavior for this page type).
3. Click **Continue**. This creates the page and takes you into its editor.
## 3. Fill in the content
 
You'll land on the **Content** tab by default. It has three parts:
 
**A. Title**
Already filled in from step 2 — this is the page heading (e.g. `Wallpaper January 2019`).
 
**B. Body text**
Below the title is a text editor (formatting toolbar with Bold, Italic, links, images, quote, lists, etc.). This is where the write-up/story for that month goes — write or paste it in like a normal blog post.
 
**C. Page Media / Wallpaper Image** *(optional for regular posts — skip this part if there's no standalone wallpaper-style image to offer, and just add images inline in the body text instead using the image icon in the toolbar)*
Scroll down to **Page Media**:
1. Drag and drop (or click to upload) the wallpaper photo file for that month. It'll appear as a thumbnail with its filename and file size.
Then under **Wallpaper Image**, set which uploaded image is used for each format:
- **Wallpaper - Wide Ratio** — check this box, then pick the uploaded image from the dropdown next to it (this is the main widescreen wallpaper version).
- **Wallpaper - iPad Ratio** — optional; check this box and choose an image only if you have a separate iPad-cropped version to offer.
- **Header image** — leave unchecked unless told otherwise; this controls a different display area.
- **Show Rentals** — leave checked/unchecked matching how previous entries are set (this toggles a rentals promo block on the page — don't change unless asked).
> **Tip:** If you're not sure what a field does, hover over the small **?** icons next to field labels — Grav shows a tooltip explanation.
 
## 4. Leave Advanced settings alone
 
The **Advanced** tab (Folder Name, Parent, Page Template, Ordering, etc.) is already set correctly once you've chosen the Wallpaper template and title. You shouldn't need to touch:
- **Folder Name**
- **Parent**
- **Folder Numeric Prefix** (this site has it **Disabled**, meaning pages aren't manually reordered by number — new posts just take their title-based slug)
Leave these as Grav sets them automatically.
 
## 5. Save
 
At the bottom of the page, under **After Save...**, choose:
- **Edit Item** — stays on this page after saving (good if you're still working on it)
- **List Items** — takes you back to the Journal page list after saving (good once you're done)
Then click **Save** in the top right.
 
- Saving does **not** always mean it's publicly live — check the **eye icon** (Preview) near the top to view the page as visitors would see it.
- If there's a **Publish** toggle or date field under the **Options** tab, make sure that's set correctly if you want it visible right away (vs. scheduled for later).
## 6. Double-check it appears in the list
 
Go back to **Pages → Journal** and confirm your new entry shows up alongside the others (e.g. *1000 Islands Wallpaper April 2017*, *Wallpaper April 2005*, etc.).
 
---
 
## Things NOT to touch
 
To keep the site stable, avoid changing anything in these areas unless Mike says otherwise:
- **Page Template** dropdown (once correctly set to Wallpaper)
- **Folder Numeric Prefix** toggle
- Anything under **Themes**, **Plugins**, or the **Expert** mode toggle (top right of the editor)
- Any `.twig` file references — these are template files, not content, and editing them can break page layouts across the site
If something looks broken or a field is unclear, it's faster (and safer) to screenshot it and ask than to guess.
 
