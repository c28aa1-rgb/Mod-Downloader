# Mod Downloader Site

This folder is already deployable as a plain static site.

## Included download

- [Mod Downloader-0.0.0-arm64.dmg](/Users/c28aa1/Downloads/Mod Downloader Site/Mod Downloader-0.0.0-arm64.dmg)

The homepage button links directly to that file with a relative path, so it will keep working after deployment as long as the `.dmg` stays in this folder.

## Easiest deploy option

GitHub Pages is the simplest choice here because this is just static HTML, CSS, and a downloadable file.

1. Create a GitHub repo for this folder.
2. Upload everything in this folder, including the `.dmg`.
3. In GitHub, open `Settings` > `Pages`.
4. Set the source to deploy from the main branch root.
5. Wait for Pages to publish the site.

## Also works on

- Render static sites
- Firebase Hosting

Because there is no build step, those platforms can deploy the folder as-is.
