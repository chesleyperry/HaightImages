# Haight Images — *Death of Hippie*

A black-and-white photo slideshow of San Francisco's Haight-Ashbury during the
**"Death of Hippie" period, 1967** (archival collection `ms0020`,
negatives `rmb-6702`).

The 20 frames run as a curated photo essay: hand-lettered shop-window messages
and a Martin Buber quote, the Haight Ashbury Free Medical Clinic closing notice,
the "Death of Hippie… Birth of the Free American" street banner, an artist
inking a psychedelic poster, a suite of park portraits, and a closing portrait of
a young man with a squirrel monkey.

## View it

The slideshow is a single, self-contained `index.html` with no external
dependencies.

- **Quickest:** open `index.html` directly in any browser, **or**
- **Locally served** (recommended, mirrors how it runs on the web):

  ```sh
  python3 -m http.server 8000
  # then visit http://localhost:8000/
  ```

### Controls
- `←` / `→`, the on-screen arrows, or clicking the left/right side of a photo — previous / next
- `Space` or the **Play** button — start/stop autoplay (pauses while you hover a photo)
- `Home` / `End` — jump to the first / last frame
- `T` or **Thumbnails** — toggle the thumbnail strip

## Aesthetic

A "darkroom gallery" treatment chosen to flatter black-and-white photography:
a near-black background with a soft vignette, warm cream serif captions, a thin
film-frame border around each print, and gentle crossfade transitions. Every
image carries a meaningful title and descriptive `alt` text for accessibility.

## Publish on GitHub Pages

Because the gallery is a root-level `index.html`, it is ready to publish as-is:

1. Push this branch to GitHub.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select the
   branch and the `/ (root)` folder, and save.
4. The slideshow will be served at the Pages URL within a minute or two.
