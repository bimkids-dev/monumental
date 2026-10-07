NIDHE ISRAEL — RENDER TEST SITE

Use the same GitHub and Render accounts as BimKids. Create a new repository and
a separate Static Site called nidhe-israel-test.

1. Create a GitHub repository named nidhe-israel-test.
2. Upload the contents of this extracted folder, including the public folder,
   render.yaml and this README. Commit the files to main.
3. In Render choose New > Static Site, then connect that repository.
4. Use these settings:
   Name: nidhe-israel-test
   Branch: main
   Root Directory: leave blank
   Build Command: echo ready
   Publish Directory: public
5. Deploy. Render provides the actual https://...onrender.com address.

If the repository is not listed in Render, grant the Render GitHub app access
to this new repository from its repository access settings.

The included render.yaml also supports deployment via Render Blueprints.
The manual Static Site workflow above does not require using Blueprints.

The site works entirely in the browser and needs no database, environment
variables or API keys. It includes all 608 records, the master transcription,
search and the automatic Barbados yahrzeit calendar.

For updates, replace public/index.html with the updated HTML and commit.
Render automatically redeploys when auto-deploy is enabled.

The test site is publicly accessible to anyone with its URL. A noindex
instruction is included to discourage search-engine indexing; it is not
password protection.

Calendar software sources and licences are included in public/calendar-source.zip.
The source archive is for rebuilding/reference; it is not needed to run the page.

Official setup documentation: https://render.com/docs/static-sites
