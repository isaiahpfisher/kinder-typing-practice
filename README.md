# Spelling Practice

A spelling page for kindergarteners. Students see a picture, tap the speaker to hear the word, and type it.

## Put it online with GitHub Pages (free)

1. Create a free account at https://github.com if you don't have one.
2. Click **+** (top right) → **New repository**. Give it a name like `spelling`, choose **Public**, and click **Create repository**.
3. On the new repository's page, click **uploading an existing file**.
4. Unzip this folder on your computer, then drag **all four files inside it** (`index.html`, `pictures.js`, `README.md`, `LICENSE-pictures.txt`) into the upload area. Click **Commit changes**.
5. Go to **Settings** → **Pages**. Under "Branch", choose **main**, leave the folder as **/ (root)**, and click **Save**.
6. Wait a minute or two, then refresh that page. Your address appears at the top, for example:
   `https://your-username.github.io/spelling/`

Share that address with students, or bookmark it on classroom devices.

**Updating later:** upload the changed files the same way, and the site updates within a minute or two.

## Changing the words

Open `index.html` and find the `WORDS` list near the top of the script. Each line looks like:

```
{word:"frog", type:"ccvc-blend", picture:"frog"},
```

- `picture` is optional: the name of a picture in `pictures.js` (usually the word itself). Leave it out and the word shows only the speaker button.

## Recording the words in your own voice

1. Open your site's address with `#teacher` on the end, for example:
   `https://your-username.github.io/spelling/#teacher`
   (Students never see this screen unless they're given that address.)
2. Allow microphone access when the browser asks.
3. For each word: press **Record** (or the Space bar), say the word, and press **Stop** (or Space again).
   Silence is trimmed and the volume is evened out automatically, and the recording plays back so you can check it.
   Use **→** to move to the next word. "Only show words with no recording" helps you find what's left.
4. Recordings are kept in that browser as you go, so you can stop and come back later on the same computer.
5. When you're done, click **Download recordings (.zip)** and unzip it. You'll get a folder named `audio`.
   GitHub's website accepts at most 100 files per upload, so with more than 90 recordings you'll get folders named
   `upload 1 of 4`, `upload 2 of 4`, and so on instead, each with an `audio` folder inside.
6. In your GitHub repository, click **Add file → Upload files**, drag in the `audio` folder, and click **Commit changes**.
   With several upload folders, repeat this for the `audio` folder inside each one. They merge into one `audio` folder on your site.

A minute or two later, every device uses your recordings. Any word without a recording uses the device's built-in voice.

## Picture credit

Pictures are from the Mulberry Symbols set by Steve Lee (https://mulberrysymbols.org), used under the
Creative Commons Attribution-ShareAlike license. Keep the credit line at the bottom of the page and the
`LICENSE-pictures.txt` file when you publish.
