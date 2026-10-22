# Birthday Surprise 💚

A responsive, green-themed birthday website for your brother. It uses plain HTML, CSS, and JavaScript, so there is no build step.

## Preview with GitHub Pages

1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/ (root)**, then save.
4. Wait a minute or two for GitHub Pages to publish the site.

## Add your own photos and music

Upload your own files into the `assets` folder using these exact names:

- `hero.jpg` — large hero photo
- `photo-1.jpg` — first gallery photo
- `photo-2.jpg` — second gallery photo
- `photo-3.jpg` — third gallery photo
- `birthday-song.mp3` — optional background music

You can use different filenames, but then update the matching paths in `index.html`. Use photos and music you have permission to share. If you don't add a song, the music button will indicate that a song needs to be added.

## Personalize the page

Open `index.html` and edit the birthday greeting, name, and letter text. The theme is controlled by CSS variables near the top of the stylesheet: `--bg`, `--panel`, `--ink`, `--muted`, `--accent`, `--accent2`, and `--line`.

The site is mobile responsive and includes a welcome screen, animated flower accents, a photo gallery/lightbox, a personal letter, and optional background music.
