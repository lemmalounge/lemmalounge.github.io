# Lemma Lounge Mathematical Society

The website of the Lemma Lounge Mathematical Society at Rutgers University–Newark, served by GitHub Pages at **https://lemmalounge.github.io**.

There is no build step. Every page is a single, self-contained HTML file: edit it, commit, and the live site updates within a minute or two.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The club page: what we do, officers, joining, and the closing poem. |
| `explore.html` | The history of mathematics, in five scroll-through chapters. |
| `404.html` | Shown for any address that doesn't exist. |
| `og-image.jpg` | The preview picture shown when the link is shared in chats and on social media. |
| `.nojekyll` | Tells GitHub Pages to serve the files as they are, without processing. Keep it. |

## Common edits

All of these can be done in the browser: open the file on GitHub, click the pencil icon, edit, then **Commit changes**.

- **Officers.** In `index.html`, search for `President`. Each officer is one line with initials, role, and name.
- **Contact details.** In `index.html`, search for `TODO`. Replace the commented-out example with the club's real email or Instagram, and remove the `<!--` and `-->` around it.
- **Page text.** Search for the sentence you want to change and edit it in place.

## If the site's address changes

The pages point link previews at `https://lemmalounge.github.io/`. If the organization gets a different name, or you add a custom domain, find and replace that address in `index.html`, `explore.html` and `404.html`.

## The generative artwork

Each visit draws a random seed that decides which artwork appears behind each section, how it is drawn, where the ink drops fall, and the paths of the billiard balls behind the page. The seed is shown in the footer. Adding `?seed=12345` to the address reproduces that exact version, which is useful for screenshots.

## Keeping the site alive

- The repository belongs to the **lemmalounge** GitHub organization, not to any one person. Keep at least two current officers as organization owners, and add incoming officers before outgoing ones graduate.
- If you add a custom domain, register it with a shared club email, turn on auto-renew, and verify it in the organization's settings (Settings → Pages → Add a domain) so no one else can claim it.

## Credits

Typefaces: IM Fell English, Bodoni Moda, STIX Two Text and IBM Plex Sans, served by Google Fonts under the SIL Open Font License. The closing lines are from William Blake's *Auguries of Innocence* (public domain).
