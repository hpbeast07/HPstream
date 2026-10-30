HPstream SEO files
==================

1) Copy sitemap.xml and robots.txt into the website's publish/root directory
   (the same directory that contains index.html).
2) Commit and push the files to the Git repository connected to Render.
3) Wait for the Render deployment to finish.
4) Verify these URLs in a browser:
   https://stream.hpmcpe.in/robots.txt
   https://stream.hpmcpe.in/sitemap.xml

Important:
- The supplied HPstream project is a single-page application with one index.html.
  Therefore this sitemap lists only the homepage. Do not add hash-based UI states
  or guessed URLs. Add further URLs only if the app has real, independently
  crawlable routes/pages.
- Google Search Console ownership verification and sitemap submission require
  signing in to the site owner's Google account; these steps are not completed
  by placing these files on the website.
