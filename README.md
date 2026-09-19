# I Am Kelp
A classroom learning experience from OceanX Education about kelp forest collapse and recovery.

The page is designed for educators working with learners aged 12-14 in a 60-minute session. Using real-time body tracking, learners experience how sea otter loss can trigger urchin overgrazing, kelp decline and ecosystem collapse, then explore how restoration helps the forest recover. Learners explore the ecology, investigate the game, reflect on what they experienced, and create a map that connects the forest's benefits for the ocean and for people.

Companion experience to [Seagrass Stories](https://github.com/pavmakerspace/seagrass-stories).

## Open locally

Serve the folder over HTTP so the YouTube embeds work correctly:

```bash
python3 -m http.server 8765
```

Then open:

```text
http://localhost:8765/
```

## Project structure

```text
index.html                         Classroom learning page
iamkelp-educator-guide.html        Printable A4 educator guide
iamkelp-learner-activity.html      Printable A4 learner activity sheet
assets/fonts/                      Zeist and DM Mono brand fonts
assets/logos/                      OceanX Education logo (white and dark variants)
assets/images/                     Kelp forest drawing-starter illustration
```

## Publish with GitHub Pages

1. In the repository, open **Settings > Pages**.
2. Select **Deploy from a branch**.
3. Choose the `main` branch and the `/ (root)` folder.
4. Open the generated Pages URL. Because the page is named `index.html`, it will load at the repository root.

The asset links use repository-relative paths, and the YouTube embeds use a valid referrer policy for hosted pages.
