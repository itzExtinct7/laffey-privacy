# Laffey Music Privacy Policy — GitHub Pages

A responsive, self-contained HTML privacy page. It needs no Node.js, server, build tools, paid hosting, or API key. CSS is embedded in index.html; the page adds no JavaScript, forms, analytics or browser storage. GitHub still processes site traffic under its own policies.

## Fill the two missing public details

Open index.html in a text editor (or use GitHub's file editor):

1. Replace every YOUR_OPERATOR_NAME with the responsible operator's public name/identity.
2. Replace every YOUR_SUPPORT_INVITE with the permanent invite code for your actual Discord support server. For example, if the invite is https://discord.gg/example, use example. A real, monitored private contact/ticket route is needed for privacy and deletion requests.
3. Remove the paragraph with class="setup-notice" after completing those replacements. Update the date and policy whenever practices change. Review the policy against the bot version and hosting practices actually used.

The code does not supply a support-server invite, operator identity, encryption or automatic deletion. These details are intentionally not invented. Do not submit the page for verification with placeholders remaining.

## Publish using GitHub's website — no terminal required

1. Create a PUBLIC repository named laffey-privacy. On a free GitHub account, public repositories support GitHub Pages.
2. Extract this ZIP locally. Use Add file > Upload files to upload index.html to the repository's root, then commit. Upload README.md and the optional empty .nojekyll file as well if your uploader shows them. Do not upload the ZIP itself or leave index.html in a nested folder. No bot files are needed in this repository.
3. Open repository Settings > Pages.
4. Under Build and deployment, choose Source: Deploy from a branch.
5. Select the main branch and /(root), then click Save. If your repository uses a different default branch, select the branch containing index.html.
6. Wait for publishing to finish. The Pages settings will show the real site URL and Visit site link. Open that URL in an incognito window to confirm public access.
7. Use that published URL in Discord Developer Portal's Privacy Policy URL field and link to it inside the bot. Add separate service terms if required by your application/review flow.

Expected URL FORMAT (not a deployed address):
https://YOUR_GITHUB_USERNAME.github.io/laffey-privacy/

If the root URL returns 404, check the selected branch/folder, exact lowercase filename index.html, deployment result, and whether the file was accidentally uploaded inside an extra folder. Allow the deployment time shown by GitHub; publishing can take up to ten minutes.

This package has not been published to a GitHub account. Its actual URL is assigned through your repository's Pages settings.

Official instructions:
https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
