# How to update your website (no software needed)

You do everything on **github.com**, in your web browser. Changes appear on the live site about 1 to 2 minutes after you save.

## One-time: open the file you want to change
1. Go to **github.com** and sign in.
2. Open the repository **drkanteshkumar.github.io**.
3. Click the file you want to change (for example `publications.html`).
4. Click the **pencil icon** (top right of the file, "Edit this file").
5. When finished, click the green **Commit changes...** button, then **Commit changes** again. That saves it.

Tip: use **Ctrl+F** (or Cmd+F on a Mac) inside the editor to find text quickly.

## Add a new publication
1. Open `publications.html` and click the pencil icon.
2. Find the year heading, for example `<h2 id="y2026">2026</h2>`. The publications for that year follow, each one starting with `<li>` and ending with `</li>`.
3. Copy one whole entry (from `<li>` to `</li>`), paste it **right under** the line `<ol class="pubs">` of that year, so the newest is first. Replace the text with the new publication.
4. Keep your name in bold by writing `<strong>Kumar K</strong>`.
5. For a link, use: `<a href="https://doi.org/PUT-DOI-HERE">https://doi.org/PUT-DOI-HERE</a>`
6. **New year?** Copy a whole block from `<section class="year"><h2 id="y2026">` down to its `</section>`, paste it above the newest year, and change the year number in both places.
7. Update the number near the top: "**19 published articles**" (change 19 to the new total).
8. Commit the changes.

## Add a presentation
1. Open `presentations.html` and click the pencil icon.
2. Find the right year heading. Copy one whole entry, from the first `<li>` to its closing `</li>` (including the small list inside it), and paste it at the top of that year's list.
3. Edit the text. Each line in the small inner list is one place it was presented.
4. Commit the changes.

## Edit your bio
1. Open `index.html` and click the pencil icon.
2. The bio is the first two paragraphs next to your photo, starting with "I am a physician and MPH candidate". If you add a publication, also update "19 peer-reviewed publications" in the second paragraph. Change only the words between `<p>` and `</p>`; leave the `<` `>` pieces alone.
3. Commit the changes.

## Change your Google Scholar, ORCID or LinkedIn link
In `index.html`, find the line with the link name (for example `LinkedIn`) and replace the web address inside `href="..."`, keeping the quote marks.

## Replace your CV
On the repository page, open the `files` folder, click **Add file > Upload files**, and upload your new PDF named exactly `Kantesh-Kumar-CV.pdf`. It will replace the old one. Click **Commit changes**.

## If something looks broken
Open the file, click **History** (top right) to see earlier versions, and use the **...** menu on the latest change to **Revert** it. Always check the live site after saving.
