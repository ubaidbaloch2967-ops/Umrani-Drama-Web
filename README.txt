UMRANI DRAMA WEB — GitHub Pages files

FILES
- index.html: main responsive drama website
- home.html: redirects to index.html
- ubaid.jpg: put the same owner photo here (keep this exact filename)

IMPORTANT
The page is a static GitHub Pages website. It cannot automatically detect newly aired episodes without a data/API integration. In index.html, find `const episodes = [` and update the sample entries with current episode details:
- country: Pakistani, Indian, or Turkish
- flag: corresponding flag emoji
- drama, episode, date, channel
- videoId: YouTube video ID from an official channel video URL
- officialUrl: official episode page URL
- downloadUrl / qualityLinks: use only when the rights holder officially offers those downloads

When videoId is supplied, the player embeds the official YouTube video. Without it, the watch button opens the official source page. Quality download options appear only when explicit official download URLs are configured. A normal YouTube watch URL is not a direct MP4 download link.

DEPLOY
Upload index.html, home.html, and ubaid.jpg into the root of the GitHub repository. In repository Settings > Pages, select the desired branch and root folder.
