REGINA'S LAST SWIPE: HOW TO PUT IT ONLINE

The folder is ready to upload as is:

  index.html
  images/   (devin, grant, jeffrey, gary, novanto, marko, patrick, fredy, samuel, gavin, reynold)

Easiest options:
- Netlify Drop: go to app.netlify.com/drop and drag the whole folder in. You get a link right away.
- GitHub Pages or Vercel: upload the folder and enable Pages/deploy.
- Your own website: upload the folder to your hosting (for example into /last-swipe/).

Edit text: open index.html in a text editor and change the CONFIG block near the bottom.
Her photo: add images/regina.jpg and set bridePhoto: "images/regina.jpg" in CONFIG.
Turn off the "That was [name]!" reveal: set showReveal to false.
Random order instead of fixed order: set shuffle to true (Reynold stays last).

Test it by double-clicking index.html before you upload. Run a full round on the laptop you will use at the party.
The page is set to noindex, but anyone with the link can open it.
