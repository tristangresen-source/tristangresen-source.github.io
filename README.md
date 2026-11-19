# Sunny Isle Tycoon website

Public website for the game: a landing page (`index.html`) and the privacy policy (`privacy.html`).
The game itself lives in a separate private repository.

## Before launch
- Replace `[your contact email here]` in `index.html` and `privacy.html` with the game's email.
- If the privacy policy changes, copy the new text from `STORE/privacy-policy.html` in the game repo
  and update the "Last updated" date.

## app-ads.txt (for AdMob, later)
AdMob asks for a file called `app-ads.txt` at the top of the website listed as the
"Developer website" in the Play Store. Once the real AdMob account exists:
1. In AdMob, go to **Apps → View all apps → app-ads.txt** and copy the line it shows.
   It looks like: `google.com, pub-0000000000000000, DIRECT, f08c47fec0942fa0`
   (the `pub-` number is your own publisher ID).
2. Save that one line in a new file named `app-ads.txt` next to `index.html` and push it.
3. Put this website's address in Play Console → **Store settings → Website**.
AdMob checks the file within about a day. It is deliberately not added yet, because a file
with a made-up publisher ID would be wrong.
